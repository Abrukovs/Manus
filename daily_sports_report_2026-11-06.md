# Отчёт V2.0: теннис, хоккей и баскетбол

**Дата и время подготовки:** 6 ноября 2026 года, 07:12 МСК.

**Окно анализа:** ближайшие 24 часа от 07:00 МСК 6 ноября 2026 года до 07:00 МСК 7 ноября 2026 года.

## 1. Охват и рассмотренные матчи

В исследование включены матчи трёх видов спорта: тенниса, хоккея и баскетбола.

### Теннис

1. Rolex Paris Masters — четвертьфинал одиночного разряда, матч дневной сессии 1: **Ben Shelton — Tommy Paul**, начало 6 ноября в 16:00 МСК.
2. Rolex Paris Masters — четвертьфинал одиночного разряда, матч дневной сессии 2: **Luca Van Assche — Rinky Hijikata**, начало 6 ноября в 16:00 МСК.
3. Rolex Paris Masters — четвертьфинал одиночного разряда, матч вечерней сессии 1, начало 6 ноября в 21:00 МСК; участники на момент анализа не были подтверждены.

### Хоккей

1. **Columbus Blue Jackets — Buffalo Sabres**, начало 7 ноября в 03:00 МСК.
2. **San Jose Sharks — Minnesota Wild**, начало 7 ноября в 04:00 МСК по переданным входным данным; независимые источники давали конфликтующее время.
3. **Anaheim Ducks — Calgary Flames**, начало 7 ноября в 06:00 МСК по переданным входным данным; официальные данные NHL указывали 04:00 МСК.

Для хоккея отдельно рассматривались рынки **2-way ML с учётом овертайма/буллитов** и **regulation-only 3-way / 60 Min Moneyline**, где ничья после 60 минут является третьим исходом.

### Баскетбол

1. **Besiktas Istanbul — Zalgiris Kaunas**, начало 6 ноября в 20:00 МСК.
2. **Olympiacos Piraeus — Crvena Zvezda Meridianbet Belgrade**, начало 6 ноября в 22:15 МСК.
3. **Oklahoma City Thunder — Memphis Grizzlies**, начало 7 ноября в 04:00 МСК.

Для баскетбола ML и тоталы рассматривались **с учётом возможного овертайма**.

## 2. Основные варианты

Выбрано не более двух вариантов из разных матчей. Оба коэффициента соответствуют минимальному требованию 1.50.

### 2.1. Tommy Paul — победа в матче

- **Матч:** Ben Shelton — Tommy Paul, четвертьфинал Rolex Paris Masters.
- **Время:** 6 ноября 2026 года, 16:00 МСК.
- **Рынок:** ML, победа в матче.
- **Основной выбор:** **Tommy Paul ML**.
- **Коэффициент:** **1.76** (−132), линия Dimers со ссылкой на DraftKings.
- **Оценка вероятности:** 55,2% по модели Dimers на 10 000 симуляций.
- **Правила расчёта:** овертайм не применяется; победитель определяется по стандартному регламенту ATP.

**Риски.** Матч близкий: H2H на быстрых хардовых покрытиях указан как 2–2. The Stats Zone отмечает текущую форму Paul и ожидает затяжные сеты, но также рекомендует рассматривать тотал больше 22,5 геймов, а не ML. Официальный турнирный материал подтверждает участников, их выход из 1/8 финала и отсутствие неподтверждённой информации о составе. Котировки могут измениться до начала.

### 2.2. Buffalo Sabres — победа в матче

- **Матч:** Columbus Blue Jackets — Buffalo Sabres.
- **Время:** 7 ноября 2026 года, 03:00 МСК.
- **Рынок:** 2-way ML с учётом овертайма и буллитов.
- **Основной выбор:** **Buffalo Sabres — победа в матче, включая ОТ/буллиты**.
- **Коэффициент:** **1.55** (−182, FanDuel).
- **Оценка вероятности:** 65,4% по модели Puckwired; независимая рыночная оценка при −182 — около 64,5% до маржи.
- **Правила расчёта:** для рекомендованного 2-way ML учитываются овертайм и буллиты. Regulation-only 3-way / 60 Min Moneyline является отдельным рынком и в основной выбор не включён.

**Риски.** Стартовые вратари официально не подтверждены; Puckwired прогнозирует Jet Greaves и Ukko-Pekka Luukkonen. У Buffalo длинный список травм, включая Alex Lyon и Matt Grzelcyk; ESPN также показывает травмы/IR. Есть конфликт независимых прогнозов: Puckwired поддерживает Buffalo с вероятностью 65,4%, а Doc’s Sports — Columbus (+145). На странице Puckwired есть несогласованность времени: в шапке 19:00 ET, в тексте 20:00 ET; официальным NHL API подтверждено 00:00 UTC / 19:00 ET. Коэффициент 1.55 лишь немного выше минимально допустимого 1.50.

