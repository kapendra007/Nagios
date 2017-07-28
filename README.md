# Nagios
Plugin To check php-fpm Running on CentOS/RHEL 6
Run Below Command and you will get Your plugin Installed

#wget -O /usr/local/nagios/libexec/check_php-fpm.sh https://raw.githubusercontent.com/kapendra007/Nagios/master/Plugins/check_php-fpm.sh.txt
#dos2unix /usr/local/nagios/libexec/check_php-fpm.sh
#chmod -R 777 /usr/local/nagios/libexec/check_php-fpm.sh
#chown -R nagios:nagios /usr/local/nagios/libexec/check_php-fpm.sh
#echo "command[check_php-fpm]=/usr/local/nagios/libexec/check_php-fpm.sh" >>/usr/local/nagios/etc/nrpe.cfg
#/usr/local/nagios/libexec/check_php-fpm.sh