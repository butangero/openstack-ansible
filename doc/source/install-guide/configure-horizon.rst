`Home <index.html>`__ OpenStack Ansible Installation Guide

Configuring HAProxy (optional)
------------------------------

Customizing the Horizon deployment is done within
``/etc/openstack_deploy/user_variables.yml``.

Securing HAProxy communication with SSL certificates
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The openstack-ansible project provides the ability to secure Horizon
communications with self-signed or user-provided SSL certificates.

Refer to `Securing services with SSL certificates`_ for available configuration
options.

.. _Securing services with SSL certificates: configure-sslcertificates.html

--------------

.. include:: navigation.txt
