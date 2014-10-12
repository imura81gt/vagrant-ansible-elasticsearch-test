# Elasticsearch Ansible

# Vagrant

2nodes up

```
vagrant up
```

|nodename|ip|
|----|----|
|esnode1 | 192.168.55.11 |
|esnode2 | 192.168.55.12 |

# install elasticsearch

```
ansible-playbook -i hosts playbook.yml
```

# URLs

## check

http://192.168.55.11:9200/
http://192.168.55.12:9200/

## cluster health check

http://192.168.55.11:9200/_cluster/health?pretty
http://192.168.55.12:9200/_cluster/health?pretty

## Plugin

### elasticsearch-head

http://192.168.55.11:9200/_plugin/head/
http://192.168.55.12:9200/_plugin/head/

### elasticsearch-HQ

http://192.168.55.11:9200/_plugin/HQ/
http://192.168.55.12:9200/_plugin/HQ/

### inquisitor

http://192.168.55.11:9200/_plugin/inquisitor/
http://192.168.55.12:9200/_plugin/inquisitor/






