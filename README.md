Playbook содержит ряд ролей:

zabbix_repository для скачивания репозитория zabbix и установки некоторых необходимых пакетов 
zabbix_proxy устанавливает zabbix_proxy и postgres 16 
zabbix_agent устанавливает zabbix_agent 
zabbix_agent2 устанавливает zabbix_agent2 
packages устанавливает Haproxy dnsmasq

после вывполнения всех задач в разделе handles выводятся состояния сервисов и версия haproxy и dnsmasq

При установке файли конфигурации для zabbix_proxy, zabbix_agent, zabbix_agent2 берутся из папок files
