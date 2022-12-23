# rda-complex-citations
Preston archive to track work related to RDA Complex Citation working group https://www.rd-alliance.org/group/complex-citations-working-group/case-statement/complex-citations-working-group-case-statement

Created in response to https://github.com/globalbioticinteractions/nomer/issues/123#issuecomment-1363947500 .

## history

generated using

```
preston history
```

```
preston history
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://purl.org/pav/hasVersion> <hash://sha256/064976329122fce99c80f769d3cdece0345ff91bb9b5a5fb7615fc0621eb1b60> .
```

with provenance generated via:

```
preston ls --anchor hash://sha256/064976329122fce99c80f769d3cdece0345ff91bb9b5a5fb7615fc0621eb1b60 --remote https://softwareheritage.org --remote https://raw.githubusercontent.com/jhpoelen/rda-complex-citations/main/data/
```

yielding:

```
<https://preston.guoda.bio> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#SoftwareAgent> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<https://preston.guoda.bio> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Agent> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<https://preston.guoda.bio> <http://purl.org/dc/terms/description> "Preston is a software program that finds, archives and provides access to biodiversity datasets."@en <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Activity> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> <http://purl.org/dc/terms/description> "A crawl event that discovers biodiversity archives."@en <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> <http://www.w3.org/ns/prov#startedAtTime> "2022-12-23T13:56:05.824Z"^^<http://www.w3.org/2001/XMLSchema#dateTime> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> <http://www.w3.org/ns/prov#wasStartedBy> <https://preston.guoda.bio> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<https://doi.org/10.5281/zenodo.1410543> <http://www.w3.org/ns/prov#usedBy> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<https://doi.org/10.5281/zenodo.1410543> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://purl.org/dc/dcmitype/Software> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<https://doi.org/10.5281/zenodo.1410543> <http://purl.org/dc/terms/bibliographicCitation> "Jorrit Poelen, Icaro Alzuru, & Michael Elliott. 2021. Preston: a biodiversity dataset tracker (Version 0.0.1-SNAPSHOT) [Software]. Zenodo. http://doi.org/10.5281/zenodo.1410543"@en <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Entity> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<urn:uuid:0659a54f-b713-4f86-a917-5be166a14110> <http://purl.org/dc/terms/description> "A biodiversity dataset graph archive."@en <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> .
<hash://sha256/58358ca2aa36da999b23899beb6a7088856d6f513832dabc80f0675acbb85b1a> <http://www.w3.org/ns/prov#wasGeneratedBy> <urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> <urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> .
<hash://sha256/58358ca2aa36da999b23899beb6a7088856d6f513832dabc80f0675acbb85b1a> <http://www.w3.org/ns/prov#qualifiedGeneration> <urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> <urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> .
<urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> <http://www.w3.org/ns/prov#generatedAtTime> "2022-12-23T13:56:07.255Z"^^<http://www.w3.org/2001/XMLSchema#dateTime> <urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> .
<urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> <http://www.w3.org/1999/02/22-rdf-syntax-ns#type> <http://www.w3.org/ns/prov#Generation> <urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> .
<urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> <http://www.w3.org/ns/prov#wasInformedBy> <urn:uuid:2646f1d4-a41b-4a0d-a35d-de0d79c530f5> <urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> .
<urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> <http://www.w3.org/ns/prov#used> <https://www.rd-alliance.org/group/complex-citations-working-group/case-statement/complex-citations-working-group-case-statement> <urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> .
<https://www.rd-alliance.org/group/complex-citations-working-group/case-statement/complex-citations-working-group-case-statement> <http://purl.org/pav/hasVersion> <hash://sha256/58358ca2aa36da999b23899beb6a7088856d6f513832dabc80f0675acbb85b1a> <urn:uuid:addb8458-9a72-4b5b-98b2-273c4c2f5ff2> .
```