## 3. Альтернативы после основного выбора

- **Besiktas Istanbul ML — 1.97.** Альтернатива из баскетбола; оценка вероятности 51%. Не включена в основные варианты, поскольку оценка близка к 50/50. У Besiktas были статусы doubtful у Ante Zizic и Devon Dotson, out у DaQuan Jeffries и Mady Sissoko; у Zalgiris Nigel Williams-Goss — out.
- **Crvena Zvezda Meridianbet Belgrade ML — 3.05.** Альтернатива из баскетбола; оценка вероятности 31%, низкая уверенность. Не включена в основные варианты из-за высокой дисперсии ML-аутсайдера и преимущества Olympiacos по домашней площадке и текущему балансу.
- **Общий тотал больше 22,5 геймов в матче Shelton — Paul.** Указан как рассматриваемая The Stats Zone альтернатива ML, но проверенный коэффициент для включения в основной выбор не приведён.

Других вариантов, допускаемых одновременно условиями по проверенной линии, вероятности, коэффициенту и отсутствию нерешённых конфликтов, нет.

## 4. Матчи без ставки и причины исключения

### Теннис

- **Luca Van Assche — Rinky Hijikata:** нет ставки. Не удалось одновременно найти независимый актуальный коэффициент и статистическую/модельную вероятность именно для этой пары. Найденные линия и модель относятся к Shelton — Paul и не перенесены на другой матч.
- **Вечерний четвертьфинал Rolex Paris Masters:** нет рекомендации. Слот подтверждён, но участники и конкретная линия не были определены; доступный источник давал futures, а не ML или тотал конкретного матча.

### Хоккей

- **San Jose Sharks — Minnesota Wild:** исключён из-за конфликтующего времени начала и отсутствия подтверждённых коэффициентов ML/тотала на странице Covers. Kalshi показывал вероятностный рынок, а не подтверждённый букмекерский decimal-коэффициент; отображались также несовпадающие вероятности 69% и 71%. Составы и стартовые вратари не подтверждены.
- **Anaheim Ducks — Calgary Flames:** нет рекомендации. Хотя Calgary ML был около 1.87 (−115), матч исключён из-за конфликта времени: входные данные указывали 06:00 МСК, NHL API — 04:00 МСК, а страница арены — 19:00 по Калгари. Стартовые вратари и окончательные составы официально не подтверждены. Regulation-only 3-way не подтверждён.

### Баскетбол

- **Oklahoma City Thunder — Memphis Grizzlies:** исключён из-за конфликтующих сведений о травмах и доступности игроков. Официальный injury report не позволил разрешить конфликт. При этом линия Thunder ML составляла 1.59, но источники по составам и вероятностям не были согласованы: Statz указывал 63%, Kalshi — 62% в текстовом прогнозе и 55% в текущем отображении рынка.

## 5. Риски и отсутствие ставок

Основные риски отчёта — изменение котировок до начала матчей, неподтверждённые стартовые составы и вратари, травмы, близкие оценки вероятности, а также конфликты во времени начала и между независимыми источниками.

Отсутствие ставки означает, что условия надёжного выбора не выполнены. Это относится к матчам, где не удалось подтвердить коэффициент не ниже 1.50 именно для целевой пары, где не была подтверждена вероятность, где участники не определены или где источники противоречат друг другу.

Даже основные варианты не являются гарантией результата: по Tommy Paul есть близкий H2H и аргументы в пользу тотала, а по Buffalo есть неопределённость со стартовыми вратарями, травмами и конфликтом прогнозов.

## 6. Итог

Основные варианты V2.0:

1. **Tommy Paul ML — 1.76**, матч против Ben Shelton, 6 ноября, 16:00 МСК.
2. **Buffalo Sabres ML с учётом ОТ/буллитов — 1.55**, матч против Columbus Blue Jackets, 7 ноября, 03:00 МСК.

Остальные рассмотренные матчи оставлены без основной ставки либо вынесены в альтернативы из-за короткой цены, высокой неопределённости, отсутствия проверенной линии, конфликтов источников или неподтверждённых составов.

## References

