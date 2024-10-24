## 1. Что нужно сделать, чтобы защитить объект критической инфраструктуры от атаки БПЛА?
Здесь и далее речь идет о БПЛА самолетного типа, которые противник запускает относительно далеко от атакуемого объекта. 
Для таких БПЛА используется термин OWA (one-way attack) UAVs

БПЛА скрытно пролетают достаточно большое расстояние, долетают до объектов критической инфраструктуры и атакуют их. 

Скрытность может достигаться 
- относительно небольшими размерами БПЛА
- полетом ночью
- полетом в режиме радимолчания
- относительно низким уровнем шума при полете
- полетом по траектории, обеспечивающей низкую вероятность обнаружения 

### Примеры БПЛА

__AQ 400 Scythe__ https://drone-catalog.ru/product/aq-400-scythe/
- Максимальная скорость - 200 км/ч (55 м/с)
- Крейсерская скорость - 144 км/ч (40 м/c)
- Размах крыльев - 2.3 м
- Дальность - 750 км
- Боевая часть - 43 кг
- Высота - от 30 м (лазерный дальномер) до 3000 м (система визуального позиционирования)
- Двигатель - ДВС

__Mugin-5 (Skyeye 5000)__
- Максимальная скорость - 150 км/ч
- Крейсерская скорость - 120 км/ч
- Размах крыльев - 5 м
- Длина - 3.5 м
- Боевая часть - 25 кг
- Двигатель - ДВС
  

__UJ-22 Airborne__
- Максимальная скорость - 160 км/ч
- Крейсерская скорость - 120 км/ч
- Боевая часть - 20 кг
- Размах крыльев - 4.6 м
- Длина - 3.7 м
- Высота - от 50 м до 6000 м

__UJ-25 Skyline__

- Крейсерская скорость - 600 км/ч (166 м/c)
- Максимальная скорость - 800 км/ч (222 м/c)
- Боевая часть - 10 кг
- Двигатель - реактивный

__UJ-26 Beaver__

- Двигатель - ДВС

__Lyutyy / Fierce__

- Длина - 4.4 м
- Размах крыльев - 6.7 м
- Боевая часть - 75 кг
- Двигатель - ДВС

__Lord__

__Y-III__
- Производство - Турция-Пакистан

__Banshee__
- Производство - Великобритания
  
__R-15__

- Размах крыльев - 2.4 м
- Двигатель - ДВС
- Боевая часть - 15 кг

__A22 Foxbat__

__Sky Ranger Nynja__

__FP-1__

__Dart 350__

- Размах крыльев - 2.9 м
- Крейсерская скорость - 432 к/ч (120 м/c)
- Двигатель - реактивный
- Боевая часть - 25 кг
- Производство - Великобритания

Приведенные БПЛА самолетного типа имеют размах крыльев от 2 метров и используют либо двигатель внутреннего сгорания, либо реактивный двигатель. __Гипотеза: такие БПЛА должны быть хорошо видимы с помощью тепловизоров из-за высокой разницы температур между двигателем БПЛА и окружающим воздухом и РЛС из-за своих размеров и скорости движения.__

Возможные варианты защиты объектов
1. Своевременно обнаруживать БПЛА и прерывать их полет.
2. Создавать инженерные укрепления, принимающие на себя поражающее воздействие БПЛА.
   
Примеры укреплений
- https://www.npo-geostroy.ru/uslugi/zashchita-ot-bpla
- https://tndsk.ru/mekhanicheskaya_zashchita_bpla

## 2. Как можно прервать полет БПЛА?
Возможные варианты
1. "сбить" - уничтожить БПЛА в воздухе с помощью ракеты, снаряда, другого БПЛА, дроби, сетки, лазера и т.д.  
2. "посадить" - оказать воздействие с помощью радиоизлучения на систему управления БПЛА, которое приведет к его посадке.

