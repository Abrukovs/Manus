# Ежедневный мультиспортивный анализ V2.0

**Дата отчёта:** 2026-10-28 05:00 по Москве  
**Окно событий:** 2026-10-28 05:00 — 2026-10-29 05:00 по Москве  
**Виды спорта:** теннис, хоккей и баскетбол  
**Футбол:** исключён  
**Ставки:** не совершались

## Итог

Проверен пул матчей всех трёх доступных видов спорта. Основной выбор — **Philadelphia 76ers ML против Indiana Pacers**, ориентировочный коэффициент около `1,60–1,68`, модель DRatings — `62,8%`. Уверенность средняя: направление поддержано линией и моделью, но у Philadelphia есть несколько игроков со статусом day-to-day.

После основного выбора добавлены отдельные альтернативы. Они не увеличивают лимит основных вариантов и не являются ставками.

## Основной выбор

### Philadelphia 76ers ML — Indiana Pacers

**Рынок:** победа Philadelphia 76ers, NBA ML.  
**Коэффициент:** ESPN около `-166` (десятичный примерно `1,60`); Statz показывает ориентир `1,68`. Коэффициент проходит порог `1,50`. [1] [2]  
**Правило расчёта:** стандартный NBA ML; победа определяется с учётом овертайма. Regulation-only рынок не использовался.  
**Модель:** DRatings даёт Philadelphia `62,8%`, Indiana `37,2%`. [3]  
**Уверенность:** средняя.  
**Ставка:** не совершалась.

Официальная карточка NBA подтверждает матч 28 октября в 19:00 ET на площадке Indiana. Philadelphia входит в игру с балансом `3-1`, Indiana — `2-2`. [4]

Кадровая ситуация неоднозначная, но важная. DeepMetrics указывает у Philadelphia Joel Embiid, VJ Edgecombe и Jabari Walker как day-to-day, а у Indiana Ivica Zubac и Andrew Nembhard как day-to-day; T.J. McConnell и ещё несколько игроков Indiana отмечены как out. Официальный NBA Injury Report является первичным источником статусов, но статусы могут обновляться до начала игры. [5] [6]

Statz показывает рыночный ориентир Philadelphia `1,68`, что близко к линии, а DRatings поддерживает Philadelphia вероятностью `62,8%`. Поэтому вариант выбран по хорошей вероятности успеха, а не как доказанная value-ставка. Главный риск — возможное ограничение или неучастие Embiid/Edgecombe; перед матчем составы требуют повторной проверки.

## Альтернативы после основного выбора

### Atlanta Hawks ML — Miami Heat

**Статус:** хороший вариант, но цена короткая и модельная поддержка умеренная.  
**Коэффициент:** около `1,62` (`-162`), выше `1,50`.  
**Независимая оценка:** DRatings — Atlanta `57,7%`, выше 50%. [3]  
**Почему не основной:** цена требует около `61,8%` до учёта маржи, поэтому value не подтверждён; модельное преимущество над Miami небольшое. Дополнительного подтверждения составов в доступном окне было недостаточно.

### Nikoloz Basilashvili ML — Jurij Rodionov, Vienna

**Статус:** альтернативный теннисный вариант с модельной вероятностью выше 50%.  
**Коэффициент:** Basilashvili около `1,88`, выше `1,50`.  
**Независимая оценка:** TennisPrediction — Basilashvili `62,86%`. [7]  
**Почему не основной:** доступный источник одновременно показывает цену и модель; второй независимый источник линии и отдельное подтверждение состава именно на странице матча не были получены в достаточном объёме. Поэтому вариант отмечен как альтернатива, а не как основной выбор.

### Другие теннисные альтернативы из того же проверенного модельного пула

- Lorenzo Musetti ML — около `2,02`, модель TennisPrediction `58,84%`.
- Jan-Lennard Struff ML — около `1,76`, модель `59,17%`.
- Alex de Minaur ML — около `1,87`, модель `51,37%`.

Эти варианты проходят формальный порог коэффициента и независимой оценки выше 50%, но не стали основными из-за отсутствия второго подтверждённого источника линии/состава в текущем запуске. Рынки отдельных сетов не рассматривались; общий тотал геймов не выбирался без дополнительной согласованной линии.

### Хоккейные кандидаты, не вынесенные в альтернативы

Colorado Avalanche ML около `1,54` (`-185`) и Buffalo Sabres ML около `1,68` (`-148`) проходят по цене, но в доступных источниках не была получена независимая вероятность победы выше 50%, согласованная именно с выбранным ML. Поэтому они не были искусственно добавлены в альтернативы.

## Хоккей

### Проверенный пул

Официальный календарь и NHL Gamecenter подтверждают матчи в окне: Buffalo — San Jose, Philadelphia — Washington, Calgary — Edmonton, New Jersey — Colorado и Toronto — Seattle. [8] [9]

ESPN показывает следующие 2-way линии: Buffalo `-148`, Washington `-230`, Edmonton `-218`, Colorado `-185`, Toronto `-120`; тоталы преимущественно `6,5`. SportsJaw даёт независимый набор ориентиров для Philadelphia — Washington (`+192/-222`, total 6), Calgary — Edmonton (`+184/-212`, total 6,5), New Jersey — Colorado (`+154/-172`, total 6,5) и Toronto — Seattle (`-117/+103`, total 6,5). [9] [10]

