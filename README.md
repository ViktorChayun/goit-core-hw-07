# goit-core-hw-07
https://www.edu.goit.global/uk/learn/26850204/19951493/19951603/homework

**додамо додатковий функціонал до класів з попередньої домашньої роботи:**
* Додайте поле birthday для дня народження в клас Record 
	* Це поле має бути класу Birthday. 
	* Це поле не обов'язкове, але може бути тільки одне.
* Додайте функціонал роботи з Birthday у клас Record, а саме функцію add_birthday
    * яка додає дату народження до контакту.
* Додайте функціонал перевірки значення в класі Birthday.
* Додайте та адаптуйте до класу AddressBook фінальну функцію з автоперевірки
	тиждень 3, get_upcoming_birthdays. 
	- Це буде метод, який визначає контакти, у яких день народження припадає вперед на 7 днів включаючи поточний день. 
	- Метод має повертати список словників. 
	- Кожен словник містить два значення - ім’я з ключем "name", та дата привітання з ключем "birthday”. 
	- Не забудьте врахувати перенесення дати на наступний робочий день, якщо день народження припадає на вихідний.
* Тепер ваш бот (4 домашнє завдання тиждень 5) повинен працювати саме з функціоналом класу AddressBook. 
	* Це значить, що замість словника contacts ми використовуємо book = AddressBook()

### бот повинен підтримувати наступний список команд:
* add [ім'я] [телефон]: Додати або новий контакт з іменем та телефонним номером, або телефонний номер до контакту який вже існує.
* change [ім'я] [старий телефон] [новий телефон]: Змінити телефонний номер для вказаного контакту.
* phone [ім'я]: Показати телефонні номери для вказаного контакту.
* all: Показати всі контакти в адресній книзі.
* add-birthday [ім'я] [дата народження]: Додати дату народження для вказаного контакту.
* show-birthday [ім'я]: Показати дату народження для вказаного контакту.
* birthdays: Показати дні народження на найближчі 7 днів з датами, коли їх треба привітати.
* hello: Отримати вітання від бота.
* close або exit: Закрити програму.