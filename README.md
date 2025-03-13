# retropie_configuration
- hardware: Raspberry Pi 4 Model B
- software: retropie 4.8

# how to run
```
1. write an image to a flash card
2. connect to network (wireless or ethernet) to get an IP address
3. configure login password
4. enable ssh
```

```bash
ansible-playbook playbook.yml -i <ip>, -u pi --ask-pass --ask-become-pass
```
