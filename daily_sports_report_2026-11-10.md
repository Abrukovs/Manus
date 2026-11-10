# Отчёт V2.0 — спортивные рынки

**Дата отчёта:** 10 ноября 2026 года  
**Окно событий:** 07:00 10.11.2026 — 07:00 11.11.2026 МСК  
**Статус:** предварительный анализ до начала матчей; ставки не совершались.

## Итог

В пул вошли 9 матчей: 3 теннисных, 3 хоккейных и 3 баскетбольных. Основные варианты ограничены двумя матчами, имеют коэффициенты не ниже 1.50 и происходят из разных матчей:

1. **Minnesota Wild — Montréal Canadiens: победа Minnesota в 2-way ML с учётом ОТ/буллитов — 1.85–1.87.** Оценка вероятности 54–55%; преимущество умеренное.
2. **Columbus Blue Jackets — Florida Panthers: победа Columbus в 2-way ML с учётом ОТ/буллитов — 1.87.** Оценка вероятности около 54%; преимущество небольшое.

Это аналитические варианты, а не распоряжение на ставку. Перед любым решением необходима повторная проверка котировки, стартовых вратарей и составов.

## Основные варианты

### 1. Minnesota Wild — Montréal Canadiens

**Начало:** 11.11.2026, 03:00 МСК (19:00 ET 10 ноября).  
**Рынок:** 2-way moneyline, включая победу в овертайме и по буллитам.  
**Коэффициент:** около 1.85–1.87 (лучшая наблюдаемая американская линия −115…−118).  
**Оценка:** 54–55%. Независимый рынок Kalshi оценивал Minnesota в 52–53%, компьютерная модель Fox Sports 710 выбирала Wild.

У Minnesota отмечены лучшие оборонительные показатели: 3.32 забитых и 2.26 пропущенных шайбы за игру против 3.47 и 3.12 у Montréal. При этом команды имеют сильный старт сезона, а разница с рыночной вероятностью невелика. Важны подтверждение стартовых вратарей и итоговых составов: сообщалось об ограничениях/отсутствии Jared Spurgeon, Brock Faber, Mike Matheson и возможной неопределённости с Samuel Montembeault.

**Правила хоккейных рынков:**
- **2-way ML с ОТ/буллитами:** учитывается победитель после основного времени, пятиминутного 3-на-3 овертайма и, если требуется, серии буллитов.
- **Regulation-only 3-way:** отдельный рынок победа Minnesota / ничья / победа Montréal после 60 минут; не выбран, поскольку надёжная цена и достаточное преимущество не подтверждены.
- Тоталы не выбраны: источники расходились между 6.0 и 6.5, а составы и вратари не были окончательно подтверждены.

### 2. Florida Panthers — Columbus Blue Jackets

**Начало:** 11.11.2026, 03:30 МСК (19:30 ET 10 ноября).  
**Рынок:** Columbus 2-way ML с ОТ/буллитами.  
**Коэффициент:** 1.87 (DraftKings через ESPN, −115).  
**Оценка:** около 54%; независимая модель также выбирала Columbus и прогнозировала 4:3.

Фактором в пользу Columbus служит домашний баланс 6–3–0. У Florida сообщалось об ограничениях Anton Lundell, Aleksander Barkov, Brad Marchand и Jonah Gadjovich, что снижает глубину состава. Однако перевес мал, а стартовые вратари и окончательные сочетания на момент проверки не были подтверждены.

**Правила хоккейных рынков:**
- **2-way ML с ОТ/буллитами:** победа Columbus засчитывается в основное время, овертайме или по буллитам; официальный NHL API указывал `otInUse=true` и `shootoutInUse=true`.
- **Regulation-only 3-way:** рынок победа Florida / ничья / победа Columbus после 60 минут в доступной линии не был найден; поэтому он не использовался.
- Тотал O5.5 был доступен примерно за 1.77, но не выбран из-за высокой зависимости от вратарей и составов.

## Альтернативы после основных вариантов

### Nicolas Jarry ML против Nikolas Sanchez Izquierdo — около 1.63
Матч 10.11, не ранее 21:00 МСК. Рыночный фаворит Jarry имеет коэффициент выше порога, а Forebet оценивает его победу примерно в 54%. Альтернатива слабее основных вариантов: Sanchez Izquierdo — восьмой сеяный и имел рейтинг ATP 151 против 790 у Jarry; независимая модель даёт лишь умеренное преимущество Jarry. Допустимо рассматривать только при сохранении коэффициента не ниже 1.50 и подтверждении участников. В теннисе овертайма нет; матч Challenger — best of 3 sets.

