# Отчёт V2.0: предматчевый отбор ставок

**Дата отчёта:** 7 ноября 2026 года  
**Расчётное окно:** 07:00 7 ноября — 07:00 8 ноября 2026 года, МСК  
**Статус:** предматчевый анализ; ставки не совершались.

## 1. Резюме

В окно попали семь матчей: один теннисный, три хоккейных и три баскетбольных. После проверки доступных рынков, коэффициентов от 1.50, согласованности источников, состава участников и временных данных подтверждён **один основной вариант**:

1. **San Jose Sharks — Dallas Stars: тотал меньше 6.5 шайб, коэффициент не хуже 1.769 (линия -130), с учётом ОТ и буллитов для расчёта тотала.**

Второй основной вариант не выбран: остальные рынки либо не достигали коэффициента 1.50 при высокой вероятности, либо имели конфликт источников, неподтверждённые составы/вратарей или недостаточную надёжность.

## 2. Основной выбор

### San Jose Sharks — Dallas Stars

**Рынок:** тотал меньше 6.5 шайб.  
**Коэффициент:** 1.769 при -130; выбор допустим только по цене **не хуже -130**.  
**Старт:** 04:00 МСК 8 ноября 2026 года.  
**Статус:** матч запланирован, на момент проверки не начался.

Опубликованные командные средние ESPN: San Jose — 2.53 заброшенной и 3.53 пропущенной шайбы за матч; Dallas — 2.75 заброшенной и 2.25 пропущенной. Простая пуассоновская модель дала ожидаемый тотал 5.53 и вероятность семи или более шайб 31.9%; соответственно, модельная вероятность тотала меньше 6.5 составляет 68.1%.

Для стандартной линии FanDuel full-game ML и тотала учитываются овертайм и последующая серия буллитов; победная шайба в буллите засчитывается в общий тотал согласно проверенному описанию рынка. Выбран именно тотал, а не Dallas ML: коэффициент на Dallas около 1.34–1.35 (-290/-295), что ниже обязательного порога 1.50.

**Риски:** стартовые пятёрки и вратари ещё не подтверждены непосредственно перед игрой; ESPN отмечал Miro Heiskanen и Sam Steel как day-to-day, а Alexander Wennberg — с предполагаемой датой возвращения 7 ноября. Поздняя замена вратаря, ранние удаления, высокий темп или гол в пустые ворота повышают риск прохода тотала больше 6.5. Котировки различались, поэтому рекомендация ограничена ценой не хуже -130.

## 3. Альтернативы после основного выбора

### 3.1. New York Knicks — Cleveland Cavaliers: Knicks ML, около 1.61

**Почему рассматривалось:** линия DraftKings/консенсус указывала Knicks ML -163, то есть около 1.61; ESPN оценивал вероятность Knicks в 58%, Kalshi — 63–64%.

**Почему не выбрано:** официальный последний доступный injury report ещё не содержал поданного отчёта Cleveland для этого матча. Кроме того, независимые оценки расходились: Statz публиковал противоречивые значения 52% для Cleveland и 55% для Knicks, а данные по составам и доступности игроков не были полностью согласованы. Альтернатива оставлена без ставки.

Для NBA ML и общего тотала стандартно учитывается овертайм.

### 3.2. Florida Panthers — Washington Capitals: Panthers ML, около 1.96

**Почему рассматривалось:** независимый источник указывал Panthers ML -104, то есть около 1.96, что выше порога 1.50.

**Почему не выбрано:** переданное время 03:00 МСК конфликтовало с официальным NHL API, где startTimeUTC соответствовал 20:30 МСК 7 ноября. Дополнительно отсутствовали подтверждённые официальные составы и стартовые вратари, а модели расходились: AccuScore давал Washington 52%, тогда как другой источник приводил собственную оценку 55–60% в пользу Florida.

## 4. Перечень всех рассмотренных матчей

### 4.1. Теннис