Вариант 2 в настоящее время практически неэффективен из-за того, что БПЛА
- могут лететь в режиме радиомолчания
- могут лететь на финальном этапе по инерциальной навигационной системе, не обращая внимание на отсутствие или искажение сигналов ГНСС
- могут лететь с использованием нестандартных частот, которые нужно сначала определить, чтобы выставлять на них помехи
- могут лететь с использованием системы Старлинк, которая обеспечивает канал управления через спутниковую связь, на которую сложно воздействовать из-за того, что на приемнике используется направленная вертикально вверх антенна, принимающая сигнал со спутника
- на БПЛА могут быть программно-аппаратные средства, определяющие внешнее электромагнитное воздействие и противодействующие ему

## 3. Как можно обнаружить БПЛА в воздухе?
   
Как правило, БПЛА отличаются от обычных ЛА (летательных аппаратов - самолетов или вертолетов) 
- меньшими размерами
- меньшей скоростью полета
- меньшей высотой полета
- меньшей шумностью, особенно при использовании электрических двигателей
- меньшей заметностью
  
Все это значительно снижает эффективность применения тех средств, которые используются для обнаружения самолетов и вертолетов.

Для обнаружения БПЛА могут и должны применяться разными способы и средства 
- РЛС (радиолокационные станции)
- средства радио мониторинга
- средства звукового мониторинга
- средства визуального обнаружения

Пример - https://www.rub-in.ru/product/obnaruzhenie-bpla/dt-rd3000-radar-obnaruzheniya-bpla-bvs-dronov-i-kvadrakopterov/#dops
  
Работу по обнаружению БПЛА можно разбить на несколько этапов:
- поиск, обнаружение и опознавание воздушных целей (БПЛА)
- определение состава и характеристик целей (одиночная, групповая, маневрирующая, неманеврирующая, низколетящая, высотная и пр)
- взятие цели (целей) на сопровождение
- определение текущих координат целей, направления и скорости их полета, завязка траекторий движения целей
- выделение наиболее важных и опасных целей с точки зрения их возможности поражения прикрываемых объектов
- сопровождение выделенных целей
- передача целеуказания на средства поражения


## 4. Как работает обнаружение БПЛА с помощью РЛС?
РЛС формирует сложный радиосигнал и излучает его в определенном направлении с помощью передающей антенны. Это сигнал отражается от БПЛА и принимается принимающей антенной. Сравнивая излученный и принятый сигналы, РЛС способна определить положение БПЛА в воздушном пространстве. Как правило, излучающая и принимающая антенны совмещены в одном устройстве.
Если РЛС излучает и принимает радиосигналы, говорят об активной радиолокации.
Если РЛС не излучает радиосигнал, а только принимает его - говорят о пассивной радиолокации.
Далее мы будем говорить про активную радиолокацию.
На этапе поиска, как правило, используют один вид радиосигнала, тогда как на этапе сопровождения другой вид радиосигнала. 
В режиме поиска антенна часто вращается на 360 градусов, обеспечивая сканирование пространства, а на этапе обнаружения и сопровождения поворачивается так, чтобы "светить" лучом на БПЛА.  
Потенциально технически продвинутая (а следовательно очень сложная и дорогая) РЛС может увидеть БПЛА на большом расстоянии.

Пример РЛС

https://www.rub-in.ru/product/obnaruzhenie-bpla/dt-rd3000-radar-obnaruzheniya-bpla-bvs-dronov-i-kvadrakopterov/#char

- Дальность обнаружения - 3000 м
- Скорость цели - до 20 м/c (меньше чем скорость БПЛА противника)
- Разрешение - 1.5 м (ЭПР 0.01 м2)

https://www.karneev.com/product/radiolokatsionnye-stantsii/karneev-spayder/

- Дальность обнаружения - 2000 м
- Разрешение - 1 м

https://xn--e1agfe6atq9c.xn--p1ai/catalog/zashchita-ot-bpla/statsionarnye-kompleksy/aktivnyy-radar-obnaruzheniya-radar-plyus-rls-bpla/

https://antidronetech.ru/catalog/radiolokator/

## 5. В чем состоит сложность обнаружения БПЛА с помощью РЛС?
- РЛС плохо различает низколетящие объекты из-за помех, которые возникают при отражении радиосигналов от деревьев и зданий, над которыми летят БПЛА
- РЛС плохо различает объекты с малой эффективной площадью рассеяния, к которым относятся БПЛА
- БПЛА сделан из композитных материалов, которые плохо отражают радиосигнал
- РЛС технически сложное и дорогое устройство

