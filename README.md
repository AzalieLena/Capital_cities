# Capital_cities

Завдання:
1.	Клонувати репозитарій https://github.com/AzalieLena/Capital_cities за допомогою команди git clone
2.	Створити гілку за допомогою команди git switch -c ТК_surname // surname – ваше прізвище
3.	Додати країну та столицю у текстовий capital_cities.txt та зберегти файл
4.	Додати в index git add capital_cities.txt 
5.	Створити комміт 
    a.	Створення: git commit -m "[ТК_surname] Add capital city for Country" // Country – Ваша країна
  	b.	Редагування: git commit --amend -m "[ТК_surname] Add capital city for Country "
7.	Відправити дані на віддалений репозиторій за допомогою команди git push -u origin ТК_surname 
8.	Cтворити запит на злиття гілок
    a.	git switch main
    b.	git pull 
    c.	git log -2 //якщо перед Вами хтось щось змінив (The source branch is n commits behind the target branch), то треба              виконати:
  	d. git switch ТК_surname
    e	 git rebase develop
