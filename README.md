# ansible-prometheus

Use ansible deploy prometheus,node_exporter,grafana

## Run

run once

```bash
ansible-playbook -u <username> -b -K -i inventory/test/hosts.ini grafana.yml
```

run all

```bash
ansible-playbook -u glk -b -K -i inventory/test/hosts.ini sites.yml
```