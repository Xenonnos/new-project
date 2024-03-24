Покрокова інструкція.

Step 1.	Змінюємо поточну директорію командою "cd c:\Users\iora\" та створюємо каталог командою "mkdir new-project".

Step 2. Переходимо до новоствореного каталогу командою: "cd new-project".

Step 3. Ініціалізуємо новий публічний Git-репозиторій командою "git init".

Step 4. Створюємо в файловому менеджері файл "README.md" у каталозі "new-project" і додаємо до нього текст.

Step 5. Командою "git add README.md" готуємо файл "README.md" до коміту.

Step 6: Комітимо зміни у репозиторій з повідомленням “init” командою "git commit -m 'init'"

Step 7. Створюємо нову гілку з назвою "development" і переходимо до неї за допомогою команд: "git branch development" i "git checkout development".

Step 8. У текстовому редакторі додаємо інструкцію до файлу "README.md" і виконуємо команду "git add README.md".

Step 9. Комітимо зміни у гілці "development" командою "git commit -m 'init'" 

Step 10. Повертаємося у гілку "main" командою "git checkout main"  і зливаємо зміни з гілки "development" у гілку "main" командою "git merge development".

Step 11. Комітимо зміни у репозиторій командою "git commit".


