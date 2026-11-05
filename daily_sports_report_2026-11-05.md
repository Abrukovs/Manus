# Ежедневный спортивный отчёт V2.0 — 5 ноября 2026

**Окно анализа:** 5 ноября 2026, 05:00 MSK — 6 ноября 2026, 05:00 MSK.  
**Футбол:** не анализировался.  
**Обязательный охват:** хоккей, баскетбол и теннис.  
**Статус:** аналитический отчёт, не рекомендация к ставке и не распоряжение совершать ставку.

## Методика и ограничения

В отчёт включались только события, попадающие в указанное окно по времени начала, и только рынки с подтверждённым правилом расчёта и ценой не ниже 1.50, если такая цена была доступна в результатах исследователей. Для хоккея отдельно рассматривались 2-way ML с учётом овертайма/буллитов и regulation-only 3-way; total допускался только при ясном правиле учёта овертайма. Для баскетбола ML и полный матчевый total считаются с учётом овертайма, включая двойной овертайм. В теннисе рассматривались только prematch ML и общий total геймов; рынки сетов не использовались. При отсутствии подтверждённого участия, состава, актуальной линии или правила рынок исключался, даже если отдельная модель показывала перевес. Все исходные данные ниже взяты только из переданных результатов исследователей [1].

## Итоговый отбор

Выбраны максимум два основных варианта из разных матчей:

1. **Баскетбол, Philadelphia 76ers @ Detroit Pistons — Pistons ML, только при цене не ниже 1.50; ориентир в исследовании: 1.77 (-130).**
2. **Баскетбол, Los Angeles Lakers @ Sacramento Kings — общий тотал больше 234.5, только при цене не ниже 1.50; ориентир в исследовании: около 1.91 (-110).**

Оба варианта являются условными аналитическими кандидатами: в отчёте не утверждается, что цена сохранялась к началу игры, и не делается ставка.

## Основной вариант 1: Detroit Pistons ML против Philadelphia 76ers

**Матч и окно.** Philadelphia 76ers @ Detroit Pistons — 5 ноября 2026, 07:00 MSK; американская карточка указывала 19:00 ET 4 ноября. Игра входит в окно. Площадка — домашняя арена Detroit Pistons; точное название арены в переданных результатах не указано.

**Рынок и цена.** 2-way ML на победу Detroit Pistons, с учётом овертайма. Ориентир источника — -130, то есть примерно 1.77; кандидат допустим только при фактической текущей цене **>= 1.50**. Спред Detroit -2.5 не выбран основным рынком.

**Независимые оценки и форма.** Переданные материалы указывают баланс 7–1 у Detroit и 6–1 у Philadelphia, домашний фактор Detroit и шесть подряд побед Detroit в очных матчах. В открытом тексте источника согласованная независимая вероятность именно победы Detroit ML не раскрыта; поэтому численную вероятность ML не выдумываем. Это снижает степень уверенности и оставляет вариант умеренным, а не сильным. [1]

**Составы и кадровый контекст.** Jalen Duren отмечен как out. Официальный NBA injury hub обновляется непрерывно; поздние статусы остальных игроков должны считаться неподтверждёнными без последнего доступного отчёта или подтверждения стартовых составов. В частности, нельзя считать отсутствие свежего статуса подтверждением участия.

**Риски.** Главные риски — отсутствие раскрытой независимой ML-вероятности, возможное изменение цены ниже 1.50, поздние изменения injury report и неполное подтверждение финальных составов. Форма и очные встречи не гарантируют исход.

**Почему не выбраны другие применимые рынки этого матча.** Over 217.5 имеет лишь умеренную независимую поддержку: SportsLine дал 53% на Over и прогноз 220 очков, но в результатах одновременно указано расхождение линий 217.5 и 219.5 у разных источников. Поэтому total не стал основным вариантом: требуется сверить конкретную актуальную линию и цену >=1.50. Spread -2.5 не выбран, поскольку в переданных результатах нет независимой вероятности покрытия и он менее устойчив к поздним изменениям состава, чем ML.

## Основной вариант 2: Lakers–Kings Over 234.5

**Матч и окно.** Los Angeles Lakers @ Sacramento Kings — 5 ноября 2026, 03:00 MSK, Golden 1 Center. Локальная дата в официальном NBA-календаре — 4 ноября; по MSK игра входит в заданное окно.

