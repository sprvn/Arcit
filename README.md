# Arcit

## Prerequisite

Ansible requires Python which is currently not named python but python2.7.
A symlink fixes this:

`ln -s /usr/bin/python2.7 /usr/bin/python`

`ansible-playbook playbook.yml -i localhost`
