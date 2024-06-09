# Heritage-Sites-Map-of-Orel
## Состав комнады
Ашурокова Мария
Козырева Алина
Кунина Анастасия

## Ссылка на карту

## Краткая информация о городе

Текст от Насти

## Описание используемых данных с указанием источников
Административные раницы города Орел выгружены из OSM.
Для слоя с историческими границами города 1611 и 1779 годов были использованы иллюстративные материалы из работы Неделина В.Н. «Орел изначальный». – Орел: Вешние воды. 2001. Границы оцифрованы в QGIS с использованием Georeferencer.
Полигоны зданий получены из OSM. При помощи join attributes by location ним были доабвлены атрибуты из предоставленных данных об ОКН. Для части зданий в слое OSM отсутствовали полигоны, в связи с чем для полноты отображения, часть недостащих объектов были отрисованы вручную.
Зоны охраны ОКН были выгружены из ФГИС ТП и при помощи dissolve объединины в один объект

## Описание основных методов
В качестве дополнительных слоев для карты взяты административная граница городского округа, установленные зоны охраны объектов культурнго наследия, исторические границы города Орел. Отображение настроено через style function = lambda feature, для исторических границ дополнительно использван footlip.
В качестве дополнительного функционала использованы MousePosition, Fullscreen и MiniMap.

## Рефлексия
Наибольшое затруднение в работе (можно только это) ...
Лучше всего получилось ...
Не получилось ...
