# ansible_simple_website_creation

# Result
```
# ansible-playbook -i inventory main.yml

PLAY [Creating Virtualhost] **********************************************************************************************************************************************

TASK [Gathering Facts] ***************************************************************************************************************************************************
ok: [172.31.41.22]

TASK [Installing Apache] *************************************************************************************************************************************************
ok: [172.31.41.22]

TASK [Creating Virtualhost] **********************************************************************************************************************************************
ok: [172.31.41.22]

TASK [Creating Documentroot] *********************************************************************************************************************************************
ok: [172.31.41.22]

TASK [downoad websiute files] ********************************************************************************************************************************************
ok: [172.31.41.22]

TASK [copy file to doc root] *********************************************************************************************************************************************
changed: [172.31.41.22]

TASK [Restarting/enabling apache] ****************************************************************************************************************************************
changed: [172.31.41.22]

PLAY RECAP ***************************************************************************************************************************************************************
172.31.41.22               : ok=7    changed=2    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0   

```
