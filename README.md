Role Name
=========

tarot-reading role: 

A very simple Ansible role for generating an HTML5 webpage that displays 3 Tarot cards (for past, present and future)

Requirements
------------

- web server
- tarot pack deck (sample deck provided)


Run ansible-playbook
--------------------

execute on local server
```
ansible-playbook -i localhost, tarot-reading.yml --connection=local
```

crontab at every minute 
```
* * * * * ansible-playbook -i localhost, /root/tarot-reading.yml --connection=local
```

Demo
--------------------
https://tarot.videoukon.info/


Why?
--------------------
I dont take tarot seriously, but I found it interesting how we are able to find meaningful discoveries after a random spread has been dealt.
This was just a little fun thing to do with Ansible :) 


License
-------

BSD

