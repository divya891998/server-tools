=================
Module Prototyper
=================

.. !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fserver--tools-lightgray.png?logo=github
    :target: https://github.com/OCA/server-tools/tree/14.0/module_prototyper
    :alt: OCA/server-tools
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/server-tools-14-0/server-tools-14-0-module_prototyper
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runbot-Try%20me-875A7B.png
    :target: https://runbot.odoo-community.org/runbot/149/14.0
    :alt: Try me on Runbot

|badge1| |badge2| |badge3| |badge4| |badge5| 


This module allows the administrator to prototype new features and export them as module.
Functional people can prepare the job for a developer who is left with the logic to implement
in addition to everything the prototype does not export yet.

Installation
============

Make sure you have Jinja2 version 2.7.3 or higher installed::

$ pip install --upgrade Jinja2==2.7.3

**Table of contents**

.. contents::
   :local:

Usage
=====

To use this module, you need to:

* install the dependencies of your future module
* customize your instance by adding fields and creating inherited views
* create your menu items and their window actions
* prepare your data and demo data by creating filters
* create your own groups with access rights and record rules
* add your own access rights and record rules to an existing group

Once you have customized your instance properly, you can go to Settings > Module Prototypes > Prototypes
and create a new prototype:

* fill in the information of your module (enter the name, the description, the logo, etc.)
* in the Depencencies tab, select all the other modules that yours will be depending on
* in the Data & Demo tab, select your filters for data and demo data
* in the Fields tab, select the fields you created or customized
* in the Interface tab, select your menu items and your views
* in the Security tab, select your groups, access rights and record rules
* save and click on export

You will get a zip file containing your module ready to be installed and compliant with the
conventions of the OCA. You can then provide the module to a developer who have to implement
things like default values or onchange methods.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/149/10.0

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/server-tools/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us smashing it by providing a detailed and welcomed
`feedback <https://github.com/OCA/server-tools/issues/new?body=module:%20module_prototyper%0Aversion:%2014.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Pelayo Gómez

Contributors
~~~~~~~~~~~~

* David Arnold <blaggacao@users.noreply.github.com>
* Jordi Riera <jordi.riera@savoirfairelinux.com>
* Maxime Chambreuil <maxime.chambreuil@savoirfairelinux.com>
* El hadji Dem <elhadji.dem@savoirfairelinux.com>
* Savoir-faire Linux <support@savoirfairelinux.com>
* Vincent Vinet <vincent.vinet@savoirfairelinux.com>
* Nicolas JEUDY <nicolas@sudokeys.com>
* Dennis Sluijk <d.sluijk@onestein.nl>
* Dhara Solanki <dhara.solanki@initos.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/server-tools <https://github.com/OCA/server-tools/tree/14.0/module_prototyper>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
