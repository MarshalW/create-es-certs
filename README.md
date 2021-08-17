# create es certs

为 elasticsearch 创建 certs 文件

## Requirements

--

## Role Variables

- es_version
- es_group_name

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

## Example Playbook

使用示例:

```yml
- name: generate certs
  hosts: localhost
  gather_facts: no
  roles:
    - role: roles/create-es-certs
  vars:
    es_version: 7.14.0
    es_group_name: servers
```

## License

BSD

## Author Information

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
