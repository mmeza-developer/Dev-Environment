# Ansible Dev Environment

This is a simple Ansible Playbook for My Development Environment

Software to be installed:

- Docker
- Docker-compose
- Node
- Go
- tmux
- dbeaver
- VisualStudio Code
    - Extension: streetsidesoftware.code-spell-checker
    - Extension: ms-python.python
    - Extension: golang.Go
    - Extension: ms-vscode.vscode-typescript-next
    - Extension: bradlc.vscode-tailwindcss
    - Extension: mads-hartmann.bash-ide-vscode
    - Extension: mads-hartmann.bash-ide-vscode
    - Extension: snyk-security.snyk-vulnerability-scanner
    - My hotkeys

Install Requeriments

~~~bash
ansible-galaxy install -r requirements.yml
~~~

To run this playbook use the following command:

~~~bash
ansible-playbook main.yml --ask-become-pass
~~~