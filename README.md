**Задача проекта:**
Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. 
В нём можно быстро узнать рыночную стоимость своего автомобиля. В вашем распоряжении исторические данные: технические характеристики, 
комплектации и цены автомобилей. Вам нужно построить модель для определения стоимости.
В данном задании необходимо решить задачу регрессии, чтобы узнать рыночную стоимость автомобиля.

**Признаки:**
- DateCrawled — дата скачивания анкеты из базы
- VehicleType — тип автомобильного кузова
- RegistrationYear — год регистрации автомобиля
- Gearbox — тип коробки передач
- Power — мощность (л. с.)
- Model — модель автомобиля
- Kilometer — пробег (км)
- RegistrationMonth — месяц регистрации автомобиля
- FuelType — тип топлива
- Brand — марка автомобиля
- Repaired — была машина в ремонте или нет
- DateCreated — дата создания анкеты
- NumberOfPictures — количество фотографий автомобиля
- PostalCode — почтовый индекс владельца анкеты (пользователя)
- LastSeen — дата последней активности пользователя
- Price — цена (евро), целевой признак

**Вывод:**
В процессе исследования были изучены модели линейной регрессии, решающего дерева, случайного леса, LightGBM. Наилучший результат показала модель линейной регрессии.
Проверка модели линейной регрессии на тестовой выборке показала ее работоспособность.
RMSE модели линейной регрессии на валидационной выборке: 2546.0967646442464
Время работы модели: 22.9 s
