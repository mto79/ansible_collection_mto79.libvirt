# [Libvirt_install](#libvirt-install)

Install libvirt ansd KVM and its required libraries on your system.

## [Requirements](#requirements)

* The minimum version of Ansible required is 2.10.
* The minimum version of Jinja template 2.11.3

## [Example Playbook](#example-playbook)

Refer to the following example:

```yaml
    - hosts: servers
      roles:
        - role: "mto79.libvirt.install"
          vars:
            __role_action:
              - "install"
          tags: ['libvirt', 'install', 'setup']

```

## [Role Variables](#role-variables)

| Variable | Default | Description |
| -------- | ------- | ----------- |
| `libvirt_` | `` |  |
| `libvirt` | `` |  |

## [Maintainers](#maintainers)

Marc Ouwerkerk (<https://github.com/mto79>)

## [Todo](#todo)

* Standaardwaarden voor molecule testen toevoegen

## [License](#license)
Apache-2.0
