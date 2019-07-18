## Assessment of all assets

Cleaned the 24 June dataset:

1. Fix the create and update date column formats
2. Delete obvious test datasets (search test and dummy, but watch out for lead test results from Asset_data sheet (the community datasets are still in there and also in the removed datasets sheet)
3. Remove community datasets, only use official, for PUBLISH sheet
4. Can't just rely on PUBLIC datasets because there are some not public ones that are accessed by public assets

The working list is Published assets that are official and are either public or not. All derived assets have a parent in the list

JSON to CSV: https://medium.com/@gabrielpires/how-to-convert-a-json-file-to-csv-python-script-a9ff0a3f906e
Use this to get JSON file with all metadata: https://data.wa.gov/views/asjc-htyz.json

Derived datasets pull metadata from underlying dataset so do not include those in assessment.


[State metadata Standards](https://docs.google.com/viewerng/viewer?url=https://ocio.wa.gov/sites/default/files/public/policies/187_10.docx) - eg origator should be department!

**During dataset upload:**

*General notes*
* Must enter title first thing
* Can specify data type for each col.
* There is an option to 'automate this' which provides python code to either update or replace
* Can set a column as 'row identifier'
* There is an option to transform column to geolocation (e.g. address to coords)
* Default metadata:
  * date created
  * owner (filled from user name)
  * column names and data type
  * number rows and columns
* Edit Dataset Metadata and Edit Column Metadata are optional (?) buttons

*Edit Dataset Metadata*
* Can edit title
* Brief Description
* Row Label (What each row represents)
* Categories- Controlled vocabulary
* Tags/Keywords- Free text
* License "Public License Type (if applicable)" - Controlled vocabulary [explanation](https://support.socrata.com/hc/en-us/articles/202950218-Which-licensing-option-should-I-use-)
* Data Provided By
* Source Link (web address of external site related to dataset)
* Contact email ("Private field. Only logged in users will see this value")
* Can add attachments
* Can add up to 6 notes (I'm unclear how this works- superscript column headings?)
* Period of Time- What range of dates does the dataset cover
* Posting Frequency
* Originator (no explanation) (identified in [187.10](https://docs.google.com/viewerng/viewer?url=https://ocio.wa.gov/sites/default/files/public/policies/187_10.docx) as the entity responsible for publishing the resource)
* Metadata Language - (no explanation but should be "English")

*Edit Column Metadata*
* Can edit Name, Description and API field name- many fail to add description

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

