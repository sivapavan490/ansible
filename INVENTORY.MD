# below mentioning hosts are ungrouped hosts like

172.33.44.23
172.33.45.25

# below mentioning model is group of hosts we can mention either ip address or dns record
[mongodb]
172.88.23.56
172.98.54.23

[cart]
172.12.84.56
175.29.84.52
172.78.45.12

[mysql]
172.56.80.45
172.88.99.66

# below mentioning model are group of group
[db:children]
mongodb
mysql

[app:children]
cart