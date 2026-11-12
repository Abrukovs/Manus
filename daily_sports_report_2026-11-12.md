# Отчёт V2.0: предматчевый отбор ставок

**Дата отчёта:** 12 ноября 2026 года  
**Расчётное окно:** 07:00 12.11.2026 — 07:00 13.11.2026 МСК  
**Статус:** предматчевый анализ; ставки не совершались.

## 1. Критерии отбора

Рассмотрены все предоставленные матчи по доступным видам спорта, попадающие в заданное 24-часовое окно. В итоговые основные варианты включены не более двух ставок из разных матчей, с десятичным коэффициентом не ниже 1.50. Оценки вероятности и риски приведены только по переданным данным; дополнительное исследование не проводилось.

Для хоккея рынки разделены следующим образом:

- **2-way ML с учётом ОТ/буллитов:** победа команды засчитывается также при выигрыше в овертайме или по буллитам.
- **Regulation-only 3-way:** исход только после 60 минут; ничья после основного времени является отдельным исходом. Такой рынок не смешивается с 2-way ML.
- **Общий тотал NHL:** по подтверждённым правилам FanDuel учитываются голы в овертайме; в серии буллитов победителю засчитывается одна шайба.

Для баскетбола ML и общий тотал рассматриваются **с учётом овертайма**, если иное не указано отдельно.

## 2. Основные варианты

### 2.1. Carolina Hurricanes — Seattle Kraken

**Начало:** 12.11.2026, 20:00 МСК  
**Основной выбор:** тотал больше 6.5 шайб  
**Рынок:** общий тотал NHL, не regulation-only  
**Коэффициент:** 1.91 (FanDuel, Over -110)

Carolina имела показатели 14-3-2, Seattle — 9-6-1. Переданные данные приводят средние показатели Carolina 4.11 заброшенной шайбы и 2.32 пропущенной за матч, Seattle — 3.44 и 3.56 соответственно. Независимая модель давала прогноз 4:3 и среднее 6.8 гола; указанная пуассоновская конверсия для 7 и более шайб — около 52.0%.

**Оценка вероятности:** около 52.0%. Это практически соответствует безубыточной вероятности для коэффициента 1.91 — около 52.36%; выраженное value не подтверждено. Выбор основан на вероятности прохода и доступном коэффициенте, а не на существенном положительном математическом ожидании.

**Почему выбран:** коэффициент проходит минимальный порог; прогнозируемый темп матча и показатели обороны Seattle допускают результат выше 6.5. Правила учёта ОТ и буллитной шайбы подтверждены для тотала.

**Риски:** стартовые вратари и окончательные составы на момент проверки не были подтверждены; отмечались травмы Jordan Staal у Carolina, Jared McCann, Ryan Lindgren, Jacob Melanson и Curtis Douglas у Seattle, а также day-to-day статус William Carrier. Международный матч в Хельсинки и поездка повышают неопределённость. Модельное преимущество практически отсутствует после округления.

### 2.2. Montréal Canadiens — Boston Bruins

**Начало:** 13.11.2026, 03:00 МСК  
**Основной выбор:** Boston Bruins — победа в матче (2-way ML)  
**Рынок:** 2-way ML, включая ОТ и буллиты  
**Коэффициент:** 1.83 (Boston -120)

Переданные оценки дают Boston около 54–55% на победу с учётом ОТ/буллитов: Dratings — 54.7%, Kalshi — 54%. Команды входили в матч с показателями 13-4-1 у Boston и 11-3-4 у Montreal. У Boston отмечалась серия из четырёх побед; у Montreal были подтверждённые кадровые ограничения, включая Mike Matheson OUT и Jake Evans questionable.

**Правила рынка:** NHL предусматривает три периода по 20 минут; при ничьей используются овертайм и затем буллиты. Для выбранного 2-way ML победа Boston в ОТ или по буллитам считается выигрышем ставки. Это не regulation-only 3-way. Официальный API указывал otInUse=true и shootoutInUse=true.

**Оценка вероятности:** около 55%. Коэффициент 1.83 примерно соответствует рыночной вероятности, поэтому существенного value не выявлено. Выбор обусловлен сочетанием более высокой оценённой вероятности, домашнего фактора и текущей формы.

**Риски:** стартовые вратари официально не были объявлены; у Montreal были потери и сомнения по составу, у Boston — James Hagens в IR. Montreal играл 11 ноября и проиграл Minnesota в ОТ, что создаёт фактор усталости, но одновременно повышает неопределённость.

## 3. Альтернативы после основных вариантов

### 3.1. Florida Panthers ML против Detroit Red Wings — альтернатива

**Начало:** 13.11.2026, 03:30 МСК  
**Рынок:** 2-way ML, включая ОТ/буллиты  
**Коэффициент:** 1.61 (Florida -165)  
**Оценка:** около 60–62%.

