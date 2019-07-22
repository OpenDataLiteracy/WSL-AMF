## Assessment of all assets notes


### What others have done:

Use Kubler et al. (2018) metadata assessment framework? 
https://github.com/OpenDataLiteracy/WSL-AMF/blob/master/assessment/Kubler-et-al-2018.JPG

> Existence, conformance, retrievability, accuracy, open data

Or Umbrich et al. (2015) portal assessment? https://github.com/OpenDataLiteracy/WSL-AMF/blob/master/assessment/Umbrich-et-al-2015.JPG

> Retrievability, usage, completeness, accuracy, openness and contactability.  

The European Open Data Portal Monitor assesses metadata completeness by these variables:
    
> licence, author, organisation, date released and date updated 

There is also the open government benchmark proposed by [Veljkovi´c et al. (2014)](https://www.sciencedirect.com/science/article/pii/S0740624X14000434)

Also think about the [5-stars](https://www.europeandataportal.eu/elearning/en/module10/#/id/co-01)

### Automatic ways to retrieve metadata:

    JSON to CSV: https://medium.com/@gabrielpires/how-to-convert-a-json-file-to-csv-python-script-a9ff0a3f906e
    Old python code to get metadata: https://github.com/josephlei/socrata-meta
    
    Socrata Metadata API (For Read and Write): https://socratametadataapi.docs.apiary.io/#introduction/available-metadata/all-available-fields
    Socrata Discovery API: https://socratadiscovery.docs.apiary.io/#reference/0/find-by-domain  Can search socrata universe by almost any field, even column name.  But it doesn't return column descriptions.
    [City of Austin Open Data](https://medium.com/open-austin/enhancing-the-city-of-austins-open-data-with-digital-citations-7fc2e9cca45) - [Contains code](https://github.com/OpenDataLiteracy/WSL-AMF/blob/master/assessment/portal-code-austin.md) that pulls all asset data from Socrata for a portal.

    >API for basic metadata: data.wa.gov/api/dcat.json
    >All Socrata dataset metadata (not record metadata): https://data.wa.gov/api/views/metadata/v1/{dataset-uid}
    >All metadata for dataset and records (put in the identifier): https://data.wa.gov/views/{dataset-uid}.json
    >ALL Asset ALL metadata: http://api.us.socrata.com/api/catalog/v1?limit=2000&domains=data.wa.gov


Derived datasets pull metadata from underlying dataset so do not include those in assessment.


[State metadata Standards](https://docs.google.com/viewerng/viewer?url=https://ocio.wa.gov/sites/default/files/public/policies/187_10.docx) - e.g. origator should be department!

### Elements to Judge Completeness

**Core**

* Owner (automatic)
* License "Public License Type (if applicable)" - Controlled vocabulary
* Categories- Controlled vocabulary
* Brief Description
* Data Provided By

**Extra**

* Row Label (What each row represents)
* Tags/Keywords- Free text
* Source Link (web address)
* Contact email ("Private field. Only logged in users will see this value")
* Period of Time
* Posting Frequency
* Originator (no explanation)
* Metadata Language (no explanation)


### Figures needed:

**Portal Assessment**

| Subject | Assets | Type |
|---------|--------|------|
Types (dataset, chart, etc) | All | pie or block
Categories | All | pie or block
Downloads | All | Box plot, by type
Views | All | Box plot, by type
Categories | Datasets | pie or block
Available metadata elements filled, % datasets | Datasets | bar
Core metadata elements filled, % datasets | Datasets | bar
% with links | Datasets | Text?

