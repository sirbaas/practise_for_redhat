Objectives:
- Create one web server
  - Has NFS mount to FTP server share
- Create ftp server
  - Has folder shared to other server
  - Selinux must work everywhere
  - I don't want to log in as root > Time-out error 20200301

Troubleshooting:
- Hostmanager error
{code}
==> server1: [vagrant-hostmanager:guests] Updating hosts file on active guest virtual machines...
The machine with the name 'ansible' was not found configured for
this Vagrant environment.
{code}
remove files from <work_folder>/.vagrant/<machine_name>
This acure when renaming machine_names