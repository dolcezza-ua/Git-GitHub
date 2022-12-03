# Git-GitHub

## JSON [repo](https://github.com/dolcezza-ua/JSON)

**1.** Создать внешний репозиторий c названием JSON. 
* Клонировать репозиторий JSON на локальный компьютер.

   * `$ git clone git@github.com:dolcezza-ua/JSON.git`

**2.** Внутри локального JSON создать файл “new.json”.
   
* `$ touch new.json`

**3.** Добавить файл под гит.
* `$ git add new.json`

**4.** Закоммитить файл.
* `$ git commit -m "add new.json"`

**5.** Отправить файл на внешний GitHub репозиторий.
* `$ git push`

**6.** Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
* `$ nano new.json`

**7.** Отправить изменения на внешний репозиторий.
* `$ git commit -am "modify new.json"`

* `$ git push`

**8.** Создать файл preferences.json. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
* `$ cat > preferences.json`
```json
{"favorite_movie": "My_dogs",
 "favorite_series": "My_cats",
 "favorite_food": "ice_cream",
 "favorite_season": "spring",
 "dream_country": "France"}
```
 
**9.** Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
* `$ cat > skills.json`
```json
{"programming_languages": "Pyton, JavaScript",
 "sniffing_web_traffic": "Charles, Fiddler",
 "database": "Postgres",
 "non-relational_database": "Redis",
 "load_testing": "Jmeter",
 "development_methodology": "Scrum"}
```

**10.** Отправить сразу 2 файла на внешний репозиторий.
* `$ git add preferences.json skills.json`
* `$ git commit -m "add 2 files"`
* `$ git push`

**11.** На веб интерфейсе создать файл bug_report.json. Сделать Commit changes (сохранить) изменения на веб интерфейсе. Mодифицировать файл bug_report.json, добавить баг репорт в формате JSON. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
* Синхронизировать внешний и локальный репозиторий JSON
   * `$ git fetch`
   * `$ git pull`

------------------------------------------------------


## XML [repo](https://github.com/dolcezza-ua/XML)
**1.** Создать внешний репозиторий c названием XML.

* Клонировать репозиторий XML на локальный компьютер.
   * `$ git clone git@github.com:dolcezza-ua/XML.git`

**2.** Внутри локального XML создать файл “new.xml”.
* `$ touch new.xml`

**3.** Добавить файл под гит.
* `$ git add new.xml`

**4.** Закоммитить файл.
* `$ git commit -m "modify new.xml"`

**5.** Отправить файл на внешний GitHub репозиторий.
* `$ git push`

**6.** Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
* Отправить изменения на внешний репозиторий.
   * `$ git commit -am "modify new.xml"`
   * `$ git push`

**7.** Создать файл preferences.xml
* `$ touch preferences.xml`

**8.** В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
* `$ nano preferences.xml`
 
**9.** Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
* `$ nano skills.xml`

**10.** Сделать коммит в одну строку.
* `$ git commit -m "modify 2 files .xml"`

**11.** Отправить сразу 2 файла на внешний репозиторий.
* `$ git push`

 **12.** На веб интерфейсе создать файл bug_report.xml. Сделать Commit changes (сохранить) изменения на веб интерфейсе. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
* Синхронизировать внешний и локальный репозиторий XML
   * `$ git fetch`
   * `$ git pull`

-------------------------------------------------------------


## TXT [repo](https://github.com/dolcezza-ua/TXT)
**1.** Создать внешний репозиторий c названием TXT.
* Клонировать репозиторий TXT на локальный компьютер.
   * `$ git clone git@github.com:dolcezza-ua/TXT.git`

**2.** Внутри локального TXT создать файл “new.txt”.
* `$ touch new.txt`
 
**3.** Добавить файл под гит.
* `$ git add new.txt`

**4.** Закоммитить файл.
* `$ git commit -m "add new.txt"`

**5.** Отправить файл на внешний GitHub репозиторий.
* `$ git push`

 **6.** Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
* `$ nano new.txt`

**7.** Отправить изменения на внешний репозиторий.
* `$ git commit -am "add new.txt"`
* `$ git push`

**8.** Создать файл preferences.txt. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
* Сделать коммит.
   * `$ git add preferences.txt skills.txt`
   * `$ git commit -m "add 2 files"`

**9.** Отправить сразу 2 файла на внешний репозиторий.
* `$ git push`

**10.** На веб интерфейсе создать файл bug_report.txt. Сделать Commit changes (сохранить) изменения на веб интерфейсе. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
* Синхронизировать внешний и локальный репозиторий TXT
   * `$ git fetch`
   * `$ git pull`