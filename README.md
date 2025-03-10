Проект demo-book-list створений як тестове завдання з використанням React
Перед встановленням даного додатку потрібно на локально встановити Node.js та npm (https://www.npmjs.com/) 

Встановлення додатку
1. Клонування репозиторію на gitHub: https://github.com/YuriyArtemchuk/demo.git
2. Перейти в корінь проекту cd demo  
3. Встановлення залежностей npm install
4. Запустити додаток npm start

Запуск віддаленого серверу
1. Зайти в bash в папку, де розміщений файл db.json:
   DemoBook\demo-book-list>\src
2. Запустити в цій папціjson-server, виконавши команду:
   json-server --watch db.json --port 5000
3. Відкрийте відалену базу даних на порту 5000 по данному посиланню:
   http://localhost:5000/books
   



