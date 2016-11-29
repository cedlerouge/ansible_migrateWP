# ansible_playbook_migrateWP
ansible playbook to migrate wordpress site from domain1 to domain2

This small playbook aims to migrate wordpress site from production to pre-production domain or vice-versa : 
* backup remote site (bdd and files)
* synchronise local and remote file 
* overwrite remote database with the local dump db
* update the remote database with the remote domain
