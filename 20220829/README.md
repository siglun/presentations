
# MODS & METS & misc stuff

## MODS

Canonical references: https://www.loc.gov/standards/mods/ and https://www.loc.gov/standards/mods/userguide/

* When I was depressed started I to write this: https://github.com/kb-dk/the-way-we-thought-on-metadata (far from complete)
* An example corpus of records from COP: https://github.com/kb-dk/ds-solr/tree/nested-solr-indexing/nested-corpus

Data available from COP backend:
https://github.com/kb-dk/access-digital-objects/blob/master/cop-backend.md#examples

See also preservation service problems...

## METS

Canonical references: https://www.loc.gov/standards/mets/ and https://www.loc.gov/standards/mets/METSOverview.v3_en.html

* The description of METS as used in Cumulus Preservation Service (CPS): http://id.kb.dk/metadata/index.html
* The _permalink_ data: https://github.com/kb-dk/permalink-manus/tree/master/src/main/webapp/data

METS KB Example: http://oraapp-prod-02.kb.dk/permalink/2006/manus/7/eng/ & http://oraapp-prod-02.kb.dk/permalink/2006/manus/7/ara/

## Rights management (proposal)

* The rights-management proposal: https://github.com/kb-dk/rights-access-metadata

## misc stuff

According to Tue: 

1. rendings links (I dag et Cumulus jpg2000 renderings sidesystem inkl. ejer og vandmærker på billeder, men forventes erstattet af nyt i Digitale samlinger). Current situation (According to Sigge): https://github.com/kb-dk/access-digital-objects/blob/master/image-delivery.md#constructing-iiif-uris
1. hierarkisk publicerings indholds struktur (Cumulus anvender udsnit af kategori struktur, som afspejles i nuværende Digitale Samlinger): For example (According to Sigge): Cop navigation service http://www5.kb.dk/cop/navigation/manus/ortsam/2009/okt/orientalia/subject637/en/ & http://www5.kb.dk/manus/ortsam/2009/okt/orientalia/subject637/en/
1. flersidede værker

This is an extremely complex problem: The TEI model for multiple sets of milestones (e.g.: page breaks in different editions):
* https://tei-c.org/release/doc/tei-p5-doc/en/html/CO.html#CORS5
* https://raw.githubusercontent.com/kb-dk/SKS_tei/master/data/v1.9/ee1/txt.xml
* http://xstorage-test-01.kb.dk:8080/exist/rest/db/text-retriever/present.xq?path=sks-ee1-txt-root#s231 (text service backend)


