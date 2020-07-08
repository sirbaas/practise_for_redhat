Objectives:
- Create playbook with the following:
  - Include at least one role
  - Has dynamic inventory or template (chapter 11)
  - Managed software repository
  - Managed group of users
  - Manage cron (chapter 10)

Troubleshooting:
{code}
==> ansible: Running provisioner: ansible_local...
    ansible: Installing Ansible...
The following SSH command responded with a non-zero exit status.
Vagrant assumes that this means the command failed!

dnf -y --enablerepo=epel install ansible

Stdout from the command:

CentOS-8 - AppStream                            2.0 kB/s | 4.3 kB     00:02
CentOS-8 - AppStream                            1.0 MB/s | 5.8 MB     00:05
CentOS-8 - Base                                 1.6 kB/s | 3.9 kB     00:02
CentOS-8 - Base                                 546 kB/s | 2.2 MB     00:04
CentOS-8 - Extras                               656  B/s | 1.5 kB     00:02
CentOS-8 - Extras                               1.8 kB/s | 6.7 kB     00:03
Extra Packages for Enterprise Linux Modular 8 - 0.0  B/s |   0  B     02:08


Stderr from the command:

Error: Failed to synchronize cache for repo 'epel-modular'
{code}