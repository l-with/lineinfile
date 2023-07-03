# lineinfile

script to replace a line matching a pattern or to add a line to a file after a pattern if the line is not already in the file

```bash
Usage: lineinfile [-h|--help] [-v|--verbose] -r|--regexp <PATTERN> -a|--insertafter <PATTERN> -l|--line <LINE> <file>
```

## Motivation

The intention is to have a replacement for [Ansible Module ansible.builtin.lineinfile](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/lineinfile_module.html) to be used in cloud-init.
