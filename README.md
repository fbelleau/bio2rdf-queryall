Bio2RDF-queryall BETA REST service
==================================

Query all SPARQL endpoints for description of Bio2RDF URIs and reverse links 
based on the statistics of each endpoints from release 3.

This project is based on Taled ESB version 5.4.

It can be deployed by downloading REST_Bio2RDF_QueryAll_9007_0.1.zip and executing the batch file. It runs on http://localhost:9007.

The namespaces.csv file contains the "namespce TO endpoint" relationship used.

Example queries :

http://queryall.rest.bio2rdf.org/queryall/go:0004396

http://queryall.rest.bio2rdf.org/queryall/genbank:BC149752

http://queryall.rest.bio2rdf.org/queryall/uniprot:A6QQB6

http://queryall.rest.bio2rdf.org/queryall/affymetrix:Bt.9225.1.A1_at

http://queryall.rest.bio2rdf.org/queryall/ec:2.7.1.1

http://queryall.rest.bio2rdf.org/queryall/refseq:NP_036866
