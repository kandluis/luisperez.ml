---
title: "Using introspection to collect provenance in R"
collection: publications
permalink: /publication/2018-03-01-provenance-in-r
excerpt: 'RDataTracker is an R package that collects data provenance from R scripts (https://github.com/End-to-end-provenance/RDataTracker)'
date: 2018-03-01
venue: 'MDPI'
paperurl: 'https://www.mdpi.com/2227-9709/5/1/12'
citation: 'Lerner, B.; Boose, E.; Perez, L. Using Introspection to Collect Provenance in R. Informatics 2018, 5, 12. https://doi.org/10.3390/informatics5010012'
---

Data provenance is the history of an item of data from the point of its creation to its present state. It can support science by improving understanding of and confidence in data. RDataTracker is an R package that collects data provenance from R scripts (https://github.com/End-to-end-provenance/RDataTracker). In addition to details on inputs, outputs, and the computing environment collected by most provenance tools, RDataTracker also records a detailed execution trace and intermediate data values. It does this using R’s powerful introspection functions and by parsing R statements prior to sending them to the interpreter so it knows what provenance to collect. The provenance is stored in a specialized graph structure called a Data Derivation Graph, which makes it possible to determine exactly how an output value is computed or how an input value is used. In this paper, we provide details about the provenance RDataTracker collects and the mechanisms used to collect it. We also speculate about how this rich source of information could be used by other tools to help an R programmer gain a deeper understanding of the software used and to support reproducibility.

[Download](/files/provenance-in-r.pdf)