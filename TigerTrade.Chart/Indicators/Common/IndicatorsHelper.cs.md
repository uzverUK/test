
# public sealed class IndicatorsHelper
## Расположение
```csharp
namespace TigerTrade.Chart.Indicators.Common
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class IndicatorsHelper
```


## Методы
| Название | Описание |
| --- | --- |
| [`SetDataProvider`](./IndicatorsHelper.cs/metody/SetDataProvider.md) | *Описание* |
| [`Price`](./IndicatorsHelper.cs/metody/Price.md) | *Описание* |
| [`MedianPrice`](./IndicatorsHelper.cs/metody/MedianPrice.md) | *Описание* |
| [`TypicalPrice`](./IndicatorsHelper.cs/metody/TypicalPrice.md) | *Описание* |
| [`Max`](./IndicatorsHelper.cs/metody/Max.md) | *Описание* |
| [`Min`](./IndicatorsHelper.cs/metody/Min.md) | *Описание* |
| [`Subtraction`](./IndicatorsHelper.cs/metody/Subtraction.md) | *Описание* |
| [`ShiftData`](./IndicatorsHelper.cs/metody/ShiftData.md) | *Описание* |
| [`SAR`](./IndicatorsHelper.cs/metody/SAR.md) | *Описание* |
| [`Aroon`](./IndicatorsHelper.cs/metody/Aroon.md) | *Описание* |
| [`SMMA`](./IndicatorsHelper.cs/metody/SMMA.md) | *Описание* |
| [`MovingAverage`](./IndicatorsHelper.cs/metody/MovingAverage.md) | *Описание* |
| [`PPO`](./IndicatorsHelper.cs/metody/PPO.md) | *Описание* |
| [`CO`](./IndicatorsHelper.cs/metody/CO.md) | *Описание* |
| [`RSI`](./IndicatorsHelper.cs/metody/RSI.md) | *Описание* |
| [`ATR`](./IndicatorsHelper.cs/metody/ATR.md) | *Описание* |
| [`CCI`](./IndicatorsHelper.cs/metody/CCI.md) | *Описание* |
| [`Momentum`](./IndicatorsHelper.cs/metody/Momentum.md) | *Описание* |
| [`ROC`](./IndicatorsHelper.cs/metody/ROC.md) | *Описание* |
| [`ADX`](./IndicatorsHelper.cs/metody/ADX.md) | *Описание* |
| [`PlusDI`](./IndicatorsHelper.cs/metody/PlusDI.md) | *Описание* |
| [`MinusDI`](./IndicatorsHelper.cs/metody/MinusDI.md) | *Описание* |
| [`Variance`](./IndicatorsHelper.cs/metody/Variance.md) | *Описание* |
| [`WilliamsR`](./IndicatorsHelper.cs/metody/WilliamsR.md) | *Описание* |
| [`StdDev`](./IndicatorsHelper.cs/metody/StdDev.md) | *Описание* |
| [`UltOsc`](./IndicatorsHelper.cs/metody/UltOsc.md) | *Описание* |
| [`AD`](./IndicatorsHelper.cs/metody/AD.md) | *Описание* |
| [`OBV`](./IndicatorsHelper.cs/metody/OBV.md) | *Описание* |
| [`TRIX`](./IndicatorsHelper.cs/metody/TRIX.md) | *Описание* |
| [`MFI`](./IndicatorsHelper.cs/metody/MFI.md) | *Описание* |
| [`CMO`](./IndicatorsHelper.cs/metody/CMO.md) | *Описание* |
| [`LinReg`](./IndicatorsHelper.cs/metody/LinReg.md) | *Описание* |
| [`CumDelta`](./IndicatorsHelper.cs/metody/CumDelta.md) | *Описание* |
| [`PriceChannel`](./IndicatorsHelper.cs/metody/PriceChannel.md) | *Описание* |
| [`VolumeOscillator`](./IndicatorsHelper.cs/metody/VolumeOscillator.md) | *Описание* |
| [`BWMFI`](./IndicatorsHelper.cs/metody/BWMFI.md) | *Описание* |
| [`AO`](./IndicatorsHelper.cs/metody/AO.md) | *Описание* |
| [`AC`](./IndicatorsHelper.cs/metody/AC.md) | *Описание* |
| [`BearsPower`](./IndicatorsHelper.cs/metody/BearsPower.md) | *Описание* |
| [`BullsPower`](./IndicatorsHelper.cs/metody/BullsPower.md) | *Описание* |
| [`Fractal`](./IndicatorsHelper.cs/metody/Fractal.md) | *Описание* |
| [`CMF`](./IndicatorsHelper.cs/metody/CMF.md) | *Описание* |
| [`EFI`](./IndicatorsHelper.cs/metody/EFI.md) | *Описание* |
| [`ChaikinsVolatility`](./IndicatorsHelper.cs/metody/ChaikinsVolatility.md) | *Описание* |
| [`WilliamsAD`](./IndicatorsHelper.cs/metody/WilliamsAD.md) | *Описание* |
| [`VHF`](./IndicatorsHelper.cs/metody/VHF.md) | *Описание* |
| [`ZIGZAG`](./IndicatorsHelper.cs/metody/ZIGZAG.md) | *Описание* |
| [`IndicatorsHelper`](./IndicatorsHelper.cs/metody/IndicatorsHelper.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`DataProvider`](./IndicatorsHelper.cs/svoistva/DataProvider.md) | *Описание* |
| [`Count`](./IndicatorsHelper.cs/svoistva/Count.md) | *Описание* |


## Пример
```csharp
using System;

class Program
{
    static void Main()
    {
        // Create a new instance of the Person class.
        Person person = new Person("John", "Doe", new DateTime(1990, 1, 1));

        // Display the person's full name and age.
        Console.WriteLine("Name: {0}", person.GetFullName());
        Console.WriteLine("Age: {0}", person.GetAge());
    }
}

class Person
{
    private string firstName;
    private string lastName;
    private DateTime dateOfBirth;

    public Person(string firstName, string lastName, DateTime dateOfBirth)
    {
        this.firstName = firstName;
        this.lastName = lastName;
        this.dateOfBirth = dateOfBirth;
    }

    public string GetFullName()
    {
        return firstName + " " + lastName;
    }

    public int GetAge()
    {
        TimeSpan span = DateTime.Now - dateOfBirth;
        int years = (int)(span.Days / 365.25);
        return years;
    }
}
```