**Рынок и цена.** Полный матчевый total больше 234.5 очка, с учётом овертайма; ориентир DraftKings — около -110, то есть примерно 1.91. Кандидат допустим только при фактической цене **>= 1.50**. Четверти, половины и player props не рассматривались.

**Независимые оценки и форма.** ESPN Matchup Predictor оценивал вероятность победы Lakers в 83.3%, а статистический контекст указывал на 122.5 очка Lakers против 110.1 у Sacramento. Sports Illustrated выделял темп Sacramento и атакующую силу Lakers, отмечал проход тотала вверх в 5 из 7 последних игр Kings и 5 из 8 последних игр Lakers; TeamRankings давал Lakers predictive rating 2.9 против -9.6 у Sacramento и рейтинги последних десяти игр 5.7 против -13.2. Эти данные поддерживают сценарий высокой результативности, но независимая вероятность именно Over 234.5 в переданных результатах не раскрыта, поэтому её не выдумываем. [1]

**Площадка.** Golden 1 Center, домашняя площадка Sacramento Kings. Контекст площадки и темпа Sacramento учитывался, но не трактуется как самостоятельная гарантия тотала.

**Составы.** В результатах указаны как out у Sacramento Adou Thiero, Daeqwon Plowden, Maxime Raynaud, Keegan Murray и Ben Simmons. Источники расходятся по полноте кадровых данных, а официальный календарь помечен как subject to change; перед началом требовалась бы повторная проверка. [1]

**Риски.** Total 234.5 чувствителен к темпу, реализации и фактическому составу. Кадровые сведения могут обновиться, а часть данных различается по полноте между источниками. Сильный ML Lakers не компенсирует слишком короткую цену.

**Почему не выбраны другие применимые рынки этого матча.** Lakers ML имел линию примерно -574/-650, что соответствует ориентировочно 1.15–1.17 и ниже минимального порога 1.50; поэтому ML исключён несмотря на сильный прогноз победы. Альтернативных подтверждённых рынков с ценой >=1.50 и независимой вероятностью выше 50% в переданных данных нет.

## Альтернативы после основного выбора

В этот раздел включены как хорошие короткие варианты, так и варианты с ценой строго выше 1.50 и независимой вероятностью строго выше 50%, если они не стали основными.

- **Heat ML против Clippers — не проходит по цене и согласованности.** BetMGM оценивал Heat в 64.1%, но линия была около 1.48–1.50 (-200), то есть не подтверждена как строго выше 1.50. Action Network давал Clippers +170 и указывал на конфликт формы и кадровых вводных; Myron Gardner был questionable, ряд игроков Clippers — out. Поэтому это не квалифицируется как альтернативный выбор.
- **Philadelphia–Detroit Over 217.5 — умеренная альтернатива, не основной выбор.** SportsLine: 53% Over, прогноз 220; цена допустима только при >=1.50. Конфликт 217.5 против 219.5 требует сверки конкретного букмекера, а перевес небольшой.
- **Tommy Paul ML против Quentin Halys — короткая цена, исключён.** Независимая модель давала Paul 74%, но цена -300, около 1.33, ниже 1.50; официальная четверговая карточка также не была полностью подтверждена.
- **Хоккейные ML с моделью выше 50% не стали альтернативами.** The Lineup давал Tampa Bay 80%, Edmonton 68%, Dallas 59%, Montréal 53%, Vegas 59% и другие оценки, но доступными были Kalshi/Polymarket вероятностные цены, а не подтверждённые sportsbook decimal odds. При отсутствии подтверждённой цены >=1.50, состава и точного правила рынка эти варианты не квалифицируются.
- **St. Louis ML против New Jersey — не альтернатива.** Модель давала 46% против 36.5% вероятностной цены рынка, но не была подтверждена допустимая sportsbook-линия, injury report и финальный состав; модельный разрыв сам по себе недостаточен.
- **Остальные теннисные варианты — не альтернативы.** Shelton–Rinderknech не имел подтверждённой текущей цены и официальной карточки; Eala ML 1.57 и Eala -1.5 гейма 1.65 имели конфликт с официальным order of play по дате; остальные матчи не имели одновременно подтверждённых участия, цены, модели и состава. [1]

