# Инженерный симулятор ОРБИТА

![Логотип Орбиты](logo.png)

Перед вами программый симулятор космического полета. Вы можете
конструировать аппраты и выполнять миссии по освоению планет Солнечной
системы, а также выполнять задачи на орбите Земли. Симулятор включает
множество моделей (баллистика, посадка на планеты, радио, теплообмен и
пр.)  Программы полета аппарата можно писать на языке Python, также
для программирования аппаратов можно использовать иерерхические машины
состояний, которые автоматически переводятся в программу полета.

Вам доступны две версии симулятора: 

* **planets** - первая версия, посвященная посадке на планеты и выполнению миссий на их поверхности;
* **earth** - вторая, более сложная версия симулятора, посвященная конструированию аппаратов для выполнения миссий на орбите Земли.

Каждая из версий дополнена специальным гравитационным калькулятором - программой для расчета
траекторий аппаратов в поле силы тяжести с учетом воздействия атмосферы и двигателей аппарата
(**planets_gravity** и **earth_gravity** соответственно).

Код симулятора распространяется под свободной лицензией GNU Public License (версия 3), документация -- под
свободной лицензией GNU Free Documentation License (версия 1.3).

Интерфейс и руководство к симулятору доступны на русском и английском языках. Русскоязычное руководство к
симулятору можно загрузить по адресу: https://disk.yandex.ru/d/IE_Xm2pjxk5zcw

Авторы симулятора:
* [Алексей Федосеев](mailto:aleksey@fedoseev.net)
* [Николай Сафронов](mailto:bfishh@gmail.com)
* [Илья Тагунов](mailto:tagunil@gmail.com)

Симулятор был реализован при поддержке компании [Образование будущего](https://introsat.ru)
и [Кружкового движения НТИ](https://kruzhok.org).
