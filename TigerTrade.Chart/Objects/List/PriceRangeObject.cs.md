
# public sealed class PriceRangeObject : PolygonObjectBase
## Расположение
```csharp
namespace TigerTrade.Chart.Objects.List
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public sealed class PriceRangeObject : PolygonObjectBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`PriceRangeObject`](./PriceRangeObject.cs/metody/PriceRangeObject.md) | *Описание* |
| [`DrawControlPoints`](./PriceRangeObject.cs/metody/DrawControlPoints.md) | *Описание* |
| [`GetControlPoint`](./PriceRangeObject.cs/metody/GetControlPoint.md) | *Описание* |
| [`CopyTemplate`](./PriceRangeObject.cs/metody/CopyTemplate.md) | *Описание* |
| [`CheckAlert`](./PriceRangeObject.cs/metody/CheckAlert.md) | *Описание* |
| [`CQTqeP3bJqxWKjH4hGUt`](./PriceRangeObject.cs/metody/CQTqeP3bJqxWKjH4hGUt.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`xsuJlZ3bylFkXacpNF53`](./PriceRangeObject.cs/svoistva/xsuJlZ3bylFkXacpNF53.md) | *Описание* |
| [`Price1`](./PriceRangeObject.cs/svoistva/Price1.md) | *Описание* |
| [`Price2`](./PriceRangeObject.cs/svoistva/Price2.md) | *Описание* |
| [`Alert`](./PriceRangeObject.cs/svoistva/Alert.md) | *Описание* |
| [`Text`](./PriceRangeObject.cs/svoistva/Text.md) | *Описание* |
| [`TextAlignment`](./PriceRangeObject.cs/svoistva/TextAlignment.md) | *Описание* |
| [`FontSize`](./PriceRangeObject.cs/svoistva/FontSize.md) | *Описание* |
| [`ByT3bF65jIi;`](./PriceRangeObject.cs/svoistva/ByT3bF65jIi;.md) | *Описание* |
| [`PhT3bdqjeim;`](./PriceRangeObject.cs/svoistva/PhT3bdqjeim;.md) | *Описание* |
| [`Center;`](./PriceRangeObject.cs/svoistva/Center;.md) | *Описание* |
| [`vcu3bCSJvax;`](./PriceRangeObject.cs/svoistva/vcu3bCSJvax;.md) | *Описание* |
| [`VML3bztEtWe;`](./PriceRangeObject.cs/svoistva/VML3bztEtWe;.md) | *Описание* |
| [`cjH3RyrD3YP;`](./PriceRangeObject.cs/svoistva/cjH3RyrD3YP;.md) | *Описание* |
| [`jjL3RqnWW1s;`](./PriceRangeObject.cs/svoistva/jjL3RqnWW1s;.md) | *Описание* |


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

