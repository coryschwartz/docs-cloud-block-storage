.. _volume-transfer-operations:

Volume transfer
~~~~~~~~~~~~~~~~~~~~~

You can transfer a volume from one owner to another by using the volumes transfer methods. The volume donor, or original owner, creates a transfer request and sends the created ``transfer_id`` and ``auth_key`` to the volume recipient. The volume recipient, or new owner, accepts the transfer by using the ID and key.

.. note::  
   The procedure for volume transfer is intended for tenants (both the volume donor and recipient) within the same cloud.

Use cases include:

- Create a custom bootable volume or a volume with a large data set and transfer it
  to a customer.

- For bulk import of data to the cloud, the data ingress system creates a new block 
  storage volume, copies data from the physical device, and transfers device 
  ownership to the end user.


.. The includes below will need to be changed to reflect the names of your method
   description files.

    

.. include:: methods/post-create-volume-transfer.rst
.. include:: methods/get-volume-transfers.rst
.. include:: methods/get-volume-transfers-detailed.rst
.. include:: methods/get-volume-transfer-detailed.rst 
.. include:: methods/delete-volume-transfer.rst
.. include:: methods/post-accept-volume-transfer.rst       
