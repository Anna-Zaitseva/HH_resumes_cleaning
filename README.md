# Проект 1. Анализ резюме с сайта hh.ru

## Оглавление  
[1. Описание проекта](.README.md#Описание-проекта)  
[2. Какой кейс решаем?](.README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](.README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](.README.md#Этапы-работы-над-проектом)  
[5. Результат](.README.md#Результат)    
[6. Выводы](.README.md#Выводы) 

### Описание проекта    
Достаем ключевые данные, создаем новые признаки об образовании, опыте работы, готовности
к переездам/командировкам и пр., исследуем взаимосвязи между призаками, очищаем данные от 
мусора: явных ошибок и аномалий.

[Датасет с исходными данными](https://drive.google.com/file/d/1ey3veR0Uylro0xRW-qAnSxyytYfDmdXf/view?usp=sharing)

[Вспомогательная таблица курсов валют](https://drive.google.com/file/d/1EyGcYvQXGla7l85a_pUw8iyPQAaHYdOv/view?usp=sharing)


### Какой кейс решаем?    
Нужно исследовать и очистить датафрейм от мусорных данных.

**Метрика качества**     
Отсутсвие нереальных данных (например, 14-летний соискатель с опытом работы 30+ лет) 
и пропущенных данных. 

**Что практикуем**     
Учимся писать хороший код на python, пользоваться библиотеками NumPy, Pandas, строить
и читать графики.


### Краткая информация о данных
Датасет содержит информацию из резюме примерно 44 тыс. соискателей из разных регионов РФ и 
стран ближнего зарубежья: пол, возраст, уровень образования, желаемая должность, зарплатаб
готовность к переезду/командировкам, пожелания к графику, опыт работы, последнее место работы,
дату и время обновления резюме.
  
  
### Этапы работы над проектом  
1. Исследование структуры данных.
2. Преобразование данных.
3. Исследование зависимостей в данных.
4. Очистка данных.


### Результаты:  
В итоге датафрейм уменьшился на 262 строки, что совсем немного для выборки размером более 44 тыс. 
Мы добавили новые (более информативные) признаки и удалили неинформативные. 


### Выводы:  

1. Уровень образования влияет на зарплату.
2. Чем старше кандидат, тем больше опыта работы.
3. Самая распространенная зарплата 50 тысяч.
4. Возраст большинства соискателей от 27 до 36 лет. Средний возраст 32 года.
5. Самые высокие зарплаты в Москве, с большим отрывом идет Санкт-Петербург. В городах-миллионниках
    и других городах зарплаты примерно на одном уровне. 
6. Женщин в представленном датафрейме всего 19 процентов, их уровень образования ничем не отличается
   от образования соискателей мужчин, но в то же время медианная зарплата на 10 тысяч рублей ниже. 
   Но поиск причин нужно осуществлять в другом исследовании. 
7. Разъезная работа оплачивается лучше. Кандидаты готовы сменить место жительства, если прибавка к 
   зарплате составит в среднем 10 тысяч рублей.

Если информация по этому проекту покажется вам интересной или полезной, то я буду очень вам благодарен, если отметите репозиторий и профиль ⭐️⭐️⭐️-дами
