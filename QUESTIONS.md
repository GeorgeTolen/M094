# М094 — банк вопросов пробного теста

Отсканировано со скриншотов: **17 вариантов, 420 вопросов** — русская версия (13) и казахская (4).

| Язык | Предмет | Вариантов | Вопросов | Максимум баллов |
|---|---|---|---|---|
| рус | База данных | 7 | 20 | 40 |
| рус | Алгоритмы и структуры данных | 6 | 30 | 30 |
| каз | Деректер базасы | 2 | 20 | 40 |
| каз | Алгоритмдер және деректер құрылымы | 2 | 30 | 30 |

## Как считаются баллы

**База данных / Деректер базасы** — один или несколько правильных ответов (не более трёх):

- правильный ответ один, отмечен только он — **2 балла**
- правильный ответ один, отмечено несколько — **0 баллов**
- правильных несколько, отмечена их часть без ошибок — **1 балл**
- правильных несколько, отмечены все — **2 балла**
- отмечен хотя бы один неправильный — **0 баллов**

**Алгоритмы / Алгоритмдер** — один правильный ответ, **1 балл** за верный.

> **Важно.** На исходных скриншотах правильные ответы не отмечены — они проставлены по предмету и могут содержать ошибки. Вопросы, где ответ неоднозначен, помечены ⚠ и требуют сверки с преподавателем.

---

# Русская версия — База данных

## Вариант 1

**1.** Вид отношения в базе данных между преподавателями и студентами

- A) 0:1
- B) 1:1
- C) 1:3
- D) 1:0
- E) 2:1
- **F) M:M** ✅
- G) 2:M
- H) 3:1

**Ответ: F**

**2.** Название таблицы из следующего кода  
create table calc (x int, y int);  
insert into calc values (5, 45);  
select *from calc x, y, x+y;

- A) values
- B) int
- C) y
- **D) calc** ✅
- E) *
- F) x
- G) table

**Ответ: D**

**3.** Действие выполняемое следующей функцией sum (sales)

- A) вывод минимума строки sales
- B) вывод среднего значения столбца sales
- C) вывод среднего значения строки sales
- **D) вывод суммы столбца sales** ✅
- E) вывод среднего значения переменной sales
- F) вывод среднего значения таблицы sales

**Ответ: D**

**4.** Результат выполнения следующей команды для данной таблицы  
select salary  
from table  
where city = 'Almaty'  
  
| name | city | salary |  
| Aigerim | Almaty | 50 |  
| Bauyrzhan | Almaty | 60 |  
| Gulzhan | Arkalyk | 70 |  
| Samat | Moscow | 80 |

- A) 50, 60, 70, 80
- B) 60, 70, 80
- **C) 50, 60** ✅
- D) 80
- E) 70
- F) 50

**Ответ: C**

**5.** Правильный синтаксис написания кода на SQL

- A) select from *data
- **B) select data from students** ✅
- C) select *data from students
- D) select from data
- **E) select *from data** ✅
- F) select from students
- G) select *stud from data
- H) select data*students from

**Ответ: B, E**

**6.** Применить функцию аггрегации avg к следующему массиву данных: {1,5,6,7,8,3,10, 0}

- A) 40
- B) 42
- **C) 5** ✅
- D) 41
- E) 7
- F) 43

**Ответ: C**

**7.** Виды операции можно применять к базам данных

- A) форматирование
- B) сжатие
- **C) обновление** ✅
- **D) удаление** ✅
- E) корреляция
- F) систематизация
- **G) создание** ✅
- H) оптимизация

**Ответ: C, D, G**

**8.** Архитектура ANSI/SPARC включает следующие уровни

- **A) внешний, концептуальный, внутренний** ✅
- B) внешний, концептуальный
- C) концептуальный, внутренний
- D) внешний, средний, внутренний
- E) внешний, внутренний
- F) внешний, промежуточный, внутренний
- G) внешний, промежуточный, концептуальный, внутренний

**Ответ: A**

**9.** Применение денормализации влечет

- A) понижение производительности
- B) фильтрацию данных
- C) удаление всех данных
- D) группировку данных
- E) нормализацию данных
- **F) повышение производительности** ✅
- G) выполнение запросов

**Ответ: F**

**10.** Выражение, описывающее правило объединения

- **A) if a→b and a→c, then a→bc** ✅
- B) if a→b or a→c, then a→bc
- C) if a→b and a→c, then a→c, a→b
- D) if a→b or b→c, then a→c
- E) if a→by , then a→b and a→y
- F) if a→b and b→c, then a→c

**Ответ: A**

**11.** Архитектура ANSI/SPARC содержит уровни

- A) серверный
- **B) внутренний** ✅
- C) логический
- **D) внешний** ✅
- E) средний
- **F) концептуальный** ✅
- G) промежуточный
- H) клиентский

**Ответ: B, D, F**

**12.** Для упорядочивания по алфавиту используется следующая команда

- A) filter by
- B) from A to Z
- C) filter on
- D) between A to Z
- E) list
- F) change from A to Z
- G) join
- **H) order by** ✅

**Ответ: H**

**13.** Архитектура ANSI/SPARC не включает следующие уровни

- A) логический
- **B) промежуточный** ✅
- C) внутренний
- D) концептуальный
- **E) серверный** ✅
- **F) клиентский** ✅
- G) средний
- H) внешний

**Ответ: B, E, F**

> ⚠ Спорный: ANSI/SPARC содержит только внешний, концептуальный и внутренний уровни, поэтому формально «не входят» также «логический» и «средний» — но тест допускает не более трёх ответов. Уточнить у преподавателя.

**14.** Результат выполнения следующей команды  
create table stud (x int, y int);  
insert into stud values (10, 45);  
insert into stud values (20, 70);  
insert into stud values (30, 90);  
create table stud2 (x int, y int);  
insert into stud2 values (10, 450);  
insert into stud2 values (40, 900);  
Select*from stud  
join stud2  
on stud.x= stud2.x

- A) 10 45 450
- **B) 10 45 10 450** ✅
- C) stud, stud2
- D) 45 70 90 450 900
- E) 10 20 30 40 45 70 90 450 900
- F) 10 20 30 40

**Ответ: B**

**15.** Внесение изменений в БД на языке запросов SQL осуществляется посредством следующих команд

- A) where
- **B) insert** ✅
- **C) delete** ✅
- D) view
- **E) update** ✅
- F) select
- G) between

**Ответ: B, C, E**

**16.** Вывести все данные из таблицы emp на языке SQL  
  
| id | name | city | salary |  
| 01 | Almat | Semey | 1500 |  
| 02 | Arman | Taldykorgan | 1800 |  
| 03 | Zhania | Shimkent | 2000 |

- A) select from table emp *
- **B) select id, name, city, salary from table emp** ✅
- C) select from table *emp
- D) select * from table emp where name= 'Arman'
- E) select * from table emp where salary > 1500
- **F) select * from table emp** ✅
- G) select from* table emp

**Ответ: B, F**

**17.** Виды строчных данных в работе с БД

- A) {4,6,8,6,0,10}
- **B) 'stud', 'string'** ✅
- C) null
- D) true, false
- E) 1, 2.6, 'stud'
- F) 2, 4, 8
- G) unknown

**Ответ: B**

**18.** Увеличить заработную плату таблице employers на 20 процентов с использованием команд SQL

- A) set employers salary * 1.2
- B) set employers update salary= salary * 1.2
- C) update employers insert salary = salary * 1.2
- D) insert salary = salary * 1.2
- E) update employers and insert salary = salary * 1.2
- **F) update employers set salary= salary * 1.2** ✅

**Ответ: F**

**19.** Увеличить заработную плату для тех, у кого она не превышает 80000 в таблице employers на 20 процентов с использованием команд SQL

- A) update salary = salary * 1.2 where salary < 80000
- B) set employers update salary = salary * 1.2 where salary < 80000
- C) insert salary = salary * 1.2 where salary < 80000
- **D) update employers set salary = salary * 1.2 where salary < 80000** ✅
- E) select * from emloyers where salary < 80000 insert salary = salary * 1.2
- F) insert salary = salary * 1.2 where salary < 80000; update

**Ответ: D**

**20.** Вывести список студентов 2,3,4-курсов или специальности «Туризм»

- A) select name from stud where speciality = Tourism or course > '1'
- B) select name from stud where speciality = 'Tourism' and course > 1
- C) select name from stud where speciality = 'Tourism' or course > '1'
- D) select name from stud where speciality = 'Tourism'; select name from stud where course > 1
- E) select name from stud where speciality = Tourism and course > 1
- **F) select name from stud where speciality = 'Tourism' or course > 1** ✅

**Ответ: F**

## Вариант 2

**1.** Обозначение трехуровневой архитектуры

- **A) уровень пользовательского интерфейса** ✅
- B) уровень масштабируемости
- **C) уровень реализации прикладных алгоритмов и средств обработки данных** ✅
- D) уровень соединения
- E) уровень получения данных
- **F) СУБД, в которой хранятся данные** ✅
- G) уровень присваивания
- H) уровень отправки

**Ответ: A, C, F**

**2.** Операции соединения в реляционной алгебре

- **A) естественное соединение** ✅
- **B) тета соединение** ✅
- C) условное соединение
- D) результативное соединение
- **E) внешнее соединение** ✅
- F) альфа соединение

**Ответ: A, B, E**

**3.** Операция над множествами: Set{1,2,3,4,5} union Set{1,3,4,8,9}

- A) {8,9}
- **B) {1,2,3,4,5,8,9}** ✅
- C) {2,8,9}
- **D) {8,9,5,4,1,2,3}** ✅
- E) {1,2,3,4,5,1,3,4,8,9}
- F) {2,5}
- G) {1,3,4}

**Ответ: B, D**

**4.** Основные объекты модели данных RDF

- A) запрос
- B) параметры
- **C) свойство** ✅
- **D) ресурс** ✅
- E) таблица
- F) ячейка
- **G) связь** ✅
- H) типы данных

**Ответ: C, D, G**

**5.** Ключ, который используется для создания уникальных идентификаторов строк и содержит смысл сам по себе

- A) уникальный
- B) составной
- **C) естественный** ✅
- D) простой
- E) суррогатный
- F) искусственный
- G) вторичный
- H) внешний

**Ответ: C**

**6.** Агрегирующая функция AVG

- A) позволяет упорядочить выбранные записи только в порядке убывания (DESC)
- **B) возвращает усредненное значение в указанном столбце** ✅
- C) возвращает количество значений в указанном столбце
- D) позволяет упорядочить выбранные записи только в порядке возрастания (ASC)
- E) возвращает сумму значений в указанном столбце
- F) возвращает максимальное значение в указанном столбце

**Ответ: B**

**7.** К операциям управления данных относится

- A) описание атрибутов приложения
- B) интеграция мета данных
- C) указание ограничения целостности и защиты
- **D) вставка в базу данных новых записей** ✅
- **E) модификация сведений, хранимых в базе данных** ✅
- F) обозначение системного каталога

**Ответ: D, E**

**8.** Запрос, который выбирает поля, где column1 не содержит значения от 1 до 3 включительно

- A) select * from table where column1 =1 and 3
- B) select * from table where column1< =1 or column1 > 3
- **C) select * from table where column1 not in (1,2,3)** ✅
- **D) select * from table where column1 not between 1 and 3** ✅
- E) select * from table where column1<1 and column1>3
- **F) select * from table where column1!=1 and column1!=2 and column1!=3** ✅
- G) select * from table where column1=1 and column1=2 and column1=3
- H) select * from table where column1=1 or column1=2 or column1=3

**Ответ: C, D, F**

**9.** Запрос, сортирующий сотрудников по длине их имени и фамилии вместе взятых в порядке возрастания (last_name-фамилия, first_name –имя, – атрибуты таблицы table)

- A) select last_name, first_name from table order by length(last_name) + length(first_name) desc
- **B) select last_name, first_name from table order by length(concat(last_name, first_name))** ✅
- C) select last_name, first_name from table order by last_name +first_name
- **D) select last_name, first_name from table order by length(last_name) + length(first_name)** ✅
- E) select last_name, first_name from table order by last_name ,first_name
- F) select last_name, first_name from table order by last_name ,length(first_name)

**Ответ: B, D**

**10.** Запрос, сортирующий сотрудников по последней букве фамилии в порядке (z to a)

- A) select last_name from table order by substr(last_name,1,-1) asc
- B) select last_name from table order by instr(last_name,-1,1) desc
- C) select last_name from table order by last_name[-1]
- D) select last_name from table sort by substr(last_name,-1,-1)
- **E) select last_name from table order by substr(last_name,-1,1) desc** ✅
- F) select last_name from table order by last_name desc
- G) select last_name from table sort by instr(last_name,-1,1) desc

**Ответ: E**

**11.** Оператор SELECT

- **A) выполняет выборки и отображении данных одной или более таблиц базы данных** ✅
- B) определение имен используемой таблицы или нескольких таблиц
- C) предназначен для добавления данных в таблицу
- D) предназначен для модификации уже помещенных в таблицу данных
- E) упорядочить выбранные записи в порядке возрастания (ASC) или убывания (DESC) значений любого столбца или комбинации столбцов
- F) возвращает сумму значений в указанном столбце

**Ответ: A**

**12.** DDL команда создания индекса

- A) create or replace index idx on table1;
- **B) create index idx on table1(column1);** ✅
- C) create or replace index idx on column1 of table1;
- D) create or replace index idx on table1(column1);
- E) create index idx for table1(column1);
- F) alter index idx on column1 of table1;
- G) create or replace index idx on table1(column1,column2,column3);
- **H) create index idx on table1(column1,column2);** ✅

**Ответ: B, H**

**13.** Автоматическая фиксация данных происходит при обстоятельствах

- A) один sql запрос
- **B) происходит одно заявление DCL** ✅
- C) происходит несколько последовательных заявлений DML
- D) происходит два последовательных запроса sql
- E) происходит одно заявление DML
- **F) происходит одно заявление DDL** ✅

**Ответ: B, F**

**14.** Транзакция базы данных состоит из

- A) два последовательных заявления DCL
- B) один оператор DDL
- C) одно заявление DCL
- **D) операторы DML, которые составляют одно последовательное изменение данных** ✅
- E) операторы DML, которые не составляют одно последовательное изменение данных
- F) sql запрос

**Ответ: D**

**15.** SQL является

- A) объектно-ориентированным языком программирования
- B) инструмент обработки медиафайлов
- C) процедурным языком
- **D) стандартным языком определения и манипулирования реляционными базами данных** ✅
- **E) непроцедурным языком, построенным на использовании обычных английских слов (таких как SELECT, INSERT, DELETE)** ✅
- F) процедурным языком, который непредназначен для работы с базами данных
- G) инструмент 3D моделирования

**Ответ: D, E**

**16.** В таблице products есть только 3 продукта. Цена первого продукта 15000, цена второго продукта 30000, третьего 2000. Результат запроса  
select price from products  
where price>all (select 1000 from dual  
UNION  
select 10000 from dual  
UNION  
select 12000 from dual);

- **A) 15000, 30000** ✅
- B) 10000,15000
- C) 2000
- **D) 30000,15000** ✅
- E) 30000
- F) 15000, 2000

**Ответ: A, D**

**17.** В таблице products есть только 3 продукта. Цена первого продукта 15000, цена второго продукта 20000, третьего 2000. Результат запроса  
select price from products  
where price>any (select 1000 from dual  
UNION  
select 30000 from dual  
UNION  
select 12000 from dual);

- A) 15000, 20000
- **B) 20000,15000,2000** ✅
- **C) 2000,20000,15000** ✅
- D) 10000,15000
- E) 20000
- F) 15000, 2000
- **G) 2000,15000,20000** ✅
- H) 2000,20000

**Ответ: B, C, G**

**18.** Проблемы, которые предотвращают уровень изоляции транзакций READ COMMITTED

- **A) грязное чтение** ✅
- B) ложное добавление
- C) потерянное обновление
- D) фантомное удаление
- E) дублирующее чтение
- F) фантомное чтение
- G) повторяющееся чтение
- H) фантомное обновление

**Ответ: A**

**19.** Проблемы при параллельном выполнении транзакций

- **A) грязное чтение** ✅
- **B) потерянное обновление** ✅
- C) дублирующее чтение
- D) фантомное удаление
- E) повторяющееся чтение
- **F) фантомное чтение** ✅
- G) ложное добавление
- H) фантомное обновление

**Ответ: A, B, F**

**20.** Соединение многих отношений в запросе может повлиять на чтение и сделать его чрезмерно медленным. Решение данной проблемы

- A) удаление ненужных данных
- **B) создание материализованного представления** ✅
- C) привести данные в 3 нормальную форму
- D) создание представления
- E) привести данные в 4 нормальную форму
- **F) денормализация** ✅

**Ответ: B, F**

## Вариант 3

**1.** Среда СУБД состоит

- A) только из аппаратного обеспечения (компьютеров) и пользователей
- B) только из аппаратного обеспечения (компьютеров)
- C) только из программного обеспечения
- D) только из пользователей данных
- **E) из аппаратного обеспечения (компьютеров), данных, процедур пользователей** ✅
- F) пользователей и администратора
- G) только из моделей мета данных
- H) только из моделей и данных

**Ответ: E**

**2.** Реляционные операции сравнения

- A) ⊆
- B) <=
- C) ⊇
- **D) <>** ✅
- E) >=
- F) ⊂
- **G) >** ✅
- **H) <** ✅

**Ответ: D, G, H**

> ⚠ Спорный: операциями сравнения являются и <= (B), и >= (E), то есть подходят пять вариантов — но тест допускает не более трёх ответов. Уточнить у преподавателя.

**3.** Типы работы разработчика логической базы данных

- A) абстрагированое и сетевое
- B) системный и сетевое проектирование
- C) логическое и эффективное проектирование
- **D) концептуальное и логическое проектирование** ✅
- E) концептуальное и сетевое проектирование
- F) логическое и сетевое
- G) реляционное и концептуальное проектирование

**Ответ: D**

**4.** Количество атрибутов в таблице называется

- A) кардинальность отношения
- B) n-мерность отношения
- C) ранг отношения
- D) сила отношения
- E) мощность отношения
- **F) степень отношения** ✅

**Ответ: F**

**5.** Ключ, который является первичным в другой таблице, но в текущей таблице служит вспомогательным ключом для связи

- A) естественный ключ
- B) вторичный ключ
- C) суррогатный ключ
- D) первичный ключ
- E) простой ключ
- **F) внешний ключ** ✅
- G) составной ключ
- H) искусственный ключ

**Ответ: F**

**6.** Запрос, который выбирает сумму всех уникальных значений столбца в таблице

- **A) select sum(distinct column) from table;** ✅
- B) select sum(column) from table;
- C) select unique sum(column) from table;
- D) select mean(column) from table;
- E) select sum(column) from table where sum(column) is distinct;
- F) select sum(column) from table group by column;
- G) select column, sum(column) from table;

**Ответ: A**

**7.** Запрос, который выбирает поля, где column1 содержит букву 'a' или 'e'

- A) select * from table where column1 like '%a' and column1 like '%e'
- B) select * from table where column1 consist of('a','e)
- **C) select * from table where column1 like '%a%' or column1 like '%e%'** ✅
- **D) select * from table where instr(column1,'a')>0 or instr(column1,'e')>0** ✅
- E) select * from table where instr(column1,'a')>0 and instr(column1,'e')>0
- F) select * from table where column1 like '%a%' and column1 like '%e%'
- G) select * from table where column1 like 'a' and column1 like 'e'
- H) select * from table where instr(column1,'a')=1 or instr(column1,'e')=1

