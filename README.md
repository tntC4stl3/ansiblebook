# Ansible: Up and Running code samples

[tntC4stl3] Change the code to fit Ansible 2.1.2.0

Change Log:

1. Ansible 2.0 has deprecated the “ssh” from ansible_ssh_user, ansible_ssh_host, and ansible_ssh_port to become ansible_user, ansible_host, and ansible_port.
2. Begin from Ansible 1.9, instead of sudo/sudo_user, use become/become_user and make sure become_method is 'sudo' (default).


----

This repository contains code samples from [Ansible: Up and
Running](http://ansiblebook.com), organized by book chapter.

Note that most chapters have a single subdirectory named *playbooks*. I did this
so that the directory structure of the code would match the directory structure
in the book, since the book always assumes a playbooks directory.

If you encounter any problems with these samples, please submit a GitHub issue
or a pull request against this repository.
