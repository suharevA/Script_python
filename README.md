## Description 

1. **moni_disk_space.sh** -- Script to monitor disk space и запуска команды очистки docker image (Читай комментарии в файле)
crontab -e 
*/10 * * * * /opt/moni_disk_space.sh каждые 10 минут

1. **moni_disk_space.py** -- Python Script to monitor disk space и запуска команды очистки docker image (Читай комментарии в файле)
crontab -e 
*/10 * * * * /opt/moni_disk_space.py каждые 10 минут

1. **untitled12_bucardo.py** -- Скрипт решает проблему (Bucardo не может автоматически синхронизировать потерянные узлы) скрипт для отслеживания состояния сервера. Как только соединение возобновляется, скрипт выполняет команду перезагрузки bucardo восстанавливая синхронизацию.

start script: python2.7 untitled12_bucardo.py host.bucardo2 /bucardo_replication_log.txt
Скрипт добавляем в автозагрузку

1. **back_postgres.sh** -- Скрипт для резервного копирования баз данных Postgres 

1. **tool_ping.py** -- New python3.8 Скрипт решает проблему (Bucardo не может автоматически синхронизировать потерянные узлы) скрипт для отслеживания состояния сервера. Как только соединение возобновляется, скрипт выполняет команду перезагрузки сервера bucardo.Скрипт добавляем в автозагрузку
1. **enum.py** -- сканирует папку, пишет сожержиое и размер найденого в файл enum.txt 
