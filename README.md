JSON
 4. Создать внешний репозиторий c названием JSON – 
в акаунті Git натискаємо Create
Repository name JSON
обираємо Public
галочка напроти Add a README file 
тиснемо Create
 5. Клонировать репозиторий JSON на локальный компьютер.
Тиснемо кнопку Code у створеному репозиторії
Обираємо HTTPS вкладку та копіюємо адресу
Переходимо в термінал та створюємо папку git_hw та заходимо в неї
Команда git clone https://github.com/romanenkoia92/JSON.git (посилання яке скопіювали в нашому репозиторії)

 6. Внутри локального JSON создать файл “new.json”.
cd JSON
touch new.json
 7. Добавить файл под гит.
git status покаже які файли не під гітом
git add . (додасть всі нові файли під гіт)
git add new.json
 8. Закоммитить файл.
git commit -am 'add new.json'
 9. Отправить файл на внешний GitHub репозиторий.
git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
vi new.json
i
      {  'name' 'Ivanna'
        'surename' 'Romanenko'
        'age' '30'
        'number of pets' '3'
        'future desired salary' '1000'  }
Esc
:wq
 11. Отправить изменения на внешний репозиторий.
git add .
git commit -am 'add new rows'
git push
 12. Создать файл preferences.json
touch preferences.json

 13. В файл’ добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
vi preferences.json
i
       {    'favorite film' 'sweet november'
           'favorite series' 'game of thrones’
           'favorite food' 'salad'
           'favorite season of the year' 'summer'
           'country' 'there are many of them'    }
Esc
:wq
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
touch sklls.json
vi sklls.json
i
1. 'Базовая теория SDLC, STLC'
2. 'Что такое клиент-серверная архитектура'
3. 'HTTP Методы запросов на сервер'
4. 'Коды ответов HTTP сервера'
5. 'Структуры HTTP запросов и ответов'
6. 'JSON, XML. Их структура'
7. 'Тестирование API через Postman (JS, автотесты API)'
8. 'Снятие и чтение логов c внешнего сервера'
9. 'Снифинг http web трафика через Charles и Fiddler'
10. 'Dev Tools веб браузеров (Google Chrome, FireFox)'
11. 'VPN'
12. 'Мобильное тестирование'
13. 'Особенность iOS, Android, гайдлайны'
14. 'Сборка iOS приложений на XCode'
15. 'Сборка Android приложений на Android Studio'
16. 'ADB'
17. 'Настройка прокси и vpn на iOS и Android'
18. 'Charles и Fiddler на iOS и Android'
19. 'Terminal Linux'
20. 'Основы bash скриптинг, автоматизация рутинных задач на сервере'
21. 'Доступ к удалённым серверам'
22. 'SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)'
23. 'Postgres'
24. 'Redis'
25. 'Jmeter'
26. 'Scrum'
27. 'Python'
Esc
:wq
 15. Отправить сразу 2 файла на внешний репозиторий
git add .
git commit -am 'add preferences and skills'
git push
 16. На веб интерфейсе создать файл bug_report.json.
touch bug_report.json
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
git commit -m 'add bug_report'
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
vi bug_report.json
'Summary:'
'Envirouments'
'Severity'
'Priority:'
'Preconditions:'
'Steps to reproduce:'
 '1.'
 '2.'
 '3.'
'Actual result'
'Expected result'
'Attachment'

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Git add .
git commit -m 'add bug_report'
 20. Синхронизировать внешний и локальный репозиторий JSON
Git push

