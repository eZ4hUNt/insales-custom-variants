![Кастомные варианты для товара в InSales](https://github.com/eZ4hUNt/insales-custom-variants/blob/master/Screenshot_4.jpg?raw=true)
# Кастомные варианты для товара в InSales
## Инструкция по установке
1. Подключить кастомный *template.liquid*
2. Отредактировать файл *template.liquid* и заменить в строке #6 ID вариантов, на необходимые (те варианты, для которых будет использоваться кастомный шаблон)
```
<% if (option.id == '1232822' || option.id == '1232823' || option.id == '1232824') { %>
```
3. Подключить стили из файла *variants_custom.scss*

## Сам скрипт и пример на GitHub
https://github.com/eZ4hUNt/insales-custom-variants

Пример: http://myshop-mu426.myinsales.ru/

