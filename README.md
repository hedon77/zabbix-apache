# zabbix-apache

Set apache config

ExtendedStatus On

"<Location /server-status>"
    SetHandler server-status
    Require local
</Location>
