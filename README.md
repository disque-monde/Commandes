# Commandes

## Ufw: show block ips
`cat /var/log/ufw.log |grep "UFW BLOCK"|cut -d " " -f 13 |cut -d"=" -f2|uniq                                                                                                                       `