#### Prudential Hong Kong Tennis Open 2026 — Maria Sakkari — Alexandra Eala

**Матч:** полуфинал, WTA 250, outdoor hard.  
**Старт:** 16:00 МСК 7 ноября 2026 года.  
**Рассмотренные рынки:** ML; рынки сетов исключены по условию, подтверждённая числовая линия общего тотала не отображалась.  
**Коэффициенты FanDuel:** Sakkari +114 (2.14), Eala -138 (1.72).

Матч формально проходил по порогу коэффициента: Eala имела 1.72. Однако согласованная надёжная вероятность не установлена. FanDuel подразумевал около 58.0% на Eala до маржи; Matchstat приводил Eala 56.5% и Sakkari 48.31%, но его текстовый прогноз склонялся к победе Sakkari в трёх сетах. Kalshi давал снимок 55% на Eala против 44% на Sakkari.

**Решение:** исключить, без ставки.  
**Причины и риски:** конфликт рыночной линии, Kalshi и текстового прогноза Matchstat; Eala менее чем за сутки до полуфинала провела четвертьфинал длительностью 2:30 с 29 брейк-пойнтами и 11 брейками. Это повышает неопределённость физического состояния.

### 4.2. Хоккей

#### Florida Panthers — Washington Capitals

**Старт по переданному расписанию:** 03:00 МСК 8 ноября.  
**Проверенные рынки:**
- **2-way ML с ОТ/буллитами:** Panthers 1.96 (-104), Capitals 1.87 (-115);
- **regulation-only 3-way ML:** Panthers 2.55 (+155), ничья 4.20 (+320), Capitals 2.35 (+135);
- тотал 6.5: Under около 1.76 (-132), Over 2.08 (+108).

Официальный NHL API указывал, что овертайм и буллиты используются. Поэтому 2-way ML должен включать ОТ и буллиты, а regulation-only 3-way — отдельный рынок с ничьей после 60 минут.

**Решение:** no bet.  
**Причины:** конфликт времени между переданным расписанием и NHL API; неподтверждённые официальные составы и вратари; конфликт оценок AccuScore и Sportsgambler.

#### San Jose Sharks — Dallas Stars

**Старт:** 04:00 МСК 8 ноября.  
**Проверенные рынки:**
- **2-way ML с ОТ/буллитами:** Dallas около 1.34–1.35 (-290/-295), San Jose около 3.35 (+235);
- **regulation-only 3-way:** рынок был доступен у FanDuel, но пригодная подтверждённая цена не зафиксирована;
- тотал 6.5: Over около 2.05–2.06 (+105/+106), Under около 1.77–1.80 (-125/-130).

**Решение:** основной выбор — Under 6.5 по цене не хуже -130. Для ML учитываются ОТ и буллиты; 3-way regulation-only является отдельным рынком. Для выбранного тотала расчёт выполняется по правилам full-game рынка, включая ОТ и буллит согласно проверенному описанию линии.

**Риски:** не подтверждены финальные вратари и составы; возможны поздние изменения, удаления, гол в пустые ворота и расхождение котировок.

#### Vancouver Canucks — Edmonton Oilers

**Старт:** 06:00 МСК 8 ноября.  
**Проверенные рынки:**
- **2-way ML с ОТ/буллитами:** Edmonton 1.31 (-320), Vancouver 3.55 (+255);
- **regulation-only 3-way:** рынок доступен на странице FanDuel, но подтверждённая котировка не показана;
- Over 6.5: 1.67 (-150), Under 6.5: 2.22 (+122).

Стандартный NHL full-game ML учитывает ОТ и буллиты; regulation-only 3-way — отдельный рынок. Для общего тотала правила должны быть явно подтверждены.

**Решение:** исключить, без ставки.  
**Причины:** Edmonton ML ниже порога 1.50; прогноз Over 6.5 имел около 60.8% модельной вероятности при 1.67, что не компенсировало неопределённость; стартовый вратарь Edmonton не был согласованно подтверждён. Jarry одновременно фигурировал как day-to-day/болел и как предполагаемый стартер. У Vancouver также имелась неопределённость по вратарю и составу.

