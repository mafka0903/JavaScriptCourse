1. Створити локальний репозиторій і додати до нього декілька файлів. Створити репозиторій на github та синхронізувати локальний репозиторій з віддаленим.

git init
git add .  
git commit -m "first commit"  
create GitHub repository
git branch -M main
git remote add origin https://github.com/mafka0903/JavaScriptCourse.git
it push -u origin main

2. Клонувати віддалений репозиторій на свій комп'ютер

create folder on PC
open new folder on VSCode

git clone https://github.com/mafka0903/JavaScriptCourse.git

3. Подивитися історію комітів локально та на github порівняти контент комітів.

4. Створити гілку на основі майстер гілки. Внести зміни в нову гілку та завантажити їх у віддалений репозиторій. Злити зміни нової гілки в гілку master.

5. Спробувати роботу з репозиторієм через VS Code (Команди add, commit, push, pull та роботу з гілками)
