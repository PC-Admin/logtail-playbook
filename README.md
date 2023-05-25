# logtail-playbook

A simple playbook to connect clients to logtail/betterstack.

## Connecting clients

After defining a [logtail_clients] inventory, run the connect.yml playbook:

`$ ansible-playbook connect.yml`


## Disconnecting clients

If something goes wrong it's easier to start again with the disconnect.yml playbook:

`$ ansible-playbook disconnect.yml`