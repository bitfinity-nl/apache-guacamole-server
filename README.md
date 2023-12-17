# role-apache-guacamole-gateway 
Apache Guacamole is a clientless remote desktop gateway.
It supports standard protocols like VNC, RDP, and SSH.

## Troubleshooting

- Show docker logs of Apache Guacamole server: ``docker logs guacd --follow``
- Show docker logs of Apache Guacamole client: ``docker logs guacamole --follow``

### Error messages

Error: LDAP Result Code 8 “Strong Auth Required”: BindSimple: Transport encryption required
\
Resolution: https://community.nethserver.org/t/ldap-result-code-8-strong-auth-required-bindsimple-transport-encryption-required/13376

## Source(s):
- https://guacamole.apache.org/
- https://guacamole.apache.org/doc/gug/ldap-auth.html#preparing-your-ldap-directory-optional
- https://www.howtoforge.com/how-to-install-apache-guacamole-as-docker-container-on-ubuntu/
- https://guacamole.apache.org/doc/gug/configuring-guacamole.html#parameter-tokens
- https://github.com/nitnelave/lldap/blob/main/example_configs/apacheguacamole.md
- https://dev.mysql.com/doc/mysql-installation-excerpt/8.0/en/docker-mysql-getting-started.html
- https://hub.docker.com/_/mysql
- https://github.com/Zer0CoolX/guacamole-customize-loginscreen-extension
