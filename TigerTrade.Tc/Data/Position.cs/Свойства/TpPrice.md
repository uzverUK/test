
# Position.cs
## Расположение
```csharp
namespace TigerTrade.Tc.Data  
    class Position
```

> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public double? TpPrice { get; set; }
```

## Пример
```csharp
// Пример комментария
x -= moveSize + 1;

var y = GetY(Canvas.IsStock ? (double)tick.Price : 0.5);

// Пример комментария
var tradeDrawData = new TickData
{
    Size = tick.Size,
    IsBuy = tick.IsBuy,
    DrawSize = drawVolume,

    Radius = radius,
    Center = new Point(x, y),
    Rect = new Rect(x - radius, y - radius, radius * 2, radius * 2),
};
```
