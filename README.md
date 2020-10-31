# SPICE-OntoServer
SPICE-Ontology Server and Infrastructure Setup



The Setup provides the code of the adopted workflow of the SPICE technical infrastructure, composed by an ontology Server integrating the following software components:

• OWL-API 5 ( http://owlcs.github.io/owlapi/ )
• HERMIT ( http://www.hermit-reasoner.com/ )
• ONT-API 2.0.0 ( https://github.com/owlcs/ont-api ), 
• JENA ( https://jena.apache.org/index.html ),
• Fuseki 2 ( https://jena.apache.org/documentation/fuseki2/index.html ) 

In particular, the provided setup shows how the processes of ontology uploading and reasoning requests are obtained via OWL-API (lines 1-16) by using external IRIs; how the inferred ontology is exposed as a JENA graph model and automatically uploaded in the SPARQL server hosting Fuseki 2 via the RDF Connection APIs (//Translation into Jena Model (lines 17-31) and, finally, how it is possibile to run SPARQL queries and SPARQL updated on the provided remote Fuseki server exposed in the provided infrastructure (lines 34-67).
