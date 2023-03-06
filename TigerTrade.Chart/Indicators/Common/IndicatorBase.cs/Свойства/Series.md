
# IndicatorBase.cs
```csharp
namespace TigerTrade.Chart.Indicators.Common  
    class IndicatorBase
```

Описание

### Синтаксис
```csharp
public IndicatorSeries Series => this._series ?? (this._series = new IndicatorSeries());{ get; }
```
