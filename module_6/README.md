# unit_6
# Выбираем авто выгодно

## Описание проекта

Вы работаете в компании, которая занимается продажей автомобилей с пробегом в Москве. 

Основная задача компании и её менеджеров — максимально быстро находить выгодные предложения (проще говоря, купить ниже рынка, а продать дороже рынка). 

Руководство компании просит вашу команду создать модель, которая будет предсказывать стоимость автомобиля по его характеристикам.

Если такая модель будет работать хорошо, то вы сможете быстро выявлять выгодные предложения (когда желаемая цена продавца ниже предсказанной рыночной цены). Это значительно ускорит работу менеджеров и повысит прибыль компании.

В данном проекте требуется создать модель, которая будет предсказывать цена на автомобили, на основании данных из объявления. Т.к. пользователь сам оценивает свою машину. Эта модель может быть использована для выбора выгодных объявлений (когда установленная пользователем цена ниже предсказанной моделью)

Описание полей датасета:
+ 'bodyType' - тип кузова автомобиля 
+ 'brand' - марка (бренд) автомобиля
+ 'car_url' - прямая ссылка на объявление
+ 'color' - цвет кузова (16 цветов)
+ 'complectation_dict' - описание стандартной комплектация автомобиля
+ 'description' - свободное описание лота продавцом
+ 'engineDisplacement' - объем двигателя в литрах
+ 'enginePower' - мощность двигателя (л.с.)
+ 'equipment_dict' - дополнительные характеристики по комплектации авто
+ 'fuelType' - тип топлива (5 видов топлива: бензин, дизель, электро, гибрид, газ) 
+ 'image' - ссылка на изображение лота (фотография)
+ 'mileage' - пробег автомобиля (км)
+ 'modelDate' - модельный год автомобиля
+ 'model_info' - информация о моделе автомобиля в разных вариантах
+ 'model_name' - модель автомобиля (н-р, PASSAT) 
+ 'name' - общеупотребимое разговорное название 
+ 'numberOfDoors' - число дверей в автомобиле
+ 'parsing_unixtime' - точное время парсинга данного объявления
+ 'priceCurrency' - валюта объявленной в предложении цены
+ 'productionDate' - дата производства автомобиля 
+ 'sell_id' - уникальный идентификатор объявления
+ 'super_gen' - сложная конструкция об основных показателях (в т.ч. расход топлива)
+ 'vehicleConfiguration' - комбинация данных о типе кузова, трансмиссии, объеме двигателя 
+ 'vehicleTransmission' - тип трансмиссии (коробки передач) (4 вида: автоматическая, механическая, роботизированная, вариатор)
+ 'vendor' - регион производства автомобиля (Европа, Япония)
+ 'Владельцы' - количестов предыдущих владельцев автомобиля
+ 'Владение' - срок владения (последним владельцем)
+ 'ПТС' - тип паспорта технического средства (оригинал, дубликат)
+ 'Привод' - характеристика привода автомобиля
+ 'Руль' - положение руля (левый, правый)
+ 'Состояние' - требует или нет текущего ремонта
+ 'Таможня' - растаможен или нет