Потенциально качество обнаружения БПЛА с помощью РЛС можно повысить путем подъема антенн на определенную высоту, например, с помощью телескопических матч, либо дронов или аэростатов.

## 6. Как работает обнаружение БПЛА с помощью радиомониторинга?
Радиомониторинг можно отнести к пассивной радиолокации. Принцип определения положения БПЛА с помощью радиомониторинга состоит в том, чтобы с помощью нескольких (не менее 4) разнесенных в пространстве антенн принять один и тот же радиосигнал от БПЛА, а затем зная положение каждой антенны и разницу во времени приема сигнала на каждой из антен вычислить положение (или направление на) БПЛА. Это в принципе возможно, если БПЛА излучает радиосигнал во всех направлениях. В настоящее время БПЛА летают в режиме радиомолчания и используют направленные антенны для радиообмена.

## 7. В чем состоит сложность обнаружения БПЛА с помощью радиомониторинга?
БПЛА должен излучать радиосигнал, который может быть принят. 
- Если БПЛА летит в режиме радиомолчания, радио мониторинг ничего не покажет.
- Если БПЛА излучает сигнал в противоположном от принимающей антенны направлении, сигнал перехватить невозможно.
- Если БПЛА излучает сигнал с помощью направленной антенны, принять сигнал достаточной для детекции мощности на 4 антеннах крайне сложно.
   
## 8. Как работает обнаружение БПЛА с помощью звукового мониторинга?
Звуковой мониторинг работает примерно также, как и радиомониторинг. Только вместо радиосигнала принимаются звуковые сигналы. В отличие от радиосигнала звук распространяется более менее равномерно во всех направлениях. Основным источником звука в БПЛА является работающий двигатель. 
С учетом того, что известные БПЛА используют двигатели внутренного сгорания или реактивные двигатели необходимо __оценить возможную дистанцию обнаружения таких БПЛА с помощью звукового мониторинга.__  

## 9. В чем состоит сложность обнаружения БПЛА с помощью звукового мониторинга?
- БПЛА с 4-х тактным двигателем ДВС летит относительно тихо
- чем выше летит БПЛА, тем хуже его слышно на Земле

_Необходимо уточнить вопрос на каком примерно расстоянии могут услышать звук определенной мощности станции звукового мониторинга_

## 10. Как работает визуальное обнаружение БПЛА?
Установленные видеокамеры с тепловизорами постоянно делают кадры воздушного пространства, которые затем в реальном времени анализируются с помощью алгоритмов машинного зрения. Современные алгоритмы машинного зрения на базе искусственного интеллекта способны с высокой точностью и скоростью обнаруживать и локализовать на полученных кадрах БПЛА.
Зная ориентацию видеокамеры в пространстве, а также положение БПЛА на полученном кадре можно получить направление на БПЛА.
Используя несколько разнесенных видеокамер и последовательно получаемые кадры возможно с помощью стерео зрения определять параметры движения БПЛА. 
В режиме поиска БПЛА можно использовать кадры, полученные с помощью широкоугольных объективов, а при обнаружении и сопровождении БПЛА переходить на кадры, полученные с помощью большого фокусного расстояния (зум).

### 10.1 На каком расстоянии можно обнаружить БПЛА с помощью тепловизора?
ChatGpt утверждает, что в хорошую погоду и для хорошего тепловизора дальность может достигать 10-15 км, но в реальности это будет 3-5 км.
Для тепловизоров, используемых в гражданских целях, это будет 1-3 км.

Пример тепловизора https://www.premium-optics.ru/products/thermal-sights/guide/tr/id_6700/

## 10.2 Какие есть китайские производители тепловизоров и тепловизионных камер?
- Hikvision
- Dahua Technology
- Guide Infrared
- Infrared Technology
- Shanghai Thermal Imaging Technology (Satir)

