Role Name
=========

Роль для установки lighthouse.

- Устновка Git
- Скачивание lighthouse из репозитория
- Конфигурирование lighthouse

Requirements
------------

для работы требуется установленный сервер nginx

Role Variables
--------------

```yaml
lighthouse_vcs: "https://github.com/VKCOM/lighthouse.git"
lighthouse_access_log: lighthouse_access
lighthouse_dir: "/home/{{ ansible_user_id }}/lighthouse"
```

Dependencies
------------

Example Playbook
----------------

```yaml
    - hosts: lighthouse
      roles:
         - lighthouse_role
```

License
-------

BSD

Author Information
------------------
