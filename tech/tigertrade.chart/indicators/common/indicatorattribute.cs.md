# IndicatorAttribute

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Common](./)

Атрибут необходимый для создания индикатора - производного класса от InidicatorBase.

<details>

<summary>Дополнительно</summary>

#### Пример

```csharp
[DataContract(Name = "VolumeIndicator", Namespace = "http://schemas.datacontract.org/2004/07/TigerTrade.Chart.Indicators.Custom")]
[Indicator("X_Volume", "*Volume", false, Type = typeof(VolumeIndicator))]
internal sealed class VolumeIndicator : IndicatorBase
{
	protected override void Execute()
	{
		throw new NotImplementedException();
	}
}
```

</details>

#### Синтаксис

```csharp
public class IndicatorAttribute : Attribute
```

## Список методов

| Название                                                                   | Описание      |
| -------------------------------------------------------------------------- | ------------- |
| [`IndicatorAttribute`](indicatorattribute.cs.md#method-indicatorattribute) | _Конструктор_ |

## Список свойств

| Название                                                 | Описание                                                                                         |
| -------------------------------------------------------- | ------------------------------------------------------------------------------------------------ |
| [`Category`](indicatorattribute.cs.md#property-category) | _===_                                                                                            |
| [`ID`](indicatorattribute.cs.md#property-id)             | _Возвращает идентификатор индикатора._                                                           |
| [`Name`](indicatorattribute.cs.md#property-name)         | _Возвращает название индикатора._                                                                |
| [`Overlay`](indicatorattribute.cs.md#property-overlay)   | _Возвращает будет ли индикатор отрисовываться в основной области, где находится ценовой график._ |
| [`Type`](indicatorattribute.cs.md#property-type)         | Возвр_ащает или задает Type класса к которому применен данный атрибут._                          |

***

***

## Методы

### `IndicatorAttribute` <a href="#method-indicatorattribute" id="method-indicatorattribute"></a>

_Конструктор_

```csharp
public IndicatorAttribute(string id, string name, bool overlay)
```

`id` _<mark style="color:red;">`string`</mark>_\
_===_

`name` _<mark style="color:red;">`string`</mark>_\
_===_

`overlay` _<mark style="color:red;">`bool`</mark>_\
_===_

***

***

***

## Свойства

### `Category` <a href="#property-category" id="property-category"></a>

\===

```csharp
public string Category { get; set; }
```

***

### `ID` <a href="#property-id" id="property-id"></a>

_Возвращает идентификатор индикатора._

```csharp
public string ID { get; }
```

***

### `Name` <a href="#property-name" id="property-name"></a>

_Возвращает название индикатора._

```csharp
public string Name { get; }
```

***

### `Overlay` <a href="#property-overlay" id="property-overlay"></a>

_Возвращает будет ли индикатор отрисовываться в основной области, где находится ценовой график._

```csharp
public bool Overlay { get; }
```

***

### `Type` <a href="#property-type" id="property-type"></a>

Возвр_ащает или задает Type класса к которому применен данный атрибут._

```csharp
public Type Type { get; set; }
```

***
