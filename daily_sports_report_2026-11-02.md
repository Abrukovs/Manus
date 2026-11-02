# Ежедневный мультиспортивный анализ V2.0

**Дата отчёта:** 2026-11-02, 05:00 MSK  
**Окно событий:** 2026-11-02 05:00 — 2026-11-03 05:00 MSK  
**Спорт:** теннис, хоккей, баскетбол  
**Футбол:** не анализировался  
**Ставки:** не совершались

## Основной выбор

### 1. Lilli Tagger ML — Elsa Jacquemot, WTA Chennai

**Рынок и цена.** Выбран ML Tagger по коэффициенту около `1,63`, что выше установленного минимума `1,50`. Общий тотал геймов также проверялся, но согласованного направления по нему не найдено; рынки отдельных сетов не использовались. [1]

**Подтверждение и вероятность.** TennisPrediction даёт Tagger `74,49%` против `25,51%` у Jacquemot. Независимый источник Dimers оценивает Tagger примерно в `76%`. Официальная страница WTA подтверждает турнир Chennai 2026 и его разделы Scores, Draws и Player List; пара и линия дополнительно подтверждены TennisPrediction. [1] [2] [3]

**Оценка.** Источники сходятся на явном преимуществе Tagger. Цена проходит фильтр, состав участниц подтверждён, а рынок однозначен. Это выбор по хорошей вероятности успеха, а не только по формальному value.

**Уверенность:** высокая-средняя.  
**Риски:** матч первого круга может быть менее предсказуемым; независимая проверка официального order of play на момент отчёта была неполной из-за динамической загрузки WTA, поэтому подтверждение пары опирается на официальный турнир и два внешних источника. Это снижает уверенность по сравнению с полностью открытой карточкой матча.

### 2. Detroit Pistons ML — Charlotte Hornets, NBA

**Рынок и правило расчёта.** Выбран ML Detroit по линии около `-175`, то есть примерно `1,57` в десятичном формате. Для NBA ML рассчитывается по итоговому результату с учётом овертайма согласно правилам линии; regulation-only рынок не использовался. Общий тотал около `209,5` также проверен, но не выбран: модель Statz даёт `211,0`, а независимого согласованного направления over/under нет. [4]

**Подтверждение и вероятность.** Statz оценивает Detroit примерно в `61–62%` и показывает модельную линию около `-3,8/-3,9`; рыночная линия даёт Detroit около `1,57`. ESPN и официальный NBA Game Summary подтверждают матч. [4] [5] [6]

**Форма и профиль.** Detroit имеет старт `5–1`, выиграл последние четыре матча из пяти и уже победил Charlotte `97–89` 28 октября. Pistons играют в гостях, но подходят к матчу после отдыха с 30 октября. Charlotte имеет результат `3–4`, проиграла Philadelphia в последней игре и уступила Detroit в недавней очной встрече. [4] [6]

**Кадровые новости.** У Detroit отсутствуют Jalen Duren и Isaiah Joe. У Charlotte список потерь шире: Coby White, Kon Knueppel, Grant Williams и Kylan Boswell указаны как out. Statz ожидает увеличенные роли Paul Reed и John Collins у Detroit и Dennis Schroder/Brandon Miller у Charlotte. [4]

**Оценка.** Модель, форма, очная встреча и более глубокий доступный состав поддерживают Detroit. Риск состоит в отсутствии Duren и в том, что матч проходит в Charlotte.

**Уверенность:** средняя.  
**Риски:** кадровая потеря Duren ухудшает подбор и защиту кольца; коэффициент близок к минимально допустимому, поэтому запас по цене небольшой.

**Основных вариантов: 2 из 2.** Они из разных матчей и разных видов спорта.

## Обязательный охват

### Хоккей: NHL

В пределах окна рассмотрены пять матчей: Vegas Golden Knights — Boston Bruins, Detroit Red Wings — Florida Panthers, Colorado Avalanche — Chicago Blackhawks, Calgary Flames — San Jose Sharks, а также граничащий с концом окна матч Calgary — San Jose по времени линии. ESPN показывает по ним ML и totals: Vegas `-112` против Boston `-108`, Florida `-175` против Detroit `+145`, Colorado `-230` против Chicago `+190`, San Jose `-135` против Calgary `+114`; totals составляют соответственно `6,5`, `5,5`, `6,5` и `6,5`. Официальные страницы NHL подтверждают как минимум Vegas–Boston и Colorado–Chicago, а ESPN — полный набор линий. [7] [8] [9] [10]