Florida имела сезонный показатель 10-7-2 против 7-9-3 у Detroit; независимые данные указывали преимущество Florida по голам за матч, большинству и меньшинству. В пользу Panthers также выступала рыночная оценка 60–62%. Однако линия близка к независимой вероятности, выраженного value нет. Стартовый вратарь Florida не подтверждён; возвращение Aleksander Barkov и Brad Marchand официально не гарантировалось. Detroit уже выигрывал первый очный матч сезона. Поэтому вариант оставлен альтернативой, а не включён в два основных выбора.

**Regulation-only 3-way:** в предоставленных данных подтверждения такого рынка нет; его нельзя приравнивать к выбранному 2-way ML.

### 3.2. Тотал Carolina — Seattle

Этот вариант является основным выбором отчёта. Альтернативный рынок Carolina ML не рекомендован: коэффициент около 1.35–1.36 ниже обязательного порога 1.50. Seattle ML и regulation-only 3-way имеют более высокий риск и не обладают сопоставимой поддержкой вероятности.

### 3.3. Рынки баскетбола

По Dallas — Minnesota наиболее вероятным был Minnesota ML, но коэффициент около 1.48 ниже порога 1.50. Dallas ML имел коэффициент 2.76, но оценённую вероятность лишь около 28–34%; тотал 226.5 имел коэффициент около 1.91, однако независимая вероятностная оценка тотала не была предоставлена. Поэтому матч исключён.

По Toronto — Philadelphia Philadelphia была явным фаворитом, но её коэффициент около 1.25 ниже порога. Toronto имел высокую цену, однако независимые оценки давали лишь 21–38% на победу; подтверждённой линии общего тотала не было. Поэтому матч исключён. Для баскетбольных ML рынков учитывается ОТ.

## 4. Все рассмотренные матчи и решение

| Время МСК | Матч | Вид спорта | Проверенные рынки | Решение | Причина |
|---|---|---|---|---|---|
| 12.11, 20:00 | Carolina Hurricanes — Seattle Kraken | Хоккей | 2-way ML, regulation-only 3-way, тотал 6.5 | **Основной: Over 6.5, 1.91** | ML Carolina ниже 1.50; 3-way и Seattle рискованнее |
| 13.11, 03:00 | Montréal Canadiens — Boston Bruins | Хоккей | 2-way ML, regulation-only 3-way, тотал около 6.5 | **Основной: Boston ML, 1.83** | Поддержка вероятности около 55%; стартовые вратари не подтверждены |
| 13.11, 03:30 | Detroit Red Wings — Florida Panthers | Хоккей | 2-way ML, regulation-only 3-way, тоталы 5.5/6.5 | **Альтернатива: Florida ML, 1.61** | Вероятность 60–62%, но value ограничено; состав и вратарь не подтверждены |
| 13.11, 03:00 | Toronto Raptors — Philadelphia 76ers | Баскетбол | ML и общий тотал | **Исключён** | Philadelphia ML ниже 1.50; Toronto имеет низкую вероятность; тотал не опубликован |
| 13.11, 04:00 | Dallas Mavericks — Minnesota Timberwolves | Баскетбол | ML и тотал 226.5 | **Исключён** | Minnesota ML около 1.48; Dallas слишком маловероятен; по тоталу нет независимой модели |

## 5. Причины исключения и общие риски

- Не использовались ставки с коэффициентом ниже 1.50, даже если фаворит имел высокую оценённую вероятность.
- Regulation-only 3-way рынки NHL не выбирались при отсутствии подтверждённой цены и достаточного преимущества. Их нельзя считать эквивалентом 2-way ML с ОТ/буллитами.
- Не подтверждённые стартовые вратари, поздние статусы игроков и возможные изменения составов существенно влияют на хоккейные и баскетбольные оценки.
- В матче Carolina — Seattle преимущество тотала практически отсутствует относительно безубыточной вероятности.
- В матче Boston — Montreal коэффициент близок к справедливой рыночной оценке, поэтому существенное value не заявляется.
- В Florida — Detroit вероятность выше 60%, но линия близка к независимой оценке; это запасной вариант, а не обязательная ставка.
- В Toronto — Philadelphia статусы Joel Embiid и LeBron James были questionable, а источники расходились по отдельным статусам; в Dallas — Minnesota имелись существенные потери состава и небольшое расхождение отображаемого времени у букмекера с официальным расписанием.

## 6. Итог

**Два основных варианта:**

1. **Carolina Hurricanes — Seattle Kraken: тотал больше 6.5, коэффициент 1.91.** Общий тотал NHL; ОТ учитывается, в буллитах победителю засчитывается одна шайба.
2. **Boston Bruins — Montréal Canadiens: Boston 2-way ML, коэффициент 1.83.** Победа в ОТ или по буллитам учитывается.

**Альтернатива:** Florida Panthers 2-way ML против Detroit Red Wings, коэффициент 1.61, включая ОТ/буллиты.

Это аналитический предматчевый отбор. **Ставки не совершались.**

