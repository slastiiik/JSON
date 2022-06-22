# JSON
 4. Создать внешний репозиторий c названием JSON.
Создается репозиторий в гитхаб.
=> respositories =>new
5. Клонировать репозиторий JSON на локальный компьютер.
git clone
 6. Внутри локального JSON создать файл “new.json”.
touch new.json
 7. Добавить файл под гит.
git add new.json
 8. Закоммитить файл.
commit –m “add new.json”
 9. Отправить файл на внешний GitHub репозиторий.
git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
vim new.json
для начала редактирования => i
{
		"Name":"Anastasia Aleksandrovna",
		"Age":"20",
		"Number of pets":"1 cute cat",
		"Future desired salary":"100 million"
	}
для выхода из редактирования => esc => :wq
 11. Отправить изменения на внешний репозиторий.
git add new.json, git commit –m “edited content”, git push
 12. Создать файл preferences.json
touch preferences.json
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
vim preferences.json
для начала редактирования => i
{
"Favorite Movie": "The Servant"
"Favorite series": "Killing Eve",
"Favorite Food": "Noodles"
"Favorite season": "Spring and autumn",
"Country I want to go to": "France"
}
для выхода из редактирования => esc => :wq
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
vim skills.json
для начала редактирования => i
{
		"Skills": "Basic theory. HTTP structure and methods. JSON, XML, their structure. API testing via Postman. Mobile testing. SQL basics."
	}
для выхода из редактирования => esc => :wq
 15. Отправить сразу 2 файла на внешний репозиторий.
git add .
git commit –m “new json files”
git push
 16. На веб интерфейсе создать файл bug_report.json.
Создаётся файл bug_report.json в гитхабе.
add file=>create new file
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
сommit changes
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
В гитхабе меняется файл bug_report.json.
=>Edit this file
{
	"Summary": "Persistent sneezing",
	"Project":"Nastya",
	"Component":"Nasopharynx",
	"Version":"1.20",
	"Severity":"S5 Trivial",
	"Priority":"P3 Low",
	"Status":"New",
	"Author":"Anastasia",
	"Assigned To": "Anastasia",
	"Description": "The bug was found at home, this error was caused by allergies or dust, take a deep breath and the error will repeat, error result: sneezing, expected result: no sneezing"	
}
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
сommit changes
 20. Синхронизировать внешний и локальный репозиторий JSON
git pull (чтобы проверить все ли правильно синхронизировалось используется команда git fetch)
