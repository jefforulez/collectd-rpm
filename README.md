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

Dependencies
------------

g++
ganglia-devel
gcc
git
iptables-devel
java
java-devel
jpackage-utils
libcurl-devel
libdbi-devel
libesmtp-devel
libgcrypt-devel
libiptcdata-devel
libmemcached-devel
libnotify-devel
liboping-devel
libpcap-devel
librabbitmq-devel
libstatgrab-devel
libvirt-devel
libxml2-devel
lm_sensors-devel
lvm2-devel
make
memcached-devel
mysql-devel
net-snmp-devel
OpenIPMI-devel
perl-ExtUtils-Embed
perl-ExtUtils-MakeMaker
postgresql-devel
python-devel
rpm-build
rrdtool-devel
spamassassin
varnish-libs-devel
yajl-devel


