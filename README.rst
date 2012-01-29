====
FIPS
====

**FIPS** is a collection of country and sub-country encodings and mappings based on 
Federal Information Processing Standards Publication 10-4 (aka FIPS PUB 10-4),
developed by the National Institute of Standards and Technology (NIST).
Now known as Geopolitical Codes, it is currently maintained by the
National Geospatial-Intelligence Agency.[1]_

Projects Goals:

- To easily transform the data into other formats (e.g., XML or JSON)
  or generate code for use in our favorite programming languages.
- To provide a comprehensive mapping between FIPS PUB 10-4 and ISO 3166-2 codes.
- To identify deactivated codes that will show up in historical data and/or
  from data/service providers.

Why use FIPS?
=============
With the existence of ISO 3166-2 as an international standard,
and NIST's withdrawal of FIPS PUB 10-4 as a federal standard,
why bother with FIPS?

- you have a lot of unconverted historical data that uses FIPS PUB 10-4 codes
- there isn't a one-to-one mapping between FIPS PUB 10-4 and ISO 3166-2 codes
- it isn't obsolete -- Geopolitical Codes continues to be

What data is available?
=======================
The data is (currently) maintained in a tab-separated-value (TSV) file.

A *country* row consists of the following fields:

- FIPS PUB 10-3 code (2 characters)
- country name
- comment, e.g., type of administrative division

A *sub-country* row consists of the following fields:

- FIPS PUB 10-4 code (4 characters)
- sub-country name
- comment, e.g., (Conventional Names), [former Names]

Footnotes
=========
.. [1] http://earth-info.nga.mil/gns/html/gazetteers2.html
