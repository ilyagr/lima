---
title: Configuration guide
weight: 5
---

For all the configuration items, see <https://github.com/lima-vm/lima/blob/master/examples/default.yaml>.

You can edit the configuration for your VM with the `limactl edit` command. It
lives in `$HOME/.lima/VM_NAME/lima.yml` by default. 

The current default spec:
- OS: Ubuntu
- CPU: 4 cores
- Memory: 4 GiB
- Disk: 100 GiB
- Mounts: `~` (read-only), `/tmp/lima` (writable)
- SSH: 127.0.0.1:60022
