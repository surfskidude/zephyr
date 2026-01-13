.. _external_module_xedge:

Xedge
#####

Introduction
************

Xedge is a secure, embedded web and IoT edge framework designed for
resource-constrained devices and RTOS environments. It is built on the
Barracuda App Server technology and provides a high-level, Lua-based
application environment for developing secure, network-connected
devices.

It enables device manufacturers and embedded developers to implement
web-based management interfaces, REST APIs, and secure IoT services
directly on embedded hardware, without requiring external gateways or
cloud dependencies.

Usage with Zephyr
*****************

Xedge can be used alongside Zephyr by integrating it as an external
component in your application and building it for your target board.
Because Xedge is developed and documented outside of Zephyr, the most
up-to-date build instructions, supported features, and examples are
maintained on the Xedge website.

Reference
*********

- `Xedge for Zephyr GitHub Repository`_
- `Xedge Introduction`_
- `Barracuda App Server`_

.. target-notes::

.. _Real Time Logic:
    https://github.com/RealTimeLogic/Xedge4Zephyr

.. _Xedge Introduction:
    https://realtimelogic.com/products/xedge/

.. _Barracuda App Server:
    https://realtimelogic.com/products/barracuda-application-server/
