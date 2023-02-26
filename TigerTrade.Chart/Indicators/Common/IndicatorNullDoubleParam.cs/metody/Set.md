
# IndicatorNullDoubleParam.cs
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Common  
    class IndicatorNullDoubleParam
```

> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public bool Set(string key, double? value, double minValue = -1.7976931348623157E+308, double maxValue = 1.7976931348623157E+308)
```

## Пример
```csharp
// Пример комментария
public override void ApplyColors(IChartTheme theme)
{
    // Пример комментария
    TickBuyColor = new XColor(127, theme.PaletteColor6);
    TickSellColor = new XColor(127, theme.PaletteColor7);

    base.ApplyColors(theme);
}
```