**Ответ: C, D**

**8.** Запрос, который выбирает поля, где column1 содержит значения от 1 до 3 включительно

- A) select * from table where column1 =1 and 3
- **B) select * from table where column1 between 1 and 3** ✅
- C) select * from table where column1>1 and column1<3
- **D) select * from table where column1 in (1,2,3)** ✅
- E) select * from table where column1> 1 or column1 < 3
- F) select * from table where column1=1 and column1=2 or column1=3
- **G) select * from table where column1=1 or column1=2 or column1=3** ✅
- H) select * from table where column1=1 and column1=2 and column1=3

**Ответ: B, D, G**

**9.** Запрос, сортирующий отделы (порядок возрастания) по сумме зарплат сотрудников, работающих там, при подсчете суммы учитывались только зарплаты больше 10000 (department, salary – атрибуты таблицы table)

- A) select department, sum(salary) from table order by last_name desc
- B) select department, sum(salary) from table group by department order by last_name
- C) select department, sum(salary) from table group by department having salary>10000 order by sum(salary)
- **D) select sum(salary), department from table where salary>10000 group by department order by sum(salary) asc** ✅
- **E) select department, sum(salary) from table where salary>10000 group by department order by sum(salary)** ✅
- F) select department, sum(salary) from table group by department order by sum(salary) desc

**Ответ: D, E**

**10.** Запрос, сортирующий отделы по средней арифметической заплаты в порядке возрастания (department, salary – атрибуты таблицы table)

- **A) select department, sum(salary)/count(*) from table group by department order by sum(salary)/count(*) asc** ✅
- **B) select avg (salary) as average, department from table group by department order by avg(salary) asc** ✅
- C) select department, mean (salary) from table group by department order by mean(salary)
- D) select department, avg (salary) from table order by avg(salary) group by department
- E) select department, avg (salary) from table group by department order by avg(salary) desc
- **F) select department, avg (salary) from table group by department order by avg(salary)** ✅

**Ответ: A, B, F**

**11.** Объединение двух таблиц, возвращающих только совпадающие строки из двух таблиц по сопоставленному условию

- A) cross join
- B) left outer join
- C) right outer join
- D) outer join
- E) full outer join
- **F) inner join** ✅

**Ответ: F**

**12.** Цели управления параллельным выполнением в распределенной среде

- A) освобождение всех установленных блокировок
- B) отправить всем участникам команду GLOBAL_ABORT
- **C) устойчивость к отказам на узле и в линиях связи** ✅
- D) поместить в системный журнал запись commit и обеспечить ее принудительную запись из буфера
- E) направить на узлы сообщение о принятом глобальном решении
- **F) отсутствие дополнительных ограничений на структуру** ✅

**Ответ: C, F**

**13.** Подраздел SQL, который используется для добавления данных в базу данных, для изменения существующих данных в базе данных или удаления данных из базы данных

- **A) data manipulation language** ✅
- B) data definition language
- C) data altering language
- D) data control language
- E) transaction control language
- F) mdx
- G) query language
- H) query by example

**Ответ: A**

**14.** Оператор, который завершает текущую транзакцию, отбрасывая все ожидающие изменения данных до предыдущих постоянных данных

- A) rollback to savepoint A
- **B) rollback** ✅
- C) checkpoint
- D) commit A
- E) commit
- F) savepoint A

**Ответ: B**

**15.** Запрос, который выводит название продукта, чья цена выше средней арифметической цены всех продуктов

- A) select price from products where price > (select avg(price) from products)
- B) select product_name from products where price > (select mean(price) from products)
- C) select product_name from products where price >avg(price)
- D) select product_name from products where price in (select avg(price) from products)
- **E) select product_name from products where price > (select sum(price)/count(*) from products)** ✅
- F) select product_name from products where price > (select median(price) from products)
- **G) select product_name from products where price > (select avg(price) from products)** ✅

**Ответ: E, G**

**16.** Оператор DESCRIBE

- **A) передает программе описание столбцов результирующей таблицы** ✅
- **B) предоставляет программе описание входных параметров** ✅
- C) освобождает память от дополнительной информации
- D) указывает на этап обработки данных
- E) отправляет дату и время транзакций
- F) отправляет курсор на дополнительную информацию
- G) выводит адрес ошибки

**Ответ: A, B**

**17.** Операторы сравнения однострочных подзапросов

- **A) >** ✅
- B) all
- **C) <** ✅
- D) in
- **E) =** ✅
- F) some
- G) any

**Ответ: A, C, E**

**18.** Файловый сервер

- A) клиент принимает от пользователя запрос
- B) клиент управляет пользовательским интерфейсом
- **C) большой объем сетевого трафика** ✅
- **D) на каждой рабочей станции должна находиться полная копия СУБД** ✅
- E) управление параллельной работой
- F) клиент управляет пользовательской логикой приложения

**Ответ: C, D**

**19.** Нормализация

- A) включает объединение существующих таблиц в одну большую
- **B) процесс удаления избыточных данных из таблиц для повышения эффективности хранения, целостности данных и масштабируемости** ✅
- **C) процесс преобразования сложных структур данных в простые, стабильные структуры данных** ✅
- D) процесс добавления избыточных данных в таблицы для повышения эффективности хранения, целостности данных и масштабируемости
- E) процесс преобразования простых структур данных в сложные, стабильные структуры данных
- **F) включает разделение существующих таблиц на несколько других, которые могут быть объединены или связаны когда выдается запрос** ✅

**Ответ: B, C, F**

**20.** Аномалии, которые возможны при денормализации

- A) аномалии создания
- B) аномалии объединения
- **C) аномалии обновления** ✅
- D) аномалии соединения
- E) аномалии слияния
- **F) аномалии вставки** ✅
- **G) аномалии удаления** ✅
- H) аномалии поиска

**Ответ: C, F, G**

## Вариант 4

**1.** В таблице данных студентов добавьте в ячейку с номером пять 25 баллов на языке SQL

- A) create student insert 25 where number = 5 ;
- B) enter 25 to grade where number = 5;
- C) insert 25 to number=25;
- D) insert student set grade= grade + 25 where number = 5 ;
- **E) update student set grade= grade + 25 where number = 5 ;** ✅

**Ответ: E**

**2.** На SQL вывести номера, имена и номера отделов работников, служащих в отделах 15, 17, 19

- **A) select number, name, dept_number from emp where dept_number in (15, 17, 19)** ✅
- B) select * from emp where dept_number in (15, 17, 19)
- C) select number, name, dept_number from emp where dept_number order in (15, 17, 19)
- D) select number, name, dept_number from emp where dept_number on (15, 17, 19)
- E) select number, name, dept_number from emp where dept_number between (15, 17, 19)
- **F) select number, name, dept_number from emp where dept_number =15 or dept_number =17 or dept_number = 19)** ✅

**Ответ: A, F**

**3.** Результат выполнения следующей команды  
create table calc (x int, y int);  
insert into calc values (5, 45);  
select *from calc x, y, x+y;

- A) 1
- B) 5, 45
- C) 45
- D) 50
- E) 55
- F) 225
- G) 5
- **H) 5, 45, 50** ✅

**Ответ: H**

**4.** Результат выполнения данной команды на SQL  
create table department (id int, salary int);  
insert into department values (102, 45000);  
insert into department values (103, 15000);  
insert into department values (104, 90000);  
insert into department values (105, 10000);  
Select round (y)

- **A) 40000** ✅
- B) 15000
- C) 160000
- D) 90000
- E) 45000
- F) 10000

**Ответ: A**

**5.** Результат выполнения следующей команды для данной таблицы:  
select name from instructor where dept = 'Physics' order by name;  
  
| name | dept | teacher |  
| Aigerim | Physics | Berikova M.Zh. |  
| Bauyrzhan | Math | Ivanov P.A. |  
| Gulzhan | Physics | Omarova P.E. |  
| Samat | Physics | Erbolova A.S. |

- A) Berikova M.Zh., Erbolova A.S., Ivanov P.A., Omarova P.E.
- B) Physics
- C) Aigerim, Bauyrzhan
- D) Berikova M.Zh., Erbolova A.S., Omarova P.E.
- E) Aigerim, Bauyrzhan, Gulzhan, Samat
- **F) Aigerim, Gulzhan, Samat** ✅

**Ответ: F**

**6.** Результат выполнения следующей команды на SQL  
create table stud (x int, y int);  
insert into stud values (005, 45);  
insert into stud values (006, 70);  
insert into stud values (007, 95);  
insert into stud values (008, 100);  
order by y

- A) 77,5
- **B) 45, 70, 95, 100** ✅
- C) 005, 006, 007, 008
- D) 310
- E) 008, 007, 006, 005
- F) 100, 95, 70, 45

**Ответ: B**

**7.** Возможные варианты ответов следующего кода SQL  
select name from stud where name like 'A%';

- A) Serzhan
- **B) Alibek** ✅
- C) Samal
- D) Serik
- E) Saken
- **F) Aigul** ✅
- **G) Aisulu** ✅
- H) Raimbek

**Ответ: B, F, G**

**8.** Для упорядочивания по алфавиту используется следующая команда

- A) list
- B) join
- C) change from A to Z
- **D) order by** ✅
- E) between A to Z
- F) from A to Z
- G) filter by
- H) filter on

**Ответ: D**

**9.** Результат выполнения следующих операторов SQL  
SELECT NAME, DICSIPLINE  
FROM STUD  
WHERE GRADE <50;

- **A) Akbota, Math** ✅
- B) 40, Akbota, Math
- C) Akbota, Math, 47
- D) Nazgul, Geography, 40
- **E) Nazgul, Geography** ✅
- **F) Batyr, Biology** ✅
- G) Batyr, Biology, 40
- H) Nazgul, Geography, GRADE=40

**Ответ: A, E, F**

**10.** Название таблицы в следующем коде: Insert into data (id, name, table, table2)

- A) insert
- B) нет названия таблицы
- C) id
- D) name
- E) table2
- F) into
- G) table
- **H) data** ✅

**Ответ: H**

**11.** Использование команды SELECT

- A) набор
- B) начало
- C) использование
- D) фильтрация
- E) создание
- **F) отбор** ✅
- G) корреляция
- **H) выбор** ✅

**Ответ: F, H**

**12.** Правильный синтаксис написания кода на SQL

- A) select from students
- **B) select *from data** ✅
- C) select from data
- D) select *data from students
- E) select data*students from
- F) select *stud from data
- G) select from *data
- **H) select data from students** ✅

**Ответ: B, H**

**13.** Команда SQL

- A) realter
- **B) alter** ✅
- C) print
- D) cout
- **E) select** ✅
- F) rechange
- G) change
- H) scanner

**Ответ: B, E**

**14.** Виды операции можно применять к базам данных

- **A) создание** ✅
- **B) удаление** ✅
- C) систематизация
- D) форматирование
- E) оптимизация
- F) сжатие
- G) корреляция
- **H) обновление** ✅

**Ответ: A, B, H**

**15.** Виды строчных данных в работе с БД

- A) unknown
- B) {4,6,8,6,0,10}
- C) true, false
- D) 1, 2.6, 'stud'
- **E) 'stud', 'string'** ✅
- F) 2, 4, 8
- G) null

**Ответ: E**

**16.** Операции, которые нельзя применять к базам данных

- **A) сжатие** ✅
- B) удаление данных
- C) обновление
- **D) оптимизация** ✅
- E) удаление файлов
- F) создание
- G) вставлять данные
- **H) форматирование** ✅

**Ответ: A, D, H**

**17.** Команды, которые не существуют в языке SQL

- A) insert
- B) select
- C) delete
- **D) enter** ✅
- **E) input** ✅
- F) update
- G) create
- **H) start** ✅

**Ответ: D, E, H**

**18.** Названия столбцов в следующем коде: Insert into data (id, name, table)

- A) into
- **B) table** ✅
- **C) name** ✅
- D) insert
- **E) id** ✅
- F) нет названия столбцов
- G) data
- H) insert, into, data, id, name, table

**Ответ: B, C, E**

**19.** Результат выполнения следующих операторов SQL: SELECT ID, NAME, CITY, GROUP FROM STUDENT WHERE GROUP=1;

- A) 6, Erbol, Atyrau, 2
- B) 7, Zhanna, Karaganda, 2
- **C) 5, Almas, Aktau, 1** ✅
- **D) 2, Zhangir, Kostanay, 1** ✅
- E) 2, Edige, Shimkent, 2
- F) Aigul, Kostanay, 1, 2
- **G) 1, Alma, Almaty, 1** ✅
- H) 1, Altyn, Oral, 2

**Ответ: C, D, G**

**20.** Правильный вариант написания запроса на SQL

- A) select *univer, *faculty, *group from students where name= "Alma"
- B) select *univer, faculty, group from students where name= "Alma"
- C) select "univer", "faculty", "group" from "students" where "name"= Alma
- **D) select *from students where name= "Alma"** ✅
- E) select univer, faculty, group from students where "name"= "Alma"
- **F) select univer, faculty, group from students where name= "Alma"** ✅
- G) select univer, faculty, group from students where name= Alma
- H) select "univer", "faculty", "group" from students where "name"= Alma

**Ответ: D, F**

## Вариант 5

**1.** Команда добавления данных в таблицу

- A) UPDATE
- B) GET
- C) DELETE
- D) POST
- E) PUT
- **F) INSERT** ✅

**Ответ: F**

**2.** Агрегатные функции

- **A) AVG** ✅
- B) DELETE
- C) SELECT
- D) WHERE
- **E) MIN** ✅
- F) FROM
- G) UPDATE

**Ответ: A, E**

**3.** В подзапросах оператор IN

- **A) может использоваться с подзапросами** ✅
- B) предназначено для нахождения минимального значения
- C) предназначено для нахождения среднего значения
- D) определяет набор значений предиката, одно из которых не должно совпадать с другим по порядку
- E) не может использоваться с подзапросами
- F) предназначено для нахождения максимального значения
- **G) определяет набор значений предиката, одно из которых должно совпадать с другим по порядку** ✅

**Ответ: A, G**

**4.** Дана таблица Students (ID, Name, Surname, GPA, COURSE):  
1, Yerbol, Kazhigerey, 2.5, 3  
2, Aidana, Khassenova, 3, 2  
3, Marat, Aidosov, 4, 1  
4, Aidos, Kurmanov, 1.4, 4  
5, Elena, Fedorova, 2, 1  
6, Aidar, Elmanov, 3.1, 3  
7, Anna, Karenina, 2.1, 2  
Выберите все результаты следующего SQL запроса  
SELECT ID FROM Students WHERE Name='Aidar';

- A) 1
- B) 5
- C) 2
- D) 3
- E) Kurmanov
- **F) 6** ✅

**Ответ: F**

**5.** Дана таблица STUDENTS (ID, Name, Surname, GPA, COURSE):  
1, Yerbol, Urmanov, 4, 3  
2, Aidana, Ashirbekova, 4, 3  
3, Marat, Aidosov, 4, 1  
4, Aidos, Kurmanov, 1.4, 4  
5, Elena, Fedorova, 2, 1  
6, Aidar, Elmanov, 3.1, 3  
7, Gaukhar, Khassenova, 2.9, 4  
Выберите правильный SQL запрос, который для каждого курса (COURSE) определяет наименьший GPA

- A) SELECT COURSE, MAX(COURSE) FROM STUDENTS GROUP BY COURSE;
- B) SELECT COURSE, MIN(COURSE) FROM STUDENTS GROUP BY COURSE;
- C) SELECT * FROM STUDENTS GROUP BY COURSE;
- D) SELECT COURSE, MAX(GPA) FROM STUDENTS GROUP BY COURSE;
- E) SELECT * FROM STUDENTS;
- **F) SELECT COURSE, MIN(GPA) FROM STUDENTS GROUP BY COURSE;** ✅

**Ответ: F**

**6.** Операция сокращения в реляционной базе данных

- A) извлекает определенны столбцы из таблицы
- B) удаляет столбцы
- C) удаляет строки
- **D) извлекает указанные строки из таблицы** ✅
- **E) делает выборку строк** ✅
- F) осуществляет выборку столбцов из таблицы
- G) осуществляют комбинацию двух таблиц

**Ответ: D, E**

**7.** Правильные утверждения касательно предикатов включающие подзапросы

- A) предикаты не связаны с подзапросами
- **B) предикаты включающие подзапросы используют конструкцию <выражение> <оператор> <подзапрос>** ✅
- C) в этом контексте отсутствуют правила
- **D) предикаты с подзапросами являются необратимыми** ✅
- E) предикаты с подзапросами не являются необратимыми
- F) предикаты включающие подзапросы используют конструкцию <подзапрос> <оператор> <выражение>
- G) предикаты включающие подзапросы используют конструкцию <подзапрос> <оператор> <подзапрос>

**Ответ: B, D**

**8.** Денормализация предполагает

- **A) наличие повышенной избыточности данных** ✅
- B) повышенное количество запросов фильтрации
- C) повышенное количество запросов поиска
- D) пониженное количество данных
- **E) пониженное количество запросов фильтрации** ✅
- **F) пониженное количество запросов поиска** ✅

**Ответ: A, E, F**

**9.** Предикат это

- A) операнд
- B) информация
- C) дерево
- **D) функция с истинностными значениями, которая, как и все функции, имеет ряд формальных параметров** ✅
- E) параметр
- F) оператор

**Ответ: D**

**10.** Операторы, которых можно использовать в подзапросах

- A) having
- B) BETWEEN
- C) LIKE
- D) group by
- **E) ANY** ✅
- F) IS NULL
- **G) IN** ✅

**Ответ: E, G**

**11.** Дана таблица Students (ID, Name, Surname, GPA, COURSE). Выберите правильно написанные SQL запросы использующие group by

- **A) SELECT COURSE, MIN(GPA) FROM STUDENTS GROUP BY COURSE;** ✅
- B) SELECT COURSE, WHICH(GPA) FROM STUDENTS GROUP BY COURSE;
- C) SELECT COURSE, MIN(GPA) FROM STUDENTS GROUPING BY COURSE;
- D) SELECT COURSE, MAX(GPA) FROM STUDENTS GROUPING BY COURSE;
- **E) SELECT COURSE, AVG(GPA) FROM STUDENTS GROUP BY COURSE;** ✅
- F) SELECT WHO(COURSE), MAX(GPA) FROM STUDENTS GROUP BY COURSE;
- G) SELECT WHICH(COURSE), MAX(GPA) FROM STUDENTS GROUP BY COURSE;
- **H) SELECT COURSE, MAX(GPA) FROM STUDENTS GROUP BY COURSE;** ✅

**Ответ: A, E, H**

**12.** Нормальная форма, где первичный ключ (целиком) должен описывать каждый неключевой атрибут, какая то часть первичного ключа отдельно не должна описывать каждый неключевой атрибут, но где возможны зависимости одних неключевых атрибутов от других.

- A) 4NF
- B) 5NF
- C) 6NF
- **D) 2NF** ✅
- E) 3NF
- F) 1NF

**Ответ: D**

**13.** Абстракная машина доступа к данным, с которой взаимодействует пользователь

- A) строки
- B) запросы
- C) деревья
- D) столбцы
- **E) модель данных** ✅
- F) группа данных

