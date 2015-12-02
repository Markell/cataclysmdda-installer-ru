#Cataclysm DDA Installer (ru) 

![Cataclysm DDA Installer]
(https://github.com/Markell/cataclysmdda-installer-ru/blob/master/src/github/logo.png)
##Описание

Cataclysm DDA Installer это  установщик игры Cataclysm DDA для операционной системы Ubuntu, обладающий рядом возможностей и распространяющийся под лицензией creative commons.
Cataclysm: Dark Days Ahead, также известна как CataclysmDDA — это бесплатная компьютерная игра на выживание в жанре roguelike, основанная на тематике зомби-апокалипсиса.
##Особенности инсталятора

* Автоматическая загрузка и установка последней "стабильной" и "экспериментальной" версии.
* Автоматическая загрузка и установка актуального перевода

##Инструкция по запуску

Откройте терминал - "ctr" + "alt" + "t",  и выполните следующую команду:
```bash
git clone https://github.com/Markell/cataclysmdda-installer-ru.git
cd cataclysmdda-installer-ru
chmod 777 ./setup.sh & ./setup.sh
```
следуете инструкциям инсталятора

####Примечание
В связи с частым выпуском экспериментальных версий вы можете сами вписать нужную версию в файл experimental_name.txt, пример: ```cataclysmdda-0.C-3984.tar.gz``` без пробелов!

##Что планируется добавить

- [ ] Автоматическая загрузка последней "стабильной" и "экспериментальной" версии для x64 систем.
- [ ] Возможность перестановки игры
- [ ] Проверка и загрузка обновлений
- [ ] Возможность полностью удалить игру
- [ ] Возможность установки своей музыки
- [ ] Загрузка и установка звуковых эффектов


