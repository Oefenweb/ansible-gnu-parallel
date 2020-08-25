## gnu-parallel

[![Build Status](https://travis-ci.org/Oefenweb/ansible-gnu-parallel.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-gnu-parallel)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-gnu--parallel-blue.svg)](https://galaxy.ansible.com/Oefenweb/gnu-parallel)

Set up the latest version of [GNU Parallel](https://www.gnu.org/software/parallel/) in Debian-like systems.

#### Requirements

None

#### Variables

* `gnu_parallel_remove_distro_version`: [default: `true`]: Whether or not to remove the distribution version

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - gnu-parallel
```

#### License

MIT

#### Author Information

* Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-gnu-parallel/issues)!