**Ответ: E**

**14.** Правильно написанные SQL команды для изменения данных в таблице

- A) CHANGE Students SET COURSE = 4 WHERE ID = 1;
- B) UPDATE Students ASSIGN COURSE = 4 WHERE ID = 1;
- **C) UPDATE Students SET COURSE = 2 WHERE ID = 1;** ✅
- **D) UPDATE Students SET COURSE = 4 WHERE ID = 1;** ✅
- E) CHANGE Students SET COURSE = 4 WHERE ID = 5;
- F) UPDATE Students ATTACH COURSE = 4 WHERE ID = 1;
- G) UPDATE Students SET COURSE = 4 WHICH ID = 1;

**Ответ: C, D**

**15.** Оно используется для объединения таблиц

- A) WHICH
- B) ALTER
- C) WHY
- D) CONNECT
- E) CREATE
- **F) JOIN** ✅

**Ответ: F**

**16.** Переменная отношения R находится в третьей нормальной форме тогда и только тогда, когда для каждой функциональной зависимости X → A в переменной отношения R верно по крайней мере одно из следующих утверждений

- A) X входит в состав некоторого потенциального ключа переменной отношения R
- B) X не входит в состав некоторого потенциального ключа переменной отношения R
- **C) Подмножество X является суперключом переменной отношения R** ✅
- **D) Атрибут A входит в состав некоторого потенциального ключа переменной отношения R** ✅
- E) Атрибут A не входит в состав некоторого потенциального ключа переменной отношения R
- F) Подмножество X не включает атрибут A (т.е. данная ФЗ тривиальна)
- G) Подмножество X не является суперключом переменной отношения R
- **H) Подмножество X включает атрибут A (т.е. данная ФЗ тривиальна)** ✅

**Ответ: C, D, H**

**17.** Аксиомы Армстронга в контексте функциональных зависимостей

- A) образность
- B) серийность
- C) параллельность
- **D) рефлексивность** ✅
- E) балансированность
- **F) дополнение** ✅
- **G) транзитивность** ✅
- H) интеграция

**Ответ: D, F, G**

**18.** Метод сущность-связь называют также методом

- A) EA-диаграмм
- B) AE-диаграмм
- C) EE-диаграмм
- D) RR-диаграмм
- E) EZ-диаграмм
- **F) ER-диаграмм** ✅

**Ответ: F**

**19.** Дана таблица Students (ID, Name, Surname, GPA, COURSE):  
1, Yerbol, Kazhigerey, 2.5, 3  
2, Aidana, Khassenova, 3, 2  
3, Marat, Aidosov, 4, 1  
4, Aidos, Kurmanov, 1.4, 4  
5, Elena, Fedorova, 2, 1  
6, Aidar, Elmanov, 3.1, 3  
7, Anna, Karenina, 2.1, 2  
Выберите все результаты следующего SQL запроса  
SELECT Name FROM Students WHERE ID=1 OR ID=2;

- **A) Yerbol** ✅
- B) 3
- C) Karenina
- D) Aidar
- E) 5
- F) 4
- **G) Aidana** ✅

**Ответ: A, G**

**20.** Для того чтобы изменить данные в таблицы используется команда

- A) CREATE
- **B) UPDATE** ✅
- C) ATTACH
- D) ALTER
- E) DROP
- F) USE

**Ответ: B**

## Вариант 6

**1.** В этих контекстах может использоватся команда UPDATE

- **A) для изменения данных в таблицах** ✅
- **B) совместно с вложенными запросами** ✅
- C) для выделения первичного ключа в таблице
- D) при назначении первичного ключа
- E) при изменении ограничений в таблице
- F) для удаления таблицы
- G) для выборки данных

**Ответ: A, B**

**2.** Формальные параметры следующего предиката "Работник работает в отделе DEPT на позиции POSITION и получает зарплату SALARY" (слова со всеми заглавными буквами являются столбцами в таблице)

- **A) SALARY** ✅
- B) работает
- **C) DEPT** ✅
- D) Работник
- E) получает
- **F) POSITION** ✅
- G) зарплату
- H) отделе

**Ответ: A, C, F**

**3.** Нормальная форма, где первичный ключ (целиком) должен описывать каждый неключевой атрибут, какая то часть первичного ключа отдельно не должна описывать каждый неключевой атрибут, где нет зависимостей одних неключевых атрибутов от других и ключевые атрибуты не должны зависеть от неключевых

- **A) BCNF** ✅
- B) 6NF
- C) 4NF
- D) 1NF
- E) 5NF
- F) 2NF
- G) 7NF
- H) 3NF

**Ответ: A**

**4.** Дана таблица Students (ID, Name, Surname, GPA, COURSE):  
1, Yerbol, Urmanov, 2.5, 3  
2, Aidana, Ashirbekova, 3, 3  
3, Marat, Aidosov, 4, 1  
4, Aidos, Kurmanov, 1.4, 4  
5, Elena, Fedorova, 2, 1  
6, Aidar, Elmanov, 3.1, 3  
7, Gaukhar, Khassenova, 2.9, 4  
Выберите все результаты следующих SQL запросов  
UPDATE Students SET COURSE = 4 WHERE ID = 1;  
SELECT Name, Course where ID = 1;

- A) Aidana, 2
- B) Yerbol, 3
- C) Yerbol, 1
- D) Aidana, 4
- E) Yerbol, 2
- **F) Yerbol, 4** ✅

**Ответ: F**

**5.** SQL запросы использующие агрегатные функции

- A) SELECT * FROM USP WHERE SNUM=4
- **B) SELECT SNUM, AVG (OCENKA) FROM USP GROUP BY SNUM;** ✅
- **C) SELECT SNUM, MIN (OCENKA) FROM USP GROUP BY SNUM;** ✅
- D) SELECT * FROM USP
- E) SELECT * FROM USP WHERE SNUM=5
- F) SELECT * FROM USP WHERE SNUM=3
- G) SELECT SNUM FROM USP
- **H) SELECT SNUM, MAX (OCENKA) FROM USP GROUP BY SNUM;** ✅

**Ответ: B, C, H**

**6.** Основные сложности денормализации

- A) усложняет запросы группировки
- B) усложняет запросы создания таблиц
- C) усложняет запросы удаления таблиц
- D) усложняет запросы поиска
- E) усложняет запросы фильтрации
- **F) создает проблемы избыточности и аномалии обновления** ✅
- **G) сложно понять, когда ее закончить** ✅

**Ответ: F, G**

**7.** Правильно написанные SQL запросы использующие объединения таблиц

- **A) SELECT b.*, p.* FROM Branch1 b LEFT JOIN PropertyForRent1 p ON b.bCity = p.pCity;** ✅
- B) SELECT b.*, p.* FROM Branch1 b WHICH FULL JOIN PropertyForRent1 p ON b.bCity = p.pCity;
- C) SELECT b.*, p.* FROM Branch1 b CONNECT FULL JOIN PropertyForRent1 p ON b.bCity = p.pCity;
- D) SELECT b.*, p.* FROM Branch1 b CONNECT RIGHT JOIN PropertyForRent1 p ON b.bCity = p.pCity;
- E) SELECT b.*, p.* FROM Branch1 b CONNECT LEFT JOIN PropertyForRent1 p ON b.bCity = p.pCity;
- **F) SELECT b.*, p.* FROM Branch1 b RIGHT JOIN PropertyForRent1 p ON b.bCity = p.pCity;** ✅
- G) SELECT b.*, p.* FROM Branch1 b WHICH LEFT JOIN PropertyForRent1 p ON b.bCity = p.pCity;

**Ответ: A, F**

**8.** Команды DDL

- A) PUT
- **B) DROP** ✅
- **C) CREATE** ✅
- **D) ALTER** ✅
- E) INSERT
- F) DELETE
- G) GET
- H) UPDATE

**Ответ: B, C, D**

**9.** Дана таблица Students (ID, Name, Surname, GPA, COURSE):  
1, Yerbol, Urmanov, 2.5, 3  
2, Aidana, Ashirbekova, 3, 3  
3, Marat, Aidosov, 4, 1  
4, Aidos, Kurmanov, 1.4, 4  
5, Elena, Fedorova, 2, 1  
6, Aidar, Elmanov, 3.1, 3  
7, Gaukhar, Khassenova, 2.9, 4  
Выберите все результаты следующего SQL запроса  
SELECT ID FROM Students ORDER BY GPA ASC LIMIT 1;

- **A) 4** ✅
- B) 2
- C) 0
- D) 2.5
- E) 1.4
- F) 3

**Ответ: A**

**10.** Дана таблица Students (ID, Name, Surname, GPA, COURSE):  
1, Yerbol, Kazhigerey, 2.5, 3  
2, Aidana, Khassenova, 3, 2  
3, Marat, Aidosov, 4, 1  
4, Aidos, Kurmanov, 1.4, 4  
5, Elena, Fedorova, 2, 1  
6, Aidar, Elmanov, 3.1, 3  
7, Anna, Karenina, 2.1, 2  
Выберите все результаты следующего SQL запроса  
SELECT ID FROM Students WHERE Name='Yerbol' OR Name='Aidana';

- A) 4
- B) Aidosov
- C) 3
- D) Marat
- **E) 1** ✅
- **F) 2** ✅
- G) None

**Ответ: E, F**

**11.** В символической записи функциональной зависимости правильные следующие утверждения

- **A) правая часть символической записи функциональной зависимости является зависимостью** ✅
- B) правая часть символической записи функциональной зависимости является двоичностью
- **C) левая часть символической записи функциональной зависимости является детерминантом** ✅
- D) правая часть символической записи функциональной зависимости является детерминантом
- E) правая часть символической записи функциональной зависимости является независимостью
- F) левая часть символической записи функциональной зависимости является зависимостью
- G) левая часть символической записи функциональной зависимости является двоичностью

**Ответ: A, C**

**12.** Основные виды операций над таблицей в реляционной базе данных

- **A) соединение** ✅
- B) создание прокси запросов
- C) интеграция
- D) безопасность
- **E) сокращение** ✅
- **F) проекция** ✅
- G) защита
- H) балансировка

**Ответ: A, E, F**

**13.** Дана таблица Students (ID, Name, Surname, GPA, COURSE):  
1, Yerbol, Kazhigerey, 2.5, 3  
2, Aidana, Khassenova, 3, 2  
3, Marat, Aidosov, 4, 1  
4, Aidos, Kurmanov, 1.4, 4  
5, Elena, Fedorova, 2, 1  
6, Aidar, Elmanov, 3.1, 3  
7, Anna, Karenina, 2.1, 2  
Выберите все ID, которое возвратит следующий SQL запрос  
SELECT ID FROM Students WHERE COURSE=1;

- A) 6
- B) 4
- **C) 5** ✅
- D) 7
- E) 2
- F) 1
- **G) 3** ✅

**Ответ: C, G**

**14.** Операторы позволяют моделировать

- **A) поведение данных в общем плане** ✅
- B) бинарные деревья поиска
- C) контейнеры
- D) двоичные деревья поиска
- E) очереди
- **F) виды поведения данных** ✅
- G) структуру данных

**Ответ: A, F**

**15.** Конструкции, которых нельзя использовать в подзапросах

- A) MAX
- B) IN
- C) AVG
- **D) SELECT *** ✅
- E) WHERE
- **F) BETWEEN** ✅
- G) MIN

**Ответ: D, F**

**16.** То что не относится к агрегатным функциям, используемые в group by

- **A) create** ✅
- B) avg
- C) max
- D) count
- E) min
- **F) which** ✅
- G) sum

**Ответ: A, F**

**17.** Оператор, использовать которого запрещено в подзапросах

- A) min
- B) select
- C) in
- D) where
- **E) having** ✅
- F) avg

**Ответ: E**

**18.** Правила третьей нормальной формы

- **A) неключевые атрибуты (если они вообще существуют) являются взаимно независимыми** ✅
- B) когда обязательно наличие трех первичных ключей
- C) когда обязательно наличие двух внешних ключей
- D) неключевые атрибуты (если они вообще существуют) являются взаимно зависимыми
- E) когда обязательно наличие двух первичных ключей
- **F) неключевые атрибуты (если они вообще существуют) неприводимо зависимы от первичного ключа** ✅
- G) когда обязательно наличие трех внешних ключей

**Ответ: A, F**

**19.** Определите атрибуты в этом предложении "Пожалуйста, назовите фамилию и должность преподавателя."

- A) точка
- **B) должность** ✅
- C) запятая
- D) назовите
- **E) фамилия** ✅
- F) преподаватель
- G) пожалуйста

**Ответ: B, E**

**20.** Последовательность выражения, оператора и подзапроса в контексте предикатов с подзапросами

- A) подзапрос, оператор, выражение
- B) оператор, выражение, подзапрос
- C) выражение, подзапрос, оператор
- **D) выражение, оператор, подзапрос** ✅
- E) подзапрос, выражение, оператор
- F) между ними нет последовательности

**Ответ: D**

## Вариант 7

**1.** Формальная основа реляционной модели БД, основанная на теории множеств

- **A) реляционная алгебра** ✅
- B) логическая алгебра
- C) булева алгебра
- D) операционная алгебра
- E) агрегатная алгебра
- F) иерархическая алгебра

**Ответ: A**

**2.** Виртуальная таблица, содержимое которой определяется запросом

- A) realtable
- B) tempdb
- **C) views** ✅
- D) trigger
- E) resource
- F) stored procedure
- G) virtable

**Ответ: C**

**3.** Тип целостности данных проверяющая правильность связей между таблицами

- **A) ссылочная** ✅
- B) внешняя
- C) семантическая
- D) примарная
- E) верхняя
- F) доменная

**Ответ: A**

**4.** Если задан ORDER BY, то таблица является только считываемой с

- A) выполняющими соединениями двух таблиц
- **B) заданным порядком упорядочения** ✅
- C) изменяющей структурой таблицы
- D) фильтрующими группами столбцов
- E) группирующими строками с одинаковыми значениями столбца
- F) группируемыми строками с одинаковыми значениями столбцов
- G) удаляющими дублирующимися строками из результирующего набора
- H) группирующими строками с одинаковыми значениями столбца или столбцов

**Ответ: B**

**5.** Блокировка фрагмента данных имеет аспекты

- A) транзакции
- B) планировщик
- C) буфер
- **D) режим** ✅
- **E) длительность** ✅
- **F) гранулярность** ✅

**Ответ: D, E, F**

**6.** Недостатки иерархической модели

- A) безопасность данных
- **B) структурная зависимость** ✅
- C) простота понимания структуры данных
- D) каждый узел имеет свое имя (идентификатор)
- **E) ограничения в организации отношений между сущностями** ✅
- F) независимость данных
- G) целостность данных

**Ответ: B, E**

**7.** Отсортировать документы по типу и дате создания

- A) ORDER BY Type Documents, CreationDate DESCENDING
- B) ARRANGE BY Documents Type, CreationDate DESC
- **C) ORDER BY DocumentsType, CreationDate DESC** ✅
- **D) ORDER BY DocumentsType, CreationDate** ✅
- **E) ORDER BY DocumentsType, CreationDate ASC** ✅
- F) SORT Documents BY Type, CreationDate DESC

**Ответ: C, D, E**

**8.** Выборка строк с неопределенным значением в столбце

- A) SELECT * FROM VENDORS WHERE VENDOR IN ('Asus', 'Intel', 'IBM');
- B) SELECT * FROM deliveries ORDER BY amount IS NOT NULL;
- **C) SELECT * FROM goodslist WHERE weight IS NULL;** ✅
- D) SELECT * FROM VENDORS ORDER BY VENDOR IN ('Asus', 'Intel', 'IBM');
- E) SELECT * FROM deliveries WHERE amount IS NOT NULL;
- F) SELECT * FROM Asus WHERE VENDOR IS NULL;
- G) SELECT * FROM goodslist ORDER BY weight IS NULL;
- **H) SELECT * FROM deliveries WHERE amount IS NULL;** ✅

**Ответ: C, H**

**9.** Поле представления может содержать агрегированную информацию

- A) group
- B) acs
- **C) max** ✅
- **D) sum** ✅
- **E) min** ✅
- F) decs

**Ответ: C, D, E**

**10.** Реляционная модель определяется понятиями

- A) указатели
- **B) кардинальность** ✅
- C) древовидный граф
- **D) атрибут** ✅
- E) ссылочный аппарат
- F) коллекция записей
- G) навигационный подход

**Ответ: B, D**

**11.** Основные уровни-компоненты SQL Server

- A) Server Profiler
- B) Integration Services
- C) ODBCAPI
- **D) In-Memory OLTP Engine** ✅
- E) Sockets Layer
- **F) Query Processor** ✅
- **G) Storage Engine** ✅
- H) Reporting Services

**Ответ: D, F, G**

**12.** Выбрать все категории товаров, для которых суммарное количество заказов больше 10

- A) SELECT * FROM categories WHERE category id IN (SELECT category_id FROM products WHERE product_id IN (SELECT product_id FROM orders GROUP BY product_id HAVING COUNT() > 10));
- B) SELECT * FROM categories WHERE category_id IN (SELECT category_id FROM orders WHERE COUNT() == 10);
- C) SELECT * FROM categories WHERE category_id IN (SELECT category_id FROM products INNER JOIN orders ON products.product_id = orders.product_id WHERE COUNT() < 10);
- **D) SELECT * FROM categories WHERE category_id IN (SELECT category_id FROM products INNER JOIN orders ON products.product_id = orders.product_id GROUP BY category_id HAVING COUNT() > 10);** ✅
- E) SELECT * FROM categories, category_id IN (SELECT category id FROM products WHERE product_id IN (SELECT product_id FROM orders GROUP BY product_id) AND COUNT() > 10);
- F) SELECT * FROM categories WHERE category_id IN (SELECT category_id FROM orders GROUP BY category_id HAVING COUNT() = 10);

**Ответ: D**

**13.** Рекомендуемые параметры оценки системы управления базами данных с точки зрения определение данных

- A) простота реорганизации
- B) поддержка контрольных точек
- **C) предусмотренные файловые структуры** ✅
- D) расширенная поддержка первичных ключей
- **E) определение внешних ключей** ✅
- F) поддержка определения файловых структур
- **G) предусмотренные типы данных** ✅

**Ответ: C, E, G**

**14.** Выбрать все продукты, которые не были заказаны

- **A) SELECT * FROM products WHERE product_id NOT IN (SELECT product_id FROM orders GROUP BY product_id);** ✅
- B) SELECT * FROM products WHERE product_id NOT EXISTS (SELECT DISTINCT product_id FROM orders);
- C) SELECT * FROM products WHERE productId NOT EXISTS (SELECT productId FROM orders);
- D) SELECT * FROM products WHERE product_id NOT IN (SELECT product_id FROM orders HAVING COUNT(*) > 0);
- **E) SELECT * FROM products WHERE product_id NOT IN (SELECT DISTINCT product_id FROM orders);** ✅
- F) SELECT * FROM product WHERE product_id NOT IN (SELECT DISTINCT product_id FROM order);
- G) SELECT * FROM products WHERE productId NOT IN (SELECT DISTINCT productId FROM orders);

**Ответ: A, E**

**15.** Является системным экземпляром сервера, хранит информацию о конфигурации сервера, сведения обо всех учетных записях пользователя, сведения обо всех остальных базах данных

- A) msdb
- B) model
- C) odbc
- **D) master** ✅
- E) tempdb
- F) resource

**Ответ: D**

