# zabbix-check-ksm

## Description

A script to show [Kernel same-page merging](https://en.wikipedia.org/wiki/Kernel_same-page_merging) metrics in [Zabbix](https://zabbix.com).

## Usage

* Clone this repo and build the debian package yourself with `LANG=C debuild -us -uc -b; dh clean`
**or**
* Install it directly from @istoph's [repository](https://blog.chr.istoph.de/repository/)
**or**
* Clone this repo and install the script and config by hand

## Licence

New BSD License/BSD 3-Clause License (see [debian/copyright](debian/copyright))

## Template for the Zabbix frontend

A template for the Zabbix frontend can be found, as usual in our packages, in [/usr/share/doc/examples/${package_name}/](examples/)
