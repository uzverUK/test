
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


Описание

### Синтаксис
```csharp
public static class DataManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AutoConnect`](#AutoConnect-m) | *Описание* |
| [`ClientCancelAllOrders`](#ClientCancelAllOrders-m) | *Описание* |
| [`ClientCancelOrder`](#ClientCancelOrder-m) | *Описание* |
| [`ClientConnect`](#ClientConnect-m) | *Описание* |
| [`ClientDisconnect`](#ClientDisconnect-m) | *Описание* |
| [`ClientModifyOrder`](#ClientModifyOrder-m) | *Описание* |
| [`ClientPlaceOrder`](#ClientPlaceOrder-m) | *Описание* |
| [`ClientUpdateUserPosition`](#ClientUpdateUserPosition-m) | *Описание* |
| [`FilterAccount`](#FilterAccount-m) | *Описание* |
| [`GetAccount`](#GetAccount-m) | *Описание* |
| [`GetAccounts`](#GetAccounts-m) | *Описание* |
| [`GetConnectionInfo`](#GetConnectionInfo-m) | *Описание* |
| [`GetConnectionsInfo`](#GetConnectionsInfo-m) | *Описание* |
| [`GetExecutions`](#GetExecutions-m) | *Описание* |
| [`GetOrders`](#GetOrders-m) | *Описание* |
| [`GetOrdersCount`](#GetOrdersCount-m) | *Описание* |
| [`GetPositionsCount`](#GetPositionsCount-m) | *Описание* |
| [`GetSimAccounts`](#GetSimAccounts-m) | *Описание* |
| [`GetUserPosition`](#GetUserPosition-m) | *Описание* |
| [`IsClientConnected`](#IsClientConnected-m) | *Описание* |
| [`IsTradeAllowed`](#IsTradeAllowed-m) | *Описание* |
| [`LoadTrustAccounts`](#LoadTrustAccounts-m) | *Описание* |
| [`ProcessMarketData`](#ProcessMarketData-m) | *Описание* |
| [`ProcessTradeData`](#ProcessTradeData-m) | *Описание* |
| [`SetTradeMode`](#SetTradeMode-m) | *Описание* |
| [`Subscribe`](#Subscribe-m) | *Описание* |
| [`SyncSlTp`](#SyncSlTp-m) | *Описание* |
| [`UnSubscribe`](#UnSubscribe-m) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Player`](#Player-p) | *Описание* |
| [`Simulator`](#Simulator-p) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`Action`](#Action-p) | *Описание* |
| [`Action`](#Action-p) | *Описание* |
| [`Action`](#Action-p) | *Описание* |
| [`Action`](#Action-p) | *Описание* |
| [`OnAccountsReady;`](#OnAccountsReady;-p) | *Описание* |
| [`OnBarsObtained;`](#OnBarsObtained;-p) | *Описание* |
| [`OnConnected;`](#OnConnected;-p) | *Описание* |
| [`OnDisconnected;`](#OnDisconnected;-p) | *Описание* |
| [`OnDom;`](#OnDom;-p) | *Описание* |
| [`OnError;`](#OnError;-p) | *Описание* |
| [`OnExecution;`](#OnExecution;-p) | *Описание* |
| [`OnInfo;`](#OnInfo;-p) | *Описание* |
| [`OnOrder;`](#OnOrder;-p) | *Описание* |
| [`OnOrderInfo;`](#OnOrderInfo;-p) | *Описание* |
| [`OnPortfolio;`](#OnPortfolio;-p) | *Описание* |
| [`OnPosition;`](#OnPosition;-p) | *Описание* |
| [`OnSecurity;`](#OnSecurity;-p) | *Описание* |
| [`OnTick;`](#OnTick;-p) | *Описание* |
| [`OnTicksObtained;`](#OnTicksObtained;-p) | *Описание* |
| [`OnUserDeal;`](#OnUserDeal;-p) | *Описание* |
| [`OnUserPosition;`](#OnUserPosition;-p) | *Описание* |





***  
***  
# Методы

## `AutoConnect`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void AutoConnect()
```

***  

## `ClientCancelAllOrders`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientCancelAllOrders(OrderGroup group)
```

`group` <mark style="color:red;">*`OrderGroup`*</mark>  
 *Описание*  


***  

## `ClientCancelOrder`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientCancelOrder(Order order)
```
`order` <mark style="color:red;">*`Order`*</mark>  
 *Описание*  


***  

## `ClientConnect`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientConnect(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ClientDisconnect`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientDisconnect(string connectionID)
```

***  

## `ClientModifyOrder`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientModifyOrder(Order order)
```

`order` <mark style="color:red;">*`Order`*</mark>  
 *Описание*  


***  

## `ClientPlaceOrder`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientPlaceOrder(Order order)
```

***  

## `ClientUpdateUserPosition`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientUpdateUserPosition(UserPositionData position)
```

`position` <mark style="color:red;">*`UserPositionData`*</mark>  
 *Описание*  


***  

## `FilterAccount`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool FilterAccount(Account account)
```
`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `FilterAccount`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool FilterAccount(Account account)
public static bool FilterAccount(string accountID)
```
`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  

`accountID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetAccount`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Account GetAccount(string accountID)
```

***  

## `GetAccounts`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`isOfflineAccount` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetAccounts`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
public static List<Account> GetAccounts()
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`isOfflineAccount` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetConnectionInfo`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static ConnectionInfo GetConnectionInfo(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetConnectionsInfo`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static IEnumerable<ConnectionInfo> GetConnectionsInfo()
```

***  

## `GetExecutions`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Execution> GetExecutions(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `GetOrders`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Order> GetOrders(Symbol symbol, Account account)
```

***  

## `GetOrdersCount`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static int GetOrdersCount()
```

***  

## `GetPositionsCount`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static int GetPositionsCount()
```

***  

## `GetSimAccounts`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetSimAccounts()
```

`List` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `GetUserPosition`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static UserPosition GetUserPosition(Symbol symbol, Account account)
```
`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `IsClientConnected`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsClientConnected(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `IsTradeAllowed`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsTradeAllowed(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `IsTradeAllowed`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsTradeAllowed(UserPosition position)
public static bool IsTradeAllowed(Symbol symbol)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  


***  

## `LoadTrustAccounts`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadTrustAccounts(List<TrustAccount> accounts)
```

***  

## `ProcessMarketData`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ProcessMarketData()
```

***  

## `ProcessTradeData`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ProcessTradeData()
```

***  

## `SetTradeMode`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetTradeMode(int tradeMode, bool init)
```

`tradeMode` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`init` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Subscribe`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Subscribe(SubscriptionFlags flags, params Symbol[] symbols)
```
`flags` <mark style="color:red;">*`SubscriptionFlags`*</mark>  
 *Описание*  

`Symbol` <mark style="color:red;">*`params`*</mark>  
 *Описание*  


***  

## `SyncSlTp`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SyncSlTp()
```

***  

## `UnSubscribe`<a href="UnSubscribe-m" id="UnSubscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void UnSubscribe(SubscriptionFlags flags, params Symbol[] symbols)
```

`flags` <mark style="color:red;">*`SubscriptionFlags`*</mark>  
 *Описание*  

`Symbol` <mark style="color:red;">*`params`*</mark>  
 *Описание*  


***  
***  
 ***  
# Свойства

## `Player`<a href="Simulator-p" id="Simulator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool Player { get; private set; }
```  
***

## `Simulator`<a href="Simulator-p" id="Simulator-p"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool Simulator { get; private set; }
```  
***
***  
 ***  
# События

## `Action`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action OnUpdateAccount
```

## `Action`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action OnClearMarket
```

## `Action`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action OnUpdateFilters
```

## `Action`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action OnReferralDetected
```

## `OnAccountsReady;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo> OnAccountsReady;
```

## `OnBarsObtained;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<BarsResponce> OnBarsObtained;
```

## `OnConnected;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo> OnConnected;
```

## `OnDisconnected;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo> OnDisconnected;
```

## `OnDom;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<MarketDepth> OnDom;
```

## `OnError;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo, string> OnError;
```

## `OnExecution;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<Execution> OnExecution;
```

## `OnInfo;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo, string> OnInfo;
```

## `OnOrder;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<Order> OnOrder;
```

## `OnOrderInfo;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<OrderInfo> OnOrderInfo;
```

## `OnPortfolio;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<Portfolio> OnPortfolio;
```

## `OnPosition;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<Position> OnPosition;
```

## `OnSecurity;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<Security> OnSecurity;
```

## `OnTick;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<Tick> OnTick;
```

## `OnTicksObtained;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<TicksResponce> OnTicksObtained;
```

## `OnUserDeal;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<UserDeal> OnUserDeal;
```

## `OnUserPosition;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<UserPosition> OnUserPosition;
```

