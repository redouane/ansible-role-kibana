Ansible Role: Kibana
=====================

[![Build Status](https://travis-ci.org/jrybski/ansible-role-kibana.svg?branch=master)](https://travis-ci.org/jrybski/ansible-role-kibana)

Installs and configures Kibana >= 4.2.0

Requirements
------------

Ansible

Role Variables
--------------

```yaml

kibana_version: 4.2.0
kibana_port: 5601
kibana_host: 0.0.0.0
kibana_elasticsearch_url: http://localhost:9200
kibana_default_app: discover
kibana_install_dir: /opt
kibana_user: kibana
kibana_group: kibana
kibana_index: .kibana
kibana_log: /var/log/kibana.log
kibana_log_rotate_count: 5
kibana_log_rotate_interval: daily
```

License
-------

BSD