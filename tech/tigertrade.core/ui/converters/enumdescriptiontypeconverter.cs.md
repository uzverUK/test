# EnumDescriptionTypeConverter

`namespace` [TigerTrade.Core](../../).[UI](../).[Converters](./)

\===

#### Синтаксис

```csharp
public sealed class EnumDescriptionTypeConverter : EnumConverter
```

## Список методов

| Название                                                                                                 | Описание |
| -------------------------------------------------------------------------------------------------------- | -------- |
| [`EnumDescriptionTypeConverter`](enumdescriptiontypeconverter.cs.md#method-enumdescriptiontypeconverter) | _===_    |
| [`GetDescription`](enumdescriptiontypeconverter.cs.md#method-getdescription)                             | _===_    |
| [`GetValue`](enumdescriptiontypeconverter.cs.md#method-getvalue)                                         | _===_    |

***

***

## Методы

### `EnumDescriptionTypeConverter` <a href="#method-enumdescriptiontypeconverter" id="method-enumdescriptiontypeconverter"></a>

\===

```csharp
public EnumDescriptionTypeConverter(Type type)
```

`type` _<mark style="color:red;">`Type`</mark>_\
_===_

***

### `GetDescription` <a href="#method-getdescription" id="method-getdescription"></a>

\===

```csharp
public static string GetDescription(Type type, string fieldName)
```

`fieldName` _<mark style="color:red;">`string`</mark>_\
_===_

***

### `GetValue` <a href="#method-getvalue" id="method-getvalue"></a>

\===

```csharp
public static object GetValue(Type type, string description)
```

`type` _<mark style="color:red;">`Type`</mark>_\
_===_

`description` _<mark style="color:red;">`string`</mark>_\
_===_

***
