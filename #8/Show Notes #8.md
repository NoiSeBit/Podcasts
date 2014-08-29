[Noise Security Bit #8](http://noisebit.podster.fm/7)
=====
## О реверсинге firmware


### Участники:
Александр Матросов ([@matrosov](http://twitter.com/matrosov)),
Андрей Костин ([@costinandrei](https://twitter.com/costinandrei)),
Сергей Шекян ([@sshekyan](https://twitter.com/sshekyan)),
Александр Бажанюк ([@ABazhaniuk](http://twitter.com/ABazhaniuk))
Олег Купреев ([@090h](https://twitter.com/090h)),
Дмитрий Олексюк ([@d_olex](https://twitter.com/d_olex)),


###Инструменты для дампа SPI-flash памяти
* [Bus Pirate](http://dangerousprototypes.com/docs/Bus_Pirate)
* [GoodFET](http://goodfet.sourceforge.net)
* [DEDIPROG](http://www.dediprog.com/pd)

###Софт для дампа SPI-flash
* [CHIPSEC](https://github.com/chipsec/chipsec/blob/ac2ca7264f107c7b15ea8480db9c0e471dffd610/source/tool/chipsec/utilcmd/spi_cmd.py)
* [FlashROM](http://flashrom.org/Flashrom)

### Инструменты для реверсинга прошивок
* [Binwalk](http://binwalk.org/)


### Инструменты для реверсинга BIOS/UEFI
* [CHIPSEC](https://github.com/chipsec/chipsec)
* [UEFI Firmware Parser](https://github.com/theopolis/uefi-firmware-parser) - Прим. от @d_olex: много багов и плохой код!
* [UEFITool](https://github.com/LongSoft/UEFITool) - Кросс-платформенная (Win/Linux/Mac) GUI программа для разбора и модификации UEFI образов. 
* [Flash Image Tool](https://dl.dropboxusercontent.com/u/22903093/Intel%20Flash%20Image%20Tool.zip) - Инструмент от Intel для конфигурирования различных параметров UEFI Flash Image, в архиве версии для чипсетов 7, 8 и 9 серий.
* [EFI scripts for IDA Pro](https://github.com/snare/ida-efiutils) - Дополнения для IDA облегчающие реверс-инжиниринг UEFI бинарников.
* [Copernicus](http://www.mitre.org/capabilities/cybersecurity/overview/cybersecurity-blog/copernicus-question-your-assumptions-about) - Инструмент от MITRE позволяющий (в теории) обнаруживать зловредные модификации BIOS.

### Уязвимости UEFI и атаки на SecureBoot
* [Summary of Attacks Against BIOS and Secure Boot](https://www.defcon.org/images/defcon-22/dc-22-presentations/Bulygin-Bazhaniul-Furtak-Loucaides/DEFCON-22-Bulygin-Bazhaniul-Furtak-Loucaides-Summary-of-attacks-against-BIOS.pdf)
* [Extreme Privilege Escalation On Windows 8/UEFI Systems](https://www.defcon.org/images/defcon-22/dc-22-presentations/Kallenberg/DEFCON-22-Corey-Kallenberg-Extreme-Privilage-Escalation-WP-UPDATED.pdf)

### Атаки на через USB
* [USB for all!](https://www.defcon.org/images/defcon-22/dc-22-presentations/Michael-Shkatov/DEFCON-22-Jesse-Michael-Mickey-Shkatov-USB-for-All!!-UPDATED.pdf)

