Changelog
=========
2.0.3 (2016-11-23)
------------------
- Ignore x- vendor extensions in the schema at the #/paths/{path}/{http_method} level - PR #45
- Swagger 2.0 schema synced with upstream - PR #40

2.0.2 (2015-11-18)
------------------
- Fix regression with Swagger 1.2 schemas - #43

2.0.1 (2015-11-17)
------------------
- Fix rich validations that rely on a working deref with scope annotations

2.0.0 (2015-11-17)
------------------
- Support for recursive $refs
- Unqualified $refs no longer supported.
  Bad:  ``{"$ref": "User"}``
  Good: ``{"$ref": "#/definitions/User"}``

1.1.1 (2015-10-02)
------------------
 - Workaround for validation of Swagger 2.0 schemas with external refs - #38

1.1.0 (2015-08-24)
------------------
 - Validate crossrefs - #33, #34

1.0.12 (2015-07-02)
-------------------
 - Handle API level parameters - #29
 - More robust handling of $refs - #29

1.0.11 (2015-06-02)
-------------------
 - Validation for model name and it (Swagger 1.2)
 - Remove unnecessary dependency on pyyaml

1.0.10 (2015-04-15)
-------------------
 - Pin of jsonschema used for unit tests for Python3

1.0.9 (2015-03-26)
------------------
 - Sync Swagger 2.0 schema with upstream - allow empty arrays for parameter
 - Handle schemas with no definitions

1.0.8 (2015-03-11)
------------------
 - Petstore URLs updated
 - Support 'type: File' for (Swagger 1.2)

1.0.7 (2015-03-02)
------------------
 - Python3 support
 - Use simplejson when available

1.0.5 (2015-02-19)
------------------
 - Add file:// support

1.0.3 (2015-01-05)
------------------
 - Initial support for Swagger 2.0

1.0.2 (2014-10-24)
------------------
 - Bugfix for path construction in validate_resource_listing_url

1.0.1 (2014-10-24)
------------------
 - Bugfix to including jsonschema files

1.0.0 (2014-10-24)
------------------
 - Initial version