**16.** Количество полей (столбцов) в реляционной модели

- A) атрибут
- B) отношение
- C) кардинальность
- D) ссылки
- E) домен
- **F) степень отношения** ✅
- G) первичный ключ
- H) кортеж

**Ответ: F**

**17.** Не относится к агрегирующим функциям

- A) SUM
- B) MAX
- **C) ALL** ✅
- D) COUNT
- E) MIN
- F) AVG
- **G) ANY** ✅
- **H) ASC** ✅

**Ответ: C, G, H**

**18.** Вильям Армстронг предложил дополнительные полезные правила вывода, которые могут быть получены на основании правил: дополнение, рефлексивность, приращение, транзитивность

- A) слияние
- B) подмножество
- **C) декомпозиция** ✅
- **D) объединение** ✅
- **E) псевдотранзитивность** ✅
- F) репликация

**Ответ: C, D, E**

**19.** Этап проектирования БД который включает в себя инфологическое и даталогическое проектирования

- A) концептуальное проектирование
- B) системный анализ
- **C) логическое проектирование** ✅
- D) аномалия модификации
- E) физическое проектирование
- F) функциональное проектирование
- G) архитектурное проектирование

**Ответ: C**

**20.** Исправление значений в двух столбцах таблицы

- A) DELETE FROM SUPPLIERS WHERE CURRENT OF SUPPLIERS_CURSOR
- **B) UPDATE ENAME SET FNAME='JON', LNAME='JONS' WHERE ENAME_ID=67;** ✅
- **C) UPDATE GOODSLIST SET WEIGHT=100, GROSSWEIGHT=110 WHERE GOODSLIST_ID=2567;** ✅
- D) CREATE DATABASE 'WAREHOUSE';
- **E) UPDATE SUPPLER SET STATUS=100, CITY=110 WHERE SUPPLER_ID=25;** ✅
- F) CREATE DOMAIND_DATE AS DATE DEFAULT current_date;
- G) DELETE TABLE PEOPLES (IndNum int, Surname char(30), FName char(20), LName char(20), BDay date);
- H) REMOVE DATABASE 'WAREHOUSE';

**Ответ: B, C, E**

---

# Русская версия — Алгоритмы и структуры данных

## Вариант 1

**1.** Результат следующего кода: Int x=5; Alert(«x равен » +x)

- A) x равен 6
- B) x равен 1
- C) x равен 0
- D) x равен 9
- **E) x равен 5** ✅

**Ответ: E**

**2.** Обязательные свойства каждой переменной

- A) размер
- B) тип, размер, спецификатор знака
- C) спецификатор знака
- D) тип
- **E) тип, размер, имя, значение** ✅

**Ответ: E**

**3.** Изменение управляющей переменной в цикле от 20 до 2 с шагом -2

- A) for (int i = 20; i >=2; i =- 2)
- B) for (int i = 20; i >2; i -= 2)
- **C) for (int i = 20; i >=2; i -= 2)** ✅
- D) for (int i = 20; i <=2; i -= 2)
- E) for (int i = 2; i >=20; i -= 2)

**Ответ: C**

**4.** Результат операции  
int x=1, y=2, z=3;  
int a=x+y-2/2+z;  
cout<<a<<endl;

- A) 3.5
- B) 3
- C) 4
- D) 1
- **E) 5** ✅

**Ответ: E**

**5.** Оператор следующей блок-схемы (counter = 1; проверка counter<=10; тело цикла cout << counter; изменение counter++)

- A) do/while
- B) if
- C) if/else if
- **D) for** ✅
- E) if/else

**Ответ: D**

**6.** Дан фрагмент кода:  
int a=1234;  
int i=0;  
while(a){  
i++;  
a/=10;  
}  
Cout<<i<<endl;  
Вывод программы

- A) 1234
- B) 3
- **C) 4** ✅
- D) 5
- E) 10

**Ответ: C**

**7.** Оператор используемый для выполнения условия

- **A) if** ✅
- B) goto
- C) tnen
- D) else
- E) run

**Ответ: A**

**8.** Объект в Java создается с указанием имени класса ключевым словом

- **A) new** ✅
- B) begin
- C) load
- D) program
- E) start

**Ответ: A**

**9.** Имена всех элементов массива второй строки целых чисел t размером 3 на 4 записываются следующим образом

- **A) t[1][0], t[1][1], t[1][2], t[1][3]** ✅
- B) t[1,0], t[1,1], t[1,2], t[1, 3]
- C) t[2,1], t[2,2], t[2,3], t[2,4]
- D) t[2][1], t[2][2], t[2][3], t[2][4]
- E) t[2][0], t[2][1], t[2][2], t[2][3]

**Ответ: A**

**10.** Заголовочный файл, содержащий макросы и информацию для дополнительной диагностики, помогающей при отладке программы

- A) <errno.h>
- B) <signal.h>
- C) <limits.h>
- **D) <assert.h>** ✅
- E) <setjmp.h>

**Ответ: D**

**11.** Результат выполнения оператора x = pow(2, 7) будет равен

- **A) 128** ✅
- B) 255
- C) 64
- D) 256
- E) 127

**Ответ: A**

**12.** Вставка элемента в неупорядоченный массив

- A) требует сдвига других элементов для освобождения места
- B) требует нескольких сравнений
- **C) выполняется за постоянное время независимо от количества элементов** ✅
- D) требует лишнее время
- E) выполняется за время, пропорциональное размеру массива

**Ответ: C**

**13.** bool Func(A,x)  
Цикл по j, j←1, j<n, j←j+1  
if(Ai==x)  
then return true;  
return false;

- A) сортировка вставкой
- **B) линейный поиск** ✅
- C) двоичный поиск
- D) пузырьковая сортировка
- E) сортировка кучей

**Ответ: B**

**14.** Разбиением массива называется

- **A) деление элементов массива на несколько групп** ✅
- B) последовательная сортировка
- C) удаление одного элемента массива
- D) сортировка вставкой
- E) сортировка массива пузырьком

**Ответ: A**

**15.** Ш1 [Цикл по i]. COUNT[i]←0, i←1 to N  
Ш2 [Цикл по i]. Выполнить шаг 3(Ш3) i←N downto 2  
Ш3 [Цикл по j]. Выполнить шаг 4(Ш4) j←i-1 downto 1  
Ш4 if Ki<Kj then COUNT[j]++ else COUNT[i]++

- A) сортировка вставкой
- B) двоичный поиск
- **C) алгоритм подсчета сравнений** ✅
- D) быстрая сортировка
- E) поразрядная сортировка

**Ответ: C**

**16.** Сложность сортировки вставкой

- A) O(n)
- **B) O(n²)** ✅
- C) O(n!)
- D) O(eˣ)
- E) O(nlogn)

**Ответ: B**

**17.** Сложность сортировки слиянием

- **A) O(n logn)** ✅
- B) O(1)
- C) O(n³)
- D) O(logn)
- E) O(n²)

**Ответ: A**

**18.** В языке Си при формировании программы вы будете использовать следующие «строительные блоки» (неправильный ответ)

- **A) функции, сохранённые другим пользователем** ✅
- B) функции, которые были использованы ранее
- C) функции стандартной библиотеки Си
- D) функции, написанные другими людьми
- E) функции, которые вы создадите сами

**Ответ: A**

**19.** Структура данных типа LIFO известна как

- A) множество
- B) список
- C) массив
- **D) стек** ✅
- E) очередь

**Ответ: D**

**20.** Выберите правильную запись обращения к элементу одномерного массива в языке Си

- A) b[2,3]
- **B) b[3]** ✅
- C) b(2,3)
- D) b[1,2]
- E) b[1]

**Ответ: B**

**21.** Присоединение содержимого одной строки к другой строке осуществляется с помощью функции

- A) strlen()
- **B) strcat()** ✅
- C) strlength()
- D) strcpy;
- E) strcmp()

**Ответ: B**

**22.** Внешний внук

- A) является верхним потомком правого потомка (или наоборот)
- B) является левым потомком правого потомка (или наоборот)
- C) находится на противоположной стороне от своего родителя, чем его «брат» по отношению к их «предкам»
- **D) находится на той же стороне от своего родителя, что и его родитель по отношению к своему родителю** ✅
- E) находится на другой стороне от своего родителя, чем его родитель по отношению к своему «брату»

**Ответ: D**

**23.** Процедура поиска пустых ячеек, находящихся на больших расстояниях (вместо ячеек, находящихся вблизи от исходной позиции хеширования) при решении коллизии, известна как

- A) линейное пробирование
- B) открытая адресация
- **C) двойное хеширование** ✅
- D) метод цепочек
- E) квадратичное пробирование

**Ответ: C**

**24.** Пример обобщенного алгоритма

- A) 2x+3=0
- B) 5x⁴+2x=0
- C) 5x²=0
- **D) ax²+bx+c=0** ✅
- E) 6x³=0

**Ответ: D**

**25.** Время поиска в AVL-дереве

- A) O(N²)
- B) O(N)
- C) O(N³)
- D) O(N logN)
- **E) O(logN)** ✅

**Ответ: E**

**26.** Программа это

- A) алгоритм который переведенный к природному языку
- B) блок-схема
- C) устройство
- D) указания данное к пользователю
- **E) алгоритм на понятном языке для компьютера** ✅

**Ответ: E**

**27.** Вид алгоритма вычисления многочленов

- A) разветвляющий
- **B) циклический** ✅
- C) дополнительный
- D) условный
- E) линейный

**Ответ: B**

**28.** Алгоритм, решающий задачу о кратчайших путях из одной вершины для взвешенного ориентированного графа G=(V,E) исходной вершиной s, в котором веса всех ребер неотрицательны

- A) алгоритм Прима
- **B) алгоритм Дейкстры** ✅
- C) алгоритм Крускала
- D) алгоритм Белмана-Форда
- E) алгоритм Флойд-Уоршолла

**Ответ: B**

**29.** Последний узел пирамиды

- A) всегда находится на среднем уровне
- B) всегда является левым потомком
- C) никогда не бывает меньше своего «брата»
- **D) всегда находится на нижнем уровне** ✅
- E) всегда является правым потомком

**Ответ: D**

**30.** Пирамида может быть представлена в виде массива, потому что пирамида

- A) является троичным деревом
- B) не удовлетворяет условию пирамиды
- **C) полная** ✅
- D) является двоичным деревом
- E) обладает слабой упорядоченностью

**Ответ: C**

## Вариант 2

**1.** Правильный пример целого числа

- **A) -11** ✅
- B) -10.6
- C) 3/4
- D) 9.2
- E) 87,6

**Ответ: A**

**2.** Правильный идентификатор на языке программирования С++

- **A) Galina_Pachshenko** ✅
- B) Diana@Kim
- C) Kirill&first
- D) Resul#t
- E) identificator*five

**Ответ: A**

**3.** Операция, устанавливающая биты со значением 1 в 0, а биты со значением 0 в 1

- A) логическое ИЛИ
- B) поразрядное И
- **C) поразрядное НЕ** ✅
- D) логическое НЕ
- E) логическое И

**Ответ: C**

**4.** Объект входного потока данных на языке программирования С++

- A) cout
- B) return
- C) switch
- **D) cin** ✅
- E) do

**Ответ: D**

**5.** Оператор присваивания на языке программирования С++

- A) result
- **B) =** ✅
- C) is
- D) do
- E) ==

**Ответ: B**

**6.** Составная операция умножения

- **A) *=** ✅
- B) =*
- C) *
- D) multiply
- E) +=

**Ответ: A**

**7.** Метод класса string возвращающий количество символов строки на языке программирования С++

- A) eof()
- **B) length()** ✅
- C) get()
- D) data()
- E) max()

**Ответ: B**

**8.** Объявление одномерного массива и инициализация элементов

- A) int a[65, 64, 11, 43, 39, -15 ,-100 ,125, 150, -250];
- **B) int a[10]={65, 64, 11, 43, 39, -15 ,-100 ,125, 150, -250};** ✅
- C) int a[10]="65, 64, 11, 43, 39, -15 ,-100 ,125, 150, -250";
- D) int a[10]=/65, 64, 11, 43, 39, -15 ,-100 ,125, 150, -250/;
- E) int a[10]=65, 64, 11, 43, 39, -15 ,-100 ,125, 150, -250;

**Ответ: B**

**9.** Цикл для ввода элементов двумерного массива на языке программирования С++

- **A) for(int i=0; i<3; i++)for(int j=0; j<3; j++) cin>>a[i][j];** ✅
- B) for(int i=0; i<3; i++)for(int j=0; j<3; j++) cout<<a[i][j];
- C) for(int i=0; i<3; i++)for(int j=0; j<3; j++) cout>>a[i][j];
- D) for(int i=0; j<3; i++)for(int j=0; i<3; j++) cin>>a[i][i];
- E) for(int i=0; i<3; i++)for(int j=0; i<3; i++) cout>>a[i][j];

**Ответ: A**

**10.** На языке программирования С++ функция, генерирующая целое число, лежащее в интервале от 0 до значения RAND_MAX, которое определяется равным по меньшей мере 32767

- A) size
- B) max
- C) stdlib.h
- D) time
- **E) rand** ✅

**Ответ: E**

**11.** Шаг, когда функция вызывает новую копию самой себя, чтобы начать работать над меньшей проблемой

- A) встроенная функция
- B) оператор перехода
- C) копирование
- **D) рекурсивный вызов** ✅
- E) прототип функции

**Ответ: D**

**12.** Встраиваемые функции на языке программирования С++

- A) in
- B) global
- C) static
- **D) inline** ✅
- E) str

**Ответ: D**

**13.** Способ сортировки, при котором сначала выделяется наименьший (или наибольший) элемент и каким-либо образом отделяется от остальных, затем выбирается наименьший (наибольший) из оставшихся и т. д.

- A) сортировка методом вставок
- B) симметричная сортировка
- C) обменная сортировка
- **D) сортировка посредством выбора** ✅
- E) сортировка путем подсчета

**Ответ: D**

**14.** Алгоритм поиска, при котором сравнивается каждый элемент массива с ключом поиска

- A) поиск вставкой
- B) симметричный поиск
- **C) линейный поиск** ✅
- D) радиальный поиск
- E) двончный поиск

**Ответ: C**

**15.** Алгоритм поиска, который исключает половину элементов массива после каждого сравнения

- **A) двоичный поиск** ✅
- B) линейный поиск
- C) симметричный поиск
- D) радиальный поиск
- E) поиск по наименьшему значению

**Ответ: A**

**16.** Количество рекурсивных вызовов, которое должно быть выполнено для вычисления n-го числа Фибоначчи, оказывается порядка O(2ⁿ), называется

- A) константная сложность
- B) квадратичная сложность
- C) кубическая сложность
- **D) экспоненциальная сложность** ✅
- E) линейная сложность

**Ответ: D**

**17.** Квадратичная сложность алгоритма в O-синтаксисе

- A) O(n!)
- B) O(n)
- C) O(2ⁿ)
- D) O(log n)
- **E) O(n²)** ✅

**Ответ: E**

**18.** Метод сортировки со сложностью алгоритма O(n²)

- A) пирамидальный
- **B) пузырковый** ✅
- C) слияния
- D) двоичного дерева
- E) быстрый

**Ответ: B**

**19.** Линейный список, в котором все операции вставки и удаления выполняются на обоих концах списка

- **A) двусторонняя очередь** ✅
- B) стек
- C) вектор
- D) односторонняя очередь
- E) массив

**Ответ: A**

**20.** Чтобы обозначить дно стека, элемент указатель связи последнего узла списка устанавливается в значение

- A) минус единица
- B) end
- C) единица
- D) bottom
- **E) нуль** ✅

**Ответ: E**

**21.** Особый узел, который должен содержать каждый циклический список

- **A) заголовок списка** ✅
- B) нулевой узел
- C) регистратор списка
- D) узел разветвления
- E) корень списка

**Ответ: A**

**22.** Популярный класс методов поиска имеет общее название

- **A) хеширование** ✅
- B) полиморфизм
- C) объявление
- D) присваивание
- E) инициализация

**Ответ: A**

**23.** Разновидности открытой адресации, различающиеся способом поиска следующей свободной ячейки

- **A) линейное пробирование, квадратичное пробирование и двойное хеширование** ✅
- B) линейное пробирование, симметричное пробирование и двойное хеширование
- C) линейное пробирование, полиноминальное пробирование и двойное хеширование
- D) линейное пробирование, линейное пробирование и квадратичное хеширование
- E) линейное пробирование, квадратичное пробирование и тройное хеширование

**Ответ: A**

**24.** Отношение количества элементов данных в хеш-таблице к размеру массива

- A) коэффициент подобия
- B) относительный коэффициент
- **C) коэффициент заполнения** ✅
- D) коэффициент индексации
- E) коэффициент хеширования

**Ответ: C**

**25.** Первым узлом дерева является

- A) произвольно выбранный узел
- B) центральный узел
- C) наибольший узел
- **D) корневой узел** ✅
- E) средний узел

**Ответ: D**

**26.** Если значение в левом узле-потомке меньше значения в его родительском узле, а значение в правом узле-потомке больше или равно значению в его родительском узле, то это характеризует

- A) двумерный массив
- B) одномерный массив
- **C) дерево двоичного поиска** ✅
- D) очередь
- E) стек

**Ответ: C**

**27.** Один из видов из самобалансирующихся двоичных деревьев поиска, гарантирующих логарифмический рост высоты дерева от числа узлов и позволяющее быстро выполнять основные операции дерева поиска: добавление, удаление и поиск узла, где сбалансированность достигается за счёт введения дополнительного атрибута узла дерева — «цвета»

- A) поддерево
- B) одномерный массив
- C) двумерный массив
- D) двоичная куча
- **E) красно-черное дерево** ✅

**Ответ: E**

**28.** Две вершины в графе соединяющие ребро

- A) равноудаленные
- B) соединительные
- **C) смежные** ✅
- D) соседние
- E) равноправные

**Ответ: C**

**29.** Один из методов обхода графа, при котором алгоритм стремится держаться как можно ближе к исходной вершине, посещает все вершины, смежные с исходной, и только после этого отходит дальше

- A) метод наименьших квадратов
- B) метод прямого распространения
- **C) поиск в ширину** ✅
- D) симметричный поиск
- E) поиск в глубину

**Ответ: C**

**30.** Алгоритм построения минимального остовного дерева взвешенного связного неориентированного графа

- A) алгоритм Беллмана — Форда
- B) алгоритм Флойда
- C) алгоритм Дейкстры
- **D) алгоритм Прима** ✅
- E) алгоритм Шелла

**Ответ: D**

## Вариант 3

**1.** Выполнение каждой программы на С++ начинается с использования функции

- A) begin
- B) first
- C) init
- D) start
- **E) main** ✅

**Ответ: E**

**2.** Объявлена переменная:  
unsigned int a=-5;  
Значение переменной a

- **A) компилятор переведет число в очень большое положительное число** ✅
- B) данное присваивание недопустимо
- C) 5
- D) 0
- E) -5

**Ответ: A**

**3.** Следующая директива отказывается от символических констант и макросов

- A) #include
- B) #define
- C) ifdef
- **D) #undef** ✅
- E) #file

**Ответ: D**

**4.** Результат операции  
double x=2, y=1.5, z=0;  
z=2pow(x, 3)+y;  
cout<<z<<enld;

- A) 3.5
- **B) ошибка, пропущен знак умножения** ✅
- C) 0
- D) 17.5
- E) 1.5

