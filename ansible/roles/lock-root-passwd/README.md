# Lock Root Passwd Role

Simply runs passwd -l to lock the root password.

## Usage

ansible-playbook --verbose main.yml -i inventory/hosts -t lock-root-passwd -s 

## Variables

None

## Tags

lock-root-passwd
