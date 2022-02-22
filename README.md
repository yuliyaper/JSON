# JSON
//Создать внешний репозиторий c названием json

Create a new repository

//Клонировать репозиторий XML на локальный компьютер

$ git clone git@github.com:yuliyaper/JSON.git

//Внутри локального JSON создать файл “new.json”

$ touch new_json

//Добавить файл под гит

$ git add .

//Закоммитить файл.

$ git commit -m "new file json"

Отправить файл на внешний GitHub репозиторий.

$ git push

//Отредактировать содержание файла “new.json”

$vim new_json

//Hаписать информацию о себе(ФИО, возраст, количество домашних  животных, будущая желаемая зарплата).Всё написать в формате json

нажать i

{"FIO" : "Perevoshikova Yuliya Leonidovna",

 "age" : 41,
 
 "animal" : 1,
 
 "salary" : 500}
 
нажать esp : wq

//Отправить изменения на внешний репозиторий.

$ git commit -am "change 1 new_json"

$ git push

//Создать файл preferences.json

$ touch preferences.json

//В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, стрaна которую хотели бы посетить) в формате json.

нажать i

{"favorite movie" : "Electronics" ,

"favorite TV series" : "Sasha and Tanya" ,

"favorite food" : "borsch" ,

"favorite time of the year" : "winter" ,

"the country you would like to visit" : "Switze" 
}
нажать esp : wq

//Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате json.

$touch skils.json

$ vim skils.json

нажать i

{"studied skills" : [ "basic testing theory","JSON", "XML","API", "Postman",
	                   "DeV Tools", "Fidler","SQL"]
}

//Отправить сразу 2 файла на внешний репозиторий

$ git add .

$ git commit -m "2 files"

$ git push

//На веб интерфейсе создать файл bug_report.json

Add file

Create new file

Commit new file

//Сделать Commit changes (сохранить) изменения на веб интерфейсе

Commit changes

//На веб интерфейсе модифицировать файл bug_report.json,добавить баг репорт в формате json.

Нажать на bug_report.json

Edit this file

{ "ID":"1 AP "

  "Title":"При нажатии на кнопку «Отправить сообщение» в форме обратной связи сообщение не отправляется",
  
  "Summary":"При нажатии на кнопку «Отправить сообщение» в заполненной форме обратной связи ничего не происходит. Аналогичное поведение, если форма не заполнена",
  
  "Precondition":"Страница «Контакты»",
  
  "Steps To Reproduce": ["Заполнить поля формы обратной связи", " Нажать на копку «Отправить сообщение"],
  
  "Expected Result":"Сообщение отправляется либо система сообщает о невозможности его отправки",
  
  "Actual Result" : "Сообщение не отправляется, не появляется ошибка об отправке. После нажатия на кнопку ничего не происходит",
  
  "Priority":"Высокий",
  
  "Severity" : "Критический",
  
  "OS":"Windows 10"
}

//Сделать Commit changes (сохранить) изменения на  веб интерфейсе

Commit changes

//Синхронизировать внешний и локальный репозиторий xml

$ git pull


