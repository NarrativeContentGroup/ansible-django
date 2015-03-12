[![Travis CI](http://img.shields.io/travis/MotherNatureNetwork/ansible-django.svg?style=flat)](http://travis-ci.org/MotherNatureNetwork/ansible-django) [![test-suite](http://img.shields.io/badge/test--suite-ansible--django-blue.svg?style=flat)](https://github.com/MotherNatureNetwork/ansible-role-tests/tree/master/ansible-django/)

Deploys a Django app.

## Requirements

These are included in the meta file, so they will be automatically installed

    - name: mnn.nginx
    - name: theonion.uwsgi-emperor

We are actually currently pointing at public repos, not the galaxy version at this time.

## Role Variables

TODO

## Dependencies

TODO

## Example Playbook

    - hosts: server
      roles:
        - { role: bigjust.django }

## License

MIT

## Author Information

This role was created in 2015 by [Justin Caratzas](https://github.com/bigjust) for [Mother Nature Network](https://github.com/orgs/MotherNatureNetwork)
