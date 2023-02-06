# arista_eda_demo

Basic Network example with Event-Driven Ansible.

1. Kafka and Telegraf is needed
2. Telegraf grabs network telemetry from the switches with gMNI - You can see the example switch config.
3. Telegraf pushes the telemetry to the Kafka Topic for Event-Driven Ansible to listen to.

Telegraf.conf -> Sample config of telegraf
port_status.yml -> Ansible Rulebook
bring-her-up.yml -> remediation playbook example
