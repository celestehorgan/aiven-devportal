
``ip_filter``
-------------
*array*

**IP filter** Allow incoming connections from CIDR address block, e.g. '10.20.0.0/16'



``flink_version``
-----------------
*['string', 'null']*

**Flink major version** 



``number_of_task_slots``
------------------------
*integer*

**Flink taskmanager.numberOfTaskSlots** Task slots per node. For a 3 node plan, total number of task slots is 3x this value



``privatelink_access``
----------------------
*object*

**Allow access to selected service components through Privatelink** 

``flink``
~~~~~~~~~
*boolean*

**Enable flink** 

``prometheus``
~~~~~~~~~~~~~~
*boolean*

**Enable prometheus** 



