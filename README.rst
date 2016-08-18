====================
OpenStack repo build
====================

Role to deploy a repository build for both python packages and git sources.

.. code:: yaml

   - name: Setup repo builds
      hosts: repo_all
      user: root
      roles:
        - { role: "repo_build", tags: [ "repo-build" ] }
