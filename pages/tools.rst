.. _ref-tools:

=====
Tools
=====

Tools is available since version 1.2.0. You can find it in the component's menu. Tools are used help you do some technical tasks easily without touching the source code or the database.

At the present time there is only 1 tool "Deal alias generator", more tools will be added in future. To run a tool, you just need to click it's "Run this tool now" button.

.. image:: ../images/com_cmlivedeal_tools.jpg

Deal alias generator
--------------------

Before version 1.2.0, there was no sharing feature. Since 1.2.0 we can share deals to social networks. To be able to share deals, we need to have deal alias. This tool help you create deal alias automatically based on deal title.

If you upgrade from a version older than 1.2.0, you need to run this tool at least once to generate aliases for your existing deals.

City alias generator
--------------------

This tool is available since 1.5.0 to support friendly URLs for categories and cities. Please see :ref:`ref-friendly_url` for more information. 

If you upgrade from a version older than 1.5.0, you need to run this tool at least once to generate aliases for your existing cities.

Sample PDF coupon generator
---------------------------

PDF coupon is introduced in 1.5.0. You can use this tool to see how your PDF coupon could look like. You just need to select a deal and click "Run this tool now" button. If there is no deals selected, sample content will be used.

To support PHP coupon you need to install a PHP library. Please see :ref:`ref-pdfcoupon` section for more information.