## 11. В чем состоит сложность визуального обнаружения БПЛА?
- БПЛА совершают полеты ночью и неразличимы без тепловизоров
- видеокамеры необходимо совмещать с тепловизорами, чтобы иметь возможность обнаруживать БПЛА ночью / в плохую погоду (дождь / снег / слякоть)
- при использовании специальных теплоотводящих конструкций и материалов БПЛА будут плохо различимы с помощью тепловизоров
- для реализации алгоритмов машинного обучения на базе искусственного интеллекта необходимо иметь большое количество (100 000 и более) подготовленных и размеченных изображений БПЛА в разных условиях, в том числе снятых с использованием тепловизоров
- на большом расстоянии БПЛА из-за малых размеров будут неразличимы на изображении, получаемых с помощью широкоугольных камер
- разрешение тепловизиров меньше чем разрешение у видеокамер
- наиболее предпочительно использовать MWIR тепловизоры, которые относительно дороги - пример, https://tender.russiandrone.ru/catalog/poleznaya-nagruzka/teplovizory/teplovizor-mwir-diapazona-idc-640m15-30-300/ (от 7 млн. рублей)

Пример системы визуального обнаружения - https://www.pergam.ru/catalog/cctv/ohrannye-teplovizory/povorotnye/rtr-420m.htm

## 12. Какой способ стоит использовать для обнаружения БПЛА?
Наиболее предпочтительным является комбинация двух способов обнаружения - визуальное обнаружение и обнаружение с помощью РЛС.
Средства и компоненты, реализующие оба способа обнаружения, должны быть интегрированы в одну систему и взаимно подкреплять друг друга.
- Если с помощью РЛС в определенном направлении обнаружен БПЛА, туда сразу должна быть направлена видеокамера с тепловизором, кадры с которой подтвердят или опровергнут его наличие.
- Аналогичным образом результаты обнаружения БПЛА с помощью видеокамеры должны передаться РЛС, которая сфокусирует радиоизлучение в определенном направлении и подтвердит или опровергнет его наличие.
- Использование независимых способов обнаружения и определения параметров движения БПЛА позволяет в целом значительно повысить точность оценки этих самых параметров для передачи их __средствам прерывания полета БПЛА__ 
  
Дополнительно в систему могут быть интегрированы средства и компоненты, реализующие обнаружение БПЛА с помощью радиомониторинга и звукового мониторинга. Однако эффективность их применения в существующих условиях представляется низкой.

## 13. Сколько времени должно занимать обнаружение и пресечение полета?
Предположим БПЛА AQ 400 Scythe летит со скорость 40 м/c. Система обнаруживает БПЛА на расстоянии 2000 м. БПЛА долетит до системы обнаружения за 50 секунд. Если предположить, что средства обнаружения и прерывания полета БПЛА стоят перед атакуемым объектом, уничтожение БПЛА должно происходить примерно за это время.

Средства обнаружения и средства прерывания полета БПЛА должны быть объединены в одну систему. Время передачи информации от средств обнаружения средствам прерывания полета должно быть минимальным.

## 14. Как можно повысить вероятность обнаружения БПЛА?
Вероятность обнаружения БПЛА с помощью РЛС и визуальных средств обнаружения может быть повышена, если поднять средства обнаружения на значительную высоту, например, с помощью аэростататов или разместить на ЛА, которые могут долго находиться в воздухе (дрон на привязи).

## 15. Сколько БПЛА атакует одну цель?
Количество БПЛА, которые одновременно атакуют объекты критической инфраструктуры, увеличивается. Утверждается, что в одной из атак участвовало около 10 БПЛА.
Средства обнаружения БПЛА должны быть в состоянии обнаруживать, сопровождать и передавать целеуказания сразу по нескольким целям.

