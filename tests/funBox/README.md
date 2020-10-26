# Level I

#### Q1 Расскажите, чем, на ваш взгляд, отличается хорошая верстка от плохой с точки зрения 
* пользователя; 
* менеджера проекта; 
* дизайнера; 
* верстальщика; 
* клиентского программиста; 
* серверного программиста.

***Пользователя***: На мой взгляд,  главное для пользователя, удобство взаимодействия с элементами на странице и доступность с любого устройства.

***Менеджера проекта***: Для менеджера проекта, верстка должна полностью соотвествотвать макету (шрифты, размеры, цвета, ...). Если есть адаптивность, то идеально должно отображаться на всех устройствах. Менеджер отвечает перед клиентами за все недочеты верстки и поэтому они строго относятся к верстке чтобы показать клиенту качественную работу. Их требовательность касается только визуала. 

***Дизайнера***: Дизайнер проверяет если верстка и поведение максимально отображает его  задумки макета. Проверяеть позицианирование Элементов, шрифты, цвета, размеры, все детали которые были придуманы для макета 

***Верстальщика***: Для верстальщика, главное соблюдать правила и регламенты по которому работает компания. Проверяет если код аккуратно и понятно написан и хорошо отрабражается результат на устройстве

***Клиентского программиста***: Он проверет качество кода по методологии и использование инструментов, как реагируют элеметы при изменении или удалении контента.

***Серверного программиста***: При програмировании, верстка не должна "ломаться" при динамическом использовании блоков и их исползовании на другом месте. Верстка должна иметь возможность содержать динамический контент.



#### Q2 Опишите основные особенности верстки крупных многостраничных сайтов, дизайн которых может меняться в процессе реализации и поддержки.
#### Расскажите о своем опыте верстки подобных сайтов: какие методологии, инструменты и технологии вы применяли на практике. 

При работе с версткой крупных многостраничных проектов, необходимо реализовать элементы по модульной архитектуре. Это позволят избежать повторение кода и можно дабавлять компонент на любом месте и сохранить  дизайн. Такой подход облегчает поддержку (изменение присходит только на одном месте)
Необходимо использовать инструмент сборки проекта (webpack или gulp). С такими иструметами легко внедрить препроссесор (sass или less) и линтеры - иструменты  проверки кочества кода (Eslint и StyleLintrc) которые состоят из уникальных правил которые соблюдает все. Для css использовать Бэм чтобы назвние классов следовали одной и той же методологи и понятно всем. Для быстроты создания шаболна нужно использовать Pug или jsx в react 


#### Q3 Опишите основные особенности верстки сайтов, которые должны одинаково хорошо отображаться как на любом современном компьютере, так и на смартфонах и планшетах под управлением iOS и Android. Расскажите о своем опыте верстки подобных сайтов: какие инструменты и технологии вы применяли, как проверяли результат на различных устройствах, какие именно устройства требовалось поддерживать.

Нужно тут реализовать адаптивную верстку которая хорошо отображается на всех устройствах и использовать Autoprefixer чтобы в css все правила существовали на различных браузерах

#### Q4 Расскажите, какие инструменты помогают вам экономить время в процессе
написания, проверки и отладки кода. 

Чтобы экономить время, я использую сборки проекта - Webpack или Gulp с их плагинов, препроцессор Sass, для создание шаблоны: Pug, стал тоже использовать react. Для проверки использую линтеры Eslint и StyleLintrc. Для отладки использую Git


#### Q5  Вам нужно понять, почему страница отображается некорректно в Safari на iOS и в
IE на Windows. Код писали не вы, доступа к исходникам у вас нет. Ваши действия?
Сталкивались ли вы с подобными проблемами на практике? 

В таких случаях проблема либо в html, css или js! В первую очередь нужно опредилить проблему с помощью инспектора кода в навигаторе. Дальше зафиксировать ее.


#### Q6 Дизайнер отдал вам макет, в котором не показано, как должны выглядеть
интерактивные элементы при наведении мыши. Ваши действия?

В любом случае нужно сверстать состояние  интерактивных элементов. Исходя из моего опыта я могу предлагать эти состояния и обратиться к дизайнеру на согласование

#### Q7 Какие ресурсы вы используете для развития в профессиональной сфере? Приведите
несколько конкретных примеров (сайты, блоги и так далее). 
	 Офицальние сайты тех навыков, которыми я владею. Через требования на hh.ru, видео ролики на youtub, https://www.udemy.com/ и https://www.google.com/

### Какое направление развития вам более близко: JS-программирование, HTML/CSSверстка или и то, и другое? 

Я польностью заитересован в HTML/CSSверстке и JS-программировании

### Какие ещё области знаний, кроме тех, что непосредственно относятся к работе, вам интересны?
	* Полностью владение Английским Языком
	* Видеомонтаж 

#### Q8 Расскажите нам о себе и предоставьте несколько ссылок на последние работы,
выполненные вами. 

	Меня зовут Кевин Комбето. Мне 30лет и я живу в России - Орел с 2011го. IT сферу начал в 2015 как Верстальщик и перешел на php прогаммирование при получении проекта в Бенине в Африке. Сейчас полностью увлекаюсь HTML/CSSверсткой и JS-программированием

Несколько ссылок на последние работы:
http://serproweb.dev-spw.com/
http://topimmo.dev-spw.com/
http://rechcompt.dev-spw.com/



















