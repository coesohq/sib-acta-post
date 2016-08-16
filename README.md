records-post
============

This role records information in files about the packages used to build
artifacts, and the binary and source artifacts built.

* binary_artifacts
* build_depdencies
* installed_packages
* source_artifacts

Requirements
------------

Tested to run on Linux, FreeBSD, and OS X. Windows is not supported.

Role Variables
--------------

N/A

Dependencies
------------

* Role aikchar.sib-records-pre
* build_dependencies - from role aikchar.sib-build-pre
* installed_packages - from role aikchar.sib-build-pre
* binary_artifacts - from role aikchar.sib-build-post
* source_artifacts - from role aikchar.sib-build-post


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: aikchar.sib-records-post

License
-------

MIT

Author Information
------------------

Hamza Sheikh
