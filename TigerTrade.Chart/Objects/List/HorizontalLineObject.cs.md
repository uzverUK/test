
# public class HorizontalLineObject : LineObjectBase
## Расположение
```csharp
namespace TigerTrade.Chart.Objects.List
```



> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public class HorizontalLineObject : LineObjectBase
```


## Методы
| Название | Описание |
| --- | --- |
| [`HorizontalLineObject`](./HorizontalLineObject.cs/metody/HorizontalLineObject.md) | *Описание* |
| [`DrawControlPoints`](./HorizontalLineObject.cs/metody/DrawControlPoints.md) | *Описание* |
| [`CopyTemplate`](./HorizontalLineObject.cs/metody/CopyTemplate.md) | *Описание* |
| [`CheckAlert`](./HorizontalLineObject.cs/metody/CheckAlert.md) | *Описание* |

## Свойства
| Название | Описание |
| --- | --- |
| [`xsuJlZ3bylFkXacpNF53`](./HorizontalLineObject.cs/svoistva/xsuJlZ3bylFkXacpNF53.md) | *Описание* |
| [`Price`](./HorizontalLineObject.cs/svoistva/Price.md) | *Описание* |
| [`Alert`](./HorizontalLineObject.cs/svoistva/Alert.md) | *Описание* |
| [`AlertMinDistance`](./HorizontalLineObject.cs/svoistva/AlertMinDistance.md) | *Описание* |
| [`Text`](./HorizontalLineObject.cs/svoistva/Text.md) | *Описание* |
| [`TextAlignment`](./HorizontalLineObject.cs/svoistva/TextAlignment.md) | *Описание* |
| [`FontSize`](./HorizontalLineObject.cs/svoistva/FontSize.md) | *Описание* |


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

