Objectives:
- Create playbook with the following:
  - Include at least one role
  - Has dynamic inventory or template (chapter 11)
  - Managed software repository
  - Managed group of users
  - Manage cron (chapter 10)

Troubleshooting:
{code}
ansible: Installing Ansible...
The following SSH command responded with a non-zero exit status.
Vagrant assumes that this means the command failed!

sudo rpm -i https://dl.fedoraproject.org/pub/epel/epel-release-latest-`rpm -E %dist | sed -n 's/.*el\([0-9]\).*/\1/p'`.noarch.rpm

Stdout from the command:



Stderr from the command:

        package epel-release-8-8.el8.noarch is already installed
{code}