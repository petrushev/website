# Модели и нивните предвидувања
 
Во нашата група соработуваат и стручњаци за статистички моделирања и компјутерски симулации.
На оваа страница ќе ги објавуваме линковите до некои од нивните трудови, кои ги направија со помош на собраните податоци од [COVID-19 Трекер](https://covid-19.treker.mk).

Моделите ги земаат во обѕир сите познати информации за ширењето на вирусот во државата, ама сепак **не можат да понудат најпрецизни предвидувања** за идниот тек на епидемијата и **затоа е потребно да се прочитаат внимателно сите претпоставки на моделот**.

Податоците за тестовите и бројот на заразени лица во државата, како и на другите места во светот, не се најпрецизни. Затоа  поголемиот број на модели се темелат на податоци за хоспитализациите или, за жал, починатите. Доколку се и тие податоци непрецизни, моделите ќе ги прикажуваат идните вредности со помала прецизност. 

Глобалната наука вложува огромни напори во борба со болеста, ама сепак голем број од аспектите на ширењето и развојот на болеста сеуште не се најдобро истражени. Посебно е голема несигурноста во мерките, кои владите во светот ги изведуваат за ограничување на ширењето на болеста. Исто така и заради временските доцнења, по заразувањата и откривањето на болеста со тестови,  е практично невозможно да се оцени точно моменталната состојба на заразена популација и брзината на ширење на заразата во неа. Сите овие се причини и додатни пречки за моделите. Колку понапред гледаме во иднина, повеќе расте несигурноста во предвидувањата.   

Повеќе за [аспектите на моделирањата](https://content.sciendo.com/view/journals/sjph/59/3/article-p117.xml) од професорот Јанез Жиберт. 

## SIR модел

Моделот е прилагодена верзија на Словенечкиот модел SIR (Susceptible, Infected, and Recovered), кој се користеше за моделирање на COVID-19 динамиката во Словенија и прогноза на датумот на максималниот број на активни случаи. Моделот е изработен од страна на [проф. Љупчо Тодоровски]( http://kt.ijs.si/~ljupco/), [Никола Симиџиевски](https://simidjievskin.github.io/) и Матеј Петковиќ од Институт Јожеф Стефан во Љубљана, Словенија.
Се работи за основен модел  SIR , калибриран само за податоците на активни случаи од македонскиот [Treker](https://covid-19.treker.mk/). Моделот се калибрира редовно. Идните резултати и предвидувања можат да се најдат на [линкот](http://kt.ijs.si/~ljupco/covid-19-sir.mk/report.nb.html).

<a href="http://kt.ijs.si/~ljupco/covid-19-sir.mk/daily_report.png" class="img-link">
<img alt="SIR модел" src="http://kt.ijs.si/~ljupco/covid-19-sir.mk/daily_report.png"></a>

## SEIR модел

Моделот,  што следи, е прилагодена верзија на Словенечкиот модел SEIR (Susceptible, Exposed, Infected, and Recovered), кој се користеше и се користи за моделирање на COVID-19 динамиката во Словенија. Достапен е за употреба на веб страната [Sledilnik](https://covid-19.sledilnik.org/). Моделот е изработен од страна на  [проф. Јанез Жиберт](https://pacs.zf.uni-lj.si/janez-zibert/) од здравствениот факултет и факултетот за информатички науки на универзитетот во Љубљана, Словенија. 

Се работи за граночен модел СЕИР, раширен со додадени гранки za моделирање на бројот на хоспитализирани, пациенти на интензивна нега и починати. Моделот е засега калибриран  само за податоците на хоспитализирани и починати од македонскиот [Treker](https://covid-19.treker.mk/). Моделот се калибрира на дневна база. Идните резултати и предвидувања можат да се најдат на [линкот](https://apps.lusy.fri.uni-lj.si/appsR/CoronaMK/)


<a href="https://apps.lusy.fri.uni-lj.si/~janezz/last_simulation_MK.png" class="img-link">
<img alt="SEIR model" src="https://apps.lusy.fri.uni-lj.si/~janezz/last_simulation_MK.png"></a>

## Прoцена на репродуктивниот број

Репродуктивниот број е просечен број на новозаразени од еден заразен.
Пресметката, што следи, ја изработи [Харис Бабачиќ](https://www.linkedin.com/in/harisbabacic/) од Каролинска Институтот во Стокхолм, Шведска.

Тука претставениот репродуктивен број по денови (Rt) на SARS-CoV-2 вирусот во Македонија е проценет со метод на подобност преку кој се изведува временската динамика на репродуктивниот број врз основа на епидемиската крива (бројот на нови случаи по денови)1, при што генерациското време е базирано на модел на Ferretti et al. (2020)2. Процената на Rt е помалку сигурна на почетокот на епидемијата и во изминатите неколку дена.

При одржувањето на Rt одреден период над 1 епидемијата се шири и обратно -  при одржувањето на Rt под 1 епидемијата стивнува. Поедноставно кажано, да се сведе репродуктивниот број на 0.7 значи дека во просек од 10 заразени седуммина заразувале уште по еден човек а тројца не би заразиле никој. И со текот на времето како што заразените ќе се опоравуваат или умираат, вкупниот број на активни случаи, т.е. индивидуи кои би можеле да заразат други, ќе опаѓа и епидемијата ќе стивнува додека и последниот човек не се опорави или почине.

<a href="https://drive.google.com/uc?export=view&id=1lN77ngzSU6M4Al3yLvo-vPsppph0mhPG" class="img-link">
<img alt="Rt" src="https://drive.google.com/uc?export=view&id=1lN77ngzSU6M4Al3yLvo-vPsppph0mhPG"></a>

**График Rt.** Репродуктивен број по денови (Rt) во Македонија. Точките и линиите го покажуваат движењето на проценетиот Rt во тек на време. Бледо-сините сенки ги покажуваат 95% интервалите на доверба, т.е. покажуваат од каде до каде може да е вистинскиот Rt и ја одразуваат несигурноста во проценетиот Rt.

Слична проценка изработи [Баже Петрушев](https://www.linkedin.com/in/petrushev), овој пат со Бејзови статистички методи. Во моделот, Rt се разгледува како фактор кој бавно се менува со Гаусов произволен ôд, во логаритамска скала, а веројатноста на исходот на новозаболени се разгледува како Гама-Поасонова распределба.

<a href="https://raw.githubusercontent.com/petrushev/bayesian-modeling/covid-19-mk/07%20covid19/mk_daily_R.png" class="img-link">
<img alt="Rt-bayes" src="https://raw.githubusercontent.com/petrushev/bayesian-modeling/covid-19-mk/07%20covid19/mk_daily_R.png"></a>

Лево: Репродуктивен број по денови (Rt) во Македонија. Темната линија ја покажува средната проценка, светлата и темната сенка покажуваат 95% и 50% интервал на најголема густина, соодветно. Десно: Црните точки ги покажуваат официјалните бројки на новозаразени по денови. Темната линија и сенките се средната проценка и интервалите.

*1.       Wallinga J, Teunis P. Different epidemic curves for severe acute respiratory syndrome reveal similar impacts of control measures. Am J Epidemiol. 2004;160(6):509-516. doi:10.1093/aje/kwh255*

*2.       Ferretti L, Wymant C, Kendall M, et al. Quantifying SARS-CoV-2 transmission suggests epidemic control with digital contact tracing. Science. March 2020. doi:10.1126/science.abb6936*
