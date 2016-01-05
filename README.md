# Ansible Role Varnish

<span class="badges" align="center">
[![Build Status](https://travis-ci.org/hadenlabs/ansible-role-varnish.svg)](https://travis-ci.org/hadenlabs/ansible-role-varnish)
[![Stories in Ready](https://badge.waffle.io/hadenlabs/ansible-role-varnish.svg?label=ready&title=Ready)](http://waffle.io/hadenlabs/ansible-role-varnish)
[![GitHub issues](https://img.shields.io/github/issues/hadenlabs/ansible-role-varnish.svg)](https://github.com/hadenlabs/ansible-role-varnish/issues)
[![GitHub license](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square)](LICENSE)
</span>


Installs and configures [varnish][link-varnish] on a host.

## Requirements

 - Linux
   - none
 - OSX
   - [Homebrew][link-brew] must be installed.


## Role Variables

The default role variables in `defaults/main.yml` are:

    ---
    # defaults file for varnish


## Dependencies

none

## Example Playbook

See the [examples](./examples/) directory.

To run this playbook with default settings, create a basic playbook like this:

    - hosts: servers
      roles:
         - varnish

To install a specific version:

    - hosts: servers
      roles:
         - { role: hadenlabs.varnish }


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Credits

- [Luis Mayta][link-author]
- [All Contributors][link-contributors]

[link-varnish]: https://varnish.org/
[link-brew]: http://brew.sh/

<!-- Other -->

[link-author]: https://github.com/luismayta
[link-contributors]: AUTHORS
