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


Contributing
------------

e.g.
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write you change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: sawanobory(HiganWorks LLC)

License: Apache2
