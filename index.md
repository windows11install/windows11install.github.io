### План по установке и настройке:

- Получение образа Windows 11;
- Создание загрузочной флешки;
- Обход TPM и SecureBoot для старых компьютеров;
- Установка и начальная настройка Windows 11;
- Дополнительная настройка Windows 11;
- Необязательные приложения;
- Как не угробить Windows за год;


# Получение образа Windows 11

![](https://uupdump.net/static/images/logo.svg)



**Для получения образа Windows 11 будет использован следующий сайт --> [UUP dump](https://uupdump.net/)**

Первым что мы должны сделать после того, как зайдём на сайт - получить самый свежий образ Windows, для этого:

1. Во вкладке "*Последняя сборка публичного выпуска*" жмём **x64**:
![](https://i.imgur.com/MY6grXj.png)

2. Кликаем по названию образа (пример - *Windows 11, version 24H2 (26100.2605) amd64*):
![](https://i.imgur.com/Nh78m2U.png)

3. Выбираем язык который будет использоваться в Windows (*рекомендуется* - **Русский**):
![](https://i.imgur.com/mXnpqC0.png)

4. Выбираем какие издания нужны (*рекомендуется* - **убрать Windows Home**)
![](https://i.imgur.com/k7NilSH.png)

5. Выбираем галочки как у меня и скачиваем
![](https://i.imgur.com/07Zce6B.png)

Уже полдела сделано, осталось:

1. Распакуйте архив и откройте "**uup_download_windows.cmd**"
![](https://i.imgur.com/qmMVcDh.png)

2. Далее откроется окно "Система Windows защитила ваш компьютер", игнорируйте:
![](https://i.imgur.com/C28WO2Y.png)

3. Откроется предупреждение о безопасности, вводим "**R**" и жмём *Enter*:
![](https://i.imgur.com/dKmsQA4.png)

- Если вы сделали всё правильно, загрузка начнётся без ошибок.
- После окончания загрузки нажимаем "**0**" либо "**Q**"
- Важно понимать, что создание образа может занять от 30 минут до 1.5 часа.

#
# Создание загрузочной флешки

![](https://rufus.ie/pics/rufus-128.png)

**Для создания загрузочной флешки с Windows 11, рекомендуется** - [Rufus](https://rufus.ie/ru/)

**!!! ВАЖНО: ДЛЯ СОЗДАНИЯ ЗАГРУЗОЧНОЙ ФЛЕШКИ, ДОЛЖНА БЫТЬ ФЛЕШКА НЕ МЕНЕЕ 8 ГБ !!!**

* Для начала скачайте Rufus с выше указанного сайта
  * Пролистав немного вниз, скачиваем последнюю версию Rufus и устанавливаем:
![](https://i.imgur.com/PcmmmJq.png)


1. Скачав и установив Rufus, открываем его и нажимаем "**Выбрать**":  
![](https://i.imgur.com/wOESOt5.png)

2. После открытия проводника, переходим в папку откуда запускали "**uup_download_windows.cmd**"
   - В этой же папке будет скачанный образ Windows 11, его и выбираем:
![](https://i.imgur.com/cL0YK15.png)

3. Убедитесь что "*Файловая система*" или "*File system*" выбран **NTFS**:  
![](https://i.imgur.com/qrw3JuI.png)

4. Нажимаем на кнопку "**СТАРТ**"
   - Откроется окно в котором нужно выбрать **выделенные** пункты:
![](https://i.imgur.com/1DCGgFS.png)

- После того как нажали "**ОК**" вылезет предупреждение об форматировании флешки, нажимаем ещё раз "**ОК**"
- Процесс занимает в среднем 10-15 минут