## Хоккей: обязательный охват и решения по всем рассмотренным матчам

### Правила рынков

Проверялся **2-way ML с учётом ОТ/буллитов**, но рекомендация невозможна без подтверждённой sportsbook decimal odds >=1.50, финального участия и состава. **Regulation-only 3-way** не рекомендован: отдельная доступная линия и правило не подтверждены. **Total** не рекомендован: не подтверждены sportsbook-линия и точное правило расчёта овертайма. Нельзя заменять sportsbook decimal odds котировками Kalshi/Polymarket в центах.

### Матчи в окне и причины исключения

- **Utah Mammoth @ Montréal Canadiens, 22:00 MSK.** Модель Montréal 53% против Kalshi 47.4% давала небольшой перевес, но не были подтверждены sportsbook-цена, состав и injury report.
- **Vegas Golden Knights @ Detroit Red Wings, 22:00 MSK.** Модель и контекст были доступны, но не подтверждены допустимая цена, финальные составы и точные правила рынка.
- **Chicago Blackhawks @ Tampa Bay Lightning, 22:00 MSK.** Модель Tampa Bay 80%, а доступный контекст Hockey-Reference был положительным (7–2–0, 3.44 GF/G, 2.56 GA/G, 55.9% Corsi), но Kalshi 77.5¢ соответствует примерно 1.29 и ниже порога; sportsbook-цена не подтверждена.
- **St. Louis Blues @ New Jersey Devils, 22:00 MSK.** Модельный разрыв 46% против 36.5% был самым заметным, однако нет подтверждённых sportsbook-линии, injury report и состава.
- **Carolina Hurricanes @ New York Islanders, 22:00 MSK.** Модель была доступна, но нет подтверждённых допустимой цены, финальных составов и точных правил рынка.
- **Philadelphia Flyers @ New York Rangers, 22:00 MSK.** Исключён по тем же причинам: нет полного набора допустимая цена + финальные составы + правило рынка.
- **Boston Bruins @ Pittsburgh Penguins, 22:00 MSK.** Исключён из-за отсутствия подтверждённых sportsbook-цены, состава и применимого правила.
- **Dallas Stars @ Columbus Blue Jackets, 22:00 MSK.** Модель Dallas 59% против Kalshi 54.6% и контекст фаворита интересны, но проверенная цена >=1.50 и финальный состав отсутствуют.
- **Vancouver Canucks @ Winnipeg Jets, 22:00 MSK.** Исключён из-за отсутствия подтверждённой допустимой цены, состава и точных правил рынков.
- **Anaheim Ducks @ Edmonton Oilers, 23:00 MSK.** Модель Edmonton 68% против Kalshi 62%, но цена вероятностного рынка ниже минимального порога, а финальные goalie/lineups не подтверждены.
- **Nashville Predators @ Colorado Avalanche — исключён из окна.** Официальное начало 02:30Z 6 ноября = 05:30 MSK, то есть позже верхней границы 05:00 MSK; наличие модели (Colorado 68%) не меняет отсечение по времени.

Официальный NHL API и Hockey-Reference подтверждали календарь и статистический контекст, но динамическая schedule-страница не дала полного надёжного slate в извлечённом тексте. Не найден единый официальный injury/status report для всех матчей и не подтверждены стартовые вратари. [1]

## Баскетбол: обязательный охват и решения по всем рассмотренным матчам

Все NBA ML и full-game total в этом разделе по правилу считаются с учётом ОТ/двойного ОТ.

