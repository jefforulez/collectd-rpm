collectd-rpm
============

Repository which provides a sane RPM SPEC file for building RPMs on RHEL/CentOS
Linux.

Setting up the toolchain
------------------------

In order to compile a sane RPM file it's recommended to use the toolchain of
mock to build the rpms. mock is the same tool which is being used to build the
RPMs of Fedora, CentOS and EPEL. Basically, it sets up a chroot environment,
changes into it and runs the required compile steps.

The chroot environment is provided every time you start a new build. This
make sure that your environment is clean and only sane dependencies are used
to link the binaries.

