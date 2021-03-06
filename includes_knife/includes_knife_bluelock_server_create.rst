.. The contents of this file are included in multiple topics.
.. This file describes a command or a sub-command for Knife.
.. This file should not be changed in a way that hinders its ability to appear in multiple documentation sets.


The ``server create`` argument is used to create a new |bluelock| cloud instance. A comma-separated run-list of roles and/or recipes must be specified.

This argument has the following syntax::

   knife bluelock server create NAME [RUN_LIST...] (options)

This argument has the following options:

``-A USER_NAME``, ``--bluelock-username USER_NAME``
   |username bluelock|

``-d DISTRO``, ``--distro DISTRO``
   |distro|

``--[no-]enable-firewall``
   |enable firewall|

``-i IMAGE``, ``--bluelock-image IMAGE``
   |image|

``-K PASSWORD``, ``--bluelock-password PASSWORD``
   |password bluelock|

``-m MEMORY``, ``--memory MEMORY``
   |memory mb|

``-N NAME``, ``--node-name NAME``
   |node-name cloud|

``-P PASSWORD``, ``--ssh-password PASSWORD``
   |ssh-password|

``-r RUN_LIST``, ``--run-list RUN_LIST``
   |run-list|

``-S NAME``, ``--server-name NAME``
   |server-name|

``-T X,Y,Z``, ``--tcp X,Y,Z``
   |tcp-ports|

``--template-file TEMPLATE``
   |template-file|

``-U X,Y,Z``, ``--udp X,Y,Z``
   |udp-ports|

``-vcpus VCPUS``
   |vcpus|


