# Core-O: A Competence Reference Ontology for Professional and Learning Ecosystems

The objective of Core-O is to support the representation of competences and related elements (skills, knowledge, attitudes) both at the individual level, i.e., when these elements are attributed to particular individuals, but also when required by occupations in general. It addresses also the performance of competences (related to tasks, their context, and outcomes) as well as their evolution over time.

A reference version in OntoUML ([competence_ontology.vpp](competence_ontology.vpp)) and a gUFO-based operational version in OWL [competence_ontology.ttl](competence_ontology.ttl) are included in this repository. Competency questions used in its development are also available (see the [docs folder](docs)).

Both are published following FAIR principles. The reference version in OntoUML is published in the [OntoUML/UFO FAIR catalog](https://scs-ontouml.eemcs.utwente.nl/). The OWL version can be found in [https://purl.org/coreo#](https://purl.org/coreo). It has been checked with the [FOOPS! Ontology Pitfall Scanner for the FAIR principles](<https://foops.linkeddata.es/FAIR_validator.html>) with a 88% FAIRness score.

To use the OntoUML version, use the [OntoUML Visual Paradigm plugin](https://github.com/OntoUML/ontouml-vp-plugin).

To import Core-O in Protégé use <https://purl.org/coreo#> (using `https` instead of `http`). (This is required in Protégé up to 5.6.1 as it uses a version of the OWL API that is unable to handle multiple http redirects.)

Authors:

* Rodrigo F. Calhau;
* João Paulo A. Almeida;
* Tiago Prince Sales;
* Giancarlo Guizzardi.

See <http://purl.org/nemo/doc/gufo> for the foundational ontology employed.
