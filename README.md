Ответы на вопросы:

	1.	apt update обновляет индекс пакетов (список доступных версий) без установки, а apt upgrade обновляет установленные пакеты до новых версий из этого индекса.
	2.	Проверить, слушает ли сервис нужный порт, можно с помощью ss -lntp | grep :<порт> или sudo lsof -i :<порт>, а также протестировать соединение через curl -I http://localhost:<порт> или nc -zv localhost <порт>.
	3.	Для диагностики сетевых проблем используют ping, traceroute/tracepath, mtr, ip a, ip r, ip link, ss, lsof -i, dig, nslookup, curl, wget, nc, а для анализа трафика и логов — tcpdump, journalctl -u <сервис>, systemctl status <сервис>.