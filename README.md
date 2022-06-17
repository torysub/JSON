# JSON
 1. Создать внешний репозиторий c названием JSON. 
 
 *New repository*
 
![image](https://user-images.githubusercontent.com/105368491/173524619-1d6305b6-6ff2-477d-b706-d72bf5093f69.png)

*Name: JSON*

![image](https://user-images.githubusercontent.com/105368491/173523816-c855bbc9-bd1a-4e6d-9bdf-3dbaaa57a2ae.png)

*Public*

![image](https://user-images.githubusercontent.com/105368491/173523624-753ff0a2-d7d6-47dd-b0ce-e23765f69b39.png)

*Check "Add a README file"*

![image](https://user-images.githubusercontent.com/105368491/173522577-26a13691-3204-43c8-bbbb-dc828a8160f7.png)

*Press "Create repository"*

![image](https://user-images.githubusercontent.com/105368491/173523978-0560eece-7b0a-4f98-8e9c-8294d58febc5.png)

 
 2. Клонировать репозиторий JSON на локальный компьютер.
 
 `git clone https://github.com/torysub/JSON.git`
 
 3. Внутри локального JSON создать файл “new.json”.
 
 `touch new.json`
 
 4. Добавить файл под гит.
 
 `git add new.json`
 
 5. Закоммитить файл.
 
 `git commit -m "Add the new.json"`
 
 6. Отправить файл на внешний GitHub репозиторий.
 
 `git push`
 
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 
 `vim new.json`
 
 ```
 {
	"person":{
		"first_name":"Viktoriya",
		"middle_name":"Alexandrovna",
		"last_name":"Subbotina",
		"age":31,
		"pets":{
			"cat":1,
			"dog":1
		},
		"salary":"1000$"
	}
}
```

*Нажать **"Esc"** :wq **"Enter"***
 
 8. Отправить изменения на внешний репозиторий. 
 
 ```
 git commit -am "New information added
 
 git push
 ```
 
 9. Создать файл preferences.json 
 
 `touch preferences.json`
 
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. 
 
 `vim preferences.json`
 
 ```
 {
	"favorite_movie": "Interstellar",
        "favorite_TV_series": "Friends",
        "favorite_food": [
                "pasta",
                "potato mash",
                "shish kebab",
                "salad"
        ],
        "favorite_time_year": "summer",
        "country": "Australia"
}
```

*Нажать **"Esc"** :wq **"Enter"***
 
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON 
 
 `vim skills.json`
 
 ```
 {
	"skills":{
		"basic testing theory":[
			"testing",
			"bug reports",
			"documentation",
			"SDLC",
			"STLC"
		],
		"HTTP":[
			"client-server architecture",
			"HTTP methods of requests to the server",
			"HTTP server response codes",
			"HTTP request and Response structures"
		],
		"data exchange format":[
			"JSON",
			"XML"
		],
		"database":[
			"SQL",
			"Redis",
			"Postgres"
		],
		"API":[
			"Postman",
			"JS",
			"API autotests"
		],
		"sniffing":[
			"Charles",
			"Fidler"
		],
		"DevTools":[
			"Google Chrome",
			"FireFox"
		],
		"mobile testing":[
			"iOS",
			"Android"
		],
		"building applications":[
			"Android Studio",
			"XCode"
		],
		"working in the terminal":[
			"GitBush",
			"GitHub"
		],
		"load testing": "Jmeter",
		"methodology": "SCRUM"
	}
}
```

 *Нажать **"Esc"** :wq **"Enter"***
 
 12. Отправить сразу 2 файла на внешний репозиторий. 
 
 `git add . && git commit -m "Added preferences.json and skills.json files` && git push
 
 13. На веб интерфейсе создать файл bug_report.json. 
 
 *Add file*  
 
 ![image](https://user-images.githubusercontent.com/105368491/173528007-eec4f959-6281-4bbc-894b-4abf7b9417c1.png)
 
 *Create new file*
 
 ![image](https://user-images.githubusercontent.com/105368491/173528305-dcd57aa4-5684-44f8-8cc0-4c7adf1b0e25.png)

*Name: bug_report.json*

![image](https://user-images.githubusercontent.com/105368491/173528588-cbd0708d-d453-41d4-a3ff-8a8ff79d2310.png)


 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 
 *Commit New File*
 
 ![image](https://user-images.githubusercontent.com/105368491/173528774-f9b59f8f-15d8-4f8c-8dce-640f6d27e22c.png)
 
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. 
 
 *Choose bug_report.json* 
 
 ![image](https://user-images.githubusercontent.com/105368491/173529030-4aa4bc01-42e8-4cc3-9877-16b4f47df5eb.png)

 *Edit this file*
 
 ![image](https://user-images.githubusercontent.com/105368491/173529151-7dd2506e-d2a9-4ec1-aa96-5b369e0f1e4a.png)
 
 ```
 {
  "Bug-ID": "1",
  "Title": "Поле ввода 'Введите номер телефона' не позволяет ввести цифры после нажатия на кнопу 'Войти по номеру телефона'",
  "Project": "Сайт магазина 'Malina'",
  "STR": [
    "1. Открыть страницу входа",
    "2. Нажать на кнопку 'Войти по номеру телефона'",
    "3. Начать вводить цифры  от 0 до 9 в поле 'Введите номер телефона'"
    ],
  "AR": "Невозможно ввести цифры от 0 до 9  в поле ввода 'Введите номер телефона' ",
  "ER": "В поле 'Введите номер телефона' возможно внести 10 цифр номера телефона от 0 до 9",
  "Environment":{
    "OS": "Windows 10 PRO 64-bit operating system, x64 processor",
    "Browser": "Google Chrome Version 102.0.5005.63 (Official build), (64 bit)"
  },
  "Severity": "Major",
  "Priority": "Medium",
  "Status": "New",
  "Author": "Виктория Субботина"
}
```
 
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 
 *Commit changes*
 
 ![image](https://user-images.githubusercontent.com/105368491/173529310-928824a7-96bc-4400-8f02-3093bc6d7b4b.png)
 
 17. Синхронизировать внешний и локальный репозиторий JSON 
 
 `git pull`
