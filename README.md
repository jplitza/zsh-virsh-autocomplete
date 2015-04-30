zsh_virsh_autocompletion
========================

This is a zsh autocompletion file for [libvirt]'s `virsh` command.

Working for libvirt >= version 0.9, tested with libvirt 1.2.12 on Ubuntu

[libvirt]: https://libvirt.org/


INSTALLING
----------

```
cp _virsh /usr/share/zsh/functions/Completion/Linux
```
Actually, any path in your `$fpath` would work, so if you like that better, use `/usr/local/share/zsh/site-functions` for example.

After copying, restart your shell.
