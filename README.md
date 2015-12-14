# ifcOWL
Four OWL ontologies are maintained in this location for the Industry Foundation Classes (IFC) schema in EXPRESS. For each ontology, an RDF serialisation (OWL, RDF) and a Turtle (TTL) serialisation is made available. These ontology files are identical to the ontology files maintained at [https://github.com/pipauwel/ifcOWL](https://github.com/pipauwel/ifcOWL). The ontology files can be generated from the EXPRESS files that are available at [http://www.buildingsmart-tech.org/specifications/ifc-releases/summary](http://www.buildingsmart-tech.org/specifications/ifc-releases/summary) using the converter source code that is available at [https://github.com/mmlab/IFC-to-RDF-converter](https://github.com/mmlab/IFC-to-RDF-converter).

More information about ifcOWL can be found in: Pieter Pauwels and Walter Terkaj (2016). EXPRESS to OWL for construction industry: towards a recommendable and usable ifcOWL ontology. Automation in Construction (in press). DOI:[10.1016/j.autcon.2015.12.003](http://dx.doi.org/10.1016/j.autcon.2015.12.003).

Contact: [pipauwel.pauwels@ugent.be](mailto:pipauwel.pauwels@ugent.be)

##The ontology files

###IFC4_ADD1
namespace URI: [https://w3id.org/ifc/IFC4_ADD1](https://w3id.org/ifc/IFC4_ADD1#)
files: [RDF](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC4_ADD1.rdf) [OWL](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC4_ADD1.owl) [TTL](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC4_ADD1.ttl) (these three are identical serialisations)

###IFC4
namespace URI: [https://w3id.org/ifc/IFC4](https://w3id.org/ifc/IFC4#)
files: [RDF](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC4.rdf) [OWL](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC4.owl) [TTL](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC4.ttl) (these three are identical serialisations)

###IFC2X3_TC1
namespace URI: [https://w3id.org/ifc/IFC2X3_TC1](https://w3id.org/ifc/IFC2X3_TC1#)
files: [RDF](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC2X3_TC1.rdf) [OWL](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC2X3_TC1.owl) [TTL](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC2X3_TC1.ttl) (these three are identical serialisations)

###IFC2X3_Final
namespace URI: [https://w3id.org/ifc/IFC2X3_Final](https://w3id.org/ifc/IFC2X3_Final#)
files: [RDF](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC2X3_Final.rdf) [OWL](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC2X3_Final.owl) [TTL](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC2X3_Final.ttl) (these three are identical serialisations)

##The HTML documentation files

* [IFC4_ADD1](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC4_ADD1/index.html)
* [IFC4](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC4/index.html)
* [IFC2X3_TC1](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC2X3_TC1/index.html)
* [IFC2X3_Final](https://github.com/openBIMstandards/ifcOWL/blob/master/IFC2X3_Final/index.html)

##Set up URL redirects
If a site is intended to serve HTML and RDF content at the same web location, proper URL redirects need to be set up in the server using .htaccess files. In this regard, we follow the guidelines that are published at [http://www.w3.org/TR/swbp-vocab-pub/#recipe3](http://www.w3.org/TR/swbp-vocab-pub/#recipe3) (extended configuration for hash namespaces). The following .htaccess files are needed for the above four ontologies and the HTML documentation.

* [.htaccess for IFC4_ADD1](https://github.com/openBIMstandards/ifcOWL/blob/master/rewriteenginefiles/IFC4_ADD1/.htaccess)
* [.htaccess for IFC4](https://github.com/openBIMstandards/ifcOWL/blob/master/rewriteenginefiles/IFC4/.htaccess)
* [.htaccess for IFC2X3_TC1](https://github.com/openBIMstandards/ifcOWL/blob/master/rewriteenginefiles/IFC2X3_TC1/.htaccess)
* [.htaccess for IFC2X3_Final](https://github.com/openBIMstandards/ifcOWL/blob/master/rewriteenginefiles/IFC2X3_Final/.htaccess)