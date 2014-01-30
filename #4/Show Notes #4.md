[Noise Security Bit #4](http://noisebit.podster.fm/4)
=====
##О железячной безопасности


###Участники:
Александр Матросов [(@matrosov)](http://twitter.com/matrosov),
Дмитрий Недоспасов [(@nedos)](http://twitter.com/nedos),
Олег Купреев [(@090h)](http://twitter.com/090h),
Александр Бажанюк [(@ABazhaniuk)](http://twitter.com/ABazhaniuk),
Дмитрий Олексюк [(@d_olex)](http://twitter.com/d_olex)

###Вопросы:
####Intro
#####Почему хакинг хардвары за последние несколько лет стал так аткулен?
- Закладки в оборудовании или раздолбайство некоторых вендоров?
- [Stealthy Dopant Level Backdoors](http://people.umass.edu/gbecker/BeckerChes13.pdf)

##### Как начинал сам (@nedos) и что посоветуешь для старта нашим слушателям?
Литература:

* Weste [CMOS VLSI Design](http://amzn.com/0321547748)
* Horrowitz, Hill [Art of Electronics](http://amzn.com/0521370957)
* Verilog vs. HDL - [HDL Chip Design](http://amzn.com/0965193438)

#####Что необходимо из инструментрументов и тулов для того чтобы начать вникать в тему на практике?
* Насчет оборудования очень рекомендую смотреть: [EEVBlog](http://www.youtube.com/eevblog)

	Для начало можно ходить в хэкспейс

* < 100€

	Buspirate

	Arduino
	
	Breadboard (макетная плата)
	
	дешевый мультиметр
	
	[DP ATX Breakout Board](http://dangerousprototypes.com/2012/06/28/new-prototype-atx-breakout-board/)
* < 500€

	мультиметр (extech, amprobe, bk precision)

	logic analyzer (salae)

	пояльная станция (со смненными жаломи)

* < 1500€

	Осциллограф (Rigol DS2072)
	
	Rework station (термовоздушная пояльная станция)
	
	FPGA Devboard (Terasic DE0-nano)
	
* < 2500€

	Серьезный Мультиметр (Fluke 87V)
	
	вторая пояльная станция
	
* < 5000€

	Осциллограф с 4-мя каналами,
	
	второй "сереьезный" мультиметр (Например Agilent OLED)
	
* Нет придел

	[LPKF Protomat s63](http://www.lpkf.com/products/rapid-pcb-prototyping/circuit-board-plotter/protomat-s63.htm)
	
	[Ultratec ASAP-1](http://www.ultratecusa.com/asap-1)
	
	[Teledyne LeCroy 7-Zi](http://teledynelecroy.com/oscilloscope/oscilloscopeseries.aspx?mseries=341)
	
	[Riscure Laser Station](https://www.riscure.com/security-tools/hardware/diode-laser-station)
	
	Karl Suss Probing Station
	
	[Karl Suss PH 150](http://www.miller-design.com/Pdfs/KarlSussPH150MicroPositioner.pdf)
	
	[Pico Probe](http://www.ggb.com)
	
	[New Wave Research EZLaze](http://www.esi.com/Products/NewWaveResearch/FlatPanelDisplayRepairFailureAnalysis/EzLaze.aspx)
	
	[Hamamatsu Phemos](http://www.hamamatsu.com/jp/en/product/category/5002/5012/PHEMOS-1000/index.html)
	
	[FEI FIB](http://www.fei.com/products/fib/v400-ace/)

#####Как и где приобретать необходимый инструментарий/электронные компоненты?
* Дистрибютеры:

	[Digikey](http://www.digikey.ru)

	[Mouser](http://ru.mouser.com)

	[Farnell](http://ru.farnell.com)

- Какие тематические евенты стоило бы постетить и какую пользу из них можно извлечь? 
- Какие направления можно особо выделить, как наиболее актуальные в последнее время?
- System security или хакинг современных автомобилей?
- Device security, пара слов о различных типах атак на устройства (side channel analysis, fault attacks etc.)?

	Timo Kasper [Milking the Digital Cashcow (29c3)](http://youtu.be/Y1o2ST03O8I)
	
	Stefan Mangard - [Power Analysis Attacks: Revealing the Secrets of Smart Cards](http://amzn.com/0387308571)

- Что такое IC security в рельных примерах? Что ждать дальше в этой области?

	Olivier Thomas [@reivilo_t](http://twitter.com/reivilo_t) - [Hardware Rever-engineering Tools (REC0N 2013)](http://recon.cx/2013/schedule/events/44.html)
	
	Chris Tarnovsky [@semiconduktor](https://twitter.com/semiconduktor) - [Inducing Momentary Faults Within Secure Smartcards (DEF CON 16)] (http://youtu.be/UMPfgnQPjpk)

	Dmitry Nedospasov [@nedos](https://twitter.com/nedos) - [Security of the IC Backside (30c3)](http://youtu.be/wmv7tu7FSW0)
	
	[Murdoch’s Pirates](http://amzn.com/B009VA1NVU)

#####RF
- Анализ и воздействие на беспроводные протоколы?
- Какой инструментарий необходим для того чтобы начать исследования в этой области?
- Что можно сделать, кроме анализа беспроводных машинок при помощи HackRF?

#####Tools
- Что сподвигло к созданию Die Datenkrake и в двух словах о проекте?
- Почему энтузиасты создают такие платы, как Bus Pirate и Die Datenkrake?
- В чем принципиальное различие между Bus Pirate и Die Datenkrake?
- Какие возможности предоставляет Die Datenkrake исследователю по ИБ и куда это все можно применить?
- Сила FPGA и какие возможности для реверсинга она предоставляет?
- Какие есть распространенные вектора атак используемые при помощи Die Datenkrake?

####Outro
- Дальнейшее развитие железячного хакинга, какие есть идеи?





