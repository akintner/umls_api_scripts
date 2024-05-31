# Welcome 
The **United Medical Langauge System (UMLS)** is a compendium of many controlled vocabularies in the biomedical sciences. It provides a mapping structure among these vocabularies and thus allows one to translate among the various terminology systems; it may also be viewed as a comprehensive thesaurus and ontology of biomedical concepts. Their API interface brings together many health and biomedical vocabularies and standards to enable interoperability between computer systems.
For more information, check their website [here](https://uts.nlm.nih.gov/uts/?_gl=1*mux6y7*_ga*MTI4MzgzNzU3NC4xNzE3MTcxNDI1*_ga_7147EPK006*MTcxNzE4MTQ5NC4yLjEuMTcxNzE4MjA4Mi4wLjAuMA..*_ga_P1FPTH9PL4*MTcxNzE4MTQ5NC4yLjEuMTcxNzE4MjA4Mi4wLjAuMA..)

## USAGE: 
URIs with /search support the following use cases:
- Return a list of CUIs and their names when searching a human readable term.
- Return a list of source-asserted identifiers (codes) and their names when searching a human readable term.
- Map source-asserted identifiers to UMLS CUIs.
- Note that ‘current’ in the URI can always be used to search against the latest UMLS publication.
- You may use any valid UMLS release back to 2008AA in your URI if you would like to search against a particular version of the UMLS.

The base URI for all requests is `https://uts-ws.nlm.nih.gov/rest`

## DISCLAIMER
In order to avoid overloading their servers, NLM requires that users send `no more than 20 requests per second per IP address`. Requests that exceed this limit may not be serviced, and service will not be restored until the request rate falls beneath the limit. To limit the number of requests that you send to the APIs, NLM recommends caching results for a 12-24 hour period. This policy is in place to ensure that the service remains available and accessible to all users.

This product uses publicly available data from the U.S. National Library of Medicine (NLM), National Institutes of Health, Department of 
Health and Human Services; NLM is not responsible for the product and does not endorse or recommend this or any other product.

Developers may not use the NLM name and/or logo in conjunction with their applications.

It is not the intention of NLM to provide specific medical advice, but rather to provide users with information to better understand their health and their medications. NLM urges you to consult with a qualified physician for medical advice.
