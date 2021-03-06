# SeaBattle
# Морський бій
---

Дане технічне завдання поширюється на  розробку програмного продукту, що являє собою мережеву гру «Морський бій». Програмне забезпечення дозволить певному користувачу, що має зв’язок по мережі, проводити гру з іншим користувачем.

<br />

#### Підстава для розробки
---
Розробка програмного продукту ведеться на підставі попереднього договору із замовником(в даному випадку викладачем), що поставив завдання з дисципліни «Комп’ютерні системи»(назва дисципліни відповідає назві дисципліни, в рамках якої виконується завдання).

<br />

#### Призначення розробки
---
За допомогою продукту користувачам буде наданий доступ до додатку, який, використовуючи з’єднання по  мережі, буде з’єднюватисьз іншим певним додатком, після чого з’явиться можливість проводити процес гри в «Морський бій»

<br />

#### Вимоги до програми або програмного виробу
---
1. Вимоги до функціональних характеристик
   -	Успішне з’єднання двох користувачів;
   -	Представлення своєї карти та карти противника;
   -	Можливість заповнювати карти користувачами будь яким чином, та в будь-якому порядку;
   -	Успішна відправка та отримання вказівок між користувачами програми;
   -	Надання коректної інформації про останній хід;
   -	Можливість у будь-який момент закінчити гру та розірвати зв’язок; 
   -	Правильна обробка помилок.
  
2. Вимоги до надійності
    -	Передбачити контроль введеної інформації;
    -	Створення копій карт на певних етапах гри;
    -	Захищати від несанкціонового доступу певного користувача до чужої карти;
    -	Обробляти помилкові дії користувача та повідомляти його про це;

<br />

#### Вимоги до інформаційної та програмної сумісності
---
Система повинна працювати під управлінням операційних систем сімейств Linux, Windows.

<br />

#### Засоби реалізації програмного продукту:
---
**Мова програмування:** С++  <br />
**Використання бібліотек:** boost  <br />
**Використання стандарту:** С++11  <br />
**Pозробкa користувацького інтерфейсу:** Qt <br />

*Програмний комплекс повинен бути побудований на клієнт-серверній архітектурі,  що не вивимагають додаткового ліцензування*

<br />

#### Вимоги до лінгвістичного забезпечення
---
Користувацький інтерфейс повинен бути виконаний українською мовою.
Все документація, що створюється в рамках розробки системи, також створюється та надається українською мовою. При розробці програми вибирається ефективна мова програмування та потрібні засоби, які також допоможуть ефективніше виконати поставлену задачу
