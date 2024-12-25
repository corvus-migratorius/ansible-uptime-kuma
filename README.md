ansible-uptime-kuma
=========

[![linters](https://github.com/corvus-migratorius/ansible-uptime-kuma/actions/workflows/linters.yaml/badge.svg)](https://github.com/corvus-migratorius/ansible-uptime-kuma/actions/workflows/linters.yaml)
[![kics](https://github.com/corvus-migratorius/ansible-uptime-kuma/actions/workflows/kics.yml/badge.svg)](https://github.com/corvus-migratorius/ansible-uptime-kuma/actions/workflows/kics.yml)
[![molecule](https://github.com/corvus-migratorius/ansible-uptime-kuma/actions/workflows/molecule.yaml/badge.svg)](https://github.com/corvus-migratorius/ansible-uptime-kuma/actions/workflows/molecule.yaml)

Deploy and confugure a containerized instance of [uptime-kuma](https://github.com/louislam/uptime-kuma).

Requirements
------------

None

Role Variables
--------------

- `kuma_img_version`: "1.23.16-alpine"
- `kuma_project_dir`: "/uptime-kuma"
- `kuma_port`: 3001
- `kuma_api_version`: "1.2.0"
- `kuma_limit_cpus`: 2
- `kuma_limit_ram`: "2G"

Dependencies
------------

- `genlab.docker_ubuntu`

Example Playbook
----------------

See `molecule/default/converge`.

License
-------

BSD

Author Information
------------------

corvus-migratorius@proton.me
