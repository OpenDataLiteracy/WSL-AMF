## Assessment of all assets

Cleaned the 24 June dataset:

1. Fix the create and update date column formats
2. Delete obvious test datasets (search test and dummy, but watch out for lead test results from Asset_data sheet (the community datasets are still in there and also in the removed datasets sheet)
3. Remove community datasets, only use official, for PUBLISH sheet
4. Can't just rely on PUBLIC datasets because there are sume not public ones that are accessed by public assets

The working list is Published assets that are official and are either public or not. All derived assets have a parent in the list

Derived datasets pull metadata from underlying dataset so do not include those in assessment.


**During dataset upload:**

*General notes*
* Must enter title first thing
* Can specify data type for each col.
* There is an option to 'automate this' which provides python code to either update or replace
* Can set a col as 'row identifier'
* There is an option to transform col to geolocation (e.g. coords to address)
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
* Categroies- Controlled vocabulary
* Free entry
* License "Public License Type (if applicable)" - Controlled vocabulary
* Data Provided By
* Source Link
* Contact email ("Private field. Only logged in users will see this value")
* Can add attachments
* Period of Time
* Posting Frequency
* Originator (no explanation)
* Metadata Language (no explanation)

*Edit Column Metadata*
* Can edit Name, Description and API field name
