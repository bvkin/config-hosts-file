# config-hosts-file
An ansible role for configuring an /etc/hosts file

# Example invenrtory

```yaml

hosts:
  - hostname: localhost
    ip: 127.0.0.1
  - hostname: localhost
    ip: ::1
  - hostname: broadcasthost
    ip: 255.255.255.255
  - hostname: compute1
    ip: 192.168.1.2
  - hostname: compute2
    ip: 192.168.1.3
  - hostname: compute3
    ip: 192.168.1.4

```