- **Philadelphia 76ers @ Detroit Pistons, 07:00 MSK.** Рассмотрен; Pistons ML выбран основным условным вариантом при цене >=1.50. Over 217.5 оставлен альтернативой из-за небольшого перевеса SportsLine и конфликта 217.5/219.5.
- **Atlanta Hawks @ Washington Wizards, 07:00 MSK.** Исключён: не собран полный подтверждённый пакет актуальной линии, независимой модели, составов и injury report.
- **Milwaukee Bucks @ Boston Celtics, 07:30 MSK.** Исключён: Jayson Tatum был questionable for rest; без окончательного статуса и согласованной ML/total-модели кадровый риск слишком велик.
- **Portland Trail Blazers @ Phoenix Suns, 10:00 MSK.** Исключён: календарь и линии подтверждены, но не подтверждён полный набор независимой модели, официальных составов и injury-контекста.
- **Dallas Mavericks @ San Antonio Spurs, 10:30 MSK.** Исключён по той же причине: нет одновременно модели, актуальной цены и подтверждённых составов.
- **Los Angeles Lakers @ Sacramento Kings, 11:00 MSK по раннему слейту и 03:00 MSK для поздней карточки.** Рассмотрен; Over 234.5 выбран основным условным вариантом. Lakers ML исключён из-за цены ниже 1.50.
- **Miami Heat @ LA Clippers, 11:30 MSK по раннему слейту и 03:30 MSK для поздней карточки.** Исключён: Heat ML имел модель 64.1%, но цена около 1.48–1.50, а независимые данные расходились; total также не имел согласованного преимущества.

## Теннис: обязательный охват и решения по всем рассмотренным матчам

Для тенниса использовались только prematch ML и общий total геймов при ясном правиле. Рынки сетов намеренно не использовались.

### ATP Paris Masters

- **Tommy Paul — Quentin Halys, ожидаемый матч 5 ноября.** Независимая модель Paul 74%, но Paul -300, около 1.33, ниже 1.50; total не имел подтверждённой линии и правила. Официальный order of play на момент проверки ещё относился к 4 ноября, поэтому календарный риск также сохраняется.
- **Ben Shelton — Arthur Rinderknech, ожидаемый матч 5 ноября.** Независимый preview был за Shelton, но текущая цена и финальная официальная карточка не подтверждены; домашний фактор Rinderknech добавляет риск. Исключён.

### WTA Hong Kong, Chennai и Cali

- **Tereza Valentova — Alexandra Eala.** Независимый прогноз давал Eala ML 1.57 и -1.5 гейма 1.65, но официальный Hong Kong order of play конфликтовал по дате и не подтверждал именно 5 ноября. ML и total исключены до устранения конфликта.
- **Sorana Cirstea — Mary Stoiana; Zeynep Sonmez — Mika Stojsavljevic.** Независимый анализ имелся, но официальная карточка на 5 ноября и полный набор линии/участия/injury report не подтверждены.
- **Chennai Open.** Турнир и участники подтверждены, но доступная официальная версия order of play не подтверждала матчи 5 ноября; рекомендации исключены.
- **Reto Win Tennis Cali Open WTA 125.** Официальный order of play сообщал, что расписание недоступно; конкретные матчи, участие, линия и правило total не подтверждены.

### ATP Challenger и ITF

- **Charlottesville R16: Aidan Mayo — Alastair Gray; Daniel Milavsky — Max Hans Rehberg; Maks Kasnikowski — Michael Antonius; Andres Andrade — James Trotter.** Официальные пары и расписание подтверждены, но для каждой пары отсутствовал одновременно подтверждённый prematch ML/total, независимая модель и полный актуальный статус участия. Линия Bovada для Antonius относилась к другому матчу 2 ноября и непригодна.
- **ATP Challenger Taranto.** День турнира подтверждён, но официальная карточка не раскрыла пары 5 ноября; независимый injury-list сообщал retirement двух игроков 4 ноября. Рекомендации исключены.
- **ITF/WTA-кандидаты.** Уровень турниров и календарный диапазон подтверждались, но конкретные матчи 5 ноября, актуальная линия и согласованный первичный набор данных не подтверждены.

## Сводка исключений и нерекомендованных рынков

Ни один хоккейный рынок не прошёл одновременно фильтр sportsbook decimal odds >=1.50, подтверждённого правила, состава и участия. В баскетболе ранние матчи Hawks–Wizards, Bucks–Celtics, Blazers–Suns и Mavericks–Spurs исключены из-за неполного набора модель+линия+состав; Heat–Clippers — из-за конфликта цены, модели и кадров. В теннисе Paul–Halys исключён из-за цены ниже 1.50, Shelton–Rinderknech — из-за отсутствия актуальной цены и карточки, а WTA/Challenger-кандидаты — из-за нерешённых конфликтов расписания или отсутствия полного набора линии, модели и статуса участия. Футбол не анализировался.

## References

