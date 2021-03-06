#Обработка SVG-файла с помощью DOM

> __SVG__ – формат веторной графики, основанный на __XML__.

## Задание
* Найти в файле окружности `circle`, прямоугольники  `rect` и полилинии `polyline`
(вывести список на экран). Внимание: элементы могут быть вложены в группы `g`, возможно, нужен рекурсивный просмотр.
* У каждой окружности отметить центр красной точкой (добавить новый тег `circle` сразу после каждого тега `circle`). (Использовать `insertBefore`, `getParentNode`, клонирование узлов   и т. д. – на ваше усмотрение)
* Все прямоугольники `rect` перекрасить в один цвет, кривые `path` – в другой (2 строковые константы) (просто заменть атрибут `style`, старый стиль не сохранять)
* Сохранить модифицированный `Transform API` документ под другим именем.
* __XML__ – схемы не использовать (для __SVG__ слишком сложная схема).

### Примечания
__SVG__ Открывается любым современным браузером, для отладки можно редактировать __Netbeans__ или любым текстовым редактором.

> `<!DOCTYPE ...>` из файлов лучше удалить вручную!

За основу можно брать код примеров

> Анимации __SVG__, вероятно, не работают в _Internet Explorer_ при просмотре не с сервера