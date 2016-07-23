[Noise Security Bit #19]()
=====
## О "хакинге" автомобилей


### Участники:
Александр Матросов ([@matrosov](http://twitter.com/matrosov)),
Алексей Синцов ([@asintsov](http://twitter.com/asintsov)), 
Александр Гантман ([@againsthimself](http://twitter.com/againsthimself))

### Темы для обсуждения:
- Почему безопасность в аутомотив стала актуальна именно сейчас;
- Как следствие: Самоуправляемые авто, почему важно задуматься о безопасности с самого начала;
- Типовые и известные проблемы: угон, CAN-сеть ... (и как противостоять этому);
- Проблемы с безопасностью с точки зрения подключенных в облако машин;
- CANToolz или нафига плодить велосипед, когда их и так полно;
- Что нужно помимо софта для того чтобы начать исследование внутренней сети своего авто;
- Какие типовые проблемы с безопасностью автомобиля имеют место быть и что с этим можно сотворить;
- Известный факт что "security by obscurity", так почему же автопроизводители считают себя исключением из правил (или не считают, и вообще - только ли автопроизводители? DEFENSIVE часть)?;
- Куда копать, где искать информацию, чтобы начать или продолжить исследования в данной области?.

### Литература
- Car Hacker's Handbook ([by OpenGarages, 2014](http://opengarages.org/handbook/));
- Car Hacker's Handbook: A Guide for the Penetration Tester by Craig Smith ([no starch press, 2016](https://www.nostarch.com/carhacking));
- Публикации [The Center for Automotive Embedded Systems Security (CAESS)](http://www.autosec.org/publications.html), содержащие результаты работ исследователей University of California San Diego (UCSD) и University of Washington;

### Протоколы
- [UDS](http://www.iso.org/iso/catalogue_detail.htm?csnumber=55283) ;
- [ISO-TP](http://www.iso.org/iso/home/store/catalogue_ics/catalogue_detail_ics.htm?csnumber=66574) .

### Инструментарий
- CANToolz ([Blog](https://asintsov.blogspot.ru/) & [GitHub](https://github.com/eik00d/CANToolz));
- Микросхема CAN-контроллера MCP2515 от [Microchip](http://www.microchip.com/wwwproducts/en/en010406), являющаяся базовой для многих DIY-изделий;
- [USBtin](http://www.fischl.de/usbtin/) из Германии, OpenHardware;
- [CanCat](https://github.com/atlas0fd00m/CanCat);
- [CANBus Triple](https://canb.us/) из США, совершенно не порадовавший Алексея Синцова своим качеством;
- [SocketCAN](https://www.kernel.org/doc/Documentation/networking/can.txt), как часть ядра Linux;

