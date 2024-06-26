# project
Учебная работа по анализу и улучшению бизнес-процессов

# Первичная информация

Чем **занимается компания?**

Компания занимается транспортировкой грузов. В линейке продуктов компании есть предложения для частных клиентов (например, отправка писем, небольших посылок или крупногабаритного груза), для бизнес-клиентов юридических лиц (например, предоставление выделенного транспорта, перевозка сборного груза, отправка документов), а также услуги крупным производителям и ритейлу.

Перевозки осуществляются по всей России, а также в страны Таможенного союза.

**Как организована работа компании?**

Деятельность компании строится от продуктов (есть B2B продуты, есть B2C продукты). Каждый продукт развивает отдельная команда, состоящая из лидера продукта - бизнес-руководителя, принимающего решения в рамках продукта, отвечающего за показатели и успешность продукта. В команду развития входят ИТ команда полного цикла (системный аналитик, разработчики, тестировщики), бизнес-аналитик, а также специалисты по маркетингу и продвижению, дизайнер и технологи. Опционально и временно в команду могут привлекаться эксперты от направлений операционного департамента (под комплексные проекты).

Все продуктовые направления подчинены CPO (Chief Product Officer), который непосредственно подчинен ген. директору.

Отдельной командой под CPO выделена команда контроля качества и СМК.

Также есть отдельный ИТ департамент, который включает Core команды (которые организуют поддержку и развитие базовых ИТ продуктов, которые используются всеми продуктами) и Run команды (которые обеспечивают работу ИТ инфраструктуры,  осуществляют мониторинг нагрузок и других НФТ, организуют работу линий поддержки).

Операционный департамент - реализует базовые производственные процессы: планирование, организацию и управление перевозками, продажи и поддержку клиентов, функционирование складов и инфраструктуры и пр.

Управленческий департамент включает базовые функции, необходимые для функционирования компании: бух. учет, финансовый управление, юридическое обеспечение и пр.

**Как организована работа продуктовой команды?**

Команда работает по спринтам (длительность 2 недели). Каждый спринт предполагает создание небольших инкрементов в области: разработки (новая фича), результатов исследования (бизнес-анализ, маркетинговое исследование) или организационная/бизнесовая активность (регламент, проведенный аудит и пр.). Ведется бэклог продукта и road map развития на год вперед, который защищается перед CPO лидером направления. Данный road map может претерпевать изменения по результатам квартала. Бизнес-аналитик прорабатывает и согласовывает с лидеров продукта требования к изменению продукта (в формате проектного задания) - проработка такого документа может быть разбита на несколько спринтов бизнес-анализа). Команда продукта участвует в подготовке проектного задания.

Также БА работает с заинтересованными сторонами из других продуктов и департаментов (в зависимости от продукта).

Команда после утверждения проектного задания лидером продукта начинает забирать задачи в работу в соответствии с декомпозицией и приоритетами.


# Что нужно сделать

По оперативным данным в продукте наблюдается снижение оборота и отток клиентов к конкурентам.
В качестве основной версии на текущий момент рассматривается снижение качества процессов в части пунктов выдачи заказов на стороне получателя. Т.о. необходимо проанализировать путь от склада до ПВЗ и выдачу в ПВЗ, выявить проблемы и сформировать решения по их устранению.

При этом у продукта сейчас есть планы по увеличению количество ПВЗ, т.о. необходимо формализовать их деятельность и подготовить к тиражированию процессов.
В качестве основных заинтересованных сторон рассматриваются руководители и владельцы ПВЗ, а также отдел по работе с клиентами (операционный департамент). Также в качестве ЗС может быть рассмотрена команда контроля и качества СМК (т.е. их сотрудники будут вовлечены в тиражирование процессов в ПВЗ).


# Интервью

Р**езультат интервью с руководителем Службы доставки**

Ежедневно во второй половине дня нас планируются рейсы на завтра.

Службе доставки при загрузке машины передаются промаркированные запечатанные транспортные короба с заказами. Сборкой и упаковкой коробов занимается Служба складской логистики.

Маркировка содержит уникальный номер короба и информацию о ПВЗ, на который короб необходимо отвезти.

Иногда вместо короба может быть собственная упаковка товара, если он негабаритный (больше стандартного размера короба). В этом случае собственная упаковка приравнивается к коробу и маркируется как короб с одним заказом внутри.

Применяется доставка сборным грузом (это способ автомобильной грузоперевозки, при котором различные грузы перемещаются общим транспортом) путем развоза (т.е. в одну машину грузятся заказы для разных ПВЗ и далее развозятся по ним) на МТТ.

График развозки: утром с 8 до 10 утра, чтобы осуществить доставку непиковые часы загрузки ПВЗ.