**Ответ: B**

**5.** Дан фрагмент кода:  
int i, j;  
for(i=0, j=10; i<=j; i++, j--){  
cout<<i<<" ";  
}  
Результат программы

- **A) 0 1 2 3 4 5** ✅
- B) 0 1 2 3 4
- C) 1 2 3 4 5 6
- D) 1 2 3 4 5
- E) 0 1 2 3 4 5 6

**Ответ: A**

**6.** Результат операции  
int a=0, b=1, c=2, d=3, e=4;  
a=(b++, c++, d++, e++);  
cout<<"a="<<a<<endl;

- A) 1
- B) 10
- **C) 4** ✅
- D) 2
- E) 5

**Ответ: C**

**7.** Дан массив:  
int a[10] = {6, 5, 4, 3, 2};  
Все значения в ячейках массива a

- A) 6 5 4 3 2
- B) 6 5 4 3 2 6 5 4 3 2
- C) 6 5 4 3 2 2 3 4 5 6
- D) 0 0 0 0 0 0 0 0 0 0
- **E) 6 5 4 3 2 0 0 0 0 0** ✅

**Ответ: E**

**8.** В результате выполнения оператора product /= ++x; при начальных значениях всех переменных равных 5, переменные примут значения

- **A) product = 0, x = 6** ✅
- B) product = 25, x = 5
- C) product = 31, x = 5
- D) product = 0, x = 5
- E) product = 30, x = 5

**Ответ: A**

**9.** Результат операции  
for(int i=0;i<3;++i){  
for(int j=0;j<i+1;++j)  
 cout<<"*";  
cout<<endl;  
}

- A) ошибка
- **B) *\n**\n***** ✅
- C) ******
- D) **\n**\n**
- E) ***\n***

**Ответ: B**

**10.** Библиотека для функции rand()

- **A) csdtlib** ✅
- B) cmath
- C) algorithm
- D) cstdio
- E) iostream

**Ответ: A**

**11.** В объектно-ориентированном программировании объект

- A) эквивалентен атрибуту
- B) является программой
- C) может содержать классы
- **D) может содержать даты и методы** ✅
- E) является командой

**Ответ: D**

**12.** В сортировке методом вставки термин «частичная сортировка» означает, что

- A) отсортированы парные элементы
- B) большинство элементов находится в своих окончательных позициях сортировки, но некоторые из них еще требуют выполнения сортировки
- C) отсортированы только некоторые из элементов
- **D) элементы группы отсортированы между собой, но возможно, в группу еще придется вставлять элементы, находящиеся за ее пределами** ✅
- E) некоторые элементы уже отсортированы, но, возможно, их еще придется перемещать

**Ответ: D**

**13.** Алгоритм поиска, при котором каждый элемент массива сравнивается с ключом поиска известен как

- A) поиск с вставками
- B) двоичный поиск
- **C) линейный поиск** ✅
- D) быстрый поиск
- E) поиск посредством выбора

**Ответ: C**

**14.** Если большие ключи сгруппированы справа, то индексом разбиения называется

- A) значение ключа левого элемента правого подмассива
- B) значение ключа левого элемента двухстороннего массива
- C) значение ключа элемента между левым и правым подмассивами
- D) индекс элемента между левым и правым подмассивами
- **E) индекс левого элемента правого подмассива** ✅

**Ответ: E**

**15.** Цикл while завершается когда индекс находит элемент

- A) для удаления
- **B) удовлетворяющий условию** ✅
- C) для команды исполнения
- D) случайный выполнении команд
- E) для вставки

**Ответ: B**

**16.** Ошибка оператора присваивания

- **A) 1:=a;** ✅
- B) A:=1;
- C) A:=a+b;
- D) a:=a+1;
- E) a:=a+a;

**Ответ: A**

**17.** В «О-синтаксисе» сортировка методом выбора выполняется за время

- A) O(logN)
- B) O(N/2)
- C) O(N)
- D) O(1)
- **E) O(N²)** ✅

**Ответ: E**

**18.** В «О-синтаксисе» удаление в упорядоченном массиве выполняется за время

- **A) O(N)** ✅
- B) O(logN)
- C) O(N/2)
- D) O(1)
- E) O(N²)

**Ответ: A**

**19.** Записывается однострочный комментарий в языке Си после символов

- A) **
- B) {*
- C) :)
- **D) //** ✅
- E) ( *

**Ответ: D**

**20.** В сбалансированном дереве

- A) пути от корня до всех листовых узлов имеют разную длину
- B) высота всех поддеревьев жестко контролируется
- C) все левые поддеревья имеют такую же высоту, как и все правые поддеревья
- **D) пути от корня до всех листовых узлов имеют примерно одинаковую длину** ✅
- E) может потребоваться изменение структуры дерева при поиске

**Ответ: D**

**21.** Если в элементах хранится ссылка на предыдущий элемент, то для удаления элемента с наибольшим ключом потребуется

- A) 5 перемещений по односвязному списку
- B) 3 перемещения по односвязному списку
- C) 2 перемещения по односвязному списку
- **D) 1 перемещение по односвязному списку** ✅
- E) 4 перемещения по односвязному списку

**Ответ: D**

**22.** При обращении к данным, хранящимся на диске происходит

- **A) поиск места для записи данных выполняется относительно медленно, но существует возможность записи большого объема данных** ✅
- B) перемещение данных с целью освобождения места под новые данные выполняется быстро благодаря возможности одновременного обращения ко многим записям
- C) удаление данных выполняется особенно быстро
- D) вставка выполняется медленно, но позиция для записи данных находится быстро
- E) добавление данных выполняется особенно быстро

**Ответ: A**

**23.** На рисунке приведен пример решения столкновений в хеш таблице следующим образом (показаны схемы а и б с начальной пробой)

- A) линейное зондирование
- B) квадратичное зондирование
- **C) открытая адресация** ✅
- D) двойное хеширование
- E) отдельная цепочка

**Ответ: C**

**24.** Рассмотрим хеш-таблицу с n ячейками, в которой коллизии разрешаются с помощью цепочек. Хеширование равномерно: каждый новый ключ имеет равные шансы попасть во все ячейки независимо от предыдущих. Пусть M – максимальная длина цепочек после добавление n ключей. Математическое ожидание M

- A) O(n!)
- B) O(nlogn)
- C) O(n)
- D) O(n²)
- **E) O(lg n/lg lg n)** ✅

**Ответ: E**

**25.** Набор меток и символов которые используется в алгоритмическом языке

- A) конструкция
- B) семантика
- **C) алфавит языка** ✅
- D) команда
- E) рабочая область

**Ответ: C**

**26.** Начальные данные

- A) индивидуальный алгоритм
- B) результаты задачи
- C) интервальное значение задачи
- **D) данные задачи** ✅
- E) команда

**Ответ: D**

**27.** Понятия языка

- A) блок-схема
- B) величина
- **C) инструмент выражения и представления информации** ✅
- D) программа
- E) вид алгоритма

**Ответ: C**

**28.** Множество V в ориентированном графе G = (V, E) представляет

- A) дуги графа
- B) путь графа
- **C) вершины графа** ✅
- D) ребра графа
- E) объекты графа

**Ответ: C**

**29.** Версия алгоритма Дейкстры с использованием матрицы смежности находит все кратчайшие пути орграфа с n вершинами за время порядка

- A) O(logn)
- B) O(n)
- **C) O(n²)** ✅
- D) O(logn²)
- E) O(n³)

**Ответ: C**

**30.** Цепочка примера структуры данных

- A) массивы, стеки и связанные файлы
- B) массивы, стеки и связанные фамилия
- C) массивы, стеки и связанные ключи
- **D) массивы, стеки и связанные списки** ✅
- E) массивы, стеки и записанные поля

**Ответ: D**

## Вариант 4

**1.** Количество операций сравнения, выполняемое быстрой сортировкой для файла размером N в наихудшем случае

- A) N/4
- **B) N²/2** ✅
- C) N/3
- D) N/2
- E) N³/2

**Ответ: B**

**2.** Стандартная библиотека С, позволяющая модифицировать программу в зависимости от места её выполнения

- A) <local.h>
- B) <stdloc.h>
- **C) <locale.h>** ✅
- D) <loctime.h>
- E) <clocale.h>

**Ответ: C**

**3.** Структура множественного выбора в C++, при котором значение некоторой переменной или выражения проверяется на множестве допустимых значений и в зависимости от результатов проверки предпринимаются различные действия

- A) while
- B) grade
- C) square
- D) for
- **E) switch** ✅

**Ответ: E**

**4.** Деревья, узлы которых содержат две связки (одна из которых или обе могут быть нулевыми)

- A) кустистые
- B) ветвящиеся
- C) корневые
- **D) двоичные** ✅
- E) листовые

**Ответ: D**

**5.** Математическая структура, состоящая из множества точек, которые называются вершинами, и совокупности линий (ребер), соединяющих эти точки

- A) куст
- B) маршрут
- **C) граф** ✅
- D) шаблон
- E) схема

**Ответ: C**

**6.** Вставки и удаления в стеке производятся

- A) только в конце
- B) в любом месте
- C) в начале или в конце
- D) в середине
- **E) только в его вершине** ✅

**Ответ: E**

**7.** Алгоритм, не использующий операцию сравнения ключей и упорядочивающий последовательности неотрицательных целых чисел

- A) сортировка вливанием
- B) сортировка кучей
- C) выборочная сортировка
- D) сортировка пузырьками
- **E) сортировка подсчётом** ✅

**Ответ: E**

**8.** Класс сложности алгоритма, обрабатывающего все подмножества некоторого множества из n элементов

- **A) экспоненциальная** ✅
- B) параболическая
- C) линеарная
- D) восьмеричная
- E) факториальная

**Ответ: A**

**9.** Наименьший элемент массива меняется местами с первым элементом. Наименьший элемент из остальных элементов переставляется со вторым элементом в исходном массиве и т.д.

- A) сортировка вставками
- B) сортировка пузырьками
- C) распределяющая сортировка
- D) индексная сортировка
- **E) сортировка выбором** ✅

**Ответ: E**

**10.** Объявление массива с числом элементов arraySize типа float, имеющими нулевые начальные значения

- **A) float table [arraySize] = {0};** ✅
- B) float [arraySize] = {0};
- C) float table [arraySize] = {0,..,0};
- D) float mv [arraySize] = {0,0};
- E) float mv [arraySize] = {};

**Ответ: A**

**11.** Метод построения хеш-таблиц для статических множеств ключей, обеспечивающий выполнение поиска за время O(1) даже в худшем случае

- **A) идеальное, или совершенное хеширование** ✅
- B) нелинейное, или совершенное зондирование
- C) линейное, или совершенное зондирование
- D) билинейная, или отдельная цепочка
- E) тернарное, или совершенное хеширование

**Ответ: A**

**12.** Текущее множество рёбер устанавливается пустым. Затем из всех рёбер, добавление которых к уже имеющемуся множеству не вызовет появление в нём цикла, выбирается ребро минимального веса – это алгоритм

- A) Форда
- B) Фрейда
- C) Белмана
- **D) Крускала** ✅
- E) Дейтла

**Ответ: D**

**13.** Каждый объект C++ имеет доступ к своему собственному адресу через указатель с именем

- A) adress
- B) intr
- C) setpr
- D) cout
- **E) this** ✅

**Ответ: E**

**14.** Операция, в ходе которой байты пересылаются из оперативной памяти на устройства (например, экран дисплея, дисковод, принтер)

- A) рекурсия
- **B) вывод** ✅
- C) инверсия
- D) ввод
- E) инкапсуляция

**Ответ: B**

**15.** Для большинства хеш-функций пространство ключей представляется множеством ….

- **A) N={0,1,2….}** ✅
- B) рациональных чисел
- C) комплексных чисел
- D) Z={…. -2,-1,0,1,2….}
- E) действительных чисел

**Ответ: A**

**16.** Методы разрешения коллизий

- A) закрытой адресации, цепочки, линейного исследования
- B) адресации, удаления, линейноого возрастания
- **C) открытой адресации, цепочки, линейного исследования** ✅
- D) закрытой адресации, ветвления, линейного исследования
- E) кубического исследования, двоичного хеширования

**Ответ: C**

**17.** Математическая библиотечная функция С, возводящая x в степень y

- A) pow(x/y)
- B) pow(x;y)
- C) pow(x?y)
- D) pow(y,x)
- **E) pow(x,y)** ✅

**Ответ: E**

**18.** Выбор хеш-функции зависит от

- **A) типа ключа** ✅
- B) индекса ключа
- C) вида данных
- D) размера массива
- E) типа переменной

**Ответ: A**

**19.** Рекурсивное определение последовательности Фибоначчи

- **A) fibonacci (0)=0; fibonacci (1)=1; fibonacci (n)= fibonacci (n-1) + fibonacci (n-2)** ✅
- B) fibonacci (0)=0; fibonacci (1)=1; fibonacci (n)= fibonacci (n+1) + fibonacci (n+2)
- C) fibonacci (0)=1; fibonacci (1)=0; fibonacci (n)= fibonacci (n+1) + fibonacci (n+2)
- D) fibonacci (0)=0; fibonacci (1)=1; fibonacci (n)= fibonacci (n-1) - fibonacci (n-2)
- E) fibonacci (0)=1; fibonacci (1)=2; fibonacci (n)= fibonacci (n-1) - fibonacci (n-2)

**Ответ: A**

**20.** Заголовочный файл, содержащий основную информацию необходимую для всех операций ввода-вывода в С++

- A) <ostream.h>
- **B) <iostream.h>** ✅
- C) <inalude.h>
- D) <istdlib.h>
- E) <imanip.h>

**Ответ: B**

**21.** Группа операторов, которая выполняется повторно до тех пор, пока удовлетворяется некоторое условие

- A) индукция
- B) рефлексия
- C) рекурсия
- D) метка
- **E) цикл** ✅

**Ответ: E**

**22.** В C++ макрос, который вызывается перед обработкой списка с переменым числом параметров

- A) va_sign
- B) va_endl
- **C) va_start** ✅
- D) va_argv
- E) va_make

**Ответ: C**

**23.** Время выполнения программы, все инструкции которой выполняются один или несколько раз

- A) квадратично
- **B) линейно** ✅
- C) постоянно
- D) NlogN
- E) logarithmic

**Ответ: B**

**24.** Древовидная структура данных, в которой значения всех узлов, размещённых правее некоторого узла, больше значений узлов, размещённых левее, причём это справедливо как для всего дерева, так и для любой его части - это

- A) тернарная система векторов
- B) стек красных деревьев
- C) очередь связных цепочек
- D) многозадачный симплекс
- **E) двоичное дерево поиска** ✅

**Ответ: E**

**25.** Абстрактный тип данных, представляющий собой список, в котором вставка и удаление элементов производятся с одного конца. Функционирует по принципу «последним пришёл – первым вышел»

- A) таблица (table)
- B) порядок (order)
- **C) стек (stack)** ✅
- D) очередь (queue)
- E) куча (coach)

**Ответ: C**

**26.** Описание взвешенного направленного циклического графа, показанного на рисунке (1→2: 0.20, 1→3: 0.30, 1→4: 0.10, 4→2: 0.33, 4→3: 0.15)

- A) (1, 2, 0.30), (1, 3, 0.30), (1, 4, 0.10), (4, 2, 0.33), (4, 3, 0.15)
- B) (1, 4, 0.30), (1, 2, 0.20), (1, 3, 0.30), (4, 2, 0.33), (4, 3, 0.15)
- C) (1, 2, 0.20), (1, 3, 0.30), (1, 4, 0.10), (4, 2, 0.33), (4, 3, 0.25)
- **D) (1, 2, 0.20), (1, 3, 0.30), (1, 4, 0.10), (4, 2, 0.33), (4, 3, 0.15)** ✅
- E) (1, 2, 0.30), (1, 3, 0.20), (1, 4, 0.10), (4, 2, 0.30), (4, 3, 0.15)

**Ответ: D**

**27.** Вызывает сама себя либо непосредственно, либо косвенно с помощью другой функции

- **A) рекурсия** ✅
- B) индукция
- C) дедукция
- D) итерация
- E) инверсия

**Ответ: A**

**28.** Переменные, содержащие адреса других переменных или функций

- A) константы
- B) функции
- **C) указатели** ✅
- D) разделители
- E) выражения

**Ответ: C**

**29.** Характеристика качества алгоритма, отражающая объем потребляемой памяти

- A) временная эффективность (time efficiency)
- B) линейная эффективность (linear efficiency)
- **C) пространственная эффективность (space efficiency)** ✅
- D) максимальная эффективность (max efficiency)
- E) минимальная эффективность (min efficiency)

**Ответ: C**

**30.** Пользовательская функция, написанная на языке С++, проводит операцию над всеми числами в диапазоне от 1 до 10  
#include<iostream.h>  
int square (int);  
int main()  
{  
for (int x = 1; x<=10; x++)  
cout << square (x) << endl;  
return 0;  
}  
int square (y);  
{  
return y*y;  
}

- A) разность
- B) сумму
- C) произведение
- D) возведение в куб
- **E) возведение в квадрат** ✅

**Ответ: E**

## Вариант 5

**1.** Функция, преобразующая ключ поиска в адрес в таблице

- **A) хеш-функция** ✅
- B) адресная функция
- C) функция преобразования
- D) функция индекса
- E) функция-указатель

**Ответ: A**

**2.** Структуры данных: связные списки, стеки и очереди

- A) сбалансированные
- B) нелинейные
- C) наивные
- D) экспоненциальные
- **E) линейные** ✅

**Ответ: E**

**3.** Свойство применимости алгоритма для некоторого класса задач, различающихся лишь значениями входных данных

- A) результативность
- **B) массовость** ✅
- C) дискретность
- D) конечность
- E) детерминированность

**Ответ: B**

**4.** Масштабирование ключей, являющихся числами больше 0 и меньше 1, в диапазон [0, M-1]

- A) умножить на M и округлить до ближайшего целого числа снизу
- B) умножить на M-1 и округлить до целого числа из диапазона [0, M-1]
- **C) умножить на M и округлить до целого числа из диапазона [0, M-1]** ✅
- D) умножить на M и округлить до целого числа сверху из диапазона [1, M-1]
- E) умножить на M-1 и округлить до наибольшего целого числа

**Ответ: C**

**5.** Метод разрешения коллизий хеширования, при котором ключи, хешированные в одну ячейку, объединяются в связный список

- A) «при помощи столкновений»
- B) «при помощи зондирования»
- C) «при помощи кубов»
- **D) «при помощи цепочек»** ✅
- E) «при помощи диаграмм»

**Ответ: D**

**6.** Топологическая абстракция, предназначенная для описания некоторых топологических свойств самых разных объектов и отношений между ними

- **A) граф** ✅
- B) куст
- C) массив
- D) область
- E) вектор

**Ответ: A**

**7.** В «О-синтаксисе» вставка в неупорядоченном массиве выполняется за время

- A) O(N)
- B) O(N²)
- C) O(logN)
- D) O(N/2)
- **E) O(1)** ✅

**Ответ: E**

**8.** Линейный набор элементов, называемых узлами (node), соединённых указателями (link) на следующий узел

- A) динамический массив
- B) несвязный список
- C) наивный список
- D) ассоциативный массив
- **E) связный список** ✅

**Ответ: E**

**9.** Тип возвращаемого значения в С, в случае, когда функция не возвращает никакого значения

