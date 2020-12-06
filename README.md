# High-pass-IIR-Filter-5-th-order-
Данный репозиторий содержит файлы для всех этапов реализации интегральной схемы цифрового БИХ-ФВЧ Фильтра 5-го порядка в фиксированной точности. 

Характеристики реализуемого цифрового фильтра: 
1. Разрядность входного и выходного сигналов - 15
2. Граница полосы пропускания - 0,9
3. Граница полосы задерживания - 0,8
4. Подавление в полосе задерживания - 60 дБ
5. Величина неравномерности в полосе пропускания - 0,3 дБ
6. Минимальность порядка
7. Оптимальность разрядности регистров

Описание файлов, представленных в данном репозитории, приведено в таблице ниже.
Название файла | Описание файла
--
Elliptic.v     | Описание фильтра на языке Verilog HDL
Elliptic_tb.v  | Описание тестового модуля для верифицации Verilog-описания фильтра и списка логических вентилей и межсоединений после логического синтеза с привязкой к технологической библиотеке


