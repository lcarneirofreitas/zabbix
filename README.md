zabbix
=====

Repositório de configurações do zabbix


TEMPLATES:

zbx_export_templates_ups.xml

Template do zabbix para monitoramento de Ups ts shara modelos "Nobreak TS Syal e Nobreak TS Tryon"

FUNCIONAMENTO:

Realiza o monitoramento através de snmp, itens monitorados:

- Load (%)
- Capacidade Baterias (%)
- Temperatura (C°)
- Tensão de Saida (V)
- Tensão de Entrada (V)
- Frequência de Saida (Hz)
- Frequência de Entrada (Hz)

Este template tambem gera gráficos e trigger para alarmar no caso de problemas.