### 4.3. Баскетбол

#### Denver Nuggets — Indiana Pacers, NBA Mexico City Game

**Старт:** 01:00 МСК 8 ноября.  
**Проверенные рынки:** ML, фора -6.5/+6.5, тотал 229.5.

Denver ML котировался примерно 1.38–1.42, ниже порога 1.50, при оценках ESPN 76.4% и Statz 69% в пользу Denver. Indiana ML имел коэффициент выше 1.50, но низкую вероятность; фора и тотал не имели достаточно согласованной высокой оценки. Tyrese Haliburton был указан как не играющий, а по нескольким другим игрокам статусы расходились.

**Решение:** исключить.  
**Учёт ОТ:** для NBA ML, общего тотала и форы стандартно учитывается овертайм, если правила конкретного букмекера не предусматривают иное.

#### Orlando Magic — Golden State Warriors

**Старт:** 04:30 МСК 8 ноября.  
**Проверенные рынки:** ML, тотал, спред и командные тоталы.

ESPN оценивал Warriors в 56.9%, Kalshi — в 69%; доступный эквивалент Warriors ML около 1.45, ниже порога 1.50. Magic ML имел приблизительно 3.13 при вероятности около 31%. Оценки тотала и спреда не давали надёжного согласованного преимущества; Action Network не загрузил подтверждённые букмекерские котировки.

**Решение:** исключить, без ставки.  
**Учёт ОТ:** стандартные full-game NBA ML и тотал учитывают овертайм.

**Риски:** официальные injury/roster notes Warriors были TBD; между Kalshi и ESPN существовала существенная разница оценок; состав Orlando также зависел от статусов травмированных игроков.

#### New York Knicks — Cleveland Cavaliers

**Старт:** 04:00 МСК 8 ноября.  
**Проверенные рынки:** ML и общий тотал 225.5.

Knicks ML: около 1.61 (-163); Cavaliers ML: около 2.37–2.40 (+137/+140); тотал 225.5: Over около 1.94, Under около 1.88. ESPN оценивал Knicks в 58%, Kalshi — в 63–64%.

**Решение:** исключить, без ставки.  
**Причины:** официальный injury report ещё не содержал поданного отчёта Cleveland; независимые оценки и projected lineups расходились. Данные по Josh Hart, Sam Merrill, Jarrett Allen и Jaylon Tyson не формировали полностью согласованную картину состава.

**Учёт ОТ:** для NBA ML и общего тотала учитывается овертайм.

## 5. Итоговый список решений

| Матч | Рынок | Коэффициент | Решение |
|---|---|---:|---|
| San Jose Sharks — Dallas Stars | Under 6.5, ОТ/буллиты по правилам тотала | 1.769 или лучше | **Основной выбор** |
| New York Knicks — Cleveland Cavaliers | Knicks ML | около 1.61 | Альтернатива, исключена |
| Florida Panthers — Washington Capitals | Panthers ML | около 1.96 | Альтернатива, исключена |
| Prudential Hong Kong Tennis Open: Sakkari — Eala | Eala ML | 1.72 | Исключено из-за конфликта оценок |
| Vancouver Canucks — Edmonton Oilers | Over 6.5 | 1.67 | Исключено из-за вратарской неопределённости |
| Denver Nuggets — Indiana Pacers | рынки с коэффициентом от 1.50 | — | Исключено: нет согласованной ставки |
| Orlando Magic — Golden State Warriors | рынки ML/тотала/спреда | — | Исключено: цена/вероятность/составы не подтверждены |

**Фактически рекомендованная ставка:** только Under 6.5 в матче San Jose Sharks — Dallas Stars по коэффициенту не хуже 1.769 (или -130).  
**Совершение ставок:** не выполнялось.

## References

