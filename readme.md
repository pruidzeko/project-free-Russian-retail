﻿# Бесплатный проект Розница

A brief English description is at the end of the text.

Проект "розница" является абсолютно **бесплатной** альтернативой коммерческим кассовым и учетным системам для розничной торговли. Проект может использоваться как на рабочем месте кассира, так и как учетная программа для розничной компании. Проект написан для работы в системе [SunFlurry](http://sfsys.ru).

Исходные тексты проекта, выложенные здесь для скачивания, являются только частью проекта. Кроме исходных текстов, предоставляются также бинарные файлы, которые, в виде исполняемого приложения-установщика, можно [скачать](http://sfsys.ru/index.php/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82_%D0%A0%D0%BE%D0%B7%D0%BD%D0%B8%D1%86%D0%B0) с официального сайта SunFlurry. В процессе установки, создается рабочая копия с сервером и клиентом и программой Студия (позволяющей изменять исходные тексты проекта). Установщик также включает комплект исходных текстов, их не требуется скачивать с этого сайта. Однако, исходные тексты в программе-установщике могут иметь более старую ревизию по сравнению с текстами, представленными здесь.

Для разворачивания проекта в реальном рабочем магазине следует учесть несколько важных деталей:
- На тексты, распространяемые здесь, действует свободная [лицензия](http://sfsys.ru/download/EULASRC.txt) (базирующаяся на лицензии Apache версия 2.0).
- На бинарные файлы системы SunFlurry (сервер, клиент и Студия), действует свободная [лицензия](http://sfsys.ru/download/EULASOFT.txt), обладающая ограничениями при использовании в коммерческих целях. Изучите ее, пожалуйста, перед развертыванием проекта в реальном магазине.
- Несмотря на то, что для проекта написаны драйверы ККМ для наиболее распространенных производителей (Атол, Штрих-М, Вики Принт, возможно, другие с момента написания этого вступления), проект не работает с ККМ всех производителей. Это не значит, что драйверов для Вашего оборудования не появится в будущем. Кроме того, при наличии соответствующих знаний, Вы или Ваш технический специалист сможете написать нужный драйвер самостоятельно.
- Для технических специалистов и программистов есть полная документация по языку и его функциям с примерами, а также описание элементов интерфейса Студии, возможностей сервера, ключи командной строки запуска и т.д. Документация выполнена в формате Википедии и находится по адресу [http://sfsys.ru](http://sfsys.ru).


## Требовая к аппаратному обеспечению

- Операционная система: Windows XP и старше (возможна работа на Windows 2000, но она давно не проверялась).
- Процессор системы (и для сервера и для программ-клиентов): любой (вплоть до Intel Atom 1.1ГГц)
- Необходимый объем памяти: Достаточный для комфортабельной работы в операционной системе. Для больших баз данных, возможно нужно чуть больше памяти, чем в офисном компьютере. 


## Краткий список возможностей проекта на текущий момент

- При использовании проекта, как учетной системы:
  - Ведение любого количества юридических лиц и магазинов в одной базе.
  - Анализы продаж и закупок, ABC, XYZ-анализы, анализы наценки и прибыли, прогнозирование закупки товаров.
  - Система ценообразования и формирования цен, распечатка ценников.
  - Ведение бухгалтерского учета, ручные проводки, ведение учета по основным средствам.
    - Книга покупок и книга продаж, книга доходов и расходов, бух. баланс и отчет по прибыли.
  - Ведение финансового учета, ведение затрат, затраты по оплате и начислению.
    - Операционный капитал, отчет по прибылям и убыткам, маржинальная прибыль.
  - Ведение и учет маркетинга поставщиков (начисление и закрытие скидок и т.д.)
  - Ведение и анализы взаиморасчетов с поставщиками, платежная ведомость.
  - Ведение кассовых и банковских остатков. Ведение подотчета.
  - Ведение складских остатков в разрезе партий, марочный учет ЕГАИС и ГИС МТ.
  - Обрезание, объединение и перенос базы данных.
  - Обмен между базами данных, возможность выгрузки документов из периферийных баз данных в центральную.
  - Система прав отдельных пользователей.
- Возможности при использовании проекта, как кассового терминала:
  - Драйверы для популярных ККМ.
    - Продажа марочного товара ЕГАИС (алкоголь) и ГИС МТ (сигареты, молочная продукция и пр.). Работа с ФФД 1.2. 
  - Приемка поступлений ЕГАИС, автоматическое создание партий, работа с регистром 2, отчеты по сравнению с реальными остатками и прочее. Полный учет ЕГАИС.
    - Формирование декларации об объемах продаж алкоголя
  - Использование концепции "рабочее место" и "магазин", что позволяет настроить оборудование в ККТ магазина нужным образом и исключить проблемы с путаницей между оборудованием и пользователями.
  - Возможность выгружать и загружать информацию по протоколу Фронтол (к примеру, если центральная база будет использовать другую учетную систему). Другие способы обмена могут быть созданы Вашими или сторонними IT-специалистами.
  - Возможность программировать запреты на продажу алкоголя.
  - Возможность программировать торговые акции.
  - Удобная и простая самомасштабируемая форма рабочего места продавца
    - Операции типа: отложить чек, продолжить чек, возврат, аванс, кредит, временная замена прав для выполнения нужной операции и т.д. 
    - Возможности подбора товаров в чек, в т.ч. с помощью терминала сбора данных.
    - Быстрое закрытие чека, быстрая работа с комбинированными оплатами.

Дополнительная информация по проекту доступна [здесь](http://sfsys.ru/index.php/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82_%D0%A0%D0%BE%D0%B7%D0%BD%D0%B8%D1%86%D0%B0).

Пошаговая инструкция для установки и разворачивания проекта места доступна [здесь](http://sfsys.ru/index.php/%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0_%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%B0_%D0%A0%D0%BE%D0%B7%D0%BD%D0%B8%D1%86%D0%B0). 

## Импорт товаров и остатков из 1С:Розница

Для демострации простого импорта товаров и остатков в проект была создана внешняя обработка для экспорта справочников и остатков из 1С:Розница. Обработку можно скачать [по этой ссылке](http://sfsys.ru/download/ВыгрузкаСправочниковИзРозницы.epf). Обработку необходимо запустить в 1С:Розница, Для выгрузки необходимо выбрать один магазин. Нужно иметь в виду, однако, что все остатки будут загружаться на одно юридическое лицо, поэтому, если Ваши магазины работают на разных юр. лицах, необходимо будет выгрузить их отдельными файлами. После выгрузки текстового файла (скажем, *Розница.txt*), его необходимо загрузить в базу SunFlurry. В базе уже должны быть заполнены общие справочники (т.е., процедура начального заполнения справочников должна быть выполнена). Обработка загрузки находится в меню "Отделы учета", далее "Административные", "Розница" и "Загрузка справочников и остатков из 1С:Розница". Для загрузки необходимо выбрать юридическое лицо и папку справочника номенклатуры для импорта товаров (если папка не выбрана, товары будут созданы в корневой папке справочника). Кроме того, если база до этого была пустой, нужно выбрать магазин. Если магазин не будет выбран, новый магазин будет создан в базе данных автоматически.


## Краткий список простых вопросов и ответов при работе с проектом

- **Q:** Вы скачали zip-архив с github, как открыть его с помощью Studio.exe?
  - **A:** Более правильным (но более трудоемким подходом) будет настройка визуального клиента Git для обновления Вашей версии проекта. Чтобы превратить Zip-архив в рабочий проект, достаточно распаковать его в любую пустую папку, создать в этой же папке подпапку **Compiled**, при этом папку **project-free-Russian-retail-main** можно переименовать просто в **Source**, после чего запустить Studio.exe, выбрать пункт меню "Файл", "Открыть" и, с помощью диалога открытия файла, открыть файл **sfstudio.sfprj**, внутри исходной папки.

- **Q:** Как изменить пароль для входа в программу?
  - **A:** В рабочей программе, выбрать пункт меню "Общие" - "Административная панель", перейти на закладку "Учетные записи", два раза кликнуть на своей учетной записи. В появившемся диалоге установить галку "Запись защищена от изменений при синхронизации с ОС" (это означает, в частности, что пароль может не совпадать с паролем ОС). Нажать на кнопку "Сменить пароль", сменить пароль, после чего принять диалог с помощью кнопки "ОК" и нажать кнопку "Сохранить" на нижней напели окна.

- **Q:** При попытке зайти в режим продаж с ККМ, программа выдает сообщение *Для текущего пользователя не выбран соответствующий элемент контрагента!*.
  - **A:** Из-за того, что программе необходимы имя и фамилия кассира при пробитии чеков, его (кассира) необходимо завести в справочнике контрагентов. Для этого зайдите в справочник "Справочники" - "Контрагенты", перейдите в папку "Сотрудники", нажмите на *Insert* и введите сотрудника (с типом покупатель). После сохранения элемента, Вам необходимо сопоставить его с Вашей записью о пользователе. Для этого, воспользуйтесь иконкой головы человека на верхней панели иконок программы. В появившемся диалоге (где также можно настроить права доступа к функциям программы), заполнить поле "Контрагент" созданным Вами контрагентом и нажмите на "ОК".

- **Q:** Как добавить другого пользователя и настроить его права.
  - **A:** Пользователя можно добавить в закладке "Учетные записи" административной панели (см. первый вопрос). Однако, обычно это не требуется, так как настройки проекта по умолчанию позволяют заходить в программу любому пользователю с его паролем ОС. При этом, если пользователь входит в группу администраторов, ему будут даны административные права, иначе он будет считаться обычным пользователем (для доп. информации, см. описание файла *loginoptions.ini* в статье [[Установки сервера]]. После того, как пользователь зайдет в программу в первый раз, будет создан его элемент справочника пользователи ("Отделы учета" - "Административные" - "Пользователи"). Администратору необходимо открыть элемент пользователя и настроить его в соответствии с его ролью. 

- **Q:** Как задать цены на товары.
  - **A:** Ответ на этот вопрос зависит от того, как Вы создали базу номенклатуры. Если Вы создавали поступления или принимали их из ЕГАИС, цены закупки уже заполнены, необходимо заполнить цены продаж. Если Вы загружали базу из какого-то внешнего источника, возможно, что у Вас заполнены не только цены закупки, но и продажи. Для создания наценок от цен закупки и автоматического заполнения цен продаж, необходимо зайти в "Отделы учета" - "Ценообразование" - "Типы цен". Откройте тип цен продаж, который Вас интересует, и настройте его наценки от типа цен закупок. Чтобы пересчитать цены, требуется воспользоваться обработкой пересчета розничных цен. Зайдите в нее через "Отделы учета" - "Розница" - "Пересчет розничных цен, печать и выгрузка". Там можно распечатать ценники товаров.

- **Q:** При сканировании товара, программа говорит, что для товара "не задана розничная цена или не был распечатан ценник", однако, розничная цена пересчитана!
  - **A:** По умолчанию, программа имеет небольшую защиту от неверных цен в торговом зале. Если цена была изменена, однако, ценник для товара еще не был распечатан (или выведен на экран), программа будет использовать цену на момент предыдущей распечатки ценника. Если товар новый, эта предыдущая цена не задана. Зайдите в "Отделы учета" - "Розница" - "Пересчет розничных цен, печать и выгрузка", "Распечатать ценники номенклатуры" (обработка также доступна напрямую из главного меню), распечатайте ценники, установив галку "Печатать только новые ценники".

- **Q:** Марки товаров сканируются неверно или выходят в виде текста, вместо того, чтобы приниматься, как результат сканирования.
  - **A:** Сканеры в режиме клавиатуры не очень надежны. Если Сканер отдает нажатия слишком медленно, программа может посчитать, что это работает оператор. Кроме того, сканеры может отдавать необычные символы при сканировании. Начните настройку сканера с его сброса до заводского состояния. Если это не помогает, можно попробовать увеличить максимальное время между сканируемыми символами или настроить перекодировщик символов при сканировании. Для настройки сканера, зайдите в справочник магазинов, выделите нужный магазин и нажмите кнопку "Оборудование", выберите сканер из списка оборудования и откройте его диалог. Зайдите в диалог настройки с помощью кнопки с гаечным ключом в поле "Настройки". В диалоге настройки Вы можете проверить результаты сканирования и настроить корректный префикс и суффикс, используемый сканером Вашей модели. Также можно настроить таблицу перекодирования (к примеру, для замены особой комбинации символов Вашего сканера на символ GS1 для марок ГИС МТ). Если ничего не помогает, попробуйте перейти на драйвер эмуляции COM-порта. В этом режиме работа будет идти быстрее, и сканер будет работать с меньшим числом ошибок.

- **Q:** Банковский терминал не работает при пробитии чека.
  - **A:** Необходимо добавить его в список оборудования рабочего места, под которым происходит работа, либо вводить на нем сумму товара вручную, если драйвер данного банка отсутствует в списке доступных драйверов оборудования проекта. Для добавления зайдите в список рабочих мест в форме магазина, откройте нужное рабочее место (оно сопоставлено с элементом справочника пользователи кассира), нажмите кнопку "добавить" - "добавить оборудование текущего магазина", "Новый элемент", выберите драйвер оборудования, сохраните его ("ОК"), кликните на нем два раза, чтобы добавить в открытое рабочее место, сохраните изменения в рабочем месте ("ОК").

- **Q:** Как получить анализ продаж или найти наличные и безналичные продажи за день.
  - **A:** Анализ продаж -- очень гибкий отчет, позволяющий задавать большое количество фильтров, группировок и полей находит в главном меню "Отчеты" - "Анализы продаж" - "Анализ продаж". Однако, отчет не покажет продажи в разрезе наличных и безналичных оплат. Для этого, используйте простой розничный отчет "Отделы учета" - "Розница" - "Отчет по розничным продажам".

- **Q:** Как найти остатки на складе магазина.
  - **A:** Остатки можно найти несколькими способами. Первый -- остатки номенклатуры с ценами находится в главном меню "Отчеты" - "Номенклатура, ОС, аренда" - "Остатки номенклатуры и прайс-лист". Второй отчет является ведомостью и позволяет показывать движения за период в различных разрезах в т.ч. по документам, что не может первый отчет. Ведомость находится в главном меню "Отчеты" - "Номенклатура, ОС, аренда" - "Ведомость по остаткам номенклатуры".

- **Q:** Как провести инвентаризацию магазина.
  - **A:** Для инвентаризации магазина можно использовать т.с.д., сканер штрихкодов, либо выполнить подсчет вручную на листочке. Для использования т.с.д., его нужно подключить как оборудование в текущее рабочее место (см. описание выше подключения банковского терминала). В магазине останавливается рабочая деятельность (это строго рекомендуется, так как без этого придется отнимать от полученных остатков продажи, прошедшие после начала инвентаризации). Необходимо зайти в общий журнал ("Документы" - "Общий журнал документов"), *Insert*, "Акт по складу и инвентаризация", "Инвентаризация". Выберите юридическое лицо и склад. Можно установить галку "не считать остатки в разрезе по партиям", обычно, подсчет по партиям затруднителен. После этого снимите остатки на текущий момент, -- кнопка "++ Подбор", "Все товарные остатки". 
    - Для использования т.с.д. или сканера, выберите снова "++ Подбор", "Подбор со сканера или терминала", выберите терминал, если он есть, и нажмите кнопку "Выгрузить номенклатуру". После сканирования загрузите его результат с помощью кнопки "Загрузить с терминала". Для обычного сканера, можно нажимать последовательно на F3 и сканировать товар или использовать пункт "множество штрихкодов". После заполнения таблицы сканирования, нажмите на кнопку "Принять".
    - Для использования инвентаризации на бумаге, запишите документ и распечатайте печатную форму "Инвентаризация ИНВ3 (для заполнения)", либо воспользуйтесь отчетом по остаткам. Заполните результаты сканирования на бумаге и введите их в документ в поля "фактическое количество". 
    - Для окончания инвентаризации, обработайте документ, распечатайте и подпишите печатную форму "Сличительная ведомость ИНВ19". С помощью кнопки "Действия...", введите на основании документа оприходование ТМЦ и списание ТМЦ (документ Регистрация ТМЦ). В этих документах необходимо выбрать правильные партии, иначе учет на складе по партиям будет испорчен. Для списания алкогольного товара, созданное списание необходимо выгрузить в ЕГАИС. Если товар марочный, требуется также отсканировать марки списываемого товара (это может быть проблематичным на данном этапе, но система ЕГАИС иначе не работает). Списание можно не выгружать в ЕГАИС, и произвести списание напрямую из особого отчета по сверке остатков в ЕГАИС из обработки ЕГАИС (такой способ предпочтителен).

- **Q:** Как принять новое поступление в ЕГАИС.
  - **A:** Откройте обработку ЕГАИС ("Бухгалтерия" - "Отчетность" - "Выгрузка и загрузка данных ЕГАИС"). Нажмите на кнопку "Обновить" на нижней панели. Если есть новые поступления, они должны загрузиться в таблицу поступлений, нажмите правую клавишу мыши на требуемом поступлении, выберите пункт "Создать локальный документ поступления на основе входящего документа". В открывшейся таблице представлены все строки с алкогольной продукцией ЕГАИС. Если товар уже принимался базе ранее, локальная номенклатура будет сопоставлена, иначе необходимо два раза кликнуть по незаполненной ячейке в столбце "Номенклатура" и, либо выбрать локальную номенклатуру, либо создать ее на основе входящей информации, нажав кнопку с иконкой отчета. 
    - После сопоставления номенклатуры необходимо выполнить сопоставление штрихкода, если он новый или не был поставлен. Для этого необходимо кликнуть два раза по ячейке в столбце "Штрихкод" и выполнить сканирование.
    - После сопоставления штрихкодов необходимо провести сканирование марок принимаемой номенклатуры (только для марочного товара). Для этого необходимо кликнуть два раза по ячейке "Не проверено" в столбце "Проверка марок", будет выведен диалог, ожидающий сканирование штрихкодов ящиков и отдельных марок. Эту процедуру можно игнорировать, если у оператора достаточно прав для этого, но пропуск сканирования не рекомендуется, так как при наличии ошибок от поставщика это выяснится при сканировании на кассе и вернуть такой товар в дальнейшем будет сложно. Также в этом диалоге можно оформить возврат, если каких-то марок из поступления нет в наличии.
    - Когда все процедуры проделаны, и таблица не содержит красных ячеек, нажмите на кнопку "Создать", чтобы создать сам документ. После оформления и обработки документа, вернитесь в обработку ЕГАИС, обновите таблицу входящих документов снова и примите документ в ЕГАИС с помощью правой кнопки мыши "Отправить акт поставщику о принятии товара". Через какое-то время документ будет принят в ЕГАИС, Вы можете убедиться в этом, нажав на кнопку "обновить статусы поступлений", программа также сделает это сама в фоне, если Вы выйдете из обработки ЕГАИС. После принятия поступления, программа автоматически создаст перемещение на регистр 2 товара без акцизных марок, либо Вы можете форсировать этот процесс из обработки ЕГАИС.

- **Q:** Как провести инвентаризацию остатков в ЕГАИС (сравнение с остатками товара в базе).
  - **A:** Остатки в ЕГАИС могут находиться на первом и втором регистрах, причем, на втором (розничном) регистре остатки не считаются в разрезе партий, поэтому, программе необходимо сделать два запроса по остаткам и объединить их в одну таблицу сравнения. Чтобы сравнение остатков первого регистра работало корректно, необходимо принимать поступления ЕГАИС в локальной базе данных, чтобы локальные партии номенклатуры были привязаны к партиям в ЕГАИС. Для получения остатков ЕГАИС, зайдите в обработку ЕГАИС ("Бухгалтерия" - "Отчетность" - "Выгрузка и загрузка данных ЕГАИС"), нажмите на кнопку "Работа с остатками..." и выберите пункт "Отчеты по сравнению остатков партий номенклатуры с ЕГАИС". В появившемся диалоге выберите "полный отчет" для получения отчета по остаткам, "списание партий ЕГАИС" для таблицы сравнения, в которой можно провести списание лишних партий ЕГАИС (будьте внимательны при списании из ЕГАИС!), либо "отчет на регистре 2", для получения отчета только по регистру 2 (если весь товар без маркировки находится на регистре 2, этого отчета будет достаточно для сравнения).

- **Q:** При пробитии чеков, ЕГАИС может передать ошибку, либо ГИС МТ может посчитать марку неверной и т.п. Хотелось бы получить список таких случаев, чтобы найти такие плохие марки по ЕГАИС. Можно ли это сейчас сделать?
  - **A:** В данный момент такой лог ведется во внешних текстовых файлах, доступных администратору. При желании его можно вести в журнале регистрации событий базы данных. Для получения доступа к файлам, необходимо открыть папку с исходными файлами проекта (по умолчанию *C:\Program Files (x86)\SunFlurry\Config\Server\ *). Разная информация, хранится в разных подпапках:
    - ''Ошибки фиксации марок ЕГАИС (и другие ошибки ЕГАИС)'' сохраняются в виде файлов *failure_\*.txt* в подпапке *Temp\ЕГАИС\Розница\ЗапросыФиксацииМарок\ *.
    - ''Ошибки фиксации марок ГИС МТ'' сохраняются в виде файлов *problem_\*.txt* в подпапке *Temp\Розница\ОшибкиИСМП\ *.
    - ''Попытки продажи товаров с нулевой ценой'' (удобно проверять, какие товары невозможно продать, так как для них не установлена цена, продавцы не всегда записывают и передают такие случаи) сохраняются в виде файлов *problem_\*.txt* в подпапке *Temp\Розница\ТоварыБезЦены\ *.

- **Q:** Как быстро выполнить в программе произвольный код (чтобы, к примеру, сделать множественные изменения в справочниках или проверить ту или иную функцию)?
  - **A:** Зайти в главном меню в "Административную панель", перейдите на закладку "Вычисление и исполнение". Введите в текстовом редакторе необходимый код (или вставьте его из буфера обмена). Нажмите *Ctrl+F9* для его выполнения. Данная функция доступна только администраторам базы данных.

- **Q:** Как сделать простое изменение в коде отчета или обработки?
  - **A:** Будем считать, что Вам необходимо изменить что-то при пробитии чека. Запустите программу "SunFlurry Studio" с рабочего стола. В главное меню выберите "Проект" - "Конфигурация данных...". Для поиска в дереве конфигурации проекта, используйте комбинацию *Ctrl+F*, введите фразу поиска "продавца", нажмите *Enter*, курсор будет установлен на обработке "РабочееМестоПродавца". С помощью кнопок ''[+]'', откройте дерево обработки и найдите ветку *module*. Кликните на нее два раза, чтобы открыть редактор исходных текстов. Нажмите *Ctrl+F*, чтобы произвести поиск внутри текста. Введите фразу поиска "принятие", нажмите *Enter*, курсор будет установлен на начало функции принятия чека. Сделайте требуемое изменение. Сохраните изменение с помощью *Ctrl+S* или иконки дискеты на верхней панели инструментов. Для переноса сделанного изменения в рабочие файлы проекта, вызовите компиляцию проекта с помощью *Ctrl+F9*. По умолчанию, проект настроен таким образом, чтобы, после успешной компиляции, автоматически соединиться с сервером и передать на него обновленные тексты. Иными словами, после нажатия *Ctrl+F9* изменения уже в рабочей базе данных. Для некоторых изменения (изменения в глобальных модулях), будет необходимо выйти из программы и зайти снова, чтобы они заработали. Для изменений в обработках достаточно закрыть обработку и открыть ее снова.


## Пример кода начального заполнения справочника номенклатуры

Этот код можно использовать для создания своей версии загрузки номенклатуры из других источников (xls, xml, txt и пр.). Кусок кода, представленный здесь, можно запустить на закладке "Вычисление и исполнение" панели управления (административной панели) в рабочей программе (чтобы открыть панель управления, используйте пункт главного меню "Общие", "Административная панель").


```
  //Локальная функция установки цены, используется ниже по тексту
  Function ЛокУстановитьЦену(зН,ТипЦен,Цена,Магазин,ФлПродажнаяЦена)
    Дата:=BegOfDay(Date());

    Ц:=Ref.цЦены;
    Фл:=0;
    If Ц.Find("@Parent,ТипЦен",зН,ТипЦен) Then
      If Ц.Status()=1 Then
        Ц.Mark(0);
      EndIf;
    Else
      Ц.New();
      Ц.Parent(зН);
      Ц.ТипЦен:=ТипЦен;
      Ц.Save();
    EndIf;
    Ц.SetValue("Цена",Цена,Дата);

    //Кроме установки самой цены, создадим запись о том, что ценник для этой цены уже был распечатан
    //Если этого не сделать, необходимо будет хотя бы один раз распечатать ценники, чтобы новые цены начали работать
    If ФлПродажнаяЦена Then
      пЦ:=Ref.цПечатьЦенников;
      If пЦ.Find("@Parent,Магазин",зН,Магазин)=0 Then
        //Создаем
        пЦ.New();
        пЦ.Parent(зН);
        пЦ.Магазин:=Магазин;
        пЦ.ДатаПечати:=Дата;
        пЦ.ОбщаяСкидка:=0;
        пЦ.Save();
      ElseIf _Or(пЦ.ОбщаяСкидка<>0,isEmpty(пЦ.ДатаПечати),пЦ.ДатаПечати<Дата) Then
        пЦ.ДатаПечати:=Дата;
        пЦ.ОбщаяСкидка:=0;
        пЦ.Save();
      EndIf;
    EndIf;
  EndFunction

//Выбрать файл для загрузки
Файл:="";
If Not OpenFileDialog(Имя,"Выберите файл для загрузки:","Файлы txt (*.txt)|*.txt",0) Then
  Exit;
EndIf;
//Загрузить файл в объект Text
Т:=Text.Create(1);
Т.Load(Файл);

//Найдем по коду корневую папку, в которой будем создавать всю стрктуру папок
аКорневаяПапка:=DB("Ref.тмцНоменклатура","Code","000000000001");

//Найдем магазин, для которого происходит загрузка (требуется для создания цен)
аМагазин:=DB("Ref.рознМагазины","Code","000000000001");

//Единицы измерения (для упрощения примера)
аЕдиницаШт:=DB("Ref.тмцЕдиницыИзмерения","Name","шт");
аЕдиницаКг:=DB("Ref.тмцЕдиницыИзмерения","Name","кг");

//Цикл для каждой строки файла
For i:=1 To Т.Size() Do
  //Допустим, элементы строки разделены знаками табуляции (_TAB)
  //Допустим, файл также содержит папки товаров
  //Допустим, в файле есть внешние коды (артикли), с помощью которых мы можем найти, что уже было загружено, если загрузка была прервана

  //Получить текущую строку файла
  Стр:=Т.GetLine(i);
  СтрНаименование:=TearStr(Стр,_TAB);
  СтрАртикль:=TearStr(Стр,_TAB);
  СтрАртикльПапки:=TearStr(Стр,_TAB);
  ФлЭтоПапка:=Number(TearStr(Стр,_TAB));
  //Предусмотрим случай, когда для отделения дробной части используется запятая
  ЧлЦенаЗакупки:=Number(Replace(TearStr(Стр,_TAB),",","."));
  ЧлЦенаПродажи:=Number(Replace(TearStr(Стр,_TAB),",","."));
  ...

  //Если это новый элемент, создадим его, иначе найдем
  аН:=Ref.тмцНоменклатура;
  If Not аН.Find("ВнешнийТекстовыйКод",СтрАртикль) Then
    аН.New(ФлЭтоПапка);
    аН.СтрАртикль:=ВнешнийТекстовыйКод;
    аН.Save();
  ElseIf Not IsEmpty(аН.Name) Then
    //Пропускаем уже загруженный ранее элемент
    Continue;
  EndIf;

  //Помещаем элемент в нужную папку
  аПапка:=Ref.тмцНоменклатура;
  If IsEmpty(СтрАртикльПапки) Then
    аПапка:=аКорневаяПапка;
  ElseIf Not аПапка.Find("ВнешнийТекстовыйКод",СтрАртикльПапки) Then
    аПапка:=аКорневаяПапка;   
  EndIf;
  аН.Folder(аПапка);

  //Заполним наименование
  аН.Name:=СтрНаименование;
  //Если это папка, остальные реквизиты не будут нужны
  If аН.IsFolder() Then
    аН.Save();
    Continue;    
  EndIf;

  //Заполняем основные свойства товара
  аН.ВидНоменклатуры:=Enum.ВидыНоменклатуры.Товар;
  аН.СтавкаНДС:=?(ЧлСтавкаНДС=10,Enum.СтавкиНДС.НДС10,Enum.СтавкиНДС.НДС20);
  аН.ОбъемЛитров:=ЧлОбъем;
  аН.базМассаНетто:=ЧлМасса;
  //Обычно задана для табачных изделий
  аН.ЦенаМаксимальнаяПродажная:=ЧлЦенаМаксимальнаяПродажная;
  //Обычно задана для некоторых видов алкоголя
  аН.ЦенаМинимальнаяПродажная:=ЧлЦенаМинимальнаяПродажная;

  //Единицы
  аН.флВесовойТовар:=ЧлВесовойТовар;
  If аН.флВесовойТовар Then
    аН.базЕдиница:=аЕдиницаКг;
  Else
    аН.базЕдиница:=аЕдиницаШт;
  EndIf;
  аН.оснЕдиница:=аН.базЕдиница;
  аН.оснКоэффициент:=1;

  //ЕГАИС и пр.
  аН.флАлкогольнаяПродукция:=ЧлАлкогольнаяПродукция;
  аН.флПодлежитПрослеживаемости:=ЧлПодлежитПрослеживаемости;
  If ЧлАлкогольнаяПродукция Then
    аН.ЕГАИСКодАП:=ЧлКодАП;
    аН.флПартионныйУчет:=1;

    //Создадим или найдем элемент справочника тмцПартииТМЦ: аПартия
    //Здесь код опущен для улучшения читаемости
    ...

    аПартия.ЕГАИСКодАП:=ЧлКодАП;
    аПартия.ЕГАИСКодНоменклатуры:=..;
    аПартия.ЕГАИСКодПроизводителя:=..;
    аПартия.ЕГАИСКодСправок:=..;
    аПартия.Производитель:=..;
    аПартия.флМарочныйУчет:=..;
    аПартия.флИмпортнаяПродукция:=..;
    аПартия.флБезУпаковки:=..;
    ...
    аПартия.Save();    
  EndIf;
  If аН.флПодлежитПрослеживаемости Then
    аН.ГИСМТТоварнаяГруппа:=..;
  EndIf;


  //Установка закупочной и продажной цен
  ЛокУстановитьЦену(аН,аМагазин.ТипЦенПоступления,ЧлЦенаЗакупки,аМагазин);
  ЛокУстановитьЦену(аН,аМагазин.ТипЦенРеализации,ЧлЦенаПродажи,аМагазин,1);   

  //Сохраним все изменения в товаре
  аН.Save();
EndDo;
```

# Some brief English explanation to all the text above

This repository contains a free source project written for [SunFlurry](http://sfsys.ru) environment. The project can be used for Russian retail (as both POS and office software) as a free alternative to a number of commercial systems. Although you can write any kind of project in SunFlurry, unfortunately we do not have a full English documentation at the moment. You are welcome however to download and play with it, if you so desire.


