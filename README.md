java
=========

Install java, general-purpose computer programming language that is concurrent, class-based, object-oriented, and specifically designed to have as few implementation dependencies as possible

Requirements
------------

None

Role Variables
--------------

    java_ver: 1.8.0
    java_pkgs:
      - "java-{{ java_ver }}"

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-role-java }

License
-------

BSD

Author Information
------------------

John Favorite
