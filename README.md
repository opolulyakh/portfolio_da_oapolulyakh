# Портфолио Аналитик Данных Полулях Оксана
 
# Обо мне 
Привет! Меня зовут Оксага, я начинающий аналитик данных.В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.

# Навыки и технологии
<br> Инструменты анализа данных: SQL, Excel:
<br>Системы управления базами данных: MySQL

# Проекты

Проект 1: Калькулятор юнит-экономики онлайн-кинотеатра

Что нужно было сделать:

Задача №1: Необходимо посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25-процентную маржинальность
Задача №2: Собрать хорошую наглядную визуализацию, где будет показано, кто, где и в каком объеме смотрит фильмы на нашей платформе
Задача №3: Собрать калькулятор юнит-экономики нашего продукта
Как решала(-а): 
1. Сначала расчитала показатели юнит экономики за прошедший период
2. Провела анализ по активностям клиентов, в какие часы клиенты более активны, среднее количество просмотров на 1 юзера, количество подписок ежемесячно и т.д.
3. Собрала по текущим данным калькулятор
4. Добавила строки и стобци для прогнозирования а также столбец для внесение изменений
5. Выявила что у компании высокие расходы на продвижение и при этом низкая активность юзеров, из-за чего они не окупаются
6. С помощью функционала Excel "Поиск решений" и постановки ограничений по параметрам % измениний, а именно уменьшить затраты на продвижение не больше чем 50%% и увеличить стоимость подписки не больше чем на 15% , для того чтобы цифры которым необходим следовать были реальными по расходу и при этом стоимость подписки оставалась привлекательной для клиентов
7. Далее визуализировала данные и собрала в презентацию

Ссылка на проект (ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)

Выводы (итоги):

Исключить неэффективные каналы привлечения - Найти современные платформы для рекламы, нанять блогеров

Увеличить Retention, «прокачивая» функционал платформы кинотеатра - Пополнение видеотеки, уточнение рекомендаций - Семейная подписка, детский режим, возможность загружать контент заранее

Активизация «спящих» пользователей - Рассылка от приложения раз в неделю «Мария, ваша подборка фильмов к выходным..»


Проект 2: Распределение балансов студентов онлайн школы

Что нужно было сделать:

Задача №1 В результате должен получиться запрос, который собирает данные о балансах студентов за каждый прожитый ими день.
Задача №2 Визуализация распределения балансов студентов
Как решала(-а): 

1. С помощью CTE конструкций собрала данные из разных таблиц, чтобы определить первое поступление, количество пройденных уроков за период, определить календарь и т.д.
2. С помощью внутрнего функционала визуализировала данные

Ссылка на проект (ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)

Выводы (итоги):

1. У некоторых студентов минусовой баланс, примеры id студентов: 1,984,910; 3,335,256 - что является фактом потери оплат
2. Также подозрительные пропуски уроков по 10-15 дней у студентов, как будто часть данных отсутствует
3. В целом динамика положительная по прохождению уроков, студенты проходят все больше и больше уроков, с каждым днем, тоже самое можно сказать и об оплатах
Баланс плавно растет, из-за чего можно сделать вывод, что скорость оплат выше чем скорость прохождений уроков


