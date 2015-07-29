# nsl-rdf

![CHAH logo](https://raw.githubusercontent.com/bio-org-au/services/master/grails-app/assets/images/CHAH-logo.png)

This project contains the RDF artifacts for the biodiversity.org.au sparql service. The two main components are aour static vocabularies and the d2rq configuration.

## Static vocabulary
Our rdf vocabularies are hosted as static files on our webserver. These files are OWL-RDF files and are probably best read with an OWL tool such as Protege or an online ontology browser.

We use the `/voc` prefix for our various vocabularies. The primary entry point for the NSL vocabulary is [http://biodiversity.org.au/voc/nsl/NSL]() .

## D2RQ sparql service
We use D2RQ to present a sparql service at [http://biodiversity.org.au/sparql](). This repository contains the D2RQ configuration that maps the NSL data structure to an RDF graph, as well as other d2rq setup.