Ansible Nginx Role
==============
***Ubuntu Only (currently)***

An ansible role for nginx installation. Bare bones at the moment with only the domain name being customisable.

This is inspired by @fideloper's [servers for hackers](https://serversforhackers.com/) series

*** This sets the server name to the IP address, not the domain***


#### Excute
In you main yaml file add, under roles:

```
- nginx
```

#### Steps taken
- Add new Nginx repo to grab more recent version
- install Nginx
- Add the HTML5 Boilerplate nginx config
- Add a default site
- Update Nginx configuration


#### Todo
- Make multi-distribution
- Add configurable items to configuration