## Things that are confusing on Socrata

In the json files for datasets, under metadata there is the 'rowLabel' element that holds the value entered under 'Each row is...' when uploading data.  However, there are many datasets where the json file has a value of "Row" that does not show up on the main url for the dataset.  Values other than row do appear.  How does this happen?

This one has "Row":

https://data.wa.gov/views/9bjy-hi93.json

https://data.wa.gov/Health/Medicare-Beneficiary-Enrollment-and-Demographics-W/9bjy-hi93


This one has a value:

https://data.wa.gov/views/9zru-c2kz.json

### Downloads and Views
I emailed Socrata about this. Socrata online help is very responsive (Yvonne Oulo helped me) and below are answers to three questions.  I must have just missed the answer to number 1 since I read that page a few times...
1. According to this article; https://support.socrata.com/hc/en-us/articles/202949968-Learn-about-data-portal-usage-from-Socrata-Site-Analytics  API traffic does add to the number of views.

2. The number of downloads is not solely based on the number of clicks on the download button (eg. when a user clicks the 'Export' button on the site analysis page). Downloads done programmatically are also counted. These downloads can be done using a download link without having to load the dataset. A view is not required to download an asset.

3. The dataset page views should include the number of child views.  The Exported CVS file from the site analytics page will give you a breakdown of the domain metrics of the specified time. You can click on this article "https://support.socrata.com/hc/en-us/articles/115004513528" to get column definitions of the site metrics export. We are currently working on improving the granularity of the metrics events in the next couple of months so that trends can be spotted easier.

> EXCEPT See these search results: https://data.wa.gov/browse?q=Statewide+Stream+Miles+Opened  The first result, a chart, has many more page views than the second result, a dataset, on which it is based.


