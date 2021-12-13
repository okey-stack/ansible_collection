Create file role
=========

Роль для создания файлов и наполнения их контентом.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| path | "." | Параметр, который определяет имя и путь создаваемого или обновляемого файла |
| content | "" | Параметр, который определяет контент которым будет наполнен создаваемый файл |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: create-file-role }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
