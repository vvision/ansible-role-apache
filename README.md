# ansible-role-apache

[![CI](https://github.com/vvision/ansible-role-apache/workflows/CI/badge.svg?event=push)](https://github.com/vvision/ansible-role-apache/actions?query=workflow%3ACI)

Installs Apache on Debian servers.
Generate DH parameters.
Configure SSL security and security headers.

Basic role which fits my needs.
For more configuration options, see [geerlingguy.apache](https://galaxy.ansible.com/geerlingguy/apache).

## Requirements

Requires Apache >= 2.4.11

## Role Variables

    apache_disable_default_site: true

Whether to disable default site: ``000-default.conf``.

    apache_activate_modules: [
        'headers',
        'http2',
        'rewrite',
        'ssl'
    ]

Apache modules to activate.

## Dependencies

None

## License

MIT

## Author Information

This role was created in 2021 by Victor Voisin.
