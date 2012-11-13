mundo-names
===========

A project to translate the names of countries defined in ISO 3166-1, part of 
the ISO 3166 standard published by the 
[International Organization for Standardization (ISO)][1].


Scope
-----

The scope of translation is limited only to the names of countries listed in 
the current edition of ISO 3166-1.


Contributing
------------

If you would like to commit the translations directly to the repository, make a 
clone of [mundo-names GitHub repository][2] and send a pull request.


Files and directories
---------------------

* po/

    Directory containing complete, or partially complete, translation files.

* check

    Script for comparing the contents of iso3166-1_en_proper_case.csv with the 
    official list of ISO 3166-1 countries.

* genpot

    Script used to generate the pot file.

* iso3166-1_en.csv

    [Official list of ISO 3166-1 countries][3]. As the publicly available CSV 
    and XML files are not version controlled please refer to different versions 
    by the date("YYYY-mm-dd") of download from the ISO website.

* iso3166-1_en_msgid.csv

    List of ISO 3166-1 country codes along with the country name in sentence 
    case (used for translation file msgid).

* LICENCE

    Licence information.

* mundo-names.pot

    Generated translation template file.

* README.md

    This file.


See also
--------

[https://github.com/sethfischer/mundo-flags][4]


[1]: http://www.iso.org/
[2]: https://github.com/sethfischer/mundo-names
[3]: http://www.iso.org/iso/country_codes.htm
[4]: https://github.com/sethfischer/mundo-flags

