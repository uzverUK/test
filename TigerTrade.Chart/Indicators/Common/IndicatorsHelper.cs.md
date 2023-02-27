
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
| [`SetDataProvider`](./IndicatorsHelper.cs/Методы/SetDataProvider.md) | *Описание* |
| [`Price`](./IndicatorsHelper.cs/Методы/Price.md) | *Описание* |
| [`MedianPrice`](./IndicatorsHelper.cs/Методы/MedianPrice.md) | *Описание* |
| [`TypicalPrice`](./IndicatorsHelper.cs/Методы/TypicalPrice.md) | *Описание* |
| [`Max`](./IndicatorsHelper.cs/Методы/Max.md) | *Описание* |
| [`Min`](./IndicatorsHelper.cs/Методы/Min.md) | *Описание* |
| [`Subtraction`](./IndicatorsHelper.cs/Методы/Subtraction.md) | *Описание* |
| [`ShiftData`](./IndicatorsHelper.cs/Методы/ShiftData.md) | *Описание* |
| [`SAR`](./IndicatorsHelper.cs/Методы/SAR.md) | *Описание* |
| [`Aroon`](./IndicatorsHelper.cs/Методы/Aroon.md) | *Описание* |
| [`SMMA`](./IndicatorsHelper.cs/Методы/SMMA.md) | *Описание* |
| [`MovingAverage`](./IndicatorsHelper.cs/Методы/MovingAverage.md) | *Описание* |
| [`PPO`](./IndicatorsHelper.cs/Методы/PPO.md) | *Описание* |
| [`CO`](./IndicatorsHelper.cs/Методы/CO.md) | *Описание* |
| [`RSI`](./IndicatorsHelper.cs/Методы/RSI.md) | *Описание* |
| [`ATR`](./IndicatorsHelper.cs/Методы/ATR.md) | *Описание* |
| [`CCI`](./IndicatorsHelper.cs/Методы/CCI.md) | *Описание* |
| [`Momentum`](./IndicatorsHelper.cs/Методы/Momentum.md) | *Описание* |
| [`ROC`](./IndicatorsHelper.cs/Методы/ROC.md) | *Описание* |
| [`ADX`](./IndicatorsHelper.cs/Методы/ADX.md) | *Описание* |
| [`PlusDI`](./IndicatorsHelper.cs/Методы/PlusDI.md) | *Описание* |
| [`MinusDI`](./IndicatorsHelper.cs/Методы/MinusDI.md) | *Описание* |
| [`Variance`](./IndicatorsHelper.cs/Методы/Variance.md) | *Описание* |
| [`WilliamsR`](./IndicatorsHelper.cs/Методы/WilliamsR.md) | *Описание* |
| [`StdDev`](./IndicatorsHelper.cs/Методы/StdDev.md) | *Описание* |
| [`UltOsc`](./IndicatorsHelper.cs/Методы/UltOsc.md) | *Описание* |
| [`AD`](./IndicatorsHelper.cs/Методы/AD.md) | *Описание* |
| [`OBV`](./IndicatorsHelper.cs/Методы/OBV.md) | *Описание* |
| [`TRIX`](./IndicatorsHelper.cs/Методы/TRIX.md) | *Описание* |
| [`MFI`](./IndicatorsHelper.cs/Методы/MFI.md) | *Описание* |
| [`CMO`](./IndicatorsHelper.cs/Методы/CMO.md) | *Описание* |
| [`LinReg`](./IndicatorsHelper.cs/Методы/LinReg.md) | *Описание* |
| [`CumDelta`](./IndicatorsHelper.cs/Методы/CumDelta.md) | *Описание* |
| [`PriceChannel`](./IndicatorsHelper.cs/Методы/PriceChannel.md) | *Описание* |
| [`VolumeOscillator`](./IndicatorsHelper.cs/Методы/VolumeOscillator.md) | *Описание* |
| [`BWMFI`](./IndicatorsHelper.cs/Методы/BWMFI.md) | *Описание* |
| [`AO`](./IndicatorsHelper.cs/Методы/AO.md) | *Описание* |
| [`AC`](./IndicatorsHelper.cs/Методы/AC.md) | *Описание* |
| [`BearsPower`](./IndicatorsHelper.cs/Методы/BearsPower.md) | *Описание* |
| [`BullsPower`](./IndicatorsHelper.cs/Методы/BullsPower.md) | *Описание* |
| [`Fractal`](./IndicatorsHelper.cs/Методы/Fractal.md) | *Описание* |
| [`CMF`](./IndicatorsHelper.cs/Методы/CMF.md) | *Описание* |
| [`EFI`](./IndicatorsHelper.cs/Методы/EFI.md) | *Описание* |
| [`ChaikinsVolatility`](./IndicatorsHelper.cs/Методы/ChaikinsVolatility.md) | *Описание* |
| [`WilliamsAD`](./IndicatorsHelper.cs/Методы/WilliamsAD.md) | *Описание* |
| [`VHF`](./IndicatorsHelper.cs/Методы/VHF.md) | *Описание* |
| [`ZIGZAG`](./IndicatorsHelper.cs/Методы/ZIGZAG.md) | *Описание* |
| [`IndicatorsHelper`](./IndicatorsHelper.cs/Методы/IndicatorsHelper.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`DataProvider`](./IndicatorsHelper.cs/Свойства/DataProvider.md) | *Описание* |
| [`Count`](./IndicatorsHelper.cs/Свойства/Count.md) | *Описание* |


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

