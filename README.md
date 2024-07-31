# Playbook for WSL with Ubuntu 24.04

## Utilisation

```console
ansible-playbook -i inventory --ask-become-pass -e "ansible_user=$(whoami)" main.yml
```

## Mettre à jour les packages

### apt

```console
sudo apt update
sudo apt upgrade
```

### brew

```console
brew update
brew upgrade
```

### pipx

```console
pipx --include-injected upgrade-all
```
