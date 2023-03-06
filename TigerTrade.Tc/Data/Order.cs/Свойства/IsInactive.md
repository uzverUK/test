
# Order.cs
```csharp
namespace TigerTrade.Tc.Data  
    class Order
```

Описание

### Синтаксис
```csharp
public bool IsInactive => this.State == OrderState.Canceled || this.State == OrderState.Completed;{ get; }
```
