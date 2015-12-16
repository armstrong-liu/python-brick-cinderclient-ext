=============================
python-brick-cinderclient-ext
=============================

OpenStack Cinder Brick client for local volume attachement

Features
--------

* Get volume connector information


Dependencies
------------

Depends on Cinder driver's protocol, python-brickclient could require following
packages::

* open-iscsi - for volume attachment via iSCSI
* ceph-common - for volume attachment via iSCSI (Ceph)
* nfs-common - for volume attachment using NFS protocol

For any other imformation, refer to the parent projects, Cinder and
python-cinderclient:::
*  https://github.com/openstack/cinder
*  https://github.com/openstack/python-cinderclient

* License: Apache License, Version 2.0
* Documentation: http://docs.openstack.org/developer/python-brick-cinderclient-ext
* Source: http://git.openstack.org/cgit/openstack/python-brick-cinderclient-ext
* Bugs: http://bugs.launchpad.net/python-cinderclient