[1] Переданные результаты исследователей и указанные в них первоисточники: NHL — https://api-web.nhle.com/v1/schedule/2026-11-05 ; https://www.nhl.com/schedule/2026-11-05 ; https://www.nhl.com/gamecenter/uta-vs-mtl/2026/11/05/2026020251 ; https://www.nhl.com/gamecenter/chi-vs-tbl/2026/11/05/2026020253 ; https://www.nhl.com/gamecenter/nsh-vs-col/2026/11/05/2026020261 ; https://www.thelineup.pro/predictions/nhl/2026-11-05 ; https://www.hockey-reference.com/leagues/NHL_2027_games.html ; https://www.hockey-reference.com/leagues/NHL_2027.html ; https://www.hockey-reference.com/teams/TBL/2027.html ; https://www.espn.com/nhl/odds . NBA — https://www.nba.com/news/2026-27-nba-regular-season-schedule ; https://www.espn.com/nba/schedule ; https://www.nba.com/game/mil-vs-bos-0022600175 ; https://www.cbssports.com/betting/news/76ers-pistons-prediction-odds-time-2026-nba-picks-wednesday-november-4/ ; https://www.actionnetwork.com/nba/nba-best-bets-picks-for-76ers-vs-pistons-wizards-vs-hawks-more-on-wednesday-november-4 ; https://official.nba.com/nba-injury-report-2026-27-season/ ; https://cdn.nba.com/manage/2026/08/2026-27-NBA-Regular-Season-Schedule-By-Date.pdf ; https://www.espn.com/nba/game/_/gameId/401909934/lakers-kings ; https://www.si.com/betting/lakers-vs-kings-prediction-odds-and-best-nba-prop-bets-for-wednesday-nov-4-2026 ; https://www.teamrankings.com/nba/matchup/lakers-kings-2026-11-04/power-ratings ; https://www.nba.com/heat/game/0022600186 ; https://sports.betmgm.com/en/blog/nba/heat-clippers-prediction-odds-lines-picks-nba-nov-4-jaa/ ; https://www.actionnetwork.com/nba-game/heat-clippers-score-odds-november-4-2026/295387 . ATP/WTA — https://www.atptour.com/en/news/paris-2026-atp-masters-1000-history-draw-schedule ; https://www.atptour.com/en/scores/current/paris/352/daily-schedule?day=6 ; https://www.protennislive.com/posting/2026/352/op.pdf ; https://www.dimers.com/tennis/news/tommy-paul-vs-quentin-halys-tennis-prediction-atp-paris-masters-2026-ac ; https://tenngrand.com/paris-tennis-previews-picks-predictions-shelton-vs-rinderknech-paul-halys/ ; https://kalshi.com/category/sports/tennis/atp-paris ; https://wtafiles.wtatennis.com/pdf/calendar/calendar.pdf ; https://www.wtatennis.com/tournaments/1074/hong-kong/2026 ; https://www.wtatennis.com/tournaments/1074/hong-kong/2026/order-of-play ; https://wtafiles.wtatennis.com/pdf/draws/2026/1074/OP.pdf ; https://www.wtatennis.com/tournaments/1148/chennai/2026 ; https://www.wtatennis.com/tournaments/1148/chennai/2026/order-of-play ; https://www.wtatennis.com/tournaments/1110/cali-125/2026/order-of-play ; https://www.espn.com/tennis/schedule/_/type/wta ; https://lastwordonsports.com/tennis/2026/11/04/wta-hong-kong-valentova-eala/ ; https://www.lineups.com/articles/wta-tennis-preview-hong-kong-open-chennai-open-betting-odds-picks-analysis/ ; https://sportsbook.fanduel.com/tennis/wta/hong-kong-2026 ; https://www.atptour.com/en/scores/current-challenger/charlottesville/6055/daily-schedule?day=5 ; https://www.atptour.com/en/tournaments/charlottesville/6055/overview ; https://www.atptour.com/en/scores/current-challenger/taranto/3191/daily-schedule ; https://www.atptour.com/en/scores/current-challenger/taipei/2278/daily-schedule?day=5 ; https://www.itftennis.com/en/tournament-calendar/mens-world-tennis-tour-calendar/ ; https://www.bovada.lv/sports/tennis/challenger ; https://www.tennisexplorer.com/list-players/injured/
