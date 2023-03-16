
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ExitStrategy
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#method-clear) | *Описание* |
| [`ExitStrategy`](#method-exitstrategy) | *Описание* |
| [`GetStrategySingleTarget`](#method-getstrategysingletarget) | *Описание* |
| [`GetTarget`](#method-gettarget) | *Описание* |
| [`GetTargets`](#method-gettargets) | *Описание* |
| [`GetUpdateTime`](#method-getupdatetime) | *Описание* |
| [`Init`](#method-init) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsMultiStrategy`](#property-ismultistrategy) | *Описание* |
| [`Targets`](#property-targets) | *Описание* |





***  
***  
# Методы

## `Clear`<a href="method-clear" id="method-clear"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear(bool isClosePosition = false)
```

`isClosePosition` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `ExitStrategy`<a href="method-exitstrategy" id="method-exitstrategy"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategy()
```

***  

## `GetStrategySingleTarget`<a href="method-getstrategysingletarget" id="method-getstrategysingletarget"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategyTarget GetStrategySingleTarget(bool create)
```

`create` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetTarget`<a href="method-gettarget" id="method-gettarget"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategyTarget GetTarget(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  

`Func` <mark style="color:red;">*`new`*</mark>  
 *Описание*  

`ExitStrategy` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `GetTargets`<a href="method-gettargets" id="method-gettargets"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ExitStrategyTarget> GetTargets()
```

***  

## `GetUpdateTime`<a href="method-getupdatetime" id="method-getupdatetime"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime GetUpdateTime()
```

***  

## `Init`<a href="method-init" id="method-init"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Init(ExitStrategy strategy)
```

`strategy` <mark style="color:red;">*`ExitStrategy`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `IsMultiStrategy`<a href="property-ismultistrategy" id="property-ismultistrategy"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsMultiStrategy { get; }
```  
***

## `Targets`<a href="property-targets" id="property-targets"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ExitStrategyTarget> Targets { get; set; }
```  
***

