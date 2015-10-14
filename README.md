Ansible Role: Kibana
=====================

Installs and configures Kibana

Requirements
------------

None

Role Variables
--------------

```yaml

kibana_version: 4.1.2
kibana_port: 5601
kibana_install_dir: /opt
kibana_user: kibana

```

Dependencies
------------

- redouane.nginx
    - nginx_upstream_server: 127.0.0.1,
    - nginx_upstream_port: "{{ kibana_port }}"

License
-------

BSD