# homework8 Загрузка ОС
way*.jpg - скриншоты консоли, 3 способа получить доступ к ФС без пароля.
homework8.txt - вывод консоли в процессе выполнения заданий по переименованию вольюм группы и добавлению модуля в initrd
Строка 15 - переименование вольюм группы.
Строка 23-25 - правка fstab, grub, grub.cfg на новое имя вольюм группы.
Строка 26 - пересоздание initrd image
Строка 81 - перезагрузка
Строки 86, 90 - после перезагрузки видим система загрузилась с новым именем вольюм группы
Строки 100-109 - создание каталога в /usr/lib/dracut/modules.d/ и размещение там скрипта создания модуля и исполняемого в модуле скрипта
Строка 110 - пересоздание initrd image
Строка 168 - видим, что в списке модулей dracut добавился новый модуль
Строка 195 - перезагрузка
Строки 196-210 - видим, что при загрузке выполнился скрипт который вызывается модулем.
