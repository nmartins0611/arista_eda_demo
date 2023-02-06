# arista_eda_demo

Basic Network example with Event-Driven Ansible.

1. Kafka and Telegraf is needed
2. Telegraf grabs network telemetry from the switches with gMNI - You can see the example switch config.
3. Telegraf pushes the telemetry to the Kafka Topic for Event-Driven Ansible to listen to.<br />

Telegraf.conf -> Sample config of telegraf<br />
port_status.yml -> Ansible Rulebook<br />
bring-her-up.yml -> remediation playbook example<br />
switch_config_example -> Arista conf file
