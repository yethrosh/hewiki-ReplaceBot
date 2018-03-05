urWiki Replace bot is a python script for site wide replacements in Urdu Wikipedia.

See:
https://ur.m.wikipedia.org/wiki/ویکیپیڈیا:متداول_املائی_غلطیوں_کی_فہرستیں/برائے_خودکار_درستی

The script is based on pywikibot core.

Install
=======
* install Pywikibot.
   see: Manual:Pywikibot/Installation
   important: be sure core and scripts directory in pywikibot are in your PYTHONPATH
* Download the latest database dump:
   http://dumps.wikimedia.org/urwiki/
   ( hewiki-YYYYMMDD-pages-articles.xml )

Use
=======
python pwb.py imla -xml:DUMPNAME

License
=======
Distributed under the terms of the MIT license.

