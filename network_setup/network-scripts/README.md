TEAMING 4NICS

systemctl stop NetworkManager
systemctl disable NetworkManager

copy ifcfg-bond0 and modify IPADDR
slot1=172.25.41.259 slot2=172.25.41.248 
set configuration as in ifcfg in this directpry to /etc/sysconfig/network-scripts

