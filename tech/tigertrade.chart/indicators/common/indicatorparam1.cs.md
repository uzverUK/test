# IndicatorParam1

`namespace` [TigerTrade.Chart](../../../../).[Indicators](../).[Common](./)

\===

#### Синтаксис

```csharp
public abstract class IndicatorParam<T>
```

## Список методов

| Название                                                        | Описание |
| --------------------------------------------------------------- | -------- |
| [`Clear`](indicatorparam1.cs.md#method-clear)                   | _===_    |
| [`Copy`](indicatorparam1.cs.md#method-copy)                     | _===_    |
| [`Get`](indicatorparam1.cs.md#method-get)                       | _===_    |
| [`IndicatorParam`](indicatorparam1.cs.md#method-indicatorparam) | _===_    |
| [`Set`](indicatorparam1.cs.md#method-set)                       | _===_    |

## Список свойств

| Название                                          | Описание |
| ------------------------------------------------- | -------- |
| [`Value`](indicatorparam1.cs.md#property-value)   | _===_    |
| [`Values`](indicatorparam1.cs.md#property-values) | _===_    |

***

***

## Методы

### `Clear` <a href="#method-clear" id="method-clear"></a>

\===

```csharp
public void Clear()
```

***

### `Copy` <a href="#method-copy" id="method-copy"></a>

\===

```csharp
public void Copy(IndicatorParam<T> p)
```

***

### `Get` <a href="#method-get" id="method-get"></a>

\===

```csharp
public T Get(string key, T defaultValue)
```

`key` _<mark style="color:red;">`string`</mark>_\
_===_

`defaultValue` _<mark style="color:red;">`T`</mark>_\
_===_

***

### `Get` <a href="#method-get" id="method-get"></a>

\===

```csharp
public T Get(string key, T defaultValue)
public T Get(string key)
```

`key` _<mark style="color:red;">`string`</mark>_\
_===_

`defaultValue` _<mark style="color:red;">`T`</mark>_\
_===_

***

### `IndicatorParam` <a href="#method-indicatorparam" id="method-indicatorparam"></a>

\===

```csharp
protected IndicatorParam()
```

***

### `Set` <a href="#method-set" id="method-set"></a>

\===

```csharp
protected bool Set(string key, T value)
```

`key` _<mark style="color:red;">`string`</mark>_\
_===_

`value` _<mark style="color:red;">`T`</mark>_\
_===_

***

***

***

## Свойства

### `Value` <a href="#property-value" id="property-value"></a>

\===

```csharp
public T Value { get; set; }
```

***

### `Values` <a href="#property-values" id="property-values"></a>

\===

```csharp
public Dictionary<string, T> Values { get; set; }
```

***
