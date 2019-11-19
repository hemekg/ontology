HemeKG Terminology
==================
This repository the terminology around heme comprising terms that are not belonging to any of the standard ontologies
used in the biomedical domain such as MESH or GO.

Citation
--------
If you find HemeKG useful in your work, please consider citing:

.. [1] Humayun, F., *et al.*: A computational approach for mapping heme biology in the context of hemolytic disorders. bioRxiv 804906. https://www.biorxiv.org/content/10.1101/804906v1

Contents
--------
`terms.csv <https://github.com/hemekg/terminology/blob/master/terms.csv>`_
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
List of terms in the terminology together with their identifiers, labels, descriptions, and references.

Columns:

1. Identifier - the Heme Terminology identifier (matching regular expression `HM\d{5}`
2. Class Name - the entity class, referring to https://github.com/pharmacome/conso/blob/master/classes.tsv that annotates what type of entity the term is, and what BEL types it maps to.
3. Name - the label of the term
4. References (namespace prefixed, comma separated. Example: pmid:1234, pmid:1245, pmc:PMC1234)
5. Description - a free text description of the term

`synonyms.csv <https://github.com/hemekg/terminology/blob/master/synonyms.csv>`_
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Synonyms to the terms included in the terminology.

Columns:

1. Identifier
2. Synonym
3. References (namespace prefixed, comma separated. Example: pmid:1234, pmid:1245, pmc:PMC1234)
4. Specificity (one of EXACT, BROAD, NARROW, or RELATED. See: https://owlcollab.github.io/oboformat/doc/GO.format.obo-1_4.html)