[1]: https://www.wtatennis.com/tournaments/1074/hong-kong/2026/scores/LS003 "WTA Hong Kong 2026 — Scores, LS003"  
[2]: https://www.wtatennis.com/tournaments/1074/hong-kong/2026 "WTA Hong Kong 2026 — Tournament page"  
[3]: https://sportsbook.fanduel.com/tennis/wta-hong-kong-2026/maria-sakkari-v-alexandra-eala-36287750 "FanDuel — Sakkari vs Eala odds"  
[4]: https://www.nhl.com/gamecenter/fla-vs-wsh/2026/11/07/2026020265 "NHL Gamecenter — Florida Panthers vs Washington Capitals"  
[5]: https://api-web.nhle.com/v1/gamecenter/2026020265/landing "NHL API — Gamecenter 2026020265"  
[6]: https://www.nhl.com/gamecenter/sjs-vs-dal/2026/11/07/2026020272 "NHL Gamecenter — San Jose Sharks vs Dallas Stars"  
[7]: https://www.espn.com/nhl/game/_/gameId/401892669/sharks-stars "ESPN — Sharks vs Stars"  
[8]: https://sportsbook.fanduel.com/hockey/nhl/san-jose-sharks-@-dallas-stars-36287959 "FanDuel — Sharks vs Stars odds"  
[9]: https://www.nhl.com/gamecenter/van-vs-edm/2026/11/07/2026020276 "NHL Gamecenter — Vancouver Canucks vs Edmonton Oilers"  
[10]: https://www.espn.com/nhl/game/_/gameId/401892673/canucks-oilers "ESPN — Canucks vs Oilers"  
[11]: https://www.nba.com/game/den-vs-ind-0022600189 "NBA Game — Denver Nuggets vs Indiana Pacers"  
[12]: https://www.nba.com/news/nba-mexico-city-game-2026-everything-to-know "NBA — NBA Mexico City Game 2026"  
[13]: https://www.espn.com/nba/game/_/gameId/401909938/nuggets-pacers "ESPN — Nuggets vs Pacers"  
[14]: https://www.nba.com/game/orl-vs-gsw-0022600193 "NBA Game — Orlando Magic vs Golden State Warriors"  
[15]: https://www.espn.com/nba/game/_/gameId/401909942/magic-warriors "ESPN — Magic vs Warriors"  
[16]: https://www.nba.com/cavaliers/game/0022600191-knicks-vs-cavaliers-cleveland-oh-11-07-2026 "NBA Game — New York Knicks vs Cleveland Cavaliers"  
[17]: https://www.espn.com/nba/game/_/gameId/401909940 "ESPN — Knicks vs Cavaliers"  
[18]: https://www.vegasinsider.com/nba/matchups/cavaliers-vs-knicks/ "Vegas Insider — Cavaliers vs Knicks matchup"  
[19]: https://official.nba.com/nba-injury-report-2026-27-season/ "NBA Official — Injury Report 2026–27"  
[20]: https://www.wtatennis.com/news/4605678/eala-beats-ruzic-in-hong-kong-quarterfinal-featuring-29-break-points "WTA — Eala beats Ruzic in Hong Kong quarterfinal"  
[21]: https://www.docsports.com/free-picks/nhl-hockey/2026/san-jose-sharks-vs-dallas-stars-prediction-11-7-2026-nhl-picks-best-bets-odds.html "DocSports — Sharks vs Stars prediction and odds"  
[22]: https://www.actionnetwork.com/nba-game/denver-nuggets-indiana-pacers/295390 "Action Network — Nuggets vs Pacers odds and matchup"  
[23]: https://kalshi.com/markets/kxnbagame/knicks-vs-cavaliers/kxnbagame-26nov07nykcle "Kalshi — Knicks vs Cavaliers market"  
[24]: https://ak-static.cms.nba.com/referee/injury/Injury-Report_2026-11-06_11_00PM.pdf "NBA Official Injury Report — 6 November 2026"
