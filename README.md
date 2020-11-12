# ansible-prometheus

Use ansible deploy prometheus,node_exporter,grafana

## Run

run one

```bash
ansible-playbook -u <username> -b -K -i inventory/test/hosts.ini grafana.yml
```

run all

```bash
ansible-playbook -u <username> -b -K -i inventory/test/hosts.ini sites.yml
```