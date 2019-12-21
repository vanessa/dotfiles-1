# Vanessa's dotfiles

Made with [ansible](https://www.ansible.com/) for [`Ubuntu 18.04 LTS`](http://releases.ubuntu.com/18.04/) (bionic).
Must be used locally.

## Deploy

Create and configure the local variables:

```bash
cp group_vars/local.example group_vars/local
```

Make sure your ssh private and public keys exist at:

```bash
~/.ssh/id_rsa
~/.ssh/id_rsa.pub
```

Execute the `run.sh` file:

```bash
# This will install ansible 2.5.2 if it's not installed;
# Arguments to the ansible-playbook command can be passed here.
./run.sh
```

## TODO
- [ ] Install tmuxinator and create alias
- [ ] Change wallpaper
