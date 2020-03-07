# PubTator-API-Wrapper
Functions to retrieve and process annotations with PubTator API


This is code that I wrote to help me use the PubMed and PubTator Central APIs.

My main use case for this "wrapper" was to take a single search term (e.g. "heart failure") and automatically create
a dataframe that contains each resulting PMID from PubMed, along with each Disease annotated in that PMID by PubTator Central,
plus that disease's corresponding MESH ID when available.

However! There are some basic functions in here that might be useful for other purposes. In general, it took a long time for me to
simply understand how to approach returning PMIDs and annotations from the PubMed and PTC databases, so I have outlined how to
do those things in the code and documentation. While this is neatly packaged up to serve my purposes well, I have tried to provide
thorough commenting in order to make these functions modular and modifiable to others' needs. There is a use case example included.
