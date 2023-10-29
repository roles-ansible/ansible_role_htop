 ansible role htop
==================

Ansible role to install and configure htop

<h1>WORK IN PROGRESS</h1>

 Variables
-----------
| variable | default value | usage |
| -------- | ------------- | ----- |
| ``htop__compile`` | ``false`` | Compile htop from source |
| ``htop__version`` | ``latest`` | If we compile htop from source, which version should we use? *(latest is the latest github release, use any valid git reference)* |

## Requirements
The ``community.general`` collection is required for some parts of this ansible role.
You can install it with this command:
```bash
ansible-galaxy collection install -r requirements.yml --upgrade
```
