# ExitStrategy

`namespace` [TigerTrade.Tc](../).[Data](./)

\===

#### Синтаксис

```csharp
public sealed class ExitStrategy
```

## Список методов

| Название                                                                       | Описание |
| ------------------------------------------------------------------------------ | -------- |
| [`Clear`](exitstrategy.cs.md#method-clear)                                     | _===_    |
| [`ExitStrategy`](exitstrategy.cs.md#method-exitstrategy)                       | _===_    |
| [`GetStrategySingleTarget`](exitstrategy.cs.md#method-getstrategysingletarget) | _===_    |
| [`GetTarget`](exitstrategy.cs.md#method-gettarget)                             | _===_    |
| [`GetTargets`](exitstrategy.cs.md#method-gettargets)                           | _===_    |
| [`GetUpdateTime`](exitstrategy.cs.md#method-getupdatetime)                     | _===_    |
| [`Init`](exitstrategy.cs.md#method-init)                                       | _===_    |

## Список свойств

| Название                                                         | Описание |
| ---------------------------------------------------------------- | -------- |
| [`IsMultiStrategy`](exitstrategy.cs.md#property-ismultistrategy) | _===_    |
| [`Targets`](exitstrategy.cs.md#property-targets)                 | _===_    |

***

***

## Методы

### `Clear` <a href="#method-clear" id="method-clear"></a>

\===

```csharp
public void Clear(bool isClosePosition = false)
```

`isClosePosition` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `ExitStrategy` <a href="#method-exitstrategy" id="method-exitstrategy"></a>

\===

```csharp
public ExitStrategy()
```

***

### `GetStrategySingleTarget` <a href="#method-getstrategysingletarget" id="method-getstrategysingletarget"></a>

\===

```csharp
public ExitStrategyTarget GetStrategySingleTarget(bool create)
```

`create` _<mark style="color:red;">`bool`</mark>_\
_===_

***

### `GetTarget` <a href="#method-gettarget" id="method-gettarget"></a>

\===

```csharp
public ExitStrategyTarget GetTarget(string id)
```

`id` _<mark style="color:red;">`string`</mark>_\
_===_

`Func` _<mark style="color:red;">`new`</mark>_\
_===_

`ExitStrategy` _<mark style="color:red;">`new`</mark>_\
_===_

***

### `GetTargets` <a href="#method-gettargets" id="method-gettargets"></a>

\===

```csharp
public List<ExitStrategyTarget> GetTargets()
```

***

### `GetUpdateTime` <a href="#method-getupdatetime" id="method-getupdatetime"></a>

\===

```csharp
public DateTime GetUpdateTime()
```

***

### `Init` <a href="#method-init" id="method-init"></a>

\===

```csharp
public void Init(ExitStrategy strategy)
```

`strategy` _<mark style="color:red;">`ExitStrategy`</mark>_\
_===_

***

***

***

## Свойства

### `IsMultiStrategy` <a href="#property-ismultistrategy" id="property-ismultistrategy"></a>

\===

```csharp
public bool IsMultiStrategy { get; }
```

***

### `Targets` <a href="#property-targets" id="property-targets"></a>

\===

```csharp
public List<ExitStrategyTarget> Targets { get; set; }
```

***
