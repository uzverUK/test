
`namespace` [TigerTrade.Tc](../../TigerTrade.Tc.md).[Manager](../../TigerTrade.Tc/Manager.md)


Описание

### Синтаксис
```csharp
public static class DataManager
```


# Список методов
| Название | Описание |
| --- | --- |
| [`AutoConnect`](#method-autoconnect) | *Описание* |
| [`ClientCancelAllOrders`](#method-clientcancelallorders) | *Описание* |
| [`ClientCancelOrder`](#method-clientcancelorder) | *Описание* |
| [`ClientConnect`](#method-clientconnect) | *Описание* |
| [`ClientDisconnect`](#method-clientdisconnect) | *Описание* |
| [`ClientModifyOrder`](#method-clientmodifyorder) | *Описание* |
| [`ClientPlaceOrder`](#method-clientplaceorder) | *Описание* |
| [`ClientUpdateUserPosition`](#method-clientupdateuserposition) | *Описание* |
| [`FilterAccount`](#method-filteraccount) | *Описание* |
| [`GetAccount`](#method-getaccount) | *Описание* |
| [`GetAccounts`](#method-getaccounts) | *Описание* |
| [`GetConnectionInfo`](#method-getconnectioninfo) | *Описание* |
| [`GetConnectionsInfo`](#method-getconnectionsinfo) | *Описание* |
| [`GetExecutions`](#method-getexecutions) | *Описание* |
| [`GetOrders`](#method-getorders) | *Описание* |
| [`GetOrdersCount`](#method-getorderscount) | *Описание* |
| [`GetPositionsCount`](#method-getpositionscount) | *Описание* |
| [`GetSimAccounts`](#method-getsimaccounts) | *Описание* |
| [`GetUserPosition`](#method-getuserposition) | *Описание* |
| [`IsClientConnected`](#method-isclientconnected) | *Описание* |
| [`IsTradeAllowed`](#method-istradeallowed) | *Описание* |
| [`LoadTrustAccounts`](#method-loadtrustaccounts) | *Описание* |
| [`ProcessMarketData`](#method-processmarketdata) | *Описание* |
| [`ProcessTradeData`](#method-processtradedata) | *Описание* |
| [`SetTradeMode`](#method-settrademode) | *Описание* |
| [`Subscribe`](#method-subscribe) | *Описание* |
| [`SyncSlTp`](#method-syncsltp) | *Описание* |
| [`UnSubscribe`](#method-unsubscribe) | *Описание* |

# Список свойств
| Название | Описание |
| --- | --- |
| [`Player`](#property-player) | *Описание* |
| [`Simulator`](#property-simulator) | *Описание* |

# Список событий
| Название | Описание |
| --- | --- |
| [`Action`](#event-action) | *Описание* |
| [`Action`](#event-action) | *Описание* |
| [`Action`](#event-action) | *Описание* |
| [`Action`](#event-action) | *Описание* |
| [`OnAccountsReady;`](#event-onaccountsready;) | *Описание* |
| [`OnBarsObtained;`](#event-onbarsobtained;) | *Описание* |
| [`OnConnected;`](#event-onconnected;) | *Описание* |
| [`OnDisconnected;`](#event-ondisconnected;) | *Описание* |
| [`OnDom;`](#event-ondom;) | *Описание* |
| [`OnError;`](#event-onerror;) | *Описание* |
| [`OnExecution;`](#event-onexecution;) | *Описание* |
| [`OnInfo;`](#event-oninfo;) | *Описание* |
| [`OnOrder;`](#event-onorder;) | *Описание* |
| [`OnOrderInfo;`](#event-onorderinfo;) | *Описание* |
| [`OnPortfolio;`](#event-onportfolio;) | *Описание* |
| [`OnPosition;`](#event-onposition;) | *Описание* |
| [`OnSecurity;`](#event-onsecurity;) | *Описание* |
| [`OnTick;`](#event-ontick;) | *Описание* |
| [`OnTicksObtained;`](#event-onticksobtained;) | *Описание* |
| [`OnUserDeal;`](#event-onuserdeal;) | *Описание* |
| [`OnUserPosition;`](#event-onuserposition;) | *Описание* |





***  
***  
# Методы

## `AutoConnect`<a href="method-autoconnect" id="method-autoconnect"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void AutoConnect()
```

***  

## `ClientCancelAllOrders`<a href="method-clientcancelallorders" id="method-clientcancelallorders"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientCancelAllOrders(OrderGroup group)
```

`group` <mark style="color:red;">*`OrderGroup`*</mark>  
 *Описание*  


***  

## `ClientCancelOrder`<a href="method-clientcancelorder" id="method-clientcancelorder"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientCancelOrder(Order order)
```
`order` <mark style="color:red;">*`Order`*</mark>  
 *Описание*  


***  

## `ClientConnect`<a href="method-clientconnect" id="method-clientconnect"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientConnect(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `ClientDisconnect`<a href="method-clientdisconnect" id="method-clientdisconnect"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientDisconnect(string connectionID)
```

***  

## `ClientModifyOrder`<a href="method-clientmodifyorder" id="method-clientmodifyorder"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientModifyOrder(Order order)
```

`order` <mark style="color:red;">*`Order`*</mark>  
 *Описание*  


***  

## `ClientPlaceOrder`<a href="method-clientplaceorder" id="method-clientplaceorder"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientPlaceOrder(Order order)
```

***  

## `ClientUpdateUserPosition`<a href="method-clientupdateuserposition" id="method-clientupdateuserposition"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ClientUpdateUserPosition(UserPositionData position)
```

`position` <mark style="color:red;">*`UserPositionData`*</mark>  
 *Описание*  


***  

## `FilterAccount`<a href="method-filteraccount" id="method-filteraccount"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool FilterAccount(Account account)
```
`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `FilterAccount`<a href="method-filteraccount" id="method-filteraccount"></a>
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

## `GetAccount`<a href="method-getaccount" id="method-getaccount"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static Account GetAccount(string accountID)
```

***  

## `GetAccounts`<a href="method-getaccounts" id="method-getaccounts"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetAccounts(Symbol symbol, bool isOfflineAccount = false)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`isOfflineAccount` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `GetAccounts`<a href="method-getaccounts" id="method-getaccounts"></a>
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

## `GetConnectionInfo`<a href="method-getconnectioninfo" id="method-getconnectioninfo"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static ConnectionInfo GetConnectionInfo(string id)
```
`id` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `GetConnectionsInfo`<a href="method-getconnectionsinfo" id="method-getconnectionsinfo"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static IEnumerable<ConnectionInfo> GetConnectionsInfo()
```

***  

## `GetExecutions`<a href="method-getexecutions" id="method-getexecutions"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Execution> GetExecutions(Symbol symbol, Account account)
```

`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `GetOrders`<a href="method-getorders" id="method-getorders"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Order> GetOrders(Symbol symbol, Account account)
```

***  

## `GetOrdersCount`<a href="method-getorderscount" id="method-getorderscount"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static int GetOrdersCount()
```

***  

## `GetPositionsCount`<a href="method-getpositionscount" id="method-getpositionscount"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static int GetPositionsCount()
```

***  

## `GetSimAccounts`<a href="method-getsimaccounts" id="method-getsimaccounts"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static List<Account> GetSimAccounts()
```

`List` <mark style="color:red;">*`new`*</mark>  
 *Описание*  


***  

## `GetUserPosition`<a href="method-getuserposition" id="method-getuserposition"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static UserPosition GetUserPosition(Symbol symbol, Account account)
```
`symbol` <mark style="color:red;">*`Symbol`*</mark>  
 *Описание*  

`account` <mark style="color:red;">*`Account`*</mark>  
 *Описание*  


***  

## `IsClientConnected`<a href="method-isclientconnected" id="method-isclientconnected"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsClientConnected(string connectionID)
```
`connectionID` <mark style="color:red;">*`string`*</mark>  
 *Описание*  


***  

## `IsTradeAllowed`<a href="method-istradeallowed" id="method-istradeallowed"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool IsTradeAllowed(UserPosition position)
```
`position` <mark style="color:red;">*`UserPosition`*</mark>  
 *Описание*  


***  

## `IsTradeAllowed`<a href="method-istradeallowed" id="method-istradeallowed"></a>
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

## `LoadTrustAccounts`<a href="method-loadtrustaccounts" id="method-loadtrustaccounts"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void LoadTrustAccounts(List<TrustAccount> accounts)
```

***  

## `ProcessMarketData`<a href="method-processmarketdata" id="method-processmarketdata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ProcessMarketData()
```

***  

## `ProcessTradeData`<a href="method-processtradedata" id="method-processtradedata"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void ProcessTradeData()
```

***  

## `SetTradeMode`<a href="method-settrademode" id="method-settrademode"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SetTradeMode(int tradeMode, bool init)
```

`tradeMode` <mark style="color:red;">*`int`*</mark>  
 *Описание*  

`init` <mark style="color:red;">*`bool`*</mark>  
 *Описание*  


***  

## `Subscribe`<a href="method-subscribe" id="method-subscribe"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void Subscribe(SubscriptionFlags flags, params Symbol[] symbols)
```
`flags` <mark style="color:red;">*`SubscriptionFlags`*</mark>  
 *Описание*  

`Symbol` <mark style="color:red;">*`params`*</mark>  
 *Описание*  


***  

## `SyncSlTp`<a href="method-syncsltp" id="method-syncsltp"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static void SyncSlTp()
```

***  

## `UnSubscribe`<a href="method-unsubscribe" id="method-unsubscribe"></a>
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

## `Player`<a href="property-player" id="property-player"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool Player { get; private set; }
```  
***

## `Simulator`<a href="property-simulator" id="property-simulator"></a>
Пространство имён, которое позволяет создавать и настраивать внутрипрограммные оповещение. Т.е. которые реализованы в рамках самой торговой платформы, а не, к примеру средствами Windows.

```csharp
public static bool Simulator { get; private set; }
```  
***
***  
 ***  
# События

## `Action`<a href="event-action" id="event-action"></a>
Описание

```csharp
public static event Action OnUpdateAccount
```

## `Action`<a href="event-action" id="event-action"></a>
Описание

```csharp
public static event Action OnClearMarket
```

## `Action`<a href="event-action" id="event-action"></a>
Описание

```csharp
public static event Action OnUpdateFilters
```

## `Action`<a href="event-action" id="event-action"></a>
Описание

```csharp
public static event Action OnReferralDetected
```

## `OnAccountsReady;`<a href="event-onaccountsready;" id="event-onaccountsready;"></a>
Описание

```csharp
public static event Action<ConnectionInfo> OnAccountsReady;
```

## `OnBarsObtained;`<a href="event-onbarsobtained;" id="event-onbarsobtained;"></a>
Описание

```csharp
public static event Action<BarsResponce> OnBarsObtained;
```

## `OnConnected;`<a href="event-onconnected;" id="event-onconnected;"></a>
Описание

```csharp
public static event Action<ConnectionInfo> OnConnected;
```

## `OnDisconnected;`<a href="event-ondisconnected;" id="event-ondisconnected;"></a>
Описание

```csharp
public static event Action<ConnectionInfo> OnDisconnected;
```

## `OnDom;`<a href="event-ondom;" id="event-ondom;"></a>
Описание

```csharp
public static event Action<MarketDepth> OnDom;
```

## `OnError;`<a href="event-onerror;" id="event-onerror;"></a>
Описание

```csharp
public static event Action<ConnectionInfo, string> OnError;
```

## `OnExecution;`<a href="event-onexecution;" id="event-onexecution;"></a>
Описание

```csharp
public static event Action<Execution> OnExecution;
```

## `OnInfo;`<a href="event-oninfo;" id="event-oninfo;"></a>
Описание

```csharp
public static event Action<ConnectionInfo, string> OnInfo;
```

## `OnOrder;`<a href="event-onorder;" id="event-onorder;"></a>
Описание

```csharp
public static event Action<Order> OnOrder;
```

## `OnOrderInfo;`<a href="event-onorderinfo;" id="event-onorderinfo;"></a>
Описание

```csharp
public static event Action<OrderInfo> OnOrderInfo;
```

## `OnPortfolio;`<a href="event-onportfolio;" id="event-onportfolio;"></a>
Описание

```csharp
public static event Action<Portfolio> OnPortfolio;
```

## `OnPosition;`<a href="event-onposition;" id="event-onposition;"></a>
Описание

```csharp
public static event Action<Position> OnPosition;
```

## `OnSecurity;`<a href="event-onsecurity;" id="event-onsecurity;"></a>
Описание

```csharp
public static event Action<Security> OnSecurity;
```

## `OnTick;`<a href="event-ontick;" id="event-ontick;"></a>
Описание

```csharp
public static event Action<Tick> OnTick;
```

## `OnTicksObtained;`<a href="event-onticksobtained;" id="event-onticksobtained;"></a>
Описание

```csharp
public static event Action<TicksResponce> OnTicksObtained;
```

## `OnUserDeal;`<a href="event-onuserdeal;" id="event-onuserdeal;"></a>
Описание

```csharp
public static event Action<UserDeal> OnUserDeal;
```

## `OnUserPosition;`<a href="event-onuserposition;" id="event-onuserposition;"></a>
Описание

```csharp
public static event Action<UserPosition> OnUserPosition;
```

