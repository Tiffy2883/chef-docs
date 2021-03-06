.. The contents of this file are included in multiple topics.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.

This configuration file has the following settings:

.. list-table::
   :widths: 200 300
   :header-rows: 1

   * - Setting
     - Description
   * - ``api_port``
     - The port used by the |api pushy|.
   * - ``command_port``
     - The port on which a |pushy| server listens for requests that are to be executed on managed nodes.
   * - ``heartbeat_interval``
     - The frequency of the |pushy| server heartbeat message.
   * - ``server_heartbeat_port``
     - The port on which the |pushy| server receives heartbeat messages from each |pushy| client. (This port is the ``ROUTER`` half of the |zeromq| DEALER / ROUTER pattern.)
   * - ``server_name``
     - The name of the |pushy| server.
   * - ``zeromq_listen_address``
     - The IP address used by |zeromq|.
