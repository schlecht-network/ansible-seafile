# ansible-seafile
CAUTION: quick and dirty (I may fix it later but currently this is just a quick and dirty role to deploy seafile)
NOTE: designed to run behind a tls offloading reverseproxy to inspect the http backend traffic with an ips firewall

Vars:

mysql_root_password
seafileuser_db_pw
fqdn
seafile_admin_email
seafile_admin_pw
seafile_ldap_host
seafile_ldap_basedn
seafile_ldap_binduser
seafile_ldap_bindpw
seafile_ldap_loginattr
seafile_ldap_filter