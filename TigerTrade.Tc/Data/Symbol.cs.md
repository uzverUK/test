
# public sealed class Symbol
## Расположение
```csharp
namespace TigerTrade.Tc.Data
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class Symbol
```


## Методы
| Название | Описание |
| --- | --- |
| [`GetSymbol`](./Symbol.cs/metody/GetSymbol.md) | *Описание* |
| [`GetSymbol`](./Symbol.cs/metody/GetSymbol.md) | *Описание* |
| [`CheckContract`](./Symbol.cs/metody/CheckContract.md) | *Описание* |
| [`CheckContract`](./Symbol.cs/metody/CheckContract.md) | *Описание* |
| [`CurrentSymbolID`](./Symbol.cs/metody/CurrentSymbolID.md) | *Описание* |
| [`GetContracts`](./Symbol.cs/metody/GetContracts.md) | *Описание* |
| [`GetStepPrice`](./Symbol.cs/metody/GetStepPrice.md) | *Описание* |
| [`GetShortPrice`](./Symbol.cs/metody/GetShortPrice.md) | *Описание* |
| [`GetRealPrice`](./Symbol.cs/metody/GetRealPrice.md) | *Описание* |
| [`GetShortSize`](./Symbol.cs/metody/GetShortSize.md) | *Описание* |
| [`GetRealSize`](./Symbol.cs/metody/GetRealSize.md) | *Описание* |
| [`FormatPrice`](./Symbol.cs/metody/FormatPrice.md) | *Описание* |
| [`FormatPrice`](./Symbol.cs/metody/FormatPrice.md) | *Описание* |
| [`FormatPrice`](./Symbol.cs/metody/FormatPrice.md) | *Описание* |
| [`FormatPrice`](./Symbol.cs/metody/FormatPrice.md) | *Описание* |
| [`FormatSize`](./Symbol.cs/metody/FormatSize.md) | *Описание* |
| [`FormatSize`](./Symbol.cs/metody/FormatSize.md) | *Описание* |
| [`FormatAvgSize`](./Symbol.cs/metody/FormatAvgSize.md) | *Описание* |
| [`FormatFullSize`](./Symbol.cs/metody/FormatFullSize.md) | *Описание* |
| [`FormatFullSize`](./Symbol.cs/metody/FormatFullSize.md) | *Описание* |
| [`FormatFullSize`](./Symbol.cs/metody/FormatFullSize.md) | *Описание* |
| [`FormatPnl`](./Symbol.cs/metody/FormatPnl.md) | *Описание* |
| [`FormatPnl`](./Symbol.cs/metody/FormatPnl.md) | *Описание* |
| [`FormatTime`](./Symbol.cs/metody/FormatTime.md) | *Описание* |
| [`FormatTime`](./Symbol.cs/metody/FormatTime.md) | *Описание* |
| [`ConvertTimeToLocal`](./Symbol.cs/metody/ConvertTimeToLocal.md) | *Описание* |
| [`ConvertTimeFromLocal`](./Symbol.cs/metody/ConvertTimeFromLocal.md) | *Описание* |
| [`UpdateFields`](./Symbol.cs/metody/UpdateFields.md) | *Описание* |
| [`ToString`](./Symbol.cs/metody/ToString.md) | *Описание* |
| [`GetBaseCurrency`](./Symbol.cs/metody/GetBaseCurrency.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`ID`](./Symbol.cs/svoistva/ID.md) | *Описание* |
| [`Type`](./Symbol.cs/svoistva/Type.md) | *Описание* |
| [`LongCode`](./Symbol.cs/svoistva/LongCode.md) | *Описание* |
| [`Currency`](./Symbol.cs/svoistva/Currency.md) | *Описание* |
| [`Exchange`](./Symbol.cs/svoistva/Exchange.md) | *Описание* |
| [`LotSize`](./Symbol.cs/svoistva/LotSize.md) | *Описание* |
| [`Step`](./Symbol.cs/svoistva/Step.md) | *Описание* |
| [`Precision`](./Symbol.cs/svoistva/Precision.md) | *Описание* |
| [`SizeStep`](./Symbol.cs/svoistva/SizeStep.md) | *Описание* |
| [`SizePrecision`](./Symbol.cs/svoistva/SizePrecision.md) | *Описание* |
| [`PnlPrecision`](./Symbol.cs/svoistva/PnlPrecision.md) | *Описание* |
| [`ContactValue`](./Symbol.cs/svoistva/ContactValue.md) | *Описание* |
| [`Name`](./Symbol.cs/svoistva/Name.md) | *Описание* |
| [`Description`](./Symbol.cs/svoistva/Description.md) | *Описание* |
| [`Mapping`](./Symbol.cs/svoistva/Mapping.md) | *Описание* |
| [`LotStep`](./Symbol.cs/svoistva/LotStep.md) | *Описание* |
| [`MinQty`](./Symbol.cs/svoistva/MinQty.md) | *Описание* |
| [`MinNotional`](./Symbol.cs/svoistva/MinNotional.md) | *Описание* |
| [`OptAsset`](./Symbol.cs/svoistva/OptAsset.md) | *Описание* |
| [`OptType`](./Symbol.cs/svoistva/OptType.md) | *Описание* |
| [`OptStrike`](./Symbol.cs/svoistva/OptStrike.md) | *Описание* |
| [`Expiration`](./Symbol.cs/svoistva/Expiration.md) | *Описание* |
| [`Master`](./Symbol.cs/svoistva/Master.md) | *Описание* |
| [`AdditionalData`](./Symbol.cs/svoistva/AdditionalData.md) | *Описание* |
| [`IsMaster`](./Symbol.cs/svoistva/IsMaster.md) | *Описание* |
| [`IsDeleted`](./Symbol.cs/svoistva/IsDeleted.md) | *Описание* |
| [`SpecChangeUtcDate`](./Symbol.cs/svoistva/SpecChangeUtcDate.md) | *Описание* |
| [`IsLinkable`](./Symbol.cs/svoistva/IsLinkable.md) | *Описание* |
| [`IsSplicedFutures`](./Symbol.cs/svoistva/IsSplicedFutures.md) | *Описание* |
| [`IsCrypto`](./Symbol.cs/svoistva/IsCrypto.md) | *Описание* |
| [`IsCryptoFuture`](./Symbol.cs/svoistva/IsCryptoFuture.md) | *Описание* |


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

