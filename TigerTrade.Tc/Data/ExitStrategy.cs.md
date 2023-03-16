
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Data](../../TigerTrade.Tc/Data.md)


Описание

### Синтаксис
```csharp
public sealed class ExitStrategy
```


# Список методов
| Название | Описание |
| --- | --- |
| [`Clear`](./ExitStrategy.cs/Методы/Clear.md) | *Описание* |
| [`ExitStrategy`](./ExitStrategy.cs/Методы/ExitStrategy.md) | *Описание* |
| [`GetStrategySingleTarget`](./ExitStrategy.cs/Методы/GetStrategySingleTarget.md) | *Описание* |
| [`GetTarget`](./ExitStrategy.cs/Методы/GetTarget.md) | *Описание* |
| [`GetTargets`](./ExitStrategy.cs/Методы/GetTargets.md) | *Описание* |
| [`GetUpdateTime`](./ExitStrategy.cs/Методы/GetUpdateTime.md) | *Описание* |
| [`Init`](./ExitStrategy.cs/Методы/Init.md) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`IsMultiStrategy`](./ExitStrategy.cs/Свойства/IsMultiStrategy.md) | *Описание* |
| [`Targets`](./ExitStrategy.cs/Свойства/Targets.md) | *Описание* |





***  
***  
# Методы

## `Clear`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public void Clear(bool isClosePosition = false)
```

`isClosePosition` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `ExitStrategy`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategy()
```

***  

## `GetStrategySingleTarget`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public ExitStrategyTarget GetStrategySingleTarget(bool create)
```

`create` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetTarget`
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

## `GetTargets`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ExitStrategyTarget> GetTargets()
```

***  

## `GetUpdateTime`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public DateTime GetUpdateTime()
```

***  

## `Init`
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

## `IsMultiStrategy`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public bool IsMultiStrategy { get; }
```  
***

## `Targets`
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public List<ExitStrategyTarget> Targets { get; set; }
```  
***

