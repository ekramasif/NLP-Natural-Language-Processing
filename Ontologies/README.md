# Ontology

## Food Industry

- [FoodOn: a harmonized food ontology to increase global food traceability, quality control and data integration](https://www.nature.com/articles/s41538-018-0032-6)
- [Global agricultural concept space: lightweight semantics for pragmatic interoperability](https://www.nature.com/articles/s41538-019-0048-6)

## Meetups, Webinars, Videos

- [Reconciling Disparate Data with Ontologies](https://app.aiplus.training/courses/take/a-data-scientists-rosetta-stone-reconciling-disparate-data-with-ontologies/lessons/22205621-ai-training)

## Knowledge Graph vs Ontology

### What is the difference?

A knowledge base (KB) is fact-oriented but ontology is schema-oriented.

KB: In the Google KGraph, you have certainly a schema (like the one described by DBPedia, Freebase, etc.) and a set of facts (A relation B, "Paris isA City, Paris hasInhabitants 2M, Paris isCapitalOf France, France isA Country, etc.). So, we can (easily) answer to questions like "Number of inhabitants in Paris?" or you can provide a short description of Paris, France (or any given entity in general).

The domain ontology tells people which are the main concepts of a domain, how are these concepts related and which attributes do they have. Here the focus is on the description, with the highest possible expressiveness (disjointness, values restrictions, cardinality restrictions) and the useful annotations (synonyms, definition of terms, examples, comments on design choices, etc.), of the entities of a given domain. Data (or facts) are not the main concern when designing a domain ontology VS KB.

## List of Ontologies

- [List of all ontologies in OLS](https://www.ebi.ac.uk/ols/ontologies)
- Google Product Taxonomy:
  - [google_product_category](https://support.google.com/merchants/answer/6324436?hl=en)
  - [Visualised](http://vocabulary.semantic-web.at/GoogleProductTaxonomy.html)
- [NAPCS – North American Product Classification System](https://www.census.gov/newsroom/press-releases/2020/north-american-product-classification-codes.html)

### Knowledge models:

- [FOAF](http://xmlns.com/foaf/spec/) - This specification describes the FOAF language, defined as a dictionary of named properties and classes using W3C's RDF technology
- [Schema.org](https://schema.org) - Schema.org is a collaborative, community activity with a mission to create, maintain, and promote schemas for structured data on the Internet, on web pages, in email messages, and beyond.