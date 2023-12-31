# Проект GULP_STARTER

## Інструкції з установки

- Встановіть Node.js на ваш комп'ютер, якщо він ще не встановлений. Ви можете завантажити його з офіційного сайту: [https://nodejs.org/en/](https://nodejs.org/en/).
- *Важливо! Якщо під час розгортання збірки, в консолі з'явилося нескінченне повідомлення "npm timing reifyNode:node_modules/lodash", та не зникло через 1-2 хвилини, будь-ласка, встановіть збірку через node версії 14.17.3.
- Склонуйте репозиторій проекту на ваш комп'ютер.
- Відкрийте термінал і перейдіть до директорії проекту.
- Введіть команду `npm install`, щоб встановити всі залежності проекту.

---

## Інструкції з використання

- Запустіть проект у режимі розробки: `npm run dev`.
  Ця команда запускає проект у режимі розробки, в якому файли автоматично перебираються при зміні вихідного коду.

- Зібрати проект для продакшену: `npm run build`.
  Ця команда збирає проект для продакшену, оптимізує файли для швидкого завантаження та мінімізує їх розмір.

---

## Структура проекту

- gulpfile.js - файл, в якому імпортується задача для Gulp.
- gulp/tasks/ - файли задач Gulp безпосередньо.
- gulp/config/ - файли налаштувань.
- src/ - директорія, в якій знаходяться вихідні файли проекту.
- dist/ - директорія, в яку Gulp збирає проект для продакшену.

---

## Зміна конфігурації

- gulpfile.js - у цьому файлі ви можете змінювати конфігурацію Gulp, додавати або видаляти задачі, налаштовувати їх параметри та інше.

---

## Розширення функціональності

Ви можете додавати нові задачі до gulpfile.js для розширення функціональності проекту.
При цьому варто переконатися, що ці задачі виконуються в правильному порядку та не призводять до помилок у збірці проекту.
