---
title: MyHome Battery Modules
layout: page
menu_section: Железо
menu_level: 2
menu_item: MyHome Battery Modules
ermalink: "/products/battery_shild/"
menu_order: 13
---

**Модули батарейного питания для MyHome** 
## Описание

Два модуля батарейного питания для контроллеров **MyHome**. Отличаются типами
батарей и, как следствие этого, размерами.

Оба модуля имеют управляемый повышающий стабилизатор на 3.3В и работают в трех
режимах:

1. Режим с отключенным стабилизатором. Применяется, когда когда напряжение 
батарейного питания достаточно для питания контроллера, радиомодуля и периферии. 
(Например установлено две свежие щелочные батареи или литиевые батареи ААА 
с напряжением питания 1.65В)

2. Режим с постоянно включенным стабилизатором. Применяется, когда можно полностью
использовать ресурс батареи, разрядив ее практически в "0" 
(не рекомендуется применять в аккумуляторах, так как они, как правило, не переживают 
такого). В этом режиме контроллер и периферия вполне нормально могут уходить включенным
режим глубокого сна с низким потреблением. Сам стабилизатор в режиме холостого хода 
потребляет Ток до 60мкА.

3. Режим периодически включаемого стабилизатора. Обеспечивает максимально низкое
потребление при низком напряжении питания. В этом режиме контроллер в режиме сна
питается от батареи напрямую, а при активном действии с радиомодулем и периферией
включает повышающий стабилизатор. В отличии от предыдущего режима, напряжение батареи
может снизится только до минимального, при котором может работать микроконтроллер. 
Обычно это ограничение BOM на 1.8В, что позволяет использовать NiMh аккумуляторы, разряжая их
до 0.9В.  

### Подключение и управление
Батарейные модули подключаются к любому из 8-контактных разъемов контроллера MyHome Controller в 
положении бутерброда (контроллер и модуль друг над другом)

Первый пин 3.3CH (A0 или D2 в зависимости от выбранного разъема) отвечает за включение и отключение
повышающего стабилизатора логическим уровнем.

Второй пин LED (A1 или D3 в зависимости от выбранного разъема) включает или отключает светодиод на плате.


### Модуль на двух элементах AAA 1.5В
![](/products/AAA-3D-1.jpg)
![](/products/AAA-3D-2.jpg)

### Модуль на литиевой батарее CR2450 3.0В
![](/products/CR2450-3D-1.jpg)
![](/products/CR2450-3D-2.jpg)

