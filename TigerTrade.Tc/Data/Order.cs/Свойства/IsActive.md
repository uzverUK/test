
# Order.cs
## Расположение
```csharp
namespace TigerTrade.Tc.Data  
    class Order
```

> Описание

## Синтаксис
```csharp
public bool IsActive => this.State == OrderState.Wait || this.State == OrderState.Active;{}
```