## 16. Чем и как сбивать БПЛА?
Представляется, что хорошо оснащенные и обученные силы ПВО смогут с высокой эффективностью отразить налет тех БПЛА самолетного типа, которые используются для атак на объекты критической инфраструктуры.
Современные комплексы ПВО __ближнего радиуса действия__, как правило, имеют в своем составе РЛС и оптические средства (см. пункт 11), разрабатывались или модернизировались в том числе для противодействия БПЛА и имеют достаточную огневую мощь, чтобы поразить достаточно много целей.
Примерами таких комплексов могут служить
- 2С-38, ЗАК-57, "Деривация-ПВО" https://ru.wikipedia.org/wiki/2%D0%A138
- Oerlikon Skynex - https://www.rheinmetall.com/Rheinmetall%20Group/brochure-download/Air-Defence/B200e0424-Oerlikon-Skynex-air-defence-system.pdf
Особенностью таких комплексов является использование автоматических пушек с программируемым временем подрыва снаряда. Это позволяет во время прохождения снаряда через канал ствола задать время, через которое снаряд взорвется. Далее комплекс вычисляет траекторию движения БПЛА, с упреждением выпускает в его сторону снаряды и программирует их так, чтобы они взорвались в тот момент, когда будут находиться максимально близко к цели.

Видео с визуализацией - https://www.youtube.com/watch?v=bdwjcayPuag

Такой подход обеспечивает высокую вероятность поражения БПЛА с относительно небольшим расходом боеприпасов на одну цель. Как следствие, экономное расходование боезапаса позволяет поразить множество целей без перезарядки.

Oerlikon Skynex использует снаряды AHEAD https://ru.wikipedia.org/wiki/AHEAD. Такие снаряды представляют собой технически сложное устройство, наладить массовый выпуск которых представляется достаточно сложным. 
Видео работы комплекса Oerlikon Skynex:
- https://disk.yandex.ru/d/hh6GPdKP0crBwg
- https://disk.yandex.ru/i/B3Vs_UL0cKbrzA
- https://www.youtube.com/watch?v=SDuXOxsGrtA
- https://www.youtube.com/watch?v=VPu7kNM4-Tc

Комплекс "Деривация-ПВО" использует только оптико-электронную систему обнаружения и прицеливания. Комплекс Oerlikon Skynex имеет как РЛС, так и оптико-электронную систему.

Эффективность работы комплексов ПВО предыдущих поколений против БПЛА оценить сложно. Представляется, что эффективность будем тем ниже, чем более старый комплекс будет использоваться. Снижение эффективности обусловлено характеристиками используемых РЛС, которые, как представляется, будут малоэффективы при обнаружении и сопровождении БПЛА с низкой ЭПР.

Примеры комплексов ПВО
- Панцирь
- Тунгуска
- Тор
- Стрела
- Оса
- Шилка

Представляется, что эффективность использования комплексов ПВО ближнего радиуса может быть повышена путем интеграции их с другими средствами обнаружения и сопровождения целей, модернизации используемых РЛС и встраивания средств визуального обнаружения.


## 17. Как еще можно было бы сбивать БПЛА?
В условиях недостатка штатных сил и средств ПВО рассмотрим альтернативные способы прерывания полета БПЛА. 

Наиболее перспективным способом представляется использование дронов-перехватчиков. 

Дроны-перехватчики могут как иметь в своем составе взрывчатое вещество, так и не иметь.

Пример реализации дронов-перехватчиков
- https://www.youtube.com/watch?v=ftcKM9hCbYY
- https://www.youtube.com/watch?v=_2ivnN-9jno

Попробуем определить для дрона-перехватчика
- наиболее эффективную форму
- требования к динамическим характеристикам
- возможные способы наведения на цель
- возможные аппаратные средства для реализации наведения и перехвата цели

Возможные формы 
- коптер
- дрон самолетного типа

Максимальная скорость
- до 200 км/ч (55 м/c)

Можно сбивать дроны с ДВС двигателем

## 18. Как могла бы выглядеть альтернативная система обнаружения и прерывания полета БПЛА?
Что с чем нужно иметь возможность интегрировать?
- РЛС -> средства прерывания полета
- Средства визуального обнаружения БПЛА -> средства прерывания полета
- РЛС -> Средства визуального обнаружения БПЛА
- Средства визуального обнаружения БПЛА -> РЛС

https://tender.russiandrone.ru/catalog/poleznaya-nagruzka/lokatory/ultrafioletovyy-pelengator-dlya-bespilotnikov/
