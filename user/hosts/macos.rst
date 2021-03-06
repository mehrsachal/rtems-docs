.. comment SPDX-License-Identifier: CC-BY-SA-4.0

.. comment: Copyright (c) 2016 Chris Johns <chrisj@rtems.org>
.. comment: All rights reserved.

.. _macos:

Apple MacOS
===========

Apple's OS X is fully supported. You need to download and install a recent
version of the Apple developer application Xcode. Xocde is available in the App
Store. Make sure you install the Command Line Tools add on available for
download within Xcode and once installed open a Terminal shell and enter the
command ``cc`` and accept the license agreement.

The normal prefix when working on OS X as a user is under your home directory.
Prefixes of :file:`$HOME/development/rtems` or :file:`$HOME/rtems` are
suitable.

:ref:`prefixes` details using Prefixes to manage the installation.

MacOS
.. _Mavericks:

Mavericks
~~~~~~~~~

The RSB works on Mavericks and the GNU tools can be built for RTEMS using the
Mavericks clang LLVM tool chain. You will need to build and install a couple of
packages to make the RSB pass the ``sb-check``. These are CVS and XZ. You can get
these tools from a packaging tool for MacOS such as *MacPorts* or *HomeBrew*.

I do not use 3rd party packaging on MacOS and prefer to build the packages from
source using a prefix of ``/usr/local``. There are good 3rd party packages around
however they sometimes bring in extra dependence and that complicates my build
environment and I want to know the minimal requirements when building
tools. The following are required:

. The XZ package's home page is http://tukaani.org/xz/ and I use version
  5.0.5. XZ builds and installs cleanly.

Sierra
~~~~~~

The RSB works on Sierra with the latest Xcode.