Для каждого хоккейного кандидата проверялись 2-way ML с ОТ/буллитами, regulation-only 3-way ML при наличии и общий тотал. Стандартный 2-way ML не смешивался с regulation-only рынком. Если был доступен только 2-way ориентир, отсутствие 3-way не считалось автоматическим блокером. Тоталы не выбраны, поскольку источники показывали разные линии или не давали достаточной модельной поддержки.

### Devils — Avalanche

Официальный NHL Gamecenter подтверждает матч 28 октября в 21:00 ET, New Jersey `7-4-0`, Colorado `6-5-1`. Карточка также показывает форму вратарей и командную статистику. [11] SportsJaw указывает ориентир Colorado `-172`, а ESPN — около `-185`. Цена выше `1,50`, но независимой вероятности победы, достаточной для альтернативного статуса, не найдено. Вариант оставлен кандидатом, но не опубликован.

## Баскетбол

### Проверенный пул

Официальное расписание NBA подтверждает 12 матчей: Miami — Atlanta, Washington — Cleveland, Philadelphia — Indiana, Charlotte — Detroit, Orlando — Toronto, New York — Chicago, Houston — Milwaukee, Golden State — Minnesota, Denver — New Orleans, San Antonio — Utah, Oklahoma City — Dallas и Los Angeles Lakers — Los Angeles Clippers. [12]

ESPN показывает линии, включая Miami `+136` / Atlanta `-162`, Washington `+310` / Cleveland `-395`, Philadelphia `-166` / Indiana `+140`, Orlando `+145` / Toronto `-175` и New York `-270` / Chicago `+220`, а также остальные матчи. Фавориты с коэффициентом ниже `1,50`, включая Cleveland и New York, не рассматривались как допустимые основные варианты. [1]

DRatings даёт оценки: Atlanta `57,7%`, Cleveland `76,5%`, Philadelphia `62,8%`, Detroit `63,1%`, Toronto `63,0%`, New York `65,9%`, Milwaukee `65,7%`, San Antonio `73,8%` и другие. Cleveland, New York и часть других фаворитов исключены из основных рынков из-за коэффициента ниже `1,50`; Atlanta вынесена в альтернативы. [3]

ML и общий тотал NBA трактовались как рынки с учётом овертайма. Для каждого кандидата просматривались ML и тотал; выбран только Philadelphia ML.

## Теннис

Официальные страницы ATP подтверждают турниры Erste Bank Open в Vienna и Swiss Indoors Basel, оба проходят 26 октября — 1 ноября 2026 года. [13] [14] TennisPrediction показывает пары и цены на 28 октября, включая Vienna: Musetti — Tiafoe, Rodionov — Basilashvili и другие; Basel: Struff — Hanfmann, De Minaur — Tien и другие. [7]

В основной список теннис не включён, потому что по доступному окну не удалось получить одновременно отдельную линию, независимую модель и полноценную официальную карточку конкретной пары. Тем не менее варианты с коэффициентом выше `1,50` и модельной вероятностью выше `50%` показаны в разделе альтернатив, как требует V2.0.

## Вывод

Основной вариант сегодня один: **Philadelphia 76ers ML** с умеренной уверенностью и обязательной оговоркой о кадровом статусе Embiid/Edgecombe. Дополнительно отмечены Atlanta ML как хороший вариант с короткой ценой и несколько теннисных ML с независимой модельной оценкой выше 50%. Ставки не совершались.

## References

[1]: https://www.espn.com/nba/odds "ESPN NBA odds for October 28, 2026"
[2]: https://statz.ai/nba/games/indiana-pacers-vs-philadelphia-76ers-2026-10-28/preview/projections "Statz 76ers–Pacers market and projections"
[3]: https://www.dratings.com/predictor/nba-basketball-predictions/upcoming/2 "DRatings NBA probabilities for October 28"
[4]: https://www.nba.com/game/phi-vs-ind-0022600135 "Official NBA 76ers–Pacers game card"
[5]: https://deepmetricanalytics.com/nba/game/401909884 "DeepMetrics 76ers–Pacers injuries and preview"
[6]: https://official.nba.com/nba-injury-report-2026-27-season/ "Official NBA injury report archive"
[7]: https://www.tennisprediction.com/ "TennisPrediction prices and model probabilities for October 28"
[8]: https://www.nhl.com/schedule/2026-10-28 "Official NHL schedule for October 28"
[9]: https://www.espn.com/nhl/odds "ESPN NHL odds for October 28"
[10]: https://sportsjaw.com/picks/nhl/10-28-2026 "SportsJaw NHL picks and consensus lines"
[11]: https://www.nhl.com/gamecenter/njd-vs-col/2026/10/28/2026020201 "Official NHL Devils–Avalanche game card"
[12]: https://www.nba.com/schedule "Official NBA schedule for October 28"
[13]: https://www.atptour.com/en/tournaments/vienna/337/overview "Official ATP Vienna tournament page"
[14]: https://www.atptour.com/en/tournaments/basel/328/overview "Official ATP Basel tournament page"
