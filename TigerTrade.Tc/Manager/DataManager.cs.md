
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

## `AutoConnect`<a href="AutoConnect-m" id="AutoConnect-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void AutoConnect()
```

***  

## `ClientCancelAllOrders`<a href="ClientCancelAllOrders-m" id="ClientCancelAllOrders-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientCancelAllOrders(OrderGroup group)
```

`group` <mark style="color:red;">*`OrderGroup`*</mark>  
 *Описание*  


***  

## `ClientCancelOrder`<a href="ClientCancelOrder-m" id="ClientCancelOrder-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientCancelOrder(Order order)
```
`order` <mark style="color:red;">*`Order`*</mark>  
 *Описание*  


***  

## `ClientConnect`<a href="ClientConnect-m" id="ClientConnect-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientConnect(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ClientDisconnect`<a href="ClientDisconnect-m" id="ClientDisconnect-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientDisconnect(string connectionID)
```

***  

## `ClientModifyOrder`<a href="ClientModifyOrder-m" id="ClientModifyOrder-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientModifyOrder(Order order)
```

`order` <mark style="color:red;">*`Order`*</mark>  
 *Описание*  


***  

## `ClientPlaceOrder`<a href="ClientPlaceOrder-m" id="ClientPlaceOrder-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientPlaceOrder(Order order)
```

***  

## `ClientUpdateUserPosition`<a href="ClientUpdateUserPosition-m" id="ClientUpdateUserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientUpdateUserPosition(UserPositionData position)
```

`position` <mark style="color:red;">*`UserPositionData`*</mark>  
 *Описание*  


***  

## `FilterAccount`<a href="FilterAccount-m" id="FilterAccount-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool FilterAccount(Account account)
```
`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `FilterAccount`<a href="FilterAccount-m" id="FilterAccount-m"></a>
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

## `GetAccount`<a href="GetAccount-m" id="GetAccount-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Account GetAccount(string accountID)
```

***  

## `GetAccounts`<a href="GetAccounts-m" id="GetAccounts-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`isOfflineAccount` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetAccounts`<a href="GetAccounts-m" id="GetAccounts-m"></a>
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

## `GetConnectionInfo`<a href="GetConnectionInfo-m" id="GetConnectionInfo-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static ConnectionInfo GetConnectionInfo(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetConnectionsInfo`<a href="GetConnectionsInfo-m" id="GetConnectionsInfo-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static IEnumerable<ConnectionInfo> GetConnectionsInfo()
```

***  

## `GetExecutions`<a href="GetExecutions-m" id="GetExecutions-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Execution> GetExecutions(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `GetOrders`<a href="GetOrders-m" id="GetOrders-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Order> GetOrders(Symbol symbol, Account account)
```

***  

## `GetOrdersCount`<a href="GetOrdersCount-m" id="GetOrdersCount-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static int GetOrdersCount()
```

***  

## `GetPositionsCount`<a href="GetPositionsCount-m" id="GetPositionsCount-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static int GetPositionsCount()
```

***  

## `GetSimAccounts`<a href="GetSimAccounts-m" id="GetSimAccounts-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetSimAccounts()
```

`List` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `GetUserPosition`<a href="GetUserPosition-m" id="GetUserPosition-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static UserPosition GetUserPosition(Symbol symbol, Account account)
```
`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `IsClientConnected`<a href="IsClientConnected-m" id="IsClientConnected-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsClientConnected(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `IsTradeAllowed`<a href="IsTradeAllowed-m" id="IsTradeAllowed-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsTradeAllowed(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `IsTradeAllowed`<a href="IsTradeAllowed-m" id="IsTradeAllowed-m"></a>
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

## `LoadTrustAccounts`<a href="LoadTrustAccounts-m" id="LoadTrustAccounts-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadTrustAccounts(List<TrustAccount> accounts)
```

***  

## `ProcessMarketData`<a href="ProcessMarketData-m" id="ProcessMarketData-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ProcessMarketData()
```

***  

## `ProcessTradeData`<a href="ProcessTradeData-m" id="ProcessTradeData-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ProcessTradeData()
```

