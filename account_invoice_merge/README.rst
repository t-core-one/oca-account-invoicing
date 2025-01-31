.. image:: https://img.shields.io/badge/licence-AGPL--3-blue.svg
   :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
   :alt: License: AGPL-3

=====================
Account Invoice Merge
=====================

This module adds an action in the invoices list to merge invoices. Here are
the conditions to allow merging:

* Type should be the same (Customer Invoice, Supplier Invoice, Customer Refund or
  Supplier Refund)
* Partner should be the same
* Currency should be the same
* Account receivable account should be the same

Usage
=====

Go to a invoice tree view, select several invoices and click expand the
action button and click 'Merge Partner Invoice'.

.. image:: https://odoo-community.org/website/image/ir.attachment/5784_f2813bd/datas
   :alt: Try me on Runbot
   :target: https://runbot.odoo-community.org/runbot/95/10.0

Bug Tracker
===========

Bugs are tracked on `GitHub Issues
<https://github.com/OCA/account-invoicing/issues>`_. In case of trouble, please
check there if your issue has already been reported. If you spotted it first,
help us smashing it by providing a detailed and welcomed feedback.

Credits
=======

Contributors
------------

* Ian Li <ian.li@elico-corp.com>
* Cédric Pigeon <cedric.pigeon@acsone.eu>
* Lois Rilo <lois.rilo@eficent.com>
* Miquel Raïch <miquel.raich@eficent.com>
* Sylvain Van Hoof <sylvain@okia.be>
* Freni Patel <fpatel@opensourceintegrators.com>

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
