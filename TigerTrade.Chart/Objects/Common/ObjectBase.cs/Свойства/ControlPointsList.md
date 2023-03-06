
# ObjectBase.cs
```csharp
namespace TigerTrade.Chart.Objects.Common  
    class ObjectBase
```

Описание

### Синтаксис
```csharp
public ObjectPointInfo[] ControlPointsList => ((IEnumerable<ObjectPoint>) this.ControlPoints).Select<ObjectPoint, ObjectPointInfo>((Func<ObjectPoint, int, ObjectPointInfo>) ((t, i) => new ObjectPointInfo(this.ControlPoints, i))).ToArray<ObjectPointInfo>();{ get; }
```