**Vegas — Boston.** Это наиболее близкая линия: Vegas `1,89`, Boston примерно `1,93` по 2-way ML. Covers показывает сезонные записи Vegas `9–5–1` и Boston `10–4–1`, но независимый Kalshi-рынок оценивает Vegas лишь примерно в `51%`. Консенсуса по победителю нет. Total `6,5` проверен; направление не подтверждено моделью. Регulation-only 3-way линия не была надёжно доступна в открытом источнике. Вариант исключён из-за почти равного рынка и отсутствия хорошей независимой вероятности. [11] [12]

**Detroit — Florida.** Florida около `1,57` проходит порог, а общая форма Florida лучше: `8–4` против `6–5` у Detroit. Однако Covers фиксирует существенные кадровые потери Florida — Aleksander Barkov, Brad Marchand и вратарь Jacob Markstrom — одновременно с потерями Detroit. Полного независимого модельного подтверждения именно исхода ML нет, а прогноз по total не подтверждён. Вариант исключён из-за кадровой неопределённости и недостатка согласованной модели. [13]

**Colorado — Chicago.** Colorado около `1,43`, ниже минимального коэффициента `1,50`, поэтому ML автоматически исключён. AccuScore оценивает Colorado в `65%` против `36%` у Chicago; форма также поддерживает Colorado: команда выиграла три из последних пяти, тогда как Chicago выиграл один из пяти. Total `6,5` имеет цены около `2,05` на over и `1,80` на under, но независимое направление не подтверждено. [9] [14]

**Calgary — San Jose.** San Jose около `1,74` и Calgary около `2,14`, однако линия близкая для фаворита, а подтверждённой модели и состава в требуемом объёме нет. Total `6,5` также не имеет согласованного направления. Вариант исключён.

Для каждого хоккейного кандидата проверялись три применимых типа рынка: 2-way ML с ОТ/буллитами, regulation-only 3-way ML при наличии и общий total. Стандартный NHL 2-way ML означает победу с учётом овертайма и буллитов; 3-way/regulation-only рассчитывается только по итогам 60 минут и допускает ничью. Для total правило источника должно быть подтверждено отдельно; у FanDuel стандартные totals обычно включают ОТ, если прямо не указано иное, тогда как 3-way ML ОТ не включает. [15] [16]

Ни один хоккейный вариант не выбран. Причины: Colorado имеет короткую цену, Vegas–Boston слишком близки, Detroit–Florida осложнён подтверждёнными кадровыми потерями, а Calgary–San Jose не имеет достаточной независимой модельной поддержки.

### Баскетбол: NBA

В окно до 05:00 MSK 3 ноября попали следующие матчи: Oklahoma City — Cleveland, Detroit — Charlotte, Atlanta — Indiana, Brooklyn — New York, Washington — Orlando, Chicago — Philadelphia, Sacramento — Dallas, New Orleans — Memphis, Milwaukee — Minnesota, Boston — Houston и Portland — Denver. Все перечисленные матчи отражены в официальном NBA schedule/game summary и в линии ESPN. Более поздние матчи после 05:00 MSK 3 ноября не использовались. [5] [6] [17]

**Oklahoma City — Cleveland.** Cleveland около `1,56`, но официальный NBA preview указывает, что Oklahoma City потерял трёх стартовых игроков на длительный срок: Chet Holmgren, Jalen Williams и Cason Wallace; дополнительно не ожидаются Alex Caruso и Thomas Sorber. Kalshi оценивает Cleveland примерно в `64%`, но из-за кадровой неопределённости OKC и отсутствия достаточного независимого консенсуса вариант не выбран. Total `227,5` проверен, направление не согласовано. [18] [19]

**Detroit — Charlotte.** Detroit около `1,57`, Statz `61–62%`; выбран основным вариантом. Total `209,5` отклонён из-за близости модели `211,0` к рынку и отсутствия второго согласованного источника. [4]

**Atlanta — Indiana.** DRatings даёт Atlanta около `72,1%`, но на открытой странице не была доступна надёжная ML-линия для сравнения с коэффициентом и правилом расчёта. Вариант не публикуется без подтверждённой цены.

**Brooklyn — New York.** Knicks имеют очень короткую цену около `1,12` (`-850`), ниже порога `1,50`, поэтому исключены независимо от высокой вероятности.

**Washington — Orlando.** Линия близкая: Orlando около `1,80`, Washington около `2,05`; независимой модели с устойчивым преимуществом не найдено. Total `224,5` также не имеет консенсуса.

**Chicago — Philadelphia.** Philadelphia около `1,15` (`-650`), ниже порога. Total `238,5` не имеет согласованного направления.

**Sacramento — Dallas.** Dallas около `1,25` (`-395`), ниже порога. Total `234,5` без подтверждённого направления.

**New Orleans — Memphis.** Memphis около `1,45` (`-225`), немного ниже порога; Statz также показывает нестандартную оценку, близкую к равной, поэтому вариант не проходит фильтр.

**Milwaukee — Minnesota.** Minnesota около `1,21` (`-470`), ниже порога.

