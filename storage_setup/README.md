# storage

yum install device-mapper-multipath

vi /etc/multipath.conf

systemctl enable multipathd
systemctl start multipathd

multipath -ll
fdisk -l #mapper delle dimensioni desiderate


