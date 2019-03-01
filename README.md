# FTP_Server
connected vsftpd and httpd

move the config file to 

#mv -f vsftpd.conf /etc/vsftpd/vsftpd.conf

#service vsftpd start
#chkconfig vsftpd on

place other .sh files in /var/www/

#mv ftpscript.sh /var/www/
#mv ftpappend.sh /var/www/
#chmod -R 777 /var/www
#chmod -R 777 /var/ftp/pub

#service httpd start
#chkconfig httpd on

make sure to disable the firewall or allow the port
