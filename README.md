# Book Shop

![Status](https://img.shields.io/badge/status-ready-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-orange)
![CSS3](https://img.shields.io/badge/CSS3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow)

Простий та сучасний веб-сайт для книжкового магазину. Дозволяє переглядати
книги, додавати їх до кошика та оформлювати покупки онлайн.

🔗 **Live Demo:**
[https://julia-shefner.github.io/book-shop/](https://julia-shefner.github.io/book-shop/)

---

**Зміст**

- [Технології](#computer-технології)
- [Початок роботи](#rocket-початок-роботи)
- [Використання](#jigsaw-використання)
- [Функціонал](#dart-функціонал)
- [To Do](#memo-to-do)
- [Команда проєкту](#female-technologist-команда-проєкту)
- [Джерела натхнення](#star2-джерела-натхнення)

---

**Технології**

- HTML5, CSS3, JavaScript (ES6+)
- Swiper.js — слайдери та каруселі
- IziToast — сповіщення про дії користувача
- SVG-іконки для кнопок та UI елементів
- Адаптивний дизайн через медіа-запити

---

**Початок роботи**

1. **Клонування репозиторію**

```bash
git clone https://github.com/Julia-Shefner/book-shop.git
cd book-shop
```

2. **Встановлення залежностей**

```bash
npm install
```

3. **Запуск локального сервера**

```bash
npm run dev
```

4. **Збірка білду**

```bash
npm run build
```

---

**Використання**

Відкрий сайт у браузері.

Переглядай книги на сторінці каталогу.

Натисни Add to Cart для додавання книги до кошика.

Натисни Buy Now для оформлення покупки (сповіщення підтверджує дію).

Використовуй акордеон для перегляду деталей, доставки та повернення товарів.

Приклад JS-коду:

const addToCartBtn = document.getElementById('add-to-cart');
addToCartBtn.addEventListener('click', () => { // додає книгу до кошика та
показує toast-сповіщення });

---

**Функціонал**

Перегляд книжок у слайдері та каталозі

Додавання товарів до кошика

Сповіщення при додаванні до кошика та покупці

Адаптивний дизайн для мобільних, планшетів та десктопів

Модальне вікно з деталями книги

Акордеон для деталей, доставки та повернення

---

**To Do**

Реалізація реальної корзини з підрахунком суми

Підключення платіжних систем

Покращення UI/UX для мобільних пристроїв

Мультимовність (англійська/українська)

---

**Команда проєкту**

Юлія Шефнер — team lead / GitHub: https://github.com/Julia-Shefner

Анастасія Морміль — scram master / GitHub:https://github.com/anastasiamormil

Олександр Браницький — developer / GitHub:
https://github.com/Oleksandr-Branytskyi

Валентина Підопригора — developer / GitHub:
https://github.com/Valentyna-Pidopryhora

Олег Лучко — developer / GitHub: https://github.com/Oleg2287

Ольга Шамрай — developer / GitHub: https://github.com/olha-shamrai

Степен Венгжин — developer / GitHub: https://github.com/Venhzhy

Святослав Рижиков — developer / GitHub: Julia-Shefner
https://github.com/Slavik199

Вікторія Епова — developer / GitHub: Julia-Shefner
https://github.com/viktoria-ep

---

**Джерела / Література**

Swiper.js Documentation https://swiperjs.com/swiper-api

IziToast Documentation https://marcelodolza.github.io/iziToast/

Acordeon Documentation https://github.com/michu2k/Accordion

MDN Web Docs https://developer.mozilla.org/en-US/

API Books 1.0.0 https://books-backend.p.goit.global/api-docs/
