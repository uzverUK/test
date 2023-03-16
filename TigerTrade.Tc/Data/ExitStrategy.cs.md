
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


===

### Синтаксис
```csharp
public sealed class ExitStrategy
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#method-clear) | *===* |
| [`ExitStrategy`](#method-exitstrategy) | *===* |
| [`GetStrategySingleTarget`](#method-getstrategysingletarget) | *===* |
| [`GetTarget`](#method-gettarget) | *===* |
| [`GetTargets`](#method-gettargets) | *===* |
| [`GetUpdateTime`](#method-getupdatetime) | *===* |
| [`Init`](#method-init) | *===* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsMultiStrategy`](#property-ismultistrategy) | *===* |
| [`Targets`](#property-targets) | *===* |





***  
***  
# Методы

## `Clear`<a href="method-clear" id="method-clear"></a>
===
```csharp
public void Clear(bool isClosePosition = false)
```

`isClosePosition` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `ExitStrategy`<a href="method-exitstrategy" id="method-exitstrategy"></a>
===
```csharp
public ExitStrategy()
```

***  

## `GetStrategySingleTarget`<a href="method-getstrategysingletarget" id="method-getstrategysingletarget"></a>
===
```csharp
public ExitStrategyTarget GetStrategySingleTarget(bool create)
```

`create` <mark style="color:red;">*`bool`*</mark>  
 *===*  


***  

## `GetTarget`<a href="method-gettarget" id="method-gettarget"></a>
===
```csharp
public ExitStrategyTarget GetTarget(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *===*  

`Func` <mark style="color:red;">*`new`*</mark>  
 *===*  

`ExitStrategy` <mark style="color:red;">*`new`*</mark>  
 *===*  


***  

## `GetTargets`<a href="method-gettargets" id="method-gettargets"></a>
===
```csharp
public List<ExitStrategyTarget> GetTargets()
```

***  

## `GetUpdateTime`<a href="method-getupdatetime" id="method-getupdatetime"></a>
===
```csharp
public DateTime GetUpdateTime()
```

***  

## `Init`<a href="method-init" id="method-init"></a>
===
```csharp
public void Init(ExitStrategy strategy)
```

`strategy` <mark style="color:red;">*`ExitStrategy`*</mark>  
 *===*  


***  
***  
 ***  
# Свойства

## `IsMultiStrategy`<a href="property-ismultistrategy" id="property-ismultistrategy"></a>
===
```csharp
public bool IsMultiStrategy { get; }
```  
***

## `Targets`<a href="property-targets" id="property-targets"></a>
===
```csharp
public List<ExitStrategyTarget> Targets { get; set; }
```  
***