**Boston — Houston.** Линия близкая: Houston около `1,95`, Boston около `2,65`; модель Statz показывает Houston лишь `56,4%`, а форма и цена не дают достаточного согласованного преимущества. Исключён.

**Portland — Denver.** Denver около `1,57`, но независимая модель DRatings даёт Denver `68,3%` при рыночной цене около `1,57`, тогда как официальная кадровая информация и подтверждение рынка не были открыты в достаточном объёме. Не выбран из-за неполной проверки состава и расписания.

Для NBA у каждого кандидата проверялись ML и общий total. Все используемые ML и totals рассчитываются с учётом овертайма по стандартным правилам баскетбольной линии; regulation-only рынки не смешивались и не применялись. Основной баскетбольный выбор — Detroit ML.

### Теннис

В пул вошли матчи ATP Paris Masters: Musetti–Hurkacz, Darderi–Hijikata, Buse–Bergs, Van Assche–Navone, Tabilo–Jodar, Ruud–Cerundolo, Merida Aguilar–Blockx, Norrie–Arnaldi, Bellucci–Sonego, Jacquet–Machac, Molcan–Droguet, Shapovalov–Khachanov и Humbert–Van de Zandschulp. Также рассмотрены Challenger-матчи Costa do Sauipe, Taipei, Bratislava, Charlottesville, Villa Maria и Taranto, а в WTA Chennai — Dart–Kudermetova, Jacquemot–Tagger, Sawangkaew–Hontama, Vandromme–Okamura, Falei–Linette, Yamaguchi–Kulambayeva и Uchijima–Sramkova. Основные расписания и цены взяты из TennisPrediction; официальный ATP подтверждает Paris Masters 2–8 ноября 2026, официальный WTA — Chennai 2026. [1] [20] [3]

**Tagger — Jacquemot.** Tagger около `1,63`, TennisPrediction `74,49%`, Dimers около `76%`; выбран основным. Общий total геймов проверен, но направление не подтверждено.

**Musetti — Hurkacz.** Цены около `1,88–1,89`, TennisPrediction даёт Musetti `55,32%`, но Dimers не может разделить игроков и даёт по `50%`, а Tennis Tonic выбирает Musetti лишь с оговоркой о трёх сетах. Источники недостаточно согласованы, вариант исключён. [21] [22]

**Bergs — Buse.** Bergs около `1,50`, TennisPrediction `58,04%`; цена находится на нижней границе, а второго независимого модельного подтверждения нет. Не выбран.

**Van Assche — Navone.** Van Assche около `1,57`, модель `61,61%`, но независимая проверка не даёт полного согласованного подтверждения. Отмечен как потенциальная альтернатива, но не опубликован основным.

**Ruud — Cerundolo.** Ruud имеет цену около `1,30`, ниже порога, несмотря на хорошую вероятность.

**Blockx — Merida Aguilar.** Blockx около `1,63`, модель `56,93%`; преимущество умеренное и второй независимый источник не подтверждён.

**Khachanov — Shapovalov.** Khachanov около `1,63`, модель `56,23%`; недостаточно сильного независимого консенсуса.

**Humbert — Van de Zandschulp.** Humbert около `1,57`, модель `56,13%`; независимое подтверждение недостаточно полное.

**WTA Chennai: Dart, Sawangkaew, Vandromme, Sramkova.** TennisPrediction показывает вероятности выше 63% для Dart, Sawangkaew, Vandromme и Sramkova, но цены по части фаворитов близки к порогу, а полноценная независимая проверка линий и участников доступна не по всем парам. Они не выбраны основными; Tagger имеет наиболее сильное двойное модельное подтверждение.

Для всех теннисных кандидатов проверялись ML и общий total геймов матча. Totals не выбраны из-за отсутствия согласованного направления. Рынки отдельных сетов не использовались.

## Альтернативы после основного выбора

### Хороший вариант, но цена короткая

- **Colorado Avalanche ML — Chicago Blackhawks:** AccuScore около `65%`, но цена примерно `1,43`, ниже обязательного порога `1,50`.
- **New York Knicks ML — Brooklyn Nets:** цена около `1,12`, ниже порога.
- **Philadelphia 76ers ML — Chicago Bulls:** цена около `1,15`, ниже порога.
- **Dallas Mavericks ML — Sacramento Kings:** цена около `1,25`, ниже порога.
- **Minnesota Timberwolves ML — Milwaukee Bucks:** цена около `1,21`, ниже порога.
- **Ruud ML — Cerundolo:** цена около `1,30`, ниже порога.

### Коэффициент выше `1,50` и независимая оценка выше 50%, но не основной вариант

