.. _volumes-operations:

Volumes
~~~~~~~  
   
A volume is a detachable block storage device. You can think of it as a USB hard drive. You can attach a volume to one instance at a time.

When you make an API call to create, list, or delete volumes, the following volume status values are possible:

* CREATING: The volume is being created.

* AVAILABLE: The volume is ready to be attached to any instance.

* ATTACHING: The volume is attaching to an instance.

* IN-USE: The volume is attached to an instance.

* DELETING: The volume is being deleted.

* ERROR: An error occurred with the volume.

* ERROR_DELETING: An error occurred during volume deletion.

.. The includes below will need to be changed to reflect the names of your method
   description files.
   
.. include:: methods/post-create-volume-v1-tenant-id-volumes.rst
.. include:: methods/get-list-volumes-v1-tenant-id-volumes.rst
.. include:: methods/get-list-volumes-(detailed)-v1-tenant-id-volumes-detail.rst
.. include:: methods/get-show-volume-v1-tenant-id-volumes-volume-id.rst
.. include:: methods/put-update-volume-v1-tenant-id-volumes-volume-id.rst
.. include:: methods/delete-delete-volume-v1-tenant-id-volumes-volume-id.rst
