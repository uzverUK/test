
# CandlePatternSourcePatternType.cs
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Sources
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public enum CandlePatternSourcePatternType
```


## Значения
| Название | Описание |
| --- | --- |
| ` TwoCrows` | *Описание* |
| ` ThreeBlackCrows` | *Описание* |
| ` ThreeInsideUpDown` | *Описание* |
| ` ThreeLineStrike` | *Описание* |
| ` ThreeOutsideUpDown` | *Описание* |
| ` ThreeStarsInTheSouth` | *Описание* |
| ` ThreeAdvancingWhiteSoldiers` | *Описание* |
| ` AbandonedBaby` | *Описание* |
| ` AdvanceBlock` | *Описание* |
| ` Belthold` | *Описание* |
| ` Breakaway` | *Описание* |
| ` ClosingMarubozu` | *Описание* |
| ` ConcealingBabySwallow` | *Описание* |
| ` Counterattack` | *Описание* |
| ` DarkCloudCover` | *Описание* |
| ` Doji` | *Описание* |
| ` DojiStar` | *Описание* |
| ` DragonflyDoji` | *Описание* |
| ` EngulfingPattern` | *Описание* |
| ` EveningDojiStar` | *Описание* |
| ` EveningStar` | *Описание* |
| ` UpDownGap` | *Описание* |
| ` GravestoneDoji` | *Описание* |
| ` Hammer` | *Описание* |
| ` HangingMan` | *Описание* |
| ` HaramiPattern` | *Описание* |
| ` HaramiCrossPattern` | *Описание* |
| ` HighWaveCandle` | *Описание* |
| ` HikkakePattern` | *Описание* |
| ` ModifiedHikkakePattern` | *Описание* |
| ` HomingPigeon` | *Описание* |
| ` IdenticalThreeCrows` | *Описание* |
| ` InNeckPattern` | *Описание* |
| ` InvertedHammer` | *Описание* |
| ` Kicking` | *Описание* |
| ` KickingBullBear` | *Описание* |
| ` LadderBottom` | *Описание* |
| ` LongLeggedDoji` | *Описание* |
| ` LongLineCandle` | *Описание* |
| ` Marubozu` | *Описание* |
| ` MatchingLow` | *Описание* |
| ` MatHold` | *Описание* |
| ` MorningDojiStar` | *Описание* |
| ` MorningStar` | *Описание* |
| ` OnNeckPattern` | *Описание* |
| ` PiercingPattern` | *Описание* |
| ` RickshawMan` | *Описание* |
| ` RisingFallingThreeMethods` | *Описание* |
| ` SeparatingLines` | *Описание* |
| ` ShootingStar` | *Описание* |
| ` ShortLineCandle` | *Описание* |
| ` SpinningTop` | *Описание* |
| ` StalledPattern` | *Описание* |
| ` StickSandwich` | *Описание* |
| ` Takuri` | *Описание* |
| ` TasukiGap` | *Описание* |
| ` ThrustingPattern` | *Описание* |
| ` TristarPattern` | *Описание* |
| ` Unique3River` | *Описание* |
| ` UpsideGapTwoCrows` | *Описание* |
| ` UpsideDownsideGapThreeMethods` | *Описание* |


## Пример
```csharp
public enum Weekday
{
    Monday,
    Tuesday,
    Wednesday,
    Thursday,
    Friday,
    Saturday,sssss
    Sunday
}
Weekday today = Weekday.Tuesday;
Console.WriteLine("Today is {0}.", today);
```