[1]: https://tickets.rolexparismasters.com/en/programme-previsionnel "Rolex Paris Masters — предварительная программа"
[2]: https://www.rolexparismasters.com/en/news/article/2026-edition-complete-schedule-qualifying-main-draw-singles-doubles-wheelchair-tennis "Rolex Paris Masters — расписание турнира 2026"
[3]: https://www.rolexparismasters.com/en/news/article/quarter-finals-schedule-singles-doubles-wheelchair-tennis-shelton-van-assche-alcaraz "Rolex Paris Masters — расписание четвертьфиналов"
[4]: https://www.atptour.com/en/scores/current/paris/352/daily-schedule "ATP — ежедневное расписание Paris"
[5]: https://www.atptour.com/en/news/shelton-rinderknech-paul-halys-paris-2026-thursday "ATP — результаты и новости Paris 2026"
[6]: https://www.dimers.com/tennis/predictions/2026_1_atp_2661_808628_138546 "Dimers — прогноз Shelton против Paul"
[7]: https://www.betfair.com/betting/tennis/atp-paris-2026/be-shelton-v-paul/e-36283627 "Betfair — Shelton против Paul"
[8]: https://www.thestatszone.com/ben-shelton-vs-tommy-paul-preview-prediction-2026-paris-masters-quarter-final-236610 "The Stats Zone — превью Shelton против Paul"
[9]: https://robinhood.com/us/en/prediction-markets/tennis/events/shelton-vs-paul-nov-06-2026/ "Robinhood — prediction market Shelton против Paul"
[10]: https://www.rolexparismasters.com/en/schedule-and-results "Rolex Paris Masters — расписание и результаты"
[11]: https://www.tennismajors.com/atp/rolex-paris-masters-1000-atp/rolex-paris-masters-order-of-play-alcaraz-opens-the-night-session-against-fils-or-fritz-865885.html "Tennis Majors — order of play"
[12]: https://www.atptour.com/en/scores/current/paris/352/results?matchDate=2026-11-02 "ATP — результаты Paris"
[13]: https://www.dimers.com/tennis/news/ben-shelton-vs-tommy-paul-tennis-prediction-atp-paris-masters-2026-ac "Dimers — новость и прогноз Paris Masters"
[14]: https://www.olympics.com/en/news/paris-masters-2026-order-of-play-results "Olympics — Paris Masters order of play"
[15]: https://www.tennismajors.com/atp/rolex-paris-masters-1000-atp/rolex-paris-masters-2026-draw-seeds-schedule-how-to-watch-864623.html "Tennis Majors — сетка и расписание Paris Masters"
[16]: https://www.lineups.com/articles/atp-tennis-preview-rolex-paris-masters-betting-odds-picks-analysis/ "Lineups — превью и коэффициенты Paris Masters"
[17]: https://www.tennisticketservice.com/rolex-paris-masters-schedule/ "Tennis Ticket Service — расписание турнира"
[18]: https://api-web.nhle.com/v1/gamecenter/2026020262/landing "NHL API — Columbus против Buffalo"
[19]: https://www.nhl.com/gamecenter/cbj-vs-buf/2026/11/06/2026020262 "NHL Gamecenter — Columbus против Buffalo"
[20]: https://sportsbook.fanduel.com/hockey/nhl/columbus-blue-jackets-@-buffalo-sabres-36260073 "FanDuel — линия Columbus против Buffalo"
[21]: https://www.espn.com/nhl/game/_/gameId/401892659/blue-jackets-sabres "ESPN — Columbus против Buffalo"
[22]: https://www.puckwired.com/game-coverage/game-previews/blue-jackets-vs-sabres-prediction-picks-2026-11-06/ "Puckwired — прогноз Columbus против Buffalo"
[23]: https://www.docsports.com/free-picks/nhl-hockey/2026/columbus-blue-jackets-vs-buffalo-sabres-prediction-11-6-2026-nhl-picks-best-bets-odds.html "Doc’s Sports — прогноз Columbus против Buffalo"
[24]: https://www.covers.com/sport/hockey/nhl/matchup/382538/odds "Covers — коэффициенты Columbus против Buffalo"
[25]: https://www.nhl.com/gamecenter/sjs-vs-min/2026/11/06/2026020263 "NHL Gamecenter — San Jose против Minnesota"
[26]: https://www.espn.com/nhl/game/_/gameId/401892660/sharks-wild "ESPN — San Jose против Minnesota"
[27]: https://www.covers.com/sport/hockey/nhl/matchup/382540/odds "Covers — коэффициенты San Jose против Minnesota"
[28]: https://www.covers.com/sport/hockey/nhl/matchup/382540 "Covers — San Jose против Minnesota"
[29]: https://kalshi.com/markets/kxnhlgame/sharks-vs-wild/kxnhlgame-26nov06sjmin "Kalshi — Sharks против Wild"
[30]: https://sports.yahoo.com/nhl/san-jose-sharks-minnesota-wild-2026110630/ "Yahoo Sports — San Jose против Minnesota"
[31]: https://api-web.nhle.com/v1/gamecenter/2026020264/landing "NHL API — Anaheim против Calgary"
[32]: https://api-web.nhle.com/v1/schedule/2026-11-06 "NHL API — расписание 6 ноября 2026"
[33]: https://www.nhl.com/gamecenter/ana-vs-cgy/2026/11/06/2026020264 "NHL Gamecenter — Anaheim против Calgary"
[34]: https://www.espn.com/nhl/game/_/gameId/401892661/ducks-flames "ESPN — Anaheim против Calgary"
[35]: https://www.docsports.com/free-picks/nhl-hockey/2026/anaheim-ducks-vs-calgary-flames-prediction-11-6-2026-nhl-picks-best-bets-odds.html "Doc’s Sports — прогноз Anaheim против Calgary"
[36]: https://kalshi.com/markets/kxnhlgame/nhl-game/kxnhlgame-26nov06anacgy "Kalshi — Anaheim против Calgary"
[37]: https://scotiabanksaddledome.com/events/calgary-flames-vs-anaheim-ducks-2026-11-06-700-pm "Scotiabank Saddledome — событие Calgary против Anaheim"
[38]: https://www.euroleaguebasketball.net/euroleague/game-center/2026-27/besiktas-istanbul-zalgiris-kaunas/E2026/97/ "EuroLeague Game Center — Besiktas против Zalgiris"
[39]: https://www.euroleaguebasketball.net/euroleague/teams/besiktas-istanbul/roster/bes/ "EuroLeague — состав Besiktas"
[40]: https://statsniper.com/leagues/euroleague/game/2026/97/zalgiris-kaunas-vs-besiktas/ "Statsniper — Besiktas против Zalgiris"
[41]: https://basketballsphere.com/en/besiktas-vs-zalgiris-prediction-odds-euroleague-november-6-2026/ "Basketball Sphere — прогноз Besiktas против Zalgiris"
[42]: https://www.oddschecker.com/basketball/euroleague/zalgiris-kaunas-at-besiktas/winner "Oddschecker — Besiktas против Zalgiris"
[43]: https://zalgiris.lt/en/naujienos/information-update-on-nigel-williams-goss-injury "Zalgiris — информация о травме Nigel Williams-Goss"
[44]: https://www.euroleaguebasketball.net/en/euroleague/news/tae2627-rs10-game-notes-oly-red/ "EuroLeague — game notes Olympiacos против Crvena Zvezda"
[45]: https://tips.gg/matches/basketball/06-11-2026/olympiacos-piraeus-vs-crvena-zvezda/07-15/odds/ "Tips.GG — коэффициенты Olympiacos против Crvena Zvezda"
[46]: https://basketballsphere.com/en/olympiacos-vs-crvena-zvezda-prediction-odds-euroleague-november-6-2026/ "Basketball Sphere — прогноз Olympiacos против Crvena Zvezda"
[47]: https://sportsbook.fanduel.com/basketball/euroleague-men%27s/bc-olympiakos-piraeus-v-kk-crvena-zvezda-belgrade-36269901 "FanDuel — Olympiacos против Crvena Zvezda"
[48]: https://www.nba.com/game/0022600029 "NBA — Oklahoma City против Memphis"
[49]: https://www.nba.com/game/okc-vs-mem-0022600029 "NBA Game — Oklahoma City против Memphis"
[50]: https://www.nba.com/schedule?cal=all&pd=false&region=1&season=Regular+Season "NBA — расписание регулярного сезона"
[51]: https://www.actionnetwork.com/nba-game/oklahoma-city-thunder-memphis-grizzlies/295194 "Action Network — Oklahoma City против Memphis"
[52]: https://statz.ai/nba/games/memphis-grizzlies-vs-oklahoma-city-thunder-2026-11-06/preview "Statz — превью Oklahoma City против Memphis"
[53]: https://kalshi.com/markets/kxnbagame/thunder-vs-grizzlies/kxnbagame-26nov06okcmem "Kalshi — Thunder против Grizzlies"
[54]: https://official.nba.com/nba-injury-report-2026-27-season/ "NBA Official — injury report сезона 2026–27"
[55]: https://sleeper.com/nba/scores/okc-thunder-mem-grizzlies-2026-11-06 "Sleeper — Oklahoma City против Memphis"
