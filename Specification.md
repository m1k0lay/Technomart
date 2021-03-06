# Спецификация на проект

### 1. Общие технические требования 
- 1.1. Стандарты вёрстки: HTML5, CSS3, прогрессивное улучшение. 
- 1.2. Сетка: определена в макете. 
- 1.2. Адаптивность вёрстки: нет. 
- 1.4. Используемые фреймворки: нет. 
- 1.5. Кроссбраузерность: IE11+, Chrome, Firefox, Opera, Safari. 
- 1.6. Типографика: частично определена в макете (прочее — на усмотрение разработчика). 
- 1.7. Используемые шрифты: Cuprum, PT Sans (есть в папке с макетом и на Google Fonts). 
- 1.8. С макетом предоставлен styleguide.psd, содержащий прорисовку состояний элементов интерфейса. При любых расхождениях с макетами он должен иметь наивысший приоритет. 

### 2. Обязательные требования 
- 2.1. Контентная область центрируется и не может быть уже макетной ширины. 
- 2.2. Если пользователь сделал закладку или добавил что-то в корзину, соответствующий пункт в шапке сайта меняет цвет фона на красный. 
- 2.2. Авторизованному и неавторизованному посетителю показывается разный вид блока авторизации. 
- 2.4. В блоке авторизованного посетителя имя и иконка пользователя являются ссылкой на профайл, а иконка выхода — на страницу деавторизации. 
- 2.5. Промо-блок («материалы», «инструмент», ...): ссылками являются только кнопки. 
- 2.6. Промо-блок («материалы», «инструмент», ...): слайдер. Вёрстка всех слайдов обязательна. Оживление слайдера необязательно, принцип оживления описан в 4 разделе. 
- 2.7. Кнопка: «Открыть каталог» в слайдере - это ссылка, которая ведет на внутреннюю страницу каталога.
- 2.8. Блок «Популярные производители»: карточка производителя является ссылкой. 
- 2.9. Блок «Сервисы»: слайдер. Вёрстка всех слайдов обязательна. Оживление слайдера необязательно, принцип оживления описан в 4 разделе.
- 2.10. Блок карты — достаточная реализация — обычное изображение, клик по ней приводит к переходу на сервис карт. 
- 2.11. Вёрстка модального окна обязательна. 
- 2.12. Логотип — это ссылка на главную страницу. 
- 2.12. Фильтр: верстать с помощью формы, кнопка «Показать» отвечает за отправку формы. 
- 2.14. Блок «Цена» — при наведении на любой из маркеров появляется указатель cursor: pointer, делать маркеры подвижными не обязательно, цена меняться не должна.
- 2.15. Количество товаров в правом блоке может быть любым, добавление товаров не должно ломать страницу. 
- 2.16. У любого товара может быть метка «new».
- 2.17. Вёрстка модальных окон обязательна.

### 3. Дополнительные требования 
- 3.1. Промо-блок («материалы», «инструмент», ...): оживление слайдера. Смена слайдов в слайдере должна происходить мгновенно, без промежуточных состояний и анимации. 
- 3.2. Блок «Сервисы»: оживление слайдера. Слайдер с табами работает аналогично слайдеру промо-блока: по клику на таб меняется слайд мгновенно. 
- 3.3. Блок карты — реализация по желанию — часть интерактивной карты, клик на неё приводит к появлению полного размера интерактивной карты, окно позиционируется относительно вьюпорта, а не страницы. 
- 4.4. При клике по кнопке «Заблудились?..» возникает модальное окно, окно позиционируется относительно вьюпорта, а не страницы. 
- 4.5. При клике на кнопку «Купить» возникает модальное окно с сообщением о добавлении в корзину, окно позиционируется относительно вьюпорта, а не страницы. 
- 4.6. Фильтр: по нажатию кнопки «Показать» осуществляется отправка формы. 
