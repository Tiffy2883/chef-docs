.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

This lightweight resource provider has the following attributes:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Attribute
     - Description
   * - ``app``
     - |name application| This is used for the ``/Volumes`` directory and ``.app`` directory that is copied to ``/Applications``. Default value: ``name``.
   * - ``checksum``
     - |checksum apple_disk_image| Default value: ``nil``.
   * - ``destination``
     - |directory dmg_package| Default value: ``/Applications``.
   * - ``dmg_name``
     - |name apple_disk_image| Default value: ``nil``.
   * - ``source``
     - |source lwrp dmg_package|
   * - ``volumes_dir``
     - |directory apple_disk_image| Default value: ``app``.
