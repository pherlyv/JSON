## JSON

1. Создать внешний репозиторий c названием JSON.
    * залогиниться на `https://github.com`.
    * нажать кнопку `New`.
    * в поле `Repository name` ввести JSON, выбрать Public и Add a Readme file.
2. Клонировать репозиторий JSON на локальный компьютер.
    * нажать `Code`, выбрать `https`, скопировать ссылку.
    * в `Gitbash` зайти в папку, в которой будет репозитороий (мой пример) `cd git_group_27`.
    * написать команду `https://github.com/pherlyve/JSON.git`.
    * зайти в папку JSON `cd JSON`.
3. Внутри локального JSON создать файл “new.json”.
    * команда `touch new.json`.
4. Добавить файл под гит.
    * команда `git add new.json`.
5. Закоммитить файл.
    * команда `git commit -m "file new.json"`.
6. Отправить файл на внешний GitHub репозиторий.
    * команда `git push`.
7. Отредактировать содержание файла “new.json” написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
    * команда `vim new.json`.
    * нажать `I`.
	```json
	{
         "Last name":"Redko",
         "First name":"Tima",
         "Middle name":"Dmitrievich",
         "Age":"24",
         "Pets":"0",
         "Salary":"300k/nanosec"
	}
	```
    * нажать `Ecs`.
    * написать `:wq`.
8. Отправить изменения на внешний репозиторий.
    * команда `git add new.json ; git commit -m "updated file new.json" ; git push`.
9. Создать файл preferences.json.
    * команда `touch preferences.json`.
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON.
    * команда `vim preferences.json`.
    * нажать `I`.
	```json
	{
         "favotire movie":"Blade Runner 2049",
         "favorite series":"South Park",
         "favorite food":"Curd casserole",
         "favorite season":"Autumn",
         "visit coutry":"Iceland"
	}
	```
    * нажать `Ecs`.
    * написать `:wq`.

11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.
    * создать файл `touch skills.json`.
    * зайти для редактирования `vim skills.json` и нажать `I`.
	```json
	{
	"skills":[
		"1. Basic theory",
		"2. Client-server architecture",
		"3. HTTP methods of request to the server",
		"4. HTTP server response codes",
		"5. Structures of HTTP requests and responses",
		"6. What is JSON, XML. Their structure",
		"7. API testing via Postman (JS, API autotests)",
		"8. Removing and reading logs from an external server",
		"9. Sniffing http web traffic through Charles and Fiddler",
		"10. Dev Tools of web browsers (Google Chrome, FireFox)",
		"11. VPN. (How it works, why it is needed, how to use it, tool options)",
		"12. Mobile testing",
		"13. Feature of iOS, Android, guidelines",
		"14. Build iOS apps on XCode",
		"15. Build Android apps on Android Studio",
		"16. ADB (android device management)",
		"17. Setting up proxy and vpn on iOS and Android",
		"18. Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android",
		"19. Linux command line (terminal) (copying, creating, viewing, moving files on servers without a graphical interface)",
		"20. Basics of bash scripting, automation of routine tasks on the server.",
		"21. Access to remote servers.",
		"22. Basics of SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
		"23. Postgres database (installation, configuration and use)",
		"24. Non-relational database Redis (installation, configuration and use)",
		"25. Load testing in Jmeter",
		"26. Scrum development methodology",
		"27. Python. (Learning the basics. Creating a client server application)"
		]
	}
	```
