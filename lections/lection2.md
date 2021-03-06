﻿Вторая лекция по Frontend.
==========================

Парадигмы программирования
--------------------------

### Несколько определений

* **Парадигма программирования** — это совокупность идей и понятий, определяющих стиль написания компьютерных программ (подход к программированию). Это способ концептуализации, определяющий организацию вычислений и структурирование работы, выполняемой компьютером
* **Императивное программирование** — это парадигма программирования, которая, в отличие от декларативного программирования, описывает процесс вычисления в виде инструкций, изменяющих состояние данных. Императивная программа очень похожа на приказы, выражаемые повелительным наклонением в естественных языках, то есть это последовательность команд, которые должен выполнить компьютер.
* **Декларативное программирование** - описывает каково нечто, а не как его создать. Написана на исключительно функциональном, логическом или языке программирования с ограничениями. 
* **Структурное программирование** — методология разработки программного обеспечения, в основе которой лежит представление программы в виде иерархической структуры блоков.
* **Процедурное программирование** — программирование на императивном языке, при котором последовательно выполняемые операторы можно собрать в подпрограммы, то есть более крупные целостные единицы кода, с помощью механизмов самого языка
* **Модульное программирование** - является развитием и совершенствованием процедурного программирования и библиотек специальных программ. Основная черта модульного программирования - стандартизация интерфейса между отдельными программными единицами. 
* **Объектно-ориентированное программирование (ООП)** — парадигма программирования, в которой основными концепциями являются понятия объектов и классов. В случае языков с прототипированием вместо классов используются объекты-прототипы.
* **SOA - cервис-ориентированная архитектура (англ. Service-oriented Architecture)** — подход к разработке программного обеспечения на основе слабосвязанных компонентов, взаимодействующих посредством стандартизованных интерфейсов.
* **Логическое программирование** — парадигма программирования, основанная на автоматическом доказательстве теорем, а также раздел дискретной математики, изучающий принципы логического вывода информации на основе заданных фактов и правил вывода. 
* **Функциональное программирование** — раздел дискретной математики и парадигма программирования, в которой процесс вычисления трактуется как вычисление значений функций в математическом понимании последних (в отличие от функций как подпрограмм в процедурном программировании).

### Верификация и спецификация
* **Верификация** – это процесс доказательства того, что в результате исполнения программы получаются правильные решения рассматриваемой задачи, и что все правильные решения могут быть вычислены этой программой.
* **Спецификация** - определение и перечень особенностей, уточнённая классификация чего-нибудь. законченное описание поведения программы, которую требуется разработать. Включает ряд пользовательских сценариев (англ. use cases), которые описывают все варианты взаимодействия между пользователями и программным обеспечением.

* Парадигма программирования — это совокупность идей и понятий, определяющих стиль написания компьютерных программ (подход к программированию). Это способ концептуализации, определяющий организацию вычислений и структурирование работы, выполняемой компьютером
* Императивное программирование — это парадигма программирования, которая, в отличие от декларативного программирования, описывает процесс вычисления в виде инструкций, изменяющих состояние данных. Императивная программа очень похожа на приказы, выражаемые повелительным наклонением в естественных языках, то есть это последовательность команд, которые должен выполнить компьютер.
* Структурное программирование — методология разработки программного обеспечения, в основе которой лежит представление программы в виде иерархической структуры блоков.
* Процедурное программирование — программирование на императивном языке, при котором последовательно выполняемые операторы можно собрать в подпрограммы, то есть более крупные целостные единицы кода, с помощью механизмов самого языка
* Модульное программирование - является развитием и совершенствованием процедурного программирования и библиотек специальных программ. Основная черта модульного программирования - стандартизация интерфейса между отдельными программными единицами. 
* Объектно-ориентированное программирование (ООП) — парадигма программирования, в которой основными концепциями являются понятия объектов и классов. В случае языков с прототипированием вместо классов используются объекты-прототипы.
* Логическое программирование — парадигма программирования, основанная на автоматическом доказательстве теорем, а также раздел дискретной математики, изучающий принципы логического вывода информации на основе заданных фактов и правил вывода. 
* Функциональное программирование — раздел дискретной математики и парадигма программирования, в которой процесс вычисления трактуется как вычисление значений функций в математическом понимании последних (в отличие от функций как подпрограмм в процедурном программировании).
* Декларативное программирование(от declaire - обьявлять) - когда программа описывает какого нечто, а не как его создать.

------------------------
**Функция тестирования:**

*Assert* — это специальная конструкция, позволяющая проверять предположения о значениях произвольных данных в произвольном месте программы.
Эта конструкция может автоматически сигнализировать при обнаружении некорректных данных,
что обычно приводит к аварийному завершению программы с указанием места обнаружения некорректных данных

*Пример:*
bool assert(ожидаемое значение , действительное , сообщение)

*Ката* — формализованная последовательность движений, связанных принципами ведения поединка с воображаемым противником или группой противников.
*Ката в программировании* - это упражнение в программировании, который помогает программисту отточить свои навыки через практику и повторение.
Термин, вероятно, был впервые придуман Дэйв Томас, соавтор книги "прагматичный программист" в поклон японской концепции ката в боевых искусствах.

**JSLint** – это инструмент проверки качества программного кода на JavaScript, созданный Дугласом Крокфордом (Douglas Crockford),
который проверит ваш программный код и предупредит обо всех потенциальных проблемах.
**JSHint** - данный проект является ответвлением популярного JSLint.



Объекты в JavaScript
--------------------------

JavaScript может работать в парадигме объектно-ориентированного программирования, однако в отличие от многих объектно-оринтированных языков JavaScript не поддерживает классы. Если, например, в C# объект - представитель определённого класса, то в JavaScript объекты порождаются другими объектами. 

Объект можно инициализировать, например, так:

var a = {}

Любой объект в JavaScript можно рассматривать как контейнер свойств и задавать их значение в формате key:value. Названия свойств можно писать с кавычками или без.

Пример:

var a = {name:"MyName", "age": 18}

К свойствам объекта можно обращаться через dot-нотацию или через квадратные скобки

Примеры:

a.name, a["age"]

В качестве свойства объекта можно задавать другой объект

Пример:

var b = {newa: a}

Здесь создаётся объект с единственным свойством, которое представляет собой ранее созданный объект a.

Можно обратиться к нему так:

b.newa.name

Здесь в качестве значения поля newa задаётся ссылка на объект a, так что при изменении значения поля name объекта a меняется и значение b.newa.name.

Можно задавать рекурсивные ссылки на объекты. Например, a.b = b. Теперь объект a ссылается на объект b, a объект b - на объект a. 

Значение свойства объекта нельзя задать как undefined. При обращении к несуществующим свойствам объекта (например, a.param) JavaScript выводит undefined.

Свойства объектов можно удалять командой delete 

Пример:

delete b.name
### Важно знать!
* ООП появилось в 1967г.
* "Абстракция есть умышленное упрощение."
* Верификация - это проверка, например, логических выражений.
### Один из видов тестов:
* bool assert(factialVal, expectedVal, msg) 
*где : factialVal - фактическое значение
*      expectedVal - ожидаемое значение
*      msg - сообщение, которое выйдет при успешном тесте.
## Пример:
* assert(f(a),z,"OK")
* при TRUE выведет OK
