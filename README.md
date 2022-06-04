# JSON

4. Создать внешний репозиторий c названием JSON.
new

 5. Клонировать репозиторий JSON на локальный компьютер.
 git clone https://github.com/OlgaNastTest/JSON.git

 6. Внутри локального JSON создать файл “new.json”.
cd JSON
touch new.json

 7. Добавить файл под гит.
git add new.json

 8. Закоммитить файл.
git commit -m "add new.json"

 9. Отправить файл на внешний GitHub репозиторий.
git push

 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
cat >> new.json
{
        "Full Name": "Olga Nastsiushena",
        "Age": 32 ,
        "Number of pets": 0 ,
        "Salary": "1000$"
}
Ctr C

 11. Отправить изменения на внешний репозиторий.
git add new.json
git commit -m "replace new.json"
git push

 12. Создать файл preferences.json
touch preferences.json

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
cat >> preferences.json
{
	"favorite_movie": "1+1",
	"favorite_series": "The Big Bang Theory",
	"favorite_food": "Pasta with seafood",
	"favorite_time_of_the_year": "Summer",
	"country_you_would_like_to_visit": "Italy"
}
 Ctr C
14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
cat > sklls.json
{
	"Skill":"Testing Theory, SDLC, STLC",
	"Skill":"Clien-server",
	"Skill":"HTTP-methods",
	"Skill":"HTTP status-codes",
	"Skill":"HTTP resp, req stracture",
	"Skill":"JSON, XML. Structure",
	"Skill":"API Postman (JS, autotest API).",
	"Skill":"Logs from servers",
	"Skill":"Charles and Fiddler.",
	"Skill":"Dev Tools(Google Chrome, FireFox).",
	"Skill":"VPN.",
	"Skill":"Mobile testing",
	"Skill":"IOS, android guidelines",
	"Skill":"XCode.",
	"Skill":"Android Studio.",
	"Skill":"ADB",
	"Skill":"iOS Android proxy, vpn",
	"Skill":"Mobile trafic sniffing. Charles and Fiddler iOS, Android.",
	"Skill":"terminal Linux",
	"Skill":"bash scripting",
	"Skill":"Remote servers access",
	"Skill":"SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).",
	"Skill":"DB Postgres.",
	"Skill":"Redis",
	"Skill":"Load testing Jmeter.",
	"Skill":"Scrum.",
	"Skill":"Python."
}
Ctr C

 15. Отправить сразу 2 файла на внешний репозиторий.
git add .
git commit -m "replace 2 new.json"
git push

 16. На веб интерфейсе создать файл bug_report.json.
Create new file
Edit new file: bug_report.json


 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit new file

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

{
  "bug report structure":[
    "summary",
    "project",
    "component",
    "version",
    "severity",
    "priority",
    "steps to reproduce",
    "actual result",
    "expected result",
    "additional information"
  ]
}

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
commit changes

 20. Синхронизировать внешний и локальный репозиторий JSON
git pull