Заказы Клиентов доставляются в ПВЗ в промаркированных транспортных коробах, водитель не знает что внутри транспортных коробов. На каждый рейс формируется транспортно-товарная накладная, в которой фиксируются все транспортные короба с привязкой к ПВЗ, в которое их необходимо доставить.

Когда Водитель-экспедитор Службы доставки приезжает на конкретный ПВЗ, то он выгружает транспортные короба согласно транспортно-товарной накладной. Далее Сотрудник ПВЗ фиксирует факт приемки коробов в Акте приемки-передачи.

Также Водитель-экспедитор забирает короба с возвратами и излишками. Такие короба фиксируются в отдельном Акте приемки-передачи возвратов.

После этого Водитель-экспедитор отправляется в следующий ПВЗ.

# Регламент

**Регламент работы ПВЗ**

1. Заказы Клиентов доставляются в ПВЗ в промаркированных транспортных коробах. Приемка товара делится на два этапа:

- Приемка коробов
- Приемка товаров

**1.1. Приемка коробов**

1.1.1 Приемка коробов осуществляется от водителя-экспедитора при доставке в ПВЗ.

1.1.2 Сотрудник ПВЗ должен сравнить перечень передаваемых ему коробов с перечнем коробов в транспортной накладной, принадлежащих его ПВЗ.

**1.2. Приемка товаров**

1.2.1. Каждый короб может содержать от одного до нескольких заказов, одни заказ не может быть разбит на разные короба.

1.2.2. При извлечении заказов из короба Сотрудник ПВЗ должен убедиться, что каждый товар находится в своей индивидуальной упаковке, она не вскрыта и не повреждена. В случае выявления порванной или отсутствующей упаковки, либо при подозрениях, что упаковка могла быть ранее вскрыта, Сотрудник ПВЗ проверяет наличие товара внутри, открыв ее. Если товар поврежден или отсутствует, сотрудник ПВЗ должен добавить товар в АРМ Сотрудника в возвраты и складировать товары для последующей передачи Службе доставки.

1.2.3. После проверки целостности упаковки Сотрудник ПВЗ проверяет заказ в перечне заказов, принадлежащих ПВЗ.

1.2.4. Если заказ принадлежит ПВЗ, то Сотрудник ПВЗ должен отметить в АРМ Сотрудника, что товар принят.

1.2.5. Если заказ пришел на ПВЗ ошибочно, то Сотрудник ПВЗ должен добавить товар в АРМ Сотрудника в излишки и складировать товары для последующей передачи Службе доставки.

**1.3. Раскладка и хранение товаров**

1.3.1. Раскладка и хранение товаров на складе ПВЗ не регламентируется.

**1.4. Выдача товаров клиентам**

1.4.1. Выдача товара клиенту происходит по его запросу в ПВЗ.

1.4.2. Идентификация выдаваемого заказа и клиента производится по уникальному номеру заказа. После поиска в АРМ Сотрудника заказа по номеру Сотрудник ПВЗ должен запросить ФИО клиента и сравнить с ФИО в карточке заказа.

*Примечание: одновременно возможна работа только с одним заказом одного клиента.*

1.4.3. Сотрудник ПВЗ может осуществлять поиск заказа на складе ПВЗ только самостоятельно, Клиенты в зону склада ПВЗ не допускаются.

1.4.4. Примерка/проверка товара осуществляется только на территории ПВЗ в специально отведенных местах. Примерка ювелирных изделий и проверка техники должна осуществляться только под наблюдением Сотрудника ПВЗ.

1.4.5. Если Клиент отказывается от какого-либо товара после его примерки/проверки, то Сотрудник ПВЗ должен отметить в АРМ Сотрудника факт отказа.

1.4.6. Если Клиент подтверждает получение товара после его примерки/проверки, то Сотрудник ПВЗ должен отметить в АРМ Сотрудника факт выдачи:

- Все предоплаченные товары по умолчанию выдаются Клиенту. Даже если Клиент решит отказаться от какого-либо из ранее оплаченных товаров, их необходимо вначале выдать, а уже после оформлять возврат.
- В случае подтверждения получения товаров с пост-оплатой перед выдачей Сотрудник ПВЗ должен запросить в АРМ Сотрудника оплату и затем дождаться списания у Клиента денежных средств. В случае, если у Клиента в личном кабинете не привязана банковская карта, возникают какие-либо ошибки при оплате, либо Клиент сам желает осуществить оплату другим способом, Сотрудник ПВЗ может направить ему ссылку на оплату

**1.5. Возврат товара надлежащего качества**

1.5.1. Клиент вправе отказаться от товара после заказа, либо в момент проверки/примерки в пункте выдачи. В этом случае вначале осуществляется выдача всех оплаченных/подтвержденных товаров, а затем осуществляется возврат на те, от которых Клиент отказался.

