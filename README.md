# TankBot


<!-- 2 rgb
сервомотор
датчик руху
датчик лінії
ультрасонік
двигун ПС
датчик газу
датчик температури
гіроскоп та акселеметр
фоторезистор -->

Таблиця підключення
-------------------
|Датчик|Порт підклюення|піни Arduino|Піни Наніт|Примітка|
|:----:|:--------------|-|-|-|
|Мотори|1 та 12||||
|датчик газу|1|A7|P1_1|Аналоговий сигнал|
|Датчик світла|1|A6|P1_2|Аналоговий сигнал|
|Серво|2|42|P2_3||
|RGB|4|(RGB)44,45,46|(RGB)P4_2,P4_3,P4_4|ШИМ|
|Датчик руху|4|P4_1||Цифровий сигнал|
|Ультрасонік|6|23(TRIG), 22(ECHO)|P6_1(TRIG), P6_4(ECHO)||
|Гіроскоп|9|SDA(20),SDL(21)|SDA(P9_2),SDL(P9_1)||
