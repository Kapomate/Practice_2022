# Practice_2022
Задание на практику:
Необходимо разработать программу сканирования локальной IP-сети.
В качестве входных параметров задается перечень сканируемых IP-сетей
(диапазонов адресов) и набор коммутаторов.
Последовательно генерируя IP-адреса из указанных диапазонов приложение
должно посылать icmp-запросы. В случае получения ответа, указанный
адрес должен заноситься в базу. После окончания сканирования,
пользователь может получить текущую карту сети. Карта сети представляет
собой граф, в котором вершинами являются IP-сети и устройства.
Устройство и IP-сеть соединяются ребром, если у устройства есть IP-адрес
в данной сети.

Важное дополнение: запрещено использовать утилиту PING
