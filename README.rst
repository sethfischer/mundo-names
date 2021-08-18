===========
mundo-names
===========

A project to translate the names of countries defined in ISO 3166-1,
part of the ISO 3166 standard published by the
`International Organization for Standardization (ISO)`_.


Scope
-----

The scope of translation is limited only to the names of countries listed in the current edition of ISO 3166-1.


Contributing
------------

If you would like to commit the translations directly to the repository,
make a clone of `mundo-names GitHub repository`_ and send a pull request.


Files and directories
---------------------

-   po/

    Directory containing complete, or partially complete, translation files.

-   check

    Script for comparing the contents of iso3166-1_en_proper_case.csv
    with the official list of ISO 3166-1 countries.

-   genpot

    Script used to generate the pot file.

-   iso3166-1_en.csv

    `Official list of ISO 3166-1 countries`_. As the publicly available CSV and XML files are not version controlled
    please refer to different versions by the date(“YYYY-mm-dd”) of download from the ISO website.

-   iso3166-1_en_msgid.csv

    List of ISO 3166-1 country codes along with the country name in sentence case
    (used for translation file msgid).

-   LICENCE

    Licence information.

-   mundo-names.pot

    Generated translation template file.

-   README.md

    This file.


See also
--------

https://github.com/sethfischer/mundo-flags


.. _`International Organization for Standardization (ISO)`: https://www.iso.org/
.. _`mundo-names GitHub repository`: https://github.com/sethfischer/mundo-names
.. _`Official list of ISO 3166-1 countries`: https://www.iso.org/iso-3166-country-codes.html
