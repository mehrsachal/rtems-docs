.. comment SPDX-License-Identifier: CC-BY-SA-4.0

.. COMMENT: COPYRIGHT (c) 1988-2002.
.. COMMENT: On-Line Applications Research Corporation (OAR).
.. COMMENT: All rights reserved.

Introduction
************

This document describes how to create or modify a Board Support Package (BSP)
for RTEMS, i.e. how to port RTEMS on a new microcontroller, system on chip
(SoC) or board.  It is strongly recommended to notify the
`RTEMS development mailing <https://lists.rtems.org/mailman/listinfo/devel>`_
about any activity in this area and maybe also
`add tickets <https://devel.rtems.org/newticket>`_
for specific work packages.

A basic BSP consists of the following components:

- Low-level initialization
- Console driver
- Clock driver
