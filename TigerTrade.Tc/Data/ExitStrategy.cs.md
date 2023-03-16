
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ExitStrategy
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](#Clear-m) | *Описание* |
| [`ExitStrategy`](#ExitStrategy-m) | *Описание* |
| [`GetStrategySingleTarget`](#GetStrategySingleTarget-m) | *Описание* |
| [`GetTarget`](#GetTarget-m) | *Описание* |
| [`GetTargets`](#GetTargets-m) | *Описание* |
| [`GetUpdateTime`](#GetUpdateTime-m) | *Описание* |
| [`Init`](#Init-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsMultiStrategy`](#IsMultiStrategy-p) | *Описание* |
| [`Targets`](#Targets-p) | *Описание* |





***  
***  
# Методы

## `Clear`<a href="Init-m" id="Init-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear(bool isClosePosition = false)
```

`isClosePosition` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `ExitStrategy`<a href="Init-m" id="Init-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategy()
```

***  

## `GetStrategySingleTarget`<a href="Init-m" id="Init-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategyTarget GetStrategySingleTarget(bool create)
```

`create` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetTarget`<a href="Init-m" id="Init-m"></a>
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

## `GetTargets`<a href="Init-m" id="Init-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ExitStrategyTarget> GetTargets()
```

***  

## `GetUpdateTime`<a href="Init-m" id="Init-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime GetUpdateTime()
```

***  

## `Init`<a href="Init-m" id="Init-m"></a>
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

## `IsMultiStrategy`<a href="Targets-p" id="Targets-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsMultiStrategy { get; }
```  
***

## `Targets`<a href="Targets-p" id="Targets-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ExitStrategyTarget> Targets { get; set; }
```  
***