- **A) void** ✅
- B) double
- C) boolean
- D) char
- E) float

**Ответ: A**

**10.** Каждый оператор в языке С++ заканчивается

- A) .
- B) /
- C) \
- **D) ;** ✅
- E) ,

**Ответ: D**

**11.** Время выполнения программ, которые каждый элемент ввода подвергают небольшой обработке

- A) 2N
- B) N⁵
- C) const
- D) параболический
- **E) линейный** ✅

**Ответ: E**

**12.** Класс сложности алгоритма поиска минимального элемента в неупорядоченном массиве, предполагающего просмотр всего набора входных данных

- A) гиперболический
- B) квадратичный
- C) нелинейный
- D) десятичный
- **E) линейный** ✅

**Ответ: E**

**13.** Базовый алгоритм быстрой сортировки был открыт Хоаром (C.A.R. Hoare) в

- A) 1905 году
- B) 1870 году
- C) 1917 году
- **D) 1960 году** ✅
- E) 2000 году

**Ответ: D**

**14.** Методы разрешения коллизий

- **A) открытой адресации, цепочки, линейного исследования** ✅
- B) закрытой адресации, ветвления, линейного исследования
- C) кубического исследования, двоичного хеширования
- D) закрытой адресации, цепочки, линейного исследования
- E) адресации, удаления, линейноого возрастания

**Ответ: A**

**15.** Фрагмент программы моделирует бросание игральной кости (20 раз).  
# include <iostream.h>  
# include <stdlib.h>  
main()  
{  
for (int i=1; i<=20; i++)  
{cout << 1 + rand() % 6;  
}  
return;  
}  
Интервал результатов программы...

- A) от 1 до 20
- B) от 0 до 6
- C) от 1 до 5
- **D) от 1 до 6** ✅
- E) от 0 до 5

**Ответ: D**

**16.** Основные операции в бинарном дереве поиска выполняются за время, пропорциональное его

- A) количеству родительских узлов
- B) количеству дочерних узлов
- C) количеству ветвей
- D) ширине
- **E) высоте** ✅

**Ответ: E**

**17.** Базовая структура данных, в которой каждый элемент содержит информацию, необходимую для получения следующего элемента

- **A) связный список** ✅
- B) цепочный список
- C) множество
- D) массив
- E) наивный список

**Ответ: A**

**18.** Функция в класс string С++ для выделения подстроки

- A) minstr
- B) supremum
- C) outstr
- D) swap
- **E) substr** ✅

**Ответ: E**

**19.** Процесс упорядоченного размещения элементов в массиве

- A) сравнение
- B) поиск
- C) фильтр
- D) перебор
- **E) сортировка** ✅

**Ответ: E**

**20.** Алгоритм поиска вершин в графе по их ключам, использующий стек в качестве дополнительной структуры данных

- A) поиск по уровням
- **B) поиск в глубину** ✅
- C) поиск по диагонали
- D) поиск в длину
- E) поиск по широте

**Ответ: B**

**21.** Служебное слово для обозначения строковых типов данных

- **A) string** ✅
- B) float
- C) const
- D) set
- E) integer

**Ответ: A**

**22.** Элементы массива последовательно проверяются на равенство с заданным значением. Работа алгоритма прерывается при обнаружении первого совпадения – это алгоритм

- A) сортировки хешем
- **B) линейного поиска** ✅
- C) индуктивного анализа
- D) быстрой рекурсии
- E) двоичного поиска

**Ответ: B**

**23.** Фрагмент кода на языке С++ определяет сумму  
{  
total = 0  
for (row = 0; row < 10; row++)  
{for (col = 0; col < 10; col++)  
{total += a[row][col];  
…}}  
}

- **A) всех элементов массива** ✅
- B) первой строки массива
- C) первого столбца массива
- D) последней строки массива
- E) последнего столбца массива

**Ответ: A**

**24.** Изображение иллюстрирует (граф с вершинами 1,2,3,4 и направленными рёбрами по кругу)

- A) направленный циклический граф как связный вектор
- B) направленный ациклический граф как связную структуру
- **C) направленный циклический граф как связную структуру** ✅
- D) направленный циклический граф как связный стек
- E) двунаправленный циклический граф как связную структуру

**Ответ: C**

**25.** Один или более символов, определяющих действие над операндами

- A) знак разделителя
- B) знак функционала
- C) знак литерала
- **D) знак операции** ✅
- E) ключевой знак

**Ответ: D**

**26.** Корректность данных

- A) соответствие среде разработки
- B) интерпретируемость бизнес-аналитиком
- **C) соответствие условиям решаемой задачи** ✅
- D) непротиворечивость входных и выходных данных
- E) соответствие решениям аналогичных задач

**Ответ: C**

**27.** Задают действия над данными

- A) ключевые операнды
- B) зависимые переменные
- **C) исполняемые операторы** ✅
- D) неисполняемые операторы
- E) независимые переменные

**Ответ: C**

**28.** Оператор, меняющий поток выполнения программы: управление передаётся первому оператору после метки, указанной в данном операторе

- A) metc
- B) raise
- C) exit
- **D) goto** ✅
- E) call

**Ответ: D**

**29.** Перегрузка операции << в С++ позволяет использовать её, в зависимости от контекста, как

- A) «вывести из потока» или «сдвиг влево»
- B) нельзя перегружать эту операцию
- C) «вывести из потока» или «сдвиг вправо»
- D) «поместить в поток» или «сдвиг вправо»
- **E) «поместить в поток» или «сдвиг влево»** ✅

**Ответ: E**

**30.** Структура функции языке С++

- A) [тип локальных переменных] [параметры (список аргументов)] {тело функции}
- B) [тип глобальных переменных] [имя функции (список параметров)] {тело функции}
- C) [тип значения константы] [имя функции (список параметров)] {тело функции}
- D) [тип возвращаемого значения] [аргументы (список параметров)] {тело функции}
- **E) [тип возвращаемого значения] [имя функции (список параметров)] {тело функции}** ✅

**Ответ: E**

## Вариант 6

**1.** Топологическая абстракция, предназначенная для описания некоторых топологических свойств самых разных объектов и отношений между ними

- A) куст
- B) область
- **C) граф** ✅
- D) вектор
- E) массив

**Ответ: C**

**2.** Операторы тела функции заключаются в операторные скобки (C++)

- **A) {…}** ✅
- B) {…)
- C) (…)
- D) < …>
- E) […]

**Ответ: A**

**3.** Элементы массива переупорядочиваются относительно выбранного опорного значения ключа. Рекомендуется выбирать опорный элемент близким к значению медианы – это

- A) сортировка узла
- B) поразрядная сортировка
- **C) быстрая сортировка** ✅
- D) сортировка слиянием
- E) медленная сортировка

**Ответ: C**

**4.** Зарезервированные обозначения, имеющие специальное значение для компилятора и используемые только в одном определенном смысле

- A) неисполняемые операторы
- B) исполняемые операторы
- **C) ключевые слова** ✅
- D) строковые литералы
- E) неисполняемые операнды

**Ответ: C**

**5.** Узел может быть вставлен в двоичное дерево только в качестве

- A) корня
- B) ветки
- **C) листа** ✅
- D) вершины
- E) саженца

**Ответ: C**

**6.** Унарная операция, позволяющая получить адрес программного объекта (C++)

- A) !
- **B) &** ✅
- C) ?
- D) %
- E) *

**Ответ: B**

**7.** Группа операторов, которая выполняется повторно до тех пор, пока удовлетворяется некоторое условие

- A) индукция
- B) рефлексия
- **C) цикл** ✅
- D) метка
- E) рекурсия

**Ответ: C**

**8.** Линейный список, доступ к элементам которого происходит по принципу «Первым пришёл и первым ушёл» (First In and First Out)

- A) таблица (table)
- B) порядок (ordnung)
- C) куча (coatch)
- D) стек (stuck)
- **E) очередь (queue)** ✅

**Ответ: E**

**9.** Задают действия над данными

- **A) исполняемые операторы** ✅
- B) зависимые переменные
- C) ключевые операнды
- D) независимые переменные
- E) неисполняемые операторы

**Ответ: A**

**10.** Деревья, узлы которых содержат две связки (одна из которых или обе могут быть нулевыми)

- A) ветвящиеся
- B) корневые
- C) листовые
- **D) двоичные** ✅
- E) кустистые

**Ответ: D**

**11.** Характеристика качества алгоритма, показывающая насколько быстро работает алгоритм

- A) линейная эффективность (linear efficiency)
- B) минимальная эффективность (min efficiency)
- C) максимальная эффективность (max efficiency)
- **D) временная эффективность (time efficiency)** ✅
- E) пространственная эффективность (space efficiency)

**Ответ: D**

**12.** Фрагмент программы моделирует бросание игральной кости (20 раз).  
# include <iostream.h>  
# include <stdlib.h>  
main()  
{  
for (int i=1; i<=20; i++)  
{cout << 1 + rand() % 6;  
}  
return;  
}  
Интервал результатов программы…

- **A) от 1 до 6** ✅
- B) от 0 до 6
- C) от 0 до 5
- D) от 1 до 5
- E) от 1 до 20

**Ответ: A**

**13.** Если второй элемент массива меньше первого, эти элементы меняются местами. На втором шаге третий элемент размещается в правильном порядке по отношению к двум первым, и т.д.

- **A) сортировка вставкой** ✅
- B) распределяющая сортировка
- C) сортировка индексацией
- D) сортировка пузырьками
- E) выборочная сортировка

**Ответ: A**

**14.** Класс сложности оптимизационных алгоритмов, реализующих полный перебор множества допустимых решений задачи

- A) кубическая
- **B) факториальная** ✅
- C) параболическая
- D) бинарная
- E) многомерная

**Ответ: B**

**15.** Список, допускающий прохождение как в прямом, так и обратном направлении

- **A) двусвязный** ✅
- B) динамический
- C) односвязный
- D) циклический
- E) референтный

**Ответ: A**

**16.** Упорядоченное дерево, состоящее из узлов двух типов: внешних узлов, не имеющих дочерних узлов, и внутренних узлов, каждый из которых имеет ровно два дочерних узла

- A) бинарный куст
- B) двоичная куча
- C) тернарное дерево
- D) красное дерево
- **E) бинарное дерево** ✅

**Ответ: E**

**17.** Оператор возврата значений из функции

- A) if
- B) for
- C) while
- D) else
- **E) return** ✅

**Ответ: E**

**18.** Хеш-функция, используемая при двойном хешировании

- A) h(k,i) = (h₁(k)+ih₂(k)) mod h₁
- B) h(k,i) = (h₁(k)+ih₂(h₂)) mod m
- **C) h(k,i) = (h₁(k)+ih₂(k)) mod m** ✅
- D) h(k,i) = (h₁(h₁)+ih₂(k)) mod m
- E) h(k,i) = (h₁(k)+ih₂(h₁)) mod m

**Ответ: C**

**19.** Ключевое слово, указывающее, что объект не является модифицируемым и что любая попытка изменения этого объекта является ошибкой

- **A) const** ✅
- B) unit
- C) base
- D) long
- E) indef

**Ответ: A**

**20.** Двоичный поиск исключает после каждого просмотра следующую часть элементов массива

- A) треть
- B) четверть
- C) десятую
- D) пятую
- **E) половину** ✅

**Ответ: E**

**21.** Имя массива есть адрес его начального элемента (и указатель на этот элемент). Поэтому инструкцию y = &a[0] можно записать в виде

- A) y = a(0);
- B) y = 1;
- C) y = a(1);
- **D) y = a;** ✅
- E) y = 0;

**Ответ: D**

**22.** Оператор C, который означает «увеличить на единицу»

- A) +/
- B) -+
- **C) ++** ✅
- D) +-
- E) /+

**Ответ: C**

**23.** Изображение иллюстрирует [граф из 4 вершин со стрелками: 1→2, 1→3, 1→4, 2→4, 3→4]

- A) простой двунаправленный циклический граф
- B) сложный направленный циклический граф
- C) простой направленный граф
- D) простой ненаправленный циклический граф
- **E) простой направленный нециклический граф** ✅

**Ответ: E**

> ⚠ Спорный: изображён направленный ациклический граф, поэтому подходит и «простой направленный граф» (C). Выбран более точный вариант.

**24.** Выбор хеш-функции зависит от

- **A) типа ключа** ✅
- B) вида данных
- C) индекса ключа
- D) размера массива
- E) типа переменной

**Ответ: A**

**25.** Функция C динамического выделения памяти

- A) molloc
- B) sizeof
- C) fullog
- **D) calloc** ✅
- E) realoc

**Ответ: D**

**26.** Алгоритм поиска вершин в графе по их ключам, использующий очередь как дополнительную структуру данных

- A) поиск по диагонали
- **B) поиск в ширину** ✅
- C) поиск в глубину
- D) поиск по слоям
- E) поиск по высоте

**Ответ: B**

**27.** Графическое представление алгоритма или фрагмента алгоритма

- A) математическая структура
- B) технологическая схема
- C) физическая схема
- D) карта компонентов
- **E) блок схема** ✅

**Ответ: E**

**28.** Время выполнения алгоритмов, которые обрабатывают все элементы данных тройками

- A) linea
- **B) N³** ✅
- C) N-3
- D) 3^N
- E) tetr

**Ответ: B**

**29.** Функция в классе string C++ для обмена содержимого строк

- A) chanstr
- **B) swap** ✅
- C) maxrstr
- D) instr
- E) supstr

**Ответ: B**

**30.** Идеальную хеш-функцию легко вычислить и аппроксимировать

- A) дельта-функцией
- **B) случайной функцией** ✅
- C) тригонометрической функцией
- D) логарифмической функцией
- E) функцией гамма

**Ответ: B**

---

# Казахская версия — Деректер базасы

## Нұсқа 1

**1.** 2021 жылғы оқылатын сабақтардың секцияларының орташа жалпы кредиттер санын табу. Бірақ әр секцияда кемінде 3 студент болу керек

- **A) SELECT CourseId, Semester, Year, SecId, AVG(TotCred) / FROM TAKES NATURAL JOIN STUDENT / WHERE Year = 2021 / HAVING COUNT(Sid) >= 3;** ✅
- B) SELECT CourseId, Semester, Year, SecId, MAX(TotCred) / FROM TAKES NATURAL JOIN STUDENT / WHERE Year = 2021 / HAVING COUNT(Sid) >= 3;
- C) SELECT CourseId, Semester, Year, SecId, MAX(TotCred) / FROM TAKES NATURAL JOIN STUDENT / WHERE Year = 2021 / HAVING AVG(Sid) > 3;
- D) SELECT CourseId, Semester, Year, SecId, MAX(TotCred) / FROM TAKES NATURAL JOIN STUDENT / HAVING COUNT(Sid) >= 3;
- E) SELECT CourseId, Semester, Year, SecId, TOTAL(TotCred) / FROM TAKES NATURAL JOIN STUDENT / WHERE Year = 2021
- F) SELECT CourseId, Semester, Year, SecId, MIN(TotCred) / FROM TAKES, STUDENT / WHERE Year = 2021 / HAVING COUNT(Sid) >= 3;

**Ответ: A**

**2.** Қала атына кері сұрыптауды қолданып, Париждан басқа және өлшемі 10 кг-нан көп болатын бөлшектердің түсі мен қай қалада шығарылатынын көрсету

- A) SELECT P.Color, P.City / FROM P / WHERE P.City <> 'Paris' OR P.Weight > 10 / GROUP BY City DESC;
- B) SELECT P.Color, P.City / FROM P / WHERE P.City <> 'Paris' OR P.Weight > 10 / ORDER BY City DESC;
- C) SELECT P.Color, P.City / FROM P / WHERE P.City <> 'Paris' AND P.Weight > 10 / ORDER BY City;
- D) SELECT P.Color, P.City / FROM P / WHERE P.City <> 'Paris' AND P.Weight > 10
- E) SELECT P.Color, P.City / FROM P;
- **F) SELECT P.Color, P.City / FROM P / WHERE P.City <> 'Paris' AND P.Weight > 10 / ORDER BY City DESC;** ✅

**Ответ: F**

**3.** Қиылысу операциясы үшін қолданылатын команда

- A) divide by
- B) project
- **C) intersect** ✅
- D) union
- E) minus
- F) join
- G) times
- H) select

**Ответ: C**

**4.** ER-моделіндегі байланыс түрі

- **A) өзіне сілтеме жасайтын** ✅
- B) паралельді
- C) композиция
- D) тізбектелген
- **E) рекурсивті** ✅
- F) шартты

**Ответ: A, E**

**5.** 2005 коды пән бойынша студент бағасын 5-ке ауыстыру

- A) APPEND USP / SET Ocenka = 5 / WHERE Pnum = 2005;
- B) DELETE USP / SET Ocenka = 5 / WHERE Pnum = 2005;
- C) UPDATE USP / SET Ocenka = 5 / WHERE Pnum > 2005;
- D) INSERT INTO USP Ocenka = 5 / WHERE Pnum = 2005;
- E) INSERT INTO USP / SET Ocenka = 5 / WHERE Pnum = 2005;
- **F) UPDATE USP / SET Ocenka = 5 / WHERE Pnum = 2005;** ✅

**Ответ: F**

**6.** Иерархиялық деректер қорында ағашты толық қарап өту реті

- A) жоғарыдан төмен, оннан солға қарай
- B) төменнен жоғары, солдан оңға қарай
- C) тек солдан оңға қарай
- D) төменнен жоғары, оңнан солға қарай
- **E) жоғарыдан төмен, солдан оңға қарай** ✅
- F) тек оңнан солға қарай

**Ответ: E**

**7.** Реляционды деректер моделінде «Көп қабатты үй - тұрғын» байланысының түрі

- A) ∞:1
- B) 1:2
- C) 2:1
- **D) 1:∞** ✅
- E) ∞:∞
- F) 1:1

**Ответ: D**

**8.** Фамилиясы И-мен С әріптерінің арасында болатын оқытушылардың сабақ беретін пәндері

- A) SELECT * FROM PREDMET / WHERE PREDMET.Tnum IN / (SELECT TEACHERS.Tnum FROM TEACHERS / WHERE TEACHERS.Tfam) ;
- B) SELECT * FROM PREDMET / WHERE PREDMET.Tnum IN / (SELECT TEACHERS.Tnum FROM TEACHERS / WHERE TEACHERS.Tfam LIKE 'И' AND 'С') ;
- C) SELECT * FROM PREDMET / WHERE PREDMET.Tnum NOT IN / (SELECT TEACHERS.Tnum FROM TEACHERS / WHERE TEACHERS.Tfam BETWEEN 'И' AND 'С') ;
- **D) SELECT * FROM PREDMET / WHERE PREDMET.Tnum IN / (SELECT TEACHERS.Tnum FROM TEACHERS / WHERE TEACHERS.Tfam BETWEEN 'И' AND 'С') ;** ✅
- E) SELECT * FROM PREDMET / WHERE PREDMET.Tnum / (SELECT TEACHERS.Tnum FROM TEACHERS / WHERE TEACHERS.Tfam BETWEEN 'И' AND 'С') ;
- F) SELECT * FROM PREDMET / WHERE PREDMET.Tnum IN / (SELECT TEACHERS.Tnum FROM TEACHERS BETWEEN 'И' OR 'С' );

**Ответ: D**

