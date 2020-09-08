# Проект «Антарктика»

## Описание проекта

[Демо](https://egarnaga.github.io/cruise-project/) | [Техническое задание](specification.md)

* **Стандарты вёрстки:** HTML5, CSS3, прогрессивное улучшение.
* **Сетка:** определена в макете.
* **Раскладка блоков на странице** делается с помощью Flexbox.
* **Адаптивность сетки:** мобильная, планшетная и десктопная версии. **Desktop First.** На всех промежуточных разрешениях используется резиновая вёрстка.
* **Используемая методология:** БЭМ.
* **Используемые фреймворки:** нет.
* **Используемый препроцессор:** Sass (SCSS).
* **Используемый инструмент автоматизации:** Gulp.
* **Кроссбраузерность:** Chrome, Firefox, Safari, Edge, Internet Explorer 11.
* **Макет** предоставляется в Figma. Графика не предоставляется и её необходимо вырезать из макета самостоятельно.
* **Нестандартные шрифты** подключены локально.
* **JavaScript:** мобильное меню, валидация формы.
* **Прочее:**  вёрстка сделана Pixel Perfect, использована webP и SVG-графика, использован SVG-спрайт, выполнена ретинизация растровой графики, проведена работа по оптимизации и улучшению доступности.

## Превью

<img src="preview.jpg" alt="Превью проекта Антарктика">

## Краткая инструкция по работе c Gulp template

### Для начала работы у вас должент быть установлен:

* Node.js v.10.15.3
* Gulp v4
* npm last version

### Основные команды для работы

* Установка - `npm i`
* Запуск локального сервера - `npm start`
* Сборка проекта без запуска локального сервера - `npm run-script build`
* Запуск тестирования на соответствия код-гайдам - `npm test`

### Все разработка ведётся в директории `source`

### Итоговый код попадает в директорию `build`
