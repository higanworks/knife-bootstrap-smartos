knife-bootstrap-smartos
=======================

knife bootstrap distro for joyent smartmachine

Its includes [ohai plugin joyent](https://github.com/ZCloud-Firstserver/ohai_plugin_joyent).

Usage
---

Add bootstrap repository as submodule to your chef-repo.

`git submodule add git://github.com/ZCloud-Firstserver/knife-bootstrap-smartos.git .chef/bootstra`

Bootstrap with --distro(-d) option

`knife bootstrap ${smartmachine_address} -d smartos`