> ⚠ Спорный: на исходном скриншоте отмечен вариант B (LIKE), но синтаксически верен BETWEEN. Отметка в скриншоте не является эталоном.

**9.** Реляциондық базада атрибуттың әлеуетті кілт болу қасиеті

- A) агрегаттылық
- **B) уникалдылық** ✅
- **C) минималдылық** ✅
- D) ассоциативтік
- E) біркелкілік
- F) ақпараттық

**Ответ: B, C**

**10.** Жалақысы 250000 мен 300000 арасындағы оқытушылардың аты-жөні

- A) SELECT Name / FROM INSTRUCTOR / WHERE Salaray <300000;
- B) SELECT Name / FROM INSTRUCTOR / WHERE Salaray = 250000;
- C) SELECT Name / FROM INSTRUCTOR / WHERE Salary LIKE 250000 AND 300000;
- D) SELECT Name / FROM INSTRUCTOR / WHERE Salaray > 250000;
- E) SELECT Name / FROM INSTRUCTOR / WHERE Salary 250000 AND 300000;
- **F) SELECT Name / FROM INSTRUCTOR / WHERE Salary BETWEEN 250000 AND 300000;** ✅

**Ответ: F**

**11.** Нормалды формалар

- A) 6НФ
- **B) 4НФ** ✅
- **C) 3НФ** ✅
- **D) Бойс-Коддтың НФ** ✅
- E) 0НФ
- F) Ажырату НФ
- G) Кодд НФ
- H) Біріктіру НФ

**Ответ: B, C, D**

> ⚠ Спорный: реально существуют также 6НФ (A), то есть верных четыре — но тест допускает не более трёх ответов. Уточнить у преподавателя.

**12.** Пән номері мен сол пәннен сабақ беретін оқытушылардың тізімі

- **A) SELECT Name, CourseId / FROM INSTRUCTOR, TEACHES / WHERE INSTRUCTOR.Id = TEACHES. Id;** ✅
- B) SELECT Name, CourseId / FROM INSTRUCTOR / WHERE INSTRUCTOR.Id = Id;
- C) SELECT Name, CourseId / FROM INSTRUCTOR, TEACHES / WHERE INSTRUCTOR.Id == TEACHES;
- D) SELECT Name, CourseId / FROM INSTRUCTOR, TEACHES;
- **E) SELECT Name, CourseId / FROM INSTRUCTOR NATURAL JOIN TEACHES** ✅
- F) SELECT Name, CourseId / FROM INSTRUCTOR / WHERE INSTRUCTOR.Id == Id;

**Ответ: A, E**

**13.** Орташа жалақысы ең үлкен болатын бөлімдерді табу

- **A) SELECT DeptName / FROM INSTRUCTOR / HAVING AVG(Salary) >= ALL ( SELECT AVG(Salary) / FROM INSTRUCTOR);** ✅
- B) SELECT DeptName / FROM INSTRUCTOR / HAVING AVG(Salary) >= ALL ( SELECT (Salary) / FROM INSTRUCTOR);
- C) SELECT DeptName / FROM INSTRUCTOR / HAVING AVG(Salary) >= ( SELECT MIN(Salary) / FROM INSTRUCTOR);
- D) SELECT DeptName / FROM INSTRUCTOR / HAVING AVG(Salary) >= ANY ( SELECT AVG(Salary) / FROM INSTRUCTOR);
- E) SELECT DeptName / FROM INSTRUCTOR / HAVING (Salary) >= ALL ( SELECT AVG(Salary) / FROM INSTRUCTOR);
- F) SELECT DeptName / FROM INSTRUCTOR / HAVING AVG(Salary) >= ( SELECT AVG(Salary) / FROM INSTRUCTOR);

**Ответ: A**

**14.** DELETE операторы

- A) кестені құру
- B) кестедегі жолдарды жаңарту
- C) кестені жою
- **D) кестеден жолдарды жою** ✅
- E) мәліметтерді таңдау
- F) жолдар енгізу

**Ответ: D**

**15.** Студенттердің 10/09/2021 күні алынған балынан жоғары балдар

- A) SELECT * FROM USP / WHERE Ocenka >= ALL (SELECT Ocenka FROM USP
- B) SELECT * FROM USP / WHERE Ocenka >= SOME (SELECT Ocenka FROM USP / WHERE Udate = 10/09/2021);
- **C) SELECT * FROM USP / WHERE Ocenka >= ALL (SELECT Ocenka FROM USP / WHERE Udate = 10/09/2021);** ✅
- D) SELECT * FROM USP / WHERE Ocenka >= NOT ALL (SELECT Ocenka FROM USP / WHERE Udate = 10/09/2021);
- E) SELECT * FROM USP / WHERE Ocenka <= (SELECT Ocenka FROM USP / WHERE Udate = 10/09/2021);
- F) SELECT * FROM USP / WHERE Ocenka >= ANY (SELECT Ocenka FROM USP / WHERE Udate = 10/09/2021);

**Ответ: C**

**16.** Деректер қорының бүтіндігі түсінігі

- A) ақпараттық қорғалғандығы
- B) ақпараттың қарама-қайшылығы
- **C) ақпараттың қарама-қайшы еместігі** ✅
- D) атрибуттарды жіктеу мүмкіндігі
- E) ақпараттың топталғандығы
- F) ақпараттың тәуелділігі
- **G) ақпараттық өзектілігі** ✅
- H) атрибуттарды топтау мүмкіндігі

**Ответ: C, G**

**17.** Қатынас 5НФ да болады, егер

- A) 3НФ-те болатын және кілттік емес атрибуттар өзара тәуелді
- **B) қатынастағы кез-келген байланысу тәуелділігі осы қатынаста мүмкін болатын кілттің бар болуынан шығады** ✅
- C) көп мәнді қатынас болса және қатынастағы қалған атрибуттар А-ға функционалды тәуелді болса
- D) 3НФ-те болса және кілттік емес атрибуттары бастапқы кілтке тәуелді болса
- E) 3НФ-те болатын және логикалық бөлінбейтін мәндерге ие қатынас
- F) 2НФ да болса және функционалдық тәуелділіктер болмаса

**Ответ: B**

**18.** Адресері Алматыдан болатын жұмысшылардың аты-жөні

- A) SELECT Fname, Lname / FROM EMPLOYEE / WHERE Address LIKE 'Алматы';
- B) SELECT Fname, Lname / FROM EMPLOYEE / WHERE Address NOT LIKE 'Алматы%';
- C) SELECT Fname, Lname / FROM EMPLOYEE
- D) SELECT Fname, Lname / FROM EMPLOYEE / WHERE Address NOT IN '%Алматы%';
- E) SELECT Fname, Lname / FROM EMPLOYEE / WHERE Address = = Алматы
- **F) SELECT Fname, Lname / FROM EMPLOYEE / WHERE Address LIKE '%Алматы%';** ✅

**Ответ: F**

**19.** Индексте мәліметтерді реттеу әдісі

- A) SORT
- **B) ASC|DESC** ✅
- C) CASCADE
- D) ON UPDATE CASCADE
- E) REFERENCES
- F) ORDER BY
- G) ON UPDATE NO ACTION
- H) CHECK

**Ответ: B**

> ⚠ Спорный: ORDER BY (F) относится к запросу, а не к индексу; при создании индекса указывается ASC|DESC.

**20.** Әр Должность бағанында жұмысшы санын анықтайтын сұраныс

- A) SELECT COUNT(*) / FROM Кадровый_состав
- B) SELECT Должность, COUNT(*) / FROM Кадровый_состав
- C) SELECT COUNT(*) / FROM Должность
- **D) SELECT COUNT(*) / FROM Кадровый_состав / GROUP BY Должность / WHERE Должность NOT NULL** ✅
- E) SELECT Должность, SUM(*) / FROM Кадровый_состав
- F) SELECT Должность, MAX(*) / FROM Кадровый_состав

**Ответ: D**

> ⚠ Спорный: ни один вариант не корректен полностью — B без GROUP BY, D с неверным порядком WHERE/GROUP BY. Выбран D как единственный с группировкой.

## Нұсқа 2

**1.** Файл-сервер архитектурасының кемшіліктері

- A) клиенттік қосымшалардың жеңілдеуі
- **B) желінің жоғары жүктемесіне байланысты өнімділіктің төмендеуі** ✅
- **C) клиент пен сервер арасындағы артық деректерді беру** ✅
- D) бір мезгілде сұраныстарды өңдеудегі шектеулер
- **E) бірнеше жазбалар сұралған кезде барлық кестенің берілуіне байланысты артық трафик** ✅
- F) клиенттер мен операциялардың көбеюімен сервер масштабтау мәселелеріне тап болуы мүмкін

**Ответ: B, C, E**

> ⚠ Спорный: недостатком файл-серверной архитектуры можно считать и D — но тест допускает не более трёх ответов.

**2.** Тұтастық шектеулерін орнату үшін маңызды

- A) UNIQUE
- **B) FOREIGN KEY** ✅
- C) NO ACTION
- **D) PRIMARY KEY** ✅
- E) CHECK
- F) NULL
- G) CLUSTERED

**Ответ: B, D**

**3.** Мәндік тұтастықты қамтамасыз ететін шектеу

- A) PRIMARY KEY
- **B) CHECK** ✅
- C) FOREIGN KEY
- D) IDENTITY
- E) UNIQUE
- F) NULL

**Ответ: B**

> ⚠ Спорный: «мәндік тұтастық» (доменная целостность) — это CHECK; UNIQUE (E) относится к целостности сущностей. Уточнить у преподавателя.

**4.** 1:1 байланыс үшін қатынас қалыптастыру ережелері

- A) егер байланыс дәрежесі 1:2 және тиістілік класы бір мағына үшін міндетті және екінші мағына үшін міндетті емес болса
- **B) егер бинарлы байланыстың дәрежесі 1:1 және тиістілік класы екі мағына үшін міндетті болса** ✅
- C) егер бинарлы байланыстың дәрежесі N:1 және тиістілік класы екі мағына үшін міндетті болса
- D) егер байланыс дәрежесі 2:1 және тиістілік класы бір мағына үшін міндетті және екінші мағына үшін міндетті емес болса
- E) егер байланыс дәрежесі 1:1 және тиістілік класы бір мағына үшін міндетті және екінші мағына үшін міндетті емес болса
- F) егер бинарлы байланыстың дәрежесі 1:N және тиістілік класы екі мағына үшін міндетті болса

**Ответ: B**

**5.** Әр семестрдегі емтихан саны

- A) SELECT Semester, COUNT(*) AS 'ExamCOUNT' / FROM UCHPLAN / WHERE Report = 'емтихан' / ORDER BY Semester DESC;
- B) SELECT Semester, COUNT(EXAM) AS 'ExamCOUNT' / FROM UCHPLAN / WHERE Report = 'емтихан' / ORDER BY Semester;
- C) SELECT Semester, COUNT(*) AS 'ExamCOUNT' / FROM UCHPLAN / WHERE Report = 'емтихан';
- **D) SELECT Semester, COUNT(*) AS 'ExamCOUNT' / FROM UCHPLAN / WHERE Report = 'емтихан' / GROUP BY Semester;** ✅
- E) SELECT Semester, COUNT(*) AS 'ExamCOUNT' / FROM UCHPLAN / GROUP BY Semester;
- F) SELECT Semester, COUNT(*) AS 'ExamCOUNT' / FROM UCHPLAN / WHERE Report == 'емтихан';

**Ответ: D**

**6.** F жиынынан F* жиынын құрудағы аксиомалар

- **A) біріктіру** ✅
- **B) бөліп алу** ✅
- C) кеңейту
- D) байланыстыру
- E) декомпозиция
- F) қосу

**Ответ: A, B**

> ⚠ Спорный: «бөліп алу» (B) и «декомпозиция» (E) — синонимы, а «кеңейту» (C) — аксиома Армстронга. Уточнить у преподавателя.

**7.** Microsoft SQL Server-де кестелерді жасау тәсілдері

- A) OLE DB
- B) DESKTOP
- C) DB-LIB
- D) ALTER TABLE
- **E) SQL Server Enterprise Manager** ✅
- F) STANDARD
- **G) CREATE TABLE** ✅

**Ответ: E, G**

**8.** Мән-байланыс моделінің диаграммасындағы әлсіз мән [ER-диаграмма: DEPARTMENT, EMPLOYEE, DEPENDENT, PROJECT, SUPPLIER, PART]

- **A) DEPENDENT (Қараудағы адам)** ✅
- B) PART (Бөлшек)
- C) ENAME (Толық аты)
- D) SUPPLIER (Жеткізуші)
- E) DEPARTMENT (Бөлім)
- F) PROJECT (Жоба)
- G) EMPLOYEE (Жұмыскер)

**Ответ: A**

**9.** Реляциялық модельдегі кесте жолы

- **A) кортеж** ✅
- B) primary key
- C) атрибут
- **D) tuple** ✅
- E) домен
- F) бастапқы кілт

**Ответ: A, D**

**10.** Реляциялық алгебраның алдыңғы амал нәтижесіне бір атау меншіктеу амалы

- A) көбейту
- **B) меншіктеу** ✅
- C) проекцияны құру
- D) біріктіру
- E) қиылысу
- F) бөлу
- G) қосу
- H) айыру

**Ответ: B**

**11.** Транзакцияның қасиеттері

- A) оптимизациялау
- **B) келісілгендік** ✅
- C) бүтіндік
- **D) атомарлылық** ✅
- E) компиляциялық
- **F) ұзақтылық** ✅
- G) репликациялық

**Ответ: B, D, F**

**12.** Фрагменттеуді жеңілдетудің негізгі әдістері

- A) логикалық фрагменттеу
- B) статикалық фрагменттеу
- C) динамикалық фрагменттеу
- **D) вертикальді** ✅
- **E) қарапайым горизонталды** ✅
- **F) горизонталды туынды** ✅
- G) сұрыпталған
- H) диагональді

**Ответ: D, E, F**

**13.** SQL Server агенті үшін тапсырмалар мен оқиғаларды жоспарлау туралы ақпаратты және операторлардың жұмысын ұйымдастыру туралы ақпаратты қамтитын жүйелік мәліметтер базасы

- A) master
- B) tempdb
- C) model
- D) odbc
- **E) msdb** ✅
- F) resource
- G) bcp

**Ответ: E**

**14.** Сырттай қосылу мен тета қосылу [белгілер қаріппен бұрмаланған]

- A) RÎÎS
- B) RÎÏ=S
- **C) RÉIS; RÍ ÉS** ✅
- D) RÉS
- E) RÍFS
- F) RÎÎFS

**Ответ: C**

> ⚠ Ненадёжный скан: символы обозначений в исходнике испорчены шрифтом и не читаются. Сверить с оригиналом.

**15.** Бастапқы кілттің белгісі және кесте үшін сыртқы кілтті шектеу

- A) CHECK
- B) UNIQUE
- **C) PRIMARY KEY** ✅
- **D) REFERENCES** ✅
- E) NOT NULL
- F) NOT IN
- **G) FOREIGN KEY** ✅

**Ответ: C, D, G**

**16.** Екі кестенің декарттық көбейтуін шығаратын сұраныс

- A) select table2.column1 from table1,table2 / where table1.column1=table2.column1
- B) select table1.column1,table2.column1 / from table1,table2 / where table1.column1=table2.column1
- C) select table2.column1 from table2 / where table2.column1=table2.column1
- **D) select table1.column1 from table1,table2** ✅
- E) select table1.column1 from table1,table2 / where table1.column1=table2.column1
- F) select table2.column1 from table1 cross join table2
- G) select table1.column1 from table2,table1 / where table2.column1=table1.column1

**Ответ: D**

**17.** Егер сөйлемде DESC кілттік сөзі бар болса

- A) сұраныс жасалып отырған кесте жойылады
- B) сұраныс жасалып отырған кестенің бағандары жойылады
- C) сұраныс жасалып отырған кестенің бағандары ретке келтіріледі
- D) ретке келтіру әрекеті өсу реті бойынша жүреді
- E) сұраныс жасалып отырған кестенің құрылымы өзгереді
- **F) сұраныс жасалып отырған кестенің жазбалары ретке келтіріледі** ✅
- **G) ретке келтіру әрекеті кему реті бойынша жүреді** ✅

**Ответ: F, G**

**18.** Байланыс 1:1

- A) мағынасыз байланыс
- B) бір класс түйінінің бір данасы басқа класс түйінінің көптеген данасымен байланысқан
- C) жұптық байланыс
- D) бір класс түйінінің бірнеше данасы басқа класс түйінінің бірнеше данасымен байланысқан
- **E) бір класс түйінінің бір данасы басқа класс түйінінің бір данасымен байланысқан** ✅
- F) байланыстың әр жағындағы түйіндердің максималды санымен белгілейді

**Ответ: E**

**19.** Бағасы, барлық тауарлардың орташа арифметикалық мәнінен кем тауарларды кестеден жоятын DML команда

- **A) delete from products / where price<(select sum(price)/count(*) from products);** ✅
- B) delete from products / where price<=avg(price);
- C) delete from products / where price<avg(price);
- D) truncate products / where price<(select mean(price) from products);
- **E) delete from products / where price<(select avg(price) from products);** ✅
- F) remove from products / where price<(select avg(price) from products);
- G) drop products products / where price<(select avg(price) from products);

**Ответ: A, E**

**20.** Шарттар спецификациясын құру әдістері

- A) Data Manipulation Language(DML)
- **B) Hierarchy plus Input Processing-Output(HIPO)** ✅
- **C) Structured Analysis and Design Techique(SADT)** ✅
- D) Interface Definition Languag
- E) Binary Large OBject (BLO)
- F) Data Definition Language (DDL)
- **G) Data Flow Diagrams(DFD)** ✅
- H) Data Control Language(DCL)

**Ответ: B, C, G**

---

# Казахская версия — Алгоритмдер және деректер құрылымы

## Нұсқа 1

**1.** Функциядағы қайтару операторы

- **A) return** ✅
- B) if
- C) else
- D) while
- E) for

**Ответ: A**

**2.** C++ тілінде функция белсенді болады егер оны

- A) жойса
- B) шығарса
- C) көшірсе
- D) енгізсе
- **E) шақырса** ✅

**Ответ: E**

**3.** Фибоначчи сандарын есептеу функциясында рекурсияның әр деңгейін шақыруды екі есе өсіреді, сондықтан Фибоначчидің n-санын есептеу 2ⁿ болады. Есептеу әдісінде бұл күрделілік аталады

- A) сызықтық-логарифмдық
- B) сызықтық
- C) логарифмдық
- D) квадраттық
- **E) экспоненттік** ✅

**Ответ: E**

**4.** Есептегі енгізу және шығару деректерін анықтау. Есеп: Шеңбердің ұзындығын екі тәсілмен табу керек, егер диаметрі d белгілі болса: L = π·d және радиусы R белгілі болса: L1 = 2·π·R. R радиусын қолданып, дөңгелектің ауданын табу керек: S = π·R²

- A) S, L, L1 және π, R, d;
- **B) π, R, d және S, L, L1;** ✅
- C) R, L, L1 және π, S,d;
- D) π, S, R және d, L, L1;
- E) R, d, L1 және π, S, L;

**Ответ: B**

**5.** Стек пен кезектердің қолданылатын саласы

- **A) функцияны шақыру және оны орындау** ✅
- B) жергілікті және жаһанды айнымалыларға мән беру
- C) процедура мен функцияларға аргументтер мәнін жіберу
- D) процедурадағы жаһанды айнымалыны шақыру
- E) процедура мен функцияларға цикл қолдану

