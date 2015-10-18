# data.epsg.io

The regularly updated EPSG database available as Open Knowledge Foundation OKNF [Tabular DataPackage](http://data.okfn.org/doc/tabular-data-package).

The CI (=Travis) should check validity and produce a ready to use SQLite - as [proposed](https://lists.osgeo.org/pipermail/metacrs/2015-August/thread.html) in the OSGEO MetaCRS mailing-list.

Initial version to be powered by libtiff-epsg import scripts and data dumps from epsg-registry.org.
CSV format should be contain maximal amount of information from the original IOGP's http://epsg-registry.org/ GML files.
