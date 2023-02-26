
> Tiger.Trade uses dynamic depth of market (DOM). Unlike with traditional DOM, dynamic DOM provides precise tracking of the dynamics of changing prices. There are three additional sections in the DOM window. The first section displays information about opening positions, your financial results for the day, and a list of your recent trades.

## Синтаксис
```csharp
public static event Action<ConnectionInfo> OnDisconnected;
```

## Пример
```csharp
using System;

class Program
{
    // Declare the event delegate (if using non-generic pattern).
    public delegate void EventHandler(object sender, EventArgs e);

    // Declare the event using the delegate (if using non-generic pattern).
    public event EventHandler MyEvent;

    static void Main()
    {
        Program program = new Program();
        program.Run();
    }

    public void Run()
    {
        // Raise the event.
        OnMyEvent(EventArgs.Empty);
    }

    // Wrap the event in a protected virtual method
    // to enable derived classes to override the event invocation behavior.
    protected virtual void OnMyEvent(EventArgs e)
    {
        // Copy a reference to the delegate field now into a temporary field for thread safety.
        EventHandler handler = MyEvent;

        // If any subscribers exist, notify them of the event.
        if (handler != null)
        {
            handler(this, e);
        }
    }
}

```
