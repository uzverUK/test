# Base

`namespace` [TigerTrade.Chart](../../../).Base

Пространство имён содержит в себе, в большинстве своём, интерфейсы, через которые, из индикатора\графического объекта, можно получить доступ к функционалу для работы с базовым параметрам графика, как, к примеру, тема, формат отображения полученных данных с биржи на графике, информация об инструменте, который открыт на графике либо же к самому полотну, на котором отображается график и множеству его данных.&#x20;

### Пространства имён

| Название          | Описание                                                      |
| ----------------- | ------------------------------------------------------------- |
| [`Enums`](enums/) | _Перечисления периодов и видов отображения данных на графике_ |

### Интерфейсы

| Название                                 | Описание                                                   |
| ---------------------------------------- | ---------------------------------------------------------- |
| [`IChartCanvas`](ichartcanvas.cs.md)     | _Интерфейс для получения параметров из канваса графика_    |
| [`IChartPeriod`](ichartperiod.cs.md)     | _===_                                                      |
| [`IChartSettings`](ichartsettings.cs.md) | _===_                                                      |
| [`IChartSymbol`](ichartsymbol.cs.md)     | _Интерфейс для работы с текущим инструментом на графике_   |
| [`IChartTheme`](icharttheme.cs.md)       | _Интерфейс для получения параметров цветовой темы графика_ |

### Классы

| Название                         | Описание                          |
| -------------------------------- | --------------------------------- |
| [`ClientInfo`](clientinfo.cs.md) | _Информация о клиенте TigerTrade_ |
