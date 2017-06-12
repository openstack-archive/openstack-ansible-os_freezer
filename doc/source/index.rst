==============================
OpenStack-Ansible freezer role
==============================

.. toctree::
   :maxdepth: 2

   configure-freezer.rst

This role installs the following Systemd services:

    * freezre-api
    * freezer-scheduler

To clone or view the source code for this repository, visit the role repository
for `os_freezer <https://github.com/openstack/openstack-ansible-os_freezer>`_.

Default variables
~~~~~~~~~~~~~~~~~

.. literalinclude:: ../../defaults/main.yml
   :language: yaml
   :start-after: under the License.

Required variables
~~~~~~~~~~~~~~~~~~

None

Example playbook
~~~~~~~~~~~~~~~~

.. literalinclude:: ../../examples/playbook.yml
   :language: yaml

Tags
~~~~

This role supports two tags: ``freezer-install`` and ``freezer-config``.
The ``freezer-install`` tag can be used to install and upgrade. The
``freezer-config`` tag can be used to manage configuration.
