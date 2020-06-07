# ansible-public-web-server
Ansible playbooks to setup my public-web-server

```
docker-compose run --rm control-machine site.yml -i hosts.ini --ask-vault-pass --ask-become-pass
```

```
docker-compose run --rm --entrypoint "ansible-vault encrypt_string --stdin-name cloudflare_api_token" control-machine
```