- **Oklahoma City — Cleveland: Cleveland ML**, около `1,56`, Kalshi около `64%`. Не основной из-за существенных кадровых потерь Oklahoma City и неполного межисточникового консенсуса.
- **Denver Nuggets ML — Portland Trail Blazers**, около `1,57`, DRatings `68,3%`. Не основной из-за неполной проверки официальных составов и кадровых новостей.
- **Luca Van Assche ML — Mariano Navone**, около `1,57`, TennisPrediction `61,61%`. Не основной из-за отсутствия второго независимого подтверждения.
- **Alexander Blockx ML — Daniel Merida Aguilar**, около `1,63`, TennisPrediction `56,93%`. Не основной из-за умеренной вероятности и недостаточного независимого консенсуса.
- **Karen Khachanov ML — Denis Shapovalov**, около `1,63`, TennisPrediction `56,23%`. Не основной из-за умеренного преимущества и неполной внешней проверки.
- **Ugo Humbert ML — Botic van de Zandschulp**, около `1,57`, TennisPrediction `56,13%`. Не основной из-за недостатка независимого подтверждения.
- **Florida Panthers ML — Detroit Red Wings**, около `1,57`, но независимая модель не подтверждена, а Florida имеет потери Barkov, Marchand и Markstrom. Не основной из-за кадрового риска.

## Финальный вывод

В основной список включены два варианта из разных матчей: Lilli Tagger ML и Detroit Pistons ML. Хоккейных основных вариантов нет: Colorado имеет цену ниже минимума, Vegas–Boston близок к монетке, Florida имеет существенные кадровые потери, а Calgary–San Jose не получил достаточного модельного подтверждения. Ставки не совершались.

## References

[1]: https://www.tennisprediction.com/ "TennisPrediction prices and probabilities for November 2, 2026"
[2]: https://www.dimers.com/tennis/predictions/2026_1_wta_3013_906723_53789 "Dimers Tagger–Jacquemot prediction"
[3]: https://www.wtatennis.com/tournaments/1033/chennai/2026 "Official WTA Chennai 2026 tournament page"
[4]: https://statz.ai/nba/news/detroit-pistons-vs-charlotte-hornets-prediction-picks-odds-november-2-2026 "Statz Pistons–Hornets prediction, model and injuries"
[5]: https://www.nba.com/game/det-vs-cha-0022600159 "Official NBA Pistons–Hornets game page"
[6]: https://www.espn.com/nba/odds "ESPN NBA odds for November 2, 2026"
[7]: https://www.nhl.com/schedule/2026-11-02 "Official NHL schedule for November 2, 2026"
[8]: https://www.espn.com/nhl/odds "ESPN NHL odds for November 2, 2026"
[9]: https://www.nhl.com/gamecenter/col-vs-chi/2026/11/02/2026020234 "Official NHL Avalanche–Blackhawks game page"
[10]: https://www.nhl.com/gamecenter/vgk-vs-bos/2026/11/02/2026020232 "Official NHL Golden Knights–Bruins game page"
[11]: https://kalshi.com/markets/kxnhlgame/x/kxnhlgame-26nov02vgkbos "Kalshi Golden Knights–Bruins probability market"
[12]: https://www.covers.com/sport/hockey/nhl/matchup/382509 "Covers Golden Knights–Bruins form and matchup page"
[13]: https://www.covers.com/sport/hockey/nhl/matchup/382508 "Covers Red Wings–Panthers injuries and matchup page"
[14]: https://www.accuscore.com/game/cmvvmzo0uvd9hqd01fzel3ibz "AccuScore Avalanche–Blackhawks model"
[15]: https://www.caesars.com/sportsbook-and-casino/how-to-bet/hockey "Caesars NHL moneyline and regulation-market rules"
[16]: https://www.fanduel.com/sports-betting-guide/how-to-bet-on-nhl "FanDuel NHL 3-way and total rules"
[17]: https://www.nba.com/schedule "Official NBA schedule"
[18]: https://www.nba.com/game/okc-vs-cle-0022600158 "Official NBA Thunder–Cavaliers game page"
[19]: https://kalshi.com/markets/kxnbagame/thunder-vs-cavaliers/kxnbagame-26nov02okccle "Kalshi Thunder–Cavaliers probability market"
[20]: https://www.atptour.com/en/tournaments/paris/352/overview "Official ATP Paris Masters 2026 tournament page"
[21]: https://www.dimers.com/tennis/news/lorenzo-musetti-vs-hubert-hurkacz-tennis-prediction-atp-paris-masters-2026-ac "Dimers Musetti–Hurkacz prediction"
[22]: https://tennistonic.com/tennis-news/1075497/h2h-prediction-of-lorenzo-musetti-vs-hubert-hurkacz-in-paris-with-odds-preview-pick-2nd-november-2026/ "Tennis Tonic Musetti–Hurkacz prediction"
