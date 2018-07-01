# RaspberryMatic_Authentification

1. Put "auth.conf" to /etc/config/lighttpd/auth.conf
2. Put ".lighttpdpassword" to /etc/config/lighttpd/.lighttpdpassword
3. Restart httplight: /etc/init.d/S50lighttpd restart
OR Restart RaspberryMatic via GUI

# Create User & Password for ".lighttpdpassword"
htpasswd -n USERNAME
-> replace "USERNAME" with your user
-> Copy result & past into .lighttpdpassword