**Ответ: A**

**6.** Алгоритмнің факториалдық күрделілігі

- A) O(n³)
- B) O (n log n)
- C) O (log n)
- **D) O(n!)** ✅
- E) O(1)

**Ответ: D**

**7.** Қойылған есептің күрделілігіне қарай алгоритмнің жұмысын анықтайтын функция анықталады

- A) кейздейсоқ сандармен
- B) сандық алгоритмдермен
- C) арифметикалық көбейтулермен
- D) шешімдердің қабылдауымен
- **E) асимптотикалық күрделілігімен** ✅

**Ответ: E**

**8.** Бағытталған графта кез келген төбелерден кезкелген төбелерге жолдары бар максималды төбелер жиынын құрайды

- A) байланыспаған қабырғалар жиыны
- B) байланыспаған жолдар жиыны
- C) байланыспаған төбелер жиыны
- D) жеңіл байланыстағы компонент
- **E) мықты байланысты компонент** ✅

**Ответ: E**

**9.** Қызыл-қара теңестірілген ағаштың түбірі әр уақытта

- A) көк
- B) қызыл
- C) ақ
- **D) қара** ✅
- E) жасыл

**Ответ: D**

**10.** C++ тіліндегі бағдарлама фрагменті орындалу нәтижесінде экранға шығады  
{  
….  
for (int i=0; i < 15; i++)  
for (int j=0; j < 14; j++)  
a[i][j]= 1 + random (9);  
…  
printf(" %i", a[i][j]);  
getch();  
}

- A) 9 - 15 диапазонындағы кездейсоқ сандармен толтырылған 15 жолдан және 14 бағаннан тұратын екі өшемді массив шығады
- B) 1 - 14 диапазонындағы кездейсоқ сандармен толтырылған 9 жолдан және 15 бағаннан тұратын екі өшемді массив шығады
- C) 9 - 14 диапазонындағы кездейсоқ сандармен толтырылған 15 жолдан және 9 бағаннан тұратын екі өшемді массив шығады
- D) 1 - 15 диапазонындағы кездейсоқ сандармен толтырылған 9 жолдан және 9 бағаннан тұратын екі өшемді массив шығады
- **E) 1– 10 диапазонындағы кездейсоқ сандармен толтырылған 15 жолдан және 14 бағаннан тұратын екі өшемді массив шығады** ✅

**Ответ: E**

**11.** C++ тіліндегі функцияның денесі тұрады

- **A) жариялау мен операторлардан** ✅
- B) түсініктемелер мен модульдерден
- C) кітапханалар мен модульдерден
- D) жарияланған қарапайым типтерден
- E) түсініктемелер мен кітапханалардан

**Ответ: A**

**12.** Берілген key кілті үшін хеш-функция әр уақытта бірғана хеш-код has(key) қайтаруы тиіс

- **A) determinism** ✅
- B) multiplication method
- C) double hashing
- D) uniform hashing
- E) division method

**Ответ: A**

**13.** Соқтығуды шешу барысында бір ұяшықта хештелген барлық элементтерді байланысқан тізімге біріктіреміз. Мұндағы j ұяшығында кілтінің хеш-мәні j-ға тең болатын тізімдегі барлық элементтерінің төбесіне көрсеткіші орналасады, егер элемент жоқ болса ұяшықта NIL мәні орналасады. Бұл әдіс аталады

- A) Ашық адрестеу
- B) Шаршылық зерттеу
- **C) Бір тізбекті** ✅
- D) Сызықты зерттеу
- E) Қос хештау

**Ответ: C**

**14.** Жолдар құрылымы ретінде ұйымдастырылатын тәсіл

- A) бірікпеген тізімдер
- B) графтар
- **C) біріккен сызықты тізім** ✅
- D) бинарлық үйін
- E) бинарлық ағаш

**Ответ: C**

> ⚠ Спорный: формулировка «Жолдар құрылымы» допускает и «графтар» (B). Уточнить у преподавателя.

**15.** Бос орынмен бір бірінен бөлінген символдардың тізбегі

- A) атрибуттар
- B) тұрақты тіркестер
- **C) лексема** ✅
- D) функция
- E) көрсеткіштер

**Ответ: C**

**16.** Ұрпақтық түйіндердің саны көрсетеді

- A) түйіндердің тереңдігін
- B) түйіндердің биіктігін
- C) түйіндердің толықтығын
- D) түйіндердің енін
- **E) түйіндердің дәрежесін** ✅

**Ответ: E**

**17.** C++ тілінде оңға және солға жылжыту операциялары орындалғанда, оң жақтағы және сол жақтағы биттер босатылып, орнына жазылады

- A) теріс сандар
- B) сызықтар
- C) сұрақ белгілері
- **D) нөлдер** ✅
- E) көбейту белгілері

**Ответ: D**

**18.** Бағытталған циклы жоқ граф

- **A) ациклді** ✅
- B) сыбайласқан
- C) циклді
- D) байланыспаған
- E) инциденті

**Ответ: A**

**19.** А массивін сұрыптау барысында i-шы этапта A[i]- элементін алып алдындағы тәртіптелген элементтердің арасына A[1], A[2], …, A[i - 1] тиісті орынға орналастырамыз

- A) шелл сұрыптауы
- **B) кірістіру арқылы сұрыптау** ✅
- C) разрядтты сұрыптау
- D) көпіршікті сұрыптау
- E) таңдау арқылы сұрыптау

**Ответ: B**

**20.** C++ тіліндегі switch құрылымына енетін бірнеше белгі және міндетті емес белгілердің атауы

- A) if, else
- **B) case, default** ✅
- C) else, case
- D) for, then
- E) continue, break

**Ответ: B**

**21.** C++ тіліндегі бағдарлама фрагменттегі есептеулерді сипаттайды  
factorial =1;  
for (int counter = number; counter >=1; counter--)  
factorial *=counter;

- A) бағдарламалық
- **B) итеративті** ✅
- C) логикалық
- D) рекурсивті
- E) математикалық

**Ответ: B**

**22.** Көпіршікті сұрыптау алгоритміне негізделген сұрыптау әдісі

- A) пирамидалық
- B) шелл
- **C) шейкерлік** ✅
- D) таңдау арқылы
- E) шаршылық

**Ответ: C**

**23.** C++ тіліндегі бағдарлама фрагментіндегі екі өлшемді массивтегі жол мен бағанның саны  
{  
static int a[?][?]={{5,3,4,2}, {3,3,4,5}, {2,3,3,4} {5,3,8,4}};  
int i, j, s = 0;  
float c = 0;  
…  
}

- A) 6, 4
- B) 3, 5
- C) 2, 3
- **D) 4, 4** ✅
- E) 5, 4

**Ответ: D**

**24.** Бинарлық іздеу ағашының биіктігі бойынша теңестіру түрлері

- **A) AVL, қызыл-қара** ✅
- B) ГМВ, Қара-қызыл
- C) тереңдік пен ені бойынша
- D) қызыл-көк, DFS
- E) BFS, DFS

**Ответ: A**

**25.** C++ тіліндегі бағдарламаның нәтижесін анықтау  
#include<iostream.h>  
#include<string.h>  
main()  
{  
Char string [10]="ББББББББ"  
cout << (char *)memset (string1, 'c', 3) << endl;  
return 0;  
}

- A) БББcccccc
- **B) cccБББББ** ✅
- C) cccБББccc
- D) ccccccБББ
- E) ББББББccc

**Ответ: B**

**26.** Параметрлік циклды қолданғанда пайдаланатын оператор

- A) while
- B) case
- C) if
- D) else
- **E) for** ✅

**Ответ: E**

**27.** Сұрыптау жасау барысында берілген массив екі массивке бөлініп, әр қайсысы рекурсияны қолданып сұрыпталады, соңында екіге бөлінген сұрыпталған массивты i және j екі индекстің қолдануымен сол жағындағы және оң жағындағы ішкі массивтерден ең кіші элементті алып жаңа массивке салу арқылы біріктіреді. Бұл сұрыптау әдісінің атауы

- A) квадратты (squarsort)
- B) разрядтты (radixsort)
- **C) қосу (margesort)** ✅
- D) жылдам (quicksort)
- E) көпіршікті (bubblesort)

**Ответ: C**

**28.** Қабырғалар арқылы байланысқан төбелердің кез келген тізбегі

- **A) жол** ✅
- B) бағыт
- C) ілмек
- D) төбе
- E) қабырға

**Ответ: A**

**29.** Белгілі бір тапсырмаларды орындауға арналған программаның жеке дара бөлігі

- A) іздеу
- B) сұрыптау
- C) массив
- **D) функциялар** ✅
- E) ерекшелеу

**Ответ: D**

**30.** Элементті іздеу мен жою байланысқан тізімнің ұзындығына байланысты. Хеш-кестеден элементті іздеу және жою операциясының есептеу күрделілігі нашар жағдайда болады

- **A) Θ(n)** ✅
- B) Θ(1)
- C) Θ(log n)
- D) Θ(cⁿ)
- E) Θ(n²)

**Ответ: A**

## Нұсқа 2

**1.** Алгоритмдердің міндетті қасиеттерінің бірі

- A) түсіндірмелік
- B) анықталмағандық
- C) шексіздік
- **D) дискреттілік** ✅
- E) үздіксіздік

**Ответ: D**

**2.** Көптік таңдау құрылымы

- A) if
- B) do-while
- C) while-do
- D) if-else
- **E) switch** ✅

**Ответ: E**

**3.** C++ тілінде бағдарламаның негізгі бөлігі келтірілген. Нәтижесінде экранға шығатын жауап  
double x=3.5;  
int y;  
if(x==0) y=7*pow(x,3);  
else y=2*pow(x,3);  
cout<<y;

- A) 0
- B) 85.75
- **C) 85** ✅
- D) 75
- E) 54

**Ответ: C**

**4.** Префиксті декремент дұрыс жазылуы

- A) a--
- B) -=a
- C) a-=
- **D) --a** ✅
- E) +=a

**Ответ: D**

**5.** Постфиксті декремент дұрыс жазылуы

- A) -=a
- B) --a
- C) a++
- D) +=a
- **E) a--** ✅

**Ответ: E**

**6.** ЖӘНЕ логикалық операторының дұрыс жазылуы

- A) a||b
- **B) a&&b** ✅
- C) a!
- D) a//b
- E) a<<b

**Ответ: B**

**7.** S жолы бос болғанда true, ал бос болмағанда false қайтаратын жолдардағы әдіс

- A) S.substr()
- B) S.find()
- C) S.insert()
- D) S.size()
- **E) S.empty()** ✅

**Ответ: E**

**8.** #include <iostream>  
using namespace std;  
int main()  
{int i = 25;  
if (i > 15) cout << "i-дің мәні 15 -тен үлкен";  
else cout << "i-дің мәні 15-тен кіші";  
return 0;  
Тармақталған алгоритмдік құрылымы нәтижесінде жауапқа шығатын өрнек

- **A) i-дің мәні 15 -тен үлкен** ✅
- B) i-дің мәні 15-ке жуық
- C) i-дің мәні 15-ке тең
- D) i-дің мәні белгісіз
- E) i-дің мәні 15-тен кіші

**Ответ: A**

**9.** Массивтерді сыртқы сұрыптау алгоритмі

- **A) біріктіріп сұрыптау** ✅
- B) қосып сұрыптау
- C) шейкерлік сұрыптау
- D) көпіршікті сұрыптау
- E) кірістіріп сұрыптау

**Ответ: A**

**10.** int func() функциясы қайтарады

- A) символ деректі
- B) мәтін деректі
- **C) бүтін деректі** ✅
- D) бөлшек деректі
- E) логикалық деректі

**Ответ: C**

**11.** f(n)=n! функцияларының дұрыс берілуі

- A) f(0)=1, f(n)=f(n - 1)+1
- B) f(0)=0, f(n)=f(n - 1)+2
- C) f(0)=1, f(n)=2n*f(n - 1)
- **D) f(0)=1, f(n)=n*f(n - 1)** ✅
- E) f(0)=0, f(n)=f(n - 1)+1

**Ответ: D**

**12.** printf() функциясының дұрыс жазылуы

- A) int a; printf("%c", a);
- B) int a; printf("a=%s", a);
- C) int a; printf("%s", a);
- **D) int a; printf("%d", a);** ✅
- E) int a; printf("a=&i", a);

**Ответ: D**

**13.** Массивтегі іздеу алгоритмінің классификациясы

- A) шелл іздеуі
- B) таңдап іздеу
- C) кірістіріп іздеу
- **D) екілік (бинарлы) іздеу** ✅
- E) квадраттық іздеу

**Ответ: D**

**14.** 2 3 17 7 8 9 1 4 6 9 2 3 1 18 тізбегі үшін табиғи біріктіріп сұрыптаудың бірінші этапы

- **A) b=2 3 17 1 4 6 9 1 18 c=7 8 9 2 3 a= 2 3 7 8 9 17 1 2 3 4 6 9 1 18** ✅
- B) b=21 2 3 3 4 6 7 8 9 9 17 c=18 1 a= 1 1 2 2 3 3 4 6 7 8 9 9 17 18
- C) b=1 2 2 3 3 4 6 7 8 9 9 17 c=1 18 a= 1 18 2 2 3 3 4 6 7 8 9 9 17 1
- D) b=2 3 17 7 4 6 9 1 18 c= 1 8 9 2 3 a= 1 2 2 3 3 4 6 7 8 9 9 17 1 18
- E) b=2 3 7 8 9 17 1 18 c=1 2 3 4 6 9 a= 2 3 7 8 9 17 1 2 3 4 6 9 1 18

**Ответ: A**

**15.** (6, 3, 2, 8, 1, 7, 4, 5) бастапқы тізбек үшін көпіршік әдісімен сұрыптау алгоритмінің бірінші қадамының нәтижесінде алынатын тізбек

- A) (1, 2, 3, 8, 6, 7, 4, 5)
- B) (3, 2, 8, 6, 7, 4, 5, 1)
- **C) (3, 2, 6, 1, 7, 4, 5, 8)** ✅
- D) (2, 6, 3, 1, 4, 8, 5, 7)
- E) (6, 3, 2, 8, 1, 7, 4, 5)

**Ответ: C**

**16.** Көпіршікті сұрыптау алгоритмінің уақыттық күрделілігі

- A) O(n³)
- B) O(n log n)
- **C) O(n²)** ✅
- D) O(1)
- E) O(log n)

**Ответ: C**

**17.** Алгоритм күрделілігінің өсу ретімен орналасқан нұсқалары

- A) O(N²), O(N), O(log N)
- **B) O(1), O(N), O(N³)** ✅
- C) O(2N), O(N), O(1)
- D) O(N), O(1), O(N log N)
- E) O(N²), O(log N), O(N³)

**Ответ: B**

**18.** O(log n) уақытта жұмыс істейтін алгоритм

- A) екі матрицаны көбейту алгоритмі
- B) сызықты іздеу алгоритмі
- C) көпіршікті сұрыптау алгоритмі
- D) бүтін санның тақ-жұптығын табу алгоритмі
- **E) екілік іздеу алгоритмі** ✅

**Ответ: E**

**19.** Бір байланыстырылған тізім анықтамасы

- A) бұл FILO принципі бойынша жұмыс істейтін мәліметтер құрылымы
- B) бұл дерек пен келесі және алдыңғы түйінге көрсеткіші бар мәліметтер құрылымы
- C) бұл LILO принципі бойынша жұмыс істейтін мәліметтер құрылымы
- D) бұл LIFO принципі бойынша жұмыс істейтін мәліметтер құрылымы
- **E) бұл дерек пен келесі түйінге көрсеткіші бар мәліметтер құрылымы** ✅

**Ответ: E**

**20.** C++ тілінде динамикалық бүтін типті массивті жариялаудың дұрыс жазылуы

- **A) int* a = new int[n]** ✅
- B) int* a = new int*[n]
- C) int a = new int[n]
- D) int a[n]
- E) int* a = new int(n)

**Ответ: A**

**21.** Стек әдістеріне жатпайтын функция

- A) pop()
- B) size()
- C) push()
- D) clear
- **E) contains()** ✅

**Ответ: E**

**22.** Хеш кестесінің анықтамасы

- A) хеш кестесі – типтері бірдей элементтерден тұратын деректер құрылымы
- B) хеш кестесі – әр-түрлі типті реттелген деректердің құрылымы
- C) хеш кестесі – FIFO принципі бойынша жұмыс істейтін деректер құрылымы
- **D) хеш кестесі – өте жылдам іздеу мен қоюды қамтамасыздандыратын деректер құрылымы** ✅
- E) хеш кестесі – бір-бірімен байланысқан деректер құрылымы

**Ответ: D**

**23.** Толтырылған массив ұяшығына кілтті хештеудің атауы

- A) бірігу
- **B) коллизия** ✅
- C) ажырау
- D) қиылысу
- E) бөліну

**Ответ: B**

**24.** Хеш кестесінде коллизиядан құтылу әдісі

- **A) ашық адресациялау әдісі** ✅
- B) трапеция әдісі
- C) орамдар әдісі
- D) қадамдық бөлшектеу әдісі
- E) квадрат ортасы әдісі

**Ответ: A**

**25.** AVL ағашында жою операциясының орындалу уақыты

- A) O(n³)
- B) O(n²)
- C) O(nlogn)
- **D) O(logn)** ✅
- E) O(1)

**Ответ: D**

**26.** 20 түйіні бар толық екілік ағаш бар. тамыры 0 деңгейінде орналасқан болса 4 деңгейіндегі түйін саны

- A) 0
- B) 8
- C) 1
- D) 4
- **E) 5** ✅

**Ответ: E**

**27.** Екілік іздеу ағашындағы қызылды-қаралы ағаш қасиеттерінің бірі

- A) түйіннің сол ішкі ағашының кілтінің мәні түйіннің кілтінің мәнінен үлкен болса
- B) барлық қызыл-қара ағаштың жапырақтары бір деңгейде орналасса
- C) түйіннің сол ішкі ағашының кілтінің мәні түйіннің кілтінің мәнінен кіші болса
- **D) егер төбе қызыл, онда оның екі мұрагері де қара** ✅
- E) әрбір түйіннің ең болмағанда бір ішкі ағашы бос

**Ответ: D**

**28.** Графтың түйінінің атауы

- A) мекенжай
- B) қабырға
- **C) төбе** ✅
- D) нүкте
- E) жол

**Ответ: C**

**29.** Барлық төбелік жұптар үшін ең қысқа жолдарды құру есебінде ең қысқа жол ізделеді

- A) бастапқы төбеден бастап бірнеше қабырға қашықтықтағы басқа шыңдарға дейін
- **B) әр төбеден барлық басқа төбелерге дейін** ✅
- C) бастапқы төбеден бастап бір қабырға қашықтықтағы басқа шыңдарға дейін
- D) бастапқы төбеден басқа төбелерге дейін
- E) әр төбеден бастапқы төбеге дейін

**Ответ: B**

**30.** Егер байланыспаған графтың төбелерінің әрқайсысы басқаларымен қабырғалармен жалғанған болса онда ол граф

- A) толық емес граф деп аталады
- B) гиперграф деп аталады
- C) шынжыр(тізбек) деп аталады
- **D) толық граф деп аталады** ✅
- E) мультиграф деп аталады

**Ответ: D**