1.5.2. На товары, которые разрешено возвращать, действует правило свободного возврата. Клиент может принести в любой пункт выдачи ранее выкупленный товар и вернуть его в течение 21 дня с момента приобретения, если товар его не устроил.

1.5.3. Прежде чем принять такой товар, Сотрудник ПВЗ должен убедиться:

- что он подлежит возврату;
- что срок возврата не истек;
- что товар исправен: на упаковке/товаре отсутствуют трещины, сколы, вмятины, нет признаков ранней эксплуатации (затертости, следы ношения, пятна), а также присутствует этикетка и упаковка для товара.

1.5.4. Если товар принесён с другого пункта, курьером и т.д., необходимо обязательно уточнять номер телефона клиента для возврата товара.

После приема возвращенного товара от Клиента Сотрудник ПВЗ складирует товары для последующей передачи Службе доставки.

**1.6. Возврат брака**

1.6.1. Если Клиент желает вернуть бракованный товар, Сотруднику ПВЗ необходимо убедиться, что у Клиента в личном кабинете присутствует согласованная заявка на проверку товара. В случае, если она отсутствует, необходимо направить Клиента на заполнение формы в соответствующем разделе личного кабинета. После заполнения и до возврата необходимо дождаться согласования данной заявки специалистами Службы поддержки.

1.6.2. Возврат бракованного товара осуществляется в срок до двух лет.

1.6.3. Если товар был получен Клиентом в постамате, курьерской доставкой, либо в стороннем пункте выдачи, его возврат оформляется как обычный.

1.6.4. После приема бракованного товара от Клиента Сотрудник ПВЗ складирует товары для последующей передачи Службе доставки.

**1.7. Правила оформления возврата Службе доставки**

1.7.1. Возврат любых товаров осуществляется в коробах.

1.7.2. Сотрудник ПВЗ может использовать пустые коробки от привезенных заказов или сложить товар в иную коробку такого же типа.

1.7.3. Если целая коробка была доставлена в ПВЗ ошибочно, ее нельзя использовать для осуществления возврата товара от Клиентов.

1.7.4. Сотрудник ПВЗ должен промаркировать короб как короб, содержащий возвраты.

1.7.5. Сотрудник ПВЗ должен передать короб с возвратами водителю-экспедитору при следующей приемке коробов.


# **Результаты обследования**

Для адресного хранение необходимо создание ячеек. Ячейкам присваивается номер. Разные ПВЗ имеют разную площадь и разное количество ячеек для хранения. Как правило, для хранения используются стеллажи.

Посылки имеют разные габариты, вес  и объем. Соответственно это должно учитываться при распределении посылок: объемные и тяжелые посылки должны располагаться внизу. Также существует категория хрупких и бьющихся грузов, и тех, которые допустимо хранить только в определенном положении.

Каждой посылке присваивается уникальный штрихкод, по которому отслеживается ее движение от сборки до выдачи. По этому коду определяется в какой ячейке находится посылка.

Клиент получает посылку по уникальному  трек-номеру. Текущая система и процессы не позволяют объединять посылки для выдачи, поэтому одной ячейке может располагаться только одна посылка.

Операторы ПВЗ работают посменно, по одному. В течении смены оператор выдает посылки, принимает возвраты, принимает грузы у экспедитора, распределяет полученные грузы. После получения посылок от экспедитора оператор ПВЗ производит раскладку на складе ПВЗ. При раскладке оператор проверяет посылки на повреждение, и отмечает при наличии. Раскладка производится в течении смены, отдельно выделенного время для этого не выделяется. Раскладку проводит тот оператор, который принимал груз у экспедитора.

В зависимости от габаритов посылка может занимать одно или несколько грузовых мест, например, мебель в разборе состоит из нескольких коробок.  Мелкие посылки собираются в тару (ящик), ящик является одним грузовым местом. При раскладке посылок из тары необходимо сверять заявленное количество позиций.

При получении посылки клиент может назвать 4-е последних цифры трек-номера или номер телефона. Для подтверждения используется код, который приходит на указанный номер телефона (получатель посылки). Смена этого номера в посылке невозможна. Отправка кода происходит при запросе оператором. Оператор имеет право выдать посылку только при подтверждении кода. Для неоплаченных посылок, оплата производится до подтверждения выдачи кодом. При отказе от получения посылки также должно пройти подтверждение клиентом по смс.

Владельцам ПВЗ важно иметь возможность расширения количества ячеек, поскольку при заполнении всех ячеек текущее ПО блокирует возможность доставки в этот ПВЗ.

Также все проблемы связанные с потерей, пересортицей посылок лежит на владельце ПВЗ, который для решения вынужден проводить “расследование” действий оператора.
