# Australian Open Data Portals

A list of Australia open data publishers and portals.

The data and content in [Australian Open Data Portals][gh-repo] by [the ODI Australian Network](https://theodi.org.au) and [contributors][gh_contributors] is licensed under a [Creative Commons By Attribution licence](https://creativecommons.org/licenses/by/4.0/).

![CC-BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)

The ODI Australian Network and contributors waive the requirement for attribution under this licence, for this data.

## The Data

The list of Australian Open Data Portals is maintained in [australian-open-data-portals.csv][dp_data].

It is described using two different specifications:

- [Frictionless Data](#frictionless-data)
- [CSV for the Web](#csv-for-the-web)

### Frictionless Data

The data is described using the [Frictionless Data](http://frictionlessdata.io) [Specification](http://frictionlessdata.io/specs/).

The [data][dp_data] is stored with its [metadata][dp_datapackage_json] and [provenance information][dp_provenance] in the [datapackage directory][dp_dir]. These files can be downloaded together in the [datapackage.zip][dp_zip] file

The data is validated against the schema in the [data package][dp_datapackage_json] whenever it changes. [GoodTables.io](http://goodtables.io/) is used to perform the validation and generate a badge:

[![goodtables.io](https://goodtables.io/badge/github/Stephen-Gates/Australian-Open-Data-Portals.svg)](https://goodtables.io/github/Stephen-Gates/Australian-Open-Data-Portals)

The data package can be viewed using [Data Package Viewer](http://data.okfn.org/tools/view?url=https%3A%2F%2Fraw.githubusercontent.com%2FODIQueensland%2Fopendataportals%2Fmaster%2Fdatapackage%2Fdatapackage.json).

### CSV for the Web

 An alternate metadata scheme, [CSV on the Web](https://www.w3.org/standards/techs/csv#w3c_all) by W3C, also describes the data.

 These files are out of date:

  - csv-metadata.json is generated using the [CSV Metadata Editor](http://data.wu.ac.at/csvengine/csvm/editor) from Vienna University and then hand edited to add restrictions
  - australian-open-data-portals.csv-metadata.json is the original hand edited file before the above generator was discovered.

## Software

The source code in this repository is available under [license][gh_license]

By [convention](http://frictionlessdata.io/specs/data-package/#illustrative-structure), scripts to prepare the data are placed in the /scripts directory within the data package.

## Contributions

Contributions are welcome - [learn how][gh_contributing]

[contact]: https://theodi.org.au/contact/
[gh-repo]: https://github.com/ODIQueensland/Australian-Open-Data-Portals
[gh_issues]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/issues
[gh_readme]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/blob/master/README.md
[gh_code_of_conduct]: https://github.com/ODIQueensland/Australian-Open-Data-Portals
[gh_license]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/blob/master/LICENSE
[gh_contributors]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/graphs/contributors
[gh_contributing]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/blob/master/.github/CONTRIBUTING.md
[dp_dir]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/blob/master/datapackage/
[dp_data]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/blob/master/datapackage/data/australian-open-data-portals.csv
[dp_provenance]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/blob/master/datapackage/README.md
[dp_datapackage_json]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/blob/master/datapackage/datapackage.json
[dp_zip]: https://github.com/ODIQueensland/Australian-Open-Data-Portals/blob/master/distribution/datapackage.zip