***  

## `SetTradeMode`<a href="SetTradeMode-m" id="SetTradeMode-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetTradeMode(int tradeMode, bool init)
```

`tradeMode` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`init` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Subscribe`<a href="Subscribe-m" id="Subscribe-m"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Subscribe(SubscriptionFlags flags, params Symbol[] symbols)
```
`flags` <mark style="color:red;">*`SubscriptionFlags`*</mark>  
 *Описание*  

`Symbol` <mark style="color:red;">*`params`*</mark>  
 *Описание*  


***  

## `SyncSlTp`<a href="SyncSlTp-m" id="SyncSlTp-m"></a>
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

## `Player`<a href="Player-p" id="Player-p"></a>
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

## `Action`<a href="Action-p" id="Action-p"></a>
Описание

```csharp
public static event Action OnUpdateAccount
```

## `Action`<a href="Action-p" id="Action-p"></a>
Описание

```csharp
public static event Action OnClearMarket
```

## `Action`<a href="Action-p" id="Action-p"></a>
Описание

```csharp
public static event Action OnUpdateFilters
```

## `Action`<a href="Action-p" id="Action-p"></a>
Описание

```csharp
public static event Action OnReferralDetected
```

## `OnAccountsReady;`<a href="OnAccountsReady;-p" id="OnAccountsReady;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo> OnAccountsReady;
```

## `OnBarsObtained;`<a href="OnBarsObtained;-p" id="OnBarsObtained;-p"></a>
Описание

```csharp
public static event Action<BarsResponce> OnBarsObtained;
```

## `OnConnected;`<a href="OnConnected;-p" id="OnConnected;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo> OnConnected;
```

## `OnDisconnected;`<a href="OnDisconnected;-p" id="OnDisconnected;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo> OnDisconnected;
```

## `OnDom;`<a href="OnDom;-p" id="OnDom;-p"></a>
Описание

```csharp
public static event Action<MarketDepth> OnDom;
```

## `OnError;`<a href="OnError;-p" id="OnError;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo, string> OnError;
```

## `OnExecution;`<a href="OnExecution;-p" id="OnExecution;-p"></a>
Описание

```csharp
public static event Action<Execution> OnExecution;
```

## `OnInfo;`<a href="OnInfo;-p" id="OnInfo;-p"></a>
Описание

```csharp
public static event Action<ConnectionInfo, string> OnInfo;
```

## `OnOrder;`<a href="OnOrder;-p" id="OnOrder;-p"></a>
Описание

```csharp
public static event Action<Order> OnOrder;
```

## `OnOrderInfo;`<a href="OnOrderInfo;-p" id="OnOrderInfo;-p"></a>
Описание

```csharp
public static event Action<OrderInfo> OnOrderInfo;
```

## `OnPortfolio;`<a href="OnPortfolio;-p" id="OnPortfolio;-p"></a>
Описание

```csharp
public static event Action<Portfolio> OnPortfolio;
```

## `OnPosition;`<a href="OnPosition;-p" id="OnPosition;-p"></a>
Описание

```csharp
public static event Action<Position> OnPosition;
```

## `OnSecurity;`<a href="OnSecurity;-p" id="OnSecurity;-p"></a>
Описание

```csharp
public static event Action<Security> OnSecurity;
```

## `OnTick;`<a href="OnTick;-p" id="OnTick;-p"></a>
Описание

```csharp
public static event Action<Tick> OnTick;
```

## `OnTicksObtained;`<a href="OnTicksObtained;-p" id="OnTicksObtained;-p"></a>
Описание

```csharp
public static event Action<TicksResponce> OnTicksObtained;
```

## `OnUserDeal;`<a href="OnUserDeal;-p" id="OnUserDeal;-p"></a>
Описание

```csharp
public static event Action<UserDeal> OnUserDeal;
```

## `OnUserPosition;`<a href="OnUserPosition;-p" id="OnUserPosition;-p"></a>
Описание

```csharp
public static event Action<UserPosition> OnUserPosition;
```

