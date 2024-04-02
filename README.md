# Домашнее задание к занятию "Система мониторинга Zabbix. Часть 2" - Пергунов Дмитрий

### Задание 1

1. Создали новый шаблон
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/1429721e-e583-4478-9b30-cd2aa168e915)
2. Создали Item CPU в процентах, добавили код в процессинг
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/a6e041b6-9a38-46f5-9b9f-adc356593ff5)
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/24e34a43-aa9c-4f3b-a09f-7983c837108d)
3. Создали ITEM RAM в процентах, добавили код в процессинг
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/a0ef68ce-52b3-45be-b144-7707a7faf9ee)
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/9e3ba928-58a7-4783-8474-2f83f1029237)

### Задание 2
1. Ранее заббикс агенты были установлены на машины, и к ним был прикреплен шаблон Linux by zabbix agent
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/9e64526f-a77f-488b-b970-7d01b0027123)

### Задание 3

1. Так как Zabbix не разрешает привязывать Шаблоны с одинаковыми итемами поступил немного по другому
 ![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/4705ce39-6ff9-4a03-adf2-3d943be7f4f4)
2.Отвязал от Template OS Linux by Zabbix agent, Template CPU И RAM потому что они дублируют мой template и привязал свой
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/93f67b02-1bdc-42ea-89d1-067b728dca6a)
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/ec1f4d82-3df5-486e-98d1-deb7fefa138d)
3.Необходимые данные поступают С помощью утилиты stress проверим, то что данные снимаются верно
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/78198cd4-62c2-4e9e-9ece-338da5948735)
4. Скриншоты графиков нагрузки
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/888db5a3-55dc-4647-8080-c2b8bda09e72)
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/4ed4940e-7e9c-4465-b4a8-07386d4b3e2d)

### Задание 4

1. Создали свой собственный дашборд, с графиками загрузки памяти и процессора 
![image](https://github.com/dimindrol/Zabbix_part2_pergunov/assets/103885836/44a2e821-2d4c-4eec-b668-0333111baeb2)