## References

[1]: https://www.nhl.com/gamecenter/car-vs-sea/2026/11/12/2026020309 "NHL GameCenter: Carolina Hurricanes — Seattle Kraken"
[2]: https://www.nhl.com/news/carolina-hurricanes-seattle-kraken-game-preview-november-11-2026 "NHL preview: Carolina Hurricanes — Seattle Kraken"
[3]: https://www.espn.com/nhl/game/_/gameId/401891808/hurricanes-kraken "ESPN: Hurricanes — Kraken"
[4]: https://sportsbook.fanduel.com/hockey/nhl/carolina-hurricanes-@-seattle-kraken-36309079 "FanDuel: Hurricanes — Kraken odds"
[5]: https://933kjr.iheart.com/content/2026-11-10-hurricanes-vs-kraken-prediction-picks-nov-12/ "iHeart/KJR: Hurricanes — Kraken prediction"
[6]: https://www.fanduel.com/sports-betting-guide/how-to-bet-on-nhl "FanDuel NHL betting rules"
[7]: https://api-web.nhle.com/v1/gamecenter/2026020299/landing "NHL API: Canadiens — Bruins"
[8]: https://api-web.nhle.com/v1/schedule/2026-11-12 "NHL schedule API"
[9]: https://www.dratings.com/predictor/nhl-hockey-predictions/1145649f-34d7-5275-b643-cb137354f397 "DRatings: Canadiens — Bruins prediction"
[10]: https://kalshi.com/markets/kxnhlgame/nhl-game/kxnhlgame-26nov12mtlbos "Kalshi: Canadiens — Bruins market"
[11]: https://www.espn.com/nhl/game/_/gameId/401892696/canadiens-bruins "ESPN: Canadiens — Bruins"
[12]: https://www.nhl.com/bruins/news/practice-report-eyssimont-bruins-prepare-for-rivalry-game-against-montreal "Boston Bruins practice report"
[13]: https://www.nhl.com/gamecenter/det-vs-fla/2026/11/12/2026020302 "NHL GameCenter: Red Wings — Panthers"
[14]: https://api-web.nhle.com/v1/gamecenter/2026020302/landing "NHL API: Red Wings — Panthers"
[15]: https://www.covers.com/sport/hockey/nhl/matchup/382581/odds "Covers: Red Wings — Panthers odds"
[16]: https://kalshi.com/markets/kxnhlgame/nhl-game/kxnhlgame-26nov12detfla "Kalshi: Red Wings — Panthers market"
[17]: https://insidetherink.com/stats/nhl/games/2026-11-12-red-wings-at-panthers-2026020302/ "Inside The Rink: Red Wings — Panthers statistics"
[18]: https://www.nhl.com/news/nhl-status-report-news-and-notes-november-10-2026 "NHL Status Report"
[19]: https://www.nba.com/timberwolves/game/0022600229-mavericks-vs-timberwolves-minneapolis-mn-11-12-2026 "NBA: Mavericks — Timberwolves official game page"
[20]: https://www.nba.com/game/dal-vs-min-0022600229 "NBA Game: Mavericks — Timberwolves"
[21]: https://sportsbook.fanduel.com/basketball/nba/dallas-mavericks-@-minnesota-timberwolves-36303940 "FanDuel: Mavericks — Timberwolves odds"
[22]: https://www.espn.com/nba/game/_/gameId/401909978/mavericks-timberwolves "ESPN: Mavericks — Timberwolves"
[23]: https://kalshi.com/markets/kxnbagame/mavericks-vs-timberwolves/kxnbagame-26nov12dalmin "Kalshi: Mavericks — Timberwolves market"
[24]: https://ak-static.cms.nba.com/referee/injury/Injury-Report_2026-11-11_11_00PM.pdf "NBA Injury Report, 11 November 2026, 23:00 ET"
[25]: https://www.nba.com/sixers/game/0022600227-raptors-vs-sixers-philadelphia-pa-11-12-2026 "NBA: Raptors — 76ers official game page"
[26]: https://ak-static.cms.nba.com/referee/injury/Injury-Report_2026-11-11_07_45PM.pdf "NBA Injury Report, 11 November 2026, 19:45 ET"
[27]: https://www.optimal-bet.com/nba/games/7317a389-585e-41d9-a2ff-5df33364c59b/raptors-at-76ers-2026-11-12 "Optimal-Bet: Raptors — 76ers odds"
[28]: https://statz.ai/nba/news/toronto-raptors-vs-philadelphia-76ers-prediction-picks-odds-november-12-2026 "Statz: Raptors — 76ers prediction"
[29]: https://www.espn.com/nba/game/_/gameId/401909976/raptors-76ers "ESPN: Raptors — 76ers"
[30]: https://kalshi.com/markets/kxnbagame/raptors-vs-76ers/kxnbagame-26nov12torphi "Kalshi: Raptors — 76ers market"
