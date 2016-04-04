===========
blue_plugin
===========

blue_plugin is an example of adding a new column extension to the
OpenStack Dashboard. The content is not meant for real use.


Requirements
============

blue_plugin is intended to use only on systems running Horizon
Applies only if the Images Table is using the Angular Table Directive
https://review.openstack.org/#/c/285002/


How to test this package
========================

1. Git clone this repo to your local machine
2. Run "python setup.py sdist" in the folder
3. Run "./tools/with_venv.sh pip install blue_plugin/sdist/..tar.gz" in horizon
4. Copy files in the enabled folder to ``openstack_dashboard/local/enabled``
5. Restart Apache or your Django test server