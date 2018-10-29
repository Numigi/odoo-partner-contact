.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
    :target: https://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3

================================
Partner first name and last name
================================


Configuration
=============

You can configure some common name patterns for the inverse function
in Settings > General settings:

* Lastname Firstname: For example 'Anderson Robert'
* Lastname, Firstname: For example 'Anderson, Robert'
* Firstname Lastname: For example 'Robert Anderson'

After applying the changes, you can recalculate all partners name clicking
"Recalculate names" button. Note: This process could take so much time depending
how many partners there are in database.

You can use *_get_inverse_name* method to get lastname and firstname from a simple string
and also *_get_computed_name* to get a name form the lastname and firstname.
These methods can be overridden to change the format specified above.


Usage
=====



.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/134/11.0

For further information, please visit:

* https://www.odoo.com/forum/help-1


Known issues / Roadmap
======================




Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/OCA/partner-contact/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
=======

Contributors
------------



Translations
------------

* Danish: Hans Henrik Gabelgaard
* Italian: Leonardo Donelli
* Spanish: Antonio Espinosa
* Antonio Espinosa <antonioea@antiun.com>

Maintainer
----------

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

This module is maintained by the OCA.

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

To contribute to this module, please visit https://odoo-community.org.