### Francisco Comesana ML против Marco Cecchinato — около 1.63
Матч 11.11, не ранее 01:30 МСК. Рыночный ориентир и модели склоняются к Comesana, оценка около 59%. Альтернатива уступает основным выборам из-за прямого риска: Cecchinato ведёт 2–0, включая победу над Comesana в трёх сетах в начале ноября 2026 года; также источники давали разные оценки вероятности. Коэффициент соответствует порогу, но преимущество нельзя считать сильным.

### Почему не Minnesota/Columbus regulation-only 3-way
Для обоих хоккейных матчей основной выбор сделан только в 2-way формате с ОТ/буллитами. 3-way после 60 минут не использовался: точные котировки этого рынка либо не были подтверждены, либо достаточный перевес над ничьей отсутствовал.

## Рассмотренные матчи и решения

### Теннис

| Матч | Время МСК | Доступные данные | Решение |
|---|---:|---|---|
| Fabio Manuel Zavalaga Uculmana — Alex Barrena | 18:00 | Barrena: около 1.01; независимая оценка 90.26%; Uculmana: 10.5 по TennisTonic, FanDuel показывал +1700, но полная пара линии не раскрыта | **Исключить.** Фаворит ниже 1.50; ставка на андердога имеет слабую подтверждённую вероятность; линии источников конфликтуют. |
| Nikolas Sanchez Izquierdo — Nicolas Jarry | 21:00 | Jarry 1.63, Sanchez Izquierdo около 2.18; Forebet 54% на Jarry | **Альтернатива.** Умеренное преимущество, но рейтинг и посев Sanchez Izquierdo противоречат рыночному фавориту Jarry. |
| Marco Cecchinato — Francisco Comesana | 01:30 | Comesana 1.63; оценка около 59%; H2H 0–2 для Comesana | **Альтернатива/осторожно.** Коэффициент проходит порог, но прямые встречи и разные модели повышают риск. |

### Хоккей

| Матч | Время МСК | Решение |
|---|---:|---|
| Minnesota Wild — Montréal Canadiens | 03:00 | **Основной вариант:** Minnesota 2-way ML с ОТ/буллитами, 1.85–1.87. Regulation-only 3-way не выбран; тотал исключён из-за расхождения 6.0/6.5 и неопределённости составов. |
| Florida Panthers — Columbus Blue Jackets | 03:30 | **Основной вариант:** Columbus 2-way ML с ОТ/буллитами, 1.87. Regulation-only 3-way не найден; тотал не выбран из-за составов и вратарей. |
| Detroit Red Wings — St. Louis Blues | 04:00 | **Исключить.** STL около 1.67 по рынку, но Pickswise даёт 53% на Detroit; конфликт линии и модели, составы/стартовый вратарь не подтверждены. 2-way учитывал бы ОТ/буллиты; FanDuel отдельно показывал 60-minute 3-way, но его точные цены не раскрыты. |

### Баскетбол

Во всех указанных NBA ML и full-game totals предполагается **учёт овертайма** по стандартным правилам букмекера; отдельные regulation-only рынки не использовались.

| Матч | Время МСК | Решение |
|---|---:|---|
| Milwaukee Bucks — New York Knicks | 03:30 | **Исключить.** NYK имеет высокую модельную вероятность 87–90.5%, но ML около 1.08–1.10 ниже порога; фора и тотал зависят от противоречивых injury-статусов. |
| LA Clippers — Phoenix Suns | 05:00 | **Исключить.** Букмекерская линия ML/форы/тотала не опубликована; Phoenix injury report ещё не был подан. Statz и Kalshi дают разные вероятности. |
| Orlando Magic — Sacramento Kings | 06:00 | **Исключить.** Orlando ML около 1.43 ниже порога; Sacramento 2.94 имеет только 34–35% по модели. Domantas Sabonis отмечен questionable в официальном отчёте, но трактуется иначе независимым источником; по составам есть дополнительные расхождения. |

## Риски и ограничения

1. Все оценки сделаны по предоставленным данным; нового исследования не проводилось.
2. Коэффициенты могли измениться до начала матчей. Для основных вариантов обязательна проверка, что цена остаётся не ниже 1.50.
3. Главный общий риск — неподтверждённые стартовые составы и вратари, особенно в NHL и NBA.
4. Хоккейные рынки чувствительны к ОТ и буллитам: 2-way и regulation-only 3-way нельзя смешивать при сравнении результатов.
5. В баскетболе приведённые ML и totals рассматриваются с учётом ОТ; это может отличаться от отдельных рынков на 48 минут, если букмекер их предлагает.
6. Независимые модели не являются гарантией исхода; в нескольких матчах они расходятся с рынком.
7. Ставки в рамках этого отчёта **не совершались**.

## References

[1]: https://www.atptour.com/en/scores/current-challenger/lima/6579/daily-schedule?day=3 "ATP Lima Challenger Daily Schedule — Day 3"  
[2]: https://www.atptour.com/en/scores/current-challenger/lima/6579/live-scores "ATP Lima Challenger Live Scores"  
[3]: https://www.atptour.com/en/scores/current-challenger/lima/6579/results "ATP Lima Challenger Results"  
[4]: https://www.atptour.com/en/scores/current-challenger/lima/6579/draws "ATP Lima Challenger Draws"  
[5]: https://sportsbook.fanduel.com/tennis/lima-challenger-2026/nikolas-sanchez-izquierdo-v-nicolas-jarry-36302444 "FanDuel — Sanchez Izquierdo v Jarry Odds"  
[6]: https://www.forebet.com/en/tennis/matches/challenger-men/lima-2/n-sanchez-izquierdo-n-jarry/363262 "Forebet — Sanchez Izquierdo v Jarry Prediction"  
[7]: https://www.atptour.com/en/players/atp-head-2-head/nikolas-sanchez-izquierdo-vs-nicolas-jarry/s0gz/j551 "ATP Head-to-Head — Sanchez Izquierdo v Jarry"  
[8]: https://tennistonic.com/tennis-news/1080089/h2h-prediction-of-francisco-comesana-vs-marco-cecchinato-in-lima-3-challenger-with-odds-preview-pick-10th-november-2026/ "TennisTonic — Comesana v Cecchinato Prediction"  
[9]: https://www.nhl.com/gamecenter/min-vs-mtl/2026/11/10/2026020287 "NHL Gamecenter — Wild v Canadiens"  
[10]: https://www.espn.com/nhl/game/_/gameId/401892684/wild-canadiens "ESPN — Wild v Canadiens Preview and Odds"  
[11]: https://www.nhl.com/gamecenter/fla-vs-cbj/2026/11/10/2026020289 "NHL Gamecenter — Panthers v Blue Jackets"  
[12]: https://api-web.nhle.com/v1/gamecenter/2026020289/landing "NHL API — Panthers v Blue Jackets Landing"  
[13]: https://www.espn.com/nhl/game/_/gameId/401892686/panthers-blue-jackets "ESPN — Panthers v Blue Jackets Preview and Odds"  
[14]: https://www.nhl.com/gamecenter/det-vs-stl/2026/11/10/2026020290 "NHL Gamecenter — Red Wings v Blues"  
[15]: https://www.espn.com/nhl/game/_/gameId/401892687/red-wings-blues "ESPN — Red Wings v Blues Preview and Odds"  
[16]: https://www.pickswise.com/nhl/games/st-louis-blues-detroit-red-wings-nhl-2026-11-10-2000/ "Pickswise — Red Wings v Blues Model"  
[17]: https://www.nba.com/game/mil-vs-nyk-0022600211 "NBA Game — Bucks v Knicks"  
[18]: https://www.espn.com/nba/game/_/gameId/401909960/bucks-knicks "ESPN — Bucks v Knicks Preview"  
[19]: https://www.nba.com/game/lac-vs-phx-0022600213 "NBA Game — Clippers v Suns"  
[20]: https://ak-static.cms.nba.com/referee/injury/Injury-Report_2026-11-09_08_45PM.pdf "NBA Official Injury Report — 9 Nov 2026 20:45 ET"  
[21]: https://www.nba.com/game/orl-vs-sac-0022600215 "NBA Game — Magic v Kings"  
[22]: https://sportsbook.fanduel.com/basketball/nba/orlando-magic-@-sacramento-kings-36295138 "FanDuel — Magic v Kings Odds"  
[23]: https://ak-static.cms.nba.com/referee/injury/Injury-Report_2026-11-09_10_15PM.pdf "NBA Official Injury Report — 9 Nov 2026 22:15 ET"  

**Вывод:** из доступного набора наиболее defensible варианты — Minnesota 2-way ML с ОТ/буллитами и Columbus 2-way ML с ОТ/буллитами, но оба имеют лишь умеренный перевес и требуют финальной проверки составов и цены.
