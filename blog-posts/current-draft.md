## Working Draft




Open government data portals can be a terrific resource for diverse public sector information in a structured format —water quality test results, licenses data for contractors and healthcare providers, lobbyist spending, et cetera. However, these data sets often vary widely in quality and utility. This is especially true where agencies publish directly to the portal without a central entity curating each dataset (e.g. unmediated deposits), leading to lots of data that may or may not be what people are looking for.  Although a decentralized approach to running an open data portal likely lowers costs and other barriers for data publishing, it also means that the steward of the open data portal needs to periodically remove datasets in order to maintain a more accessible collection for the public and other users. So, if some datasets need to be removed, how does a curator document the removal process in a transparent way??

As an intern for the Open Data Literacy (ODL) program with the University of Washington iSchool [1], I have been working with the Washington State Library to assess the state’s open data portal and offer recommendations for curating this important resource. After seven years of growth, the Washington State open data portal is now in need of curation and the State Library with its [history of curating government documents](https://www.sos.wa.gov/library/history.aspx) and state related information, is the perfect institution for the task.

As open data portals have expanded throughout all levels of our government, advocates have mostly focused on convincing agencies and departments to publish as much of what they can, when they can, using whatever means possible [2].  However, after years of successful application in hundreds of city, state, and international portals, the open government data movement now faces the problem of nearly drowning in oceans of [poor-quality data and metadata](https://blog.okfn.org/2017/05/31/open-data-quality-the-next-shift-in-open-data/). A clear and broadly applicable policy on the criteria for removing a dataset, as well as a system to track removals has yet to emerge. While this is not surprising considering one of the [10 Principles of Open Data](https://sunlightfoundation.com/policy/documents/ten-open-data-principles/) is that data should be published with permanence in mind, removing datasets is an essential activity for a portal with a variety of publishers. Weeding out low-quality datasets not only strengthens the reputation of quality for any data repository, but it can also make it easier for users of any type to find data that is current and relevant to their needs.  However, in removing datasets, curators run the risk of cutting off sources of information that users may have grown accustomed to using in the past, and there is also a concern that removing data from an open government portal could be seen as a step away from transparency, no matter how rational the decision to remove it. 

Here is a use case: A dataset of proposed coal export terminals uploaded six years ago might seem like an easy candidate for removal— but what if that old dataset populates various maps in a rarely used but important online government document?  Removing the dataset would affect that document and could also be seen as an effort to obscure information.

There has been very little focus on this topic in research or literature. In looking for examples we could use for Washington State, [New York City](https://opendata.cityofnewyork.us/wp-content/uploads/2018/02/Open-Data-Removals-Process-and-Guidelines.pdf) may have one of the clearest, and only publicly viewable, policies available.  Their process works like this:

1.	Data is identified for removal either by the dataset owner or portal curators.  Candidates include data that do not meet the definition of data or are not updated and not analytically useful.
2.	After confirmatory discussion with the dataset owner, the dataset is unpublished for three months and then deleted from the portal.  
3.	A small portion of that dataset’s metadata and the reason for removal is added to a [dataset available on the portal](https://data.cityofnewyork.us/dataset/Dataset-Removals/tm5c-buy3). 
4.  The dataset may be archived or completely deleted. 

This is a thorough solution, but it requires quite a bit of human labor and only works when a portal is curated by a central department.  Additionally, depending on the deletion process, deleted data may never be recoverable if it is ever needed again.

An ideal solution for a more decentralized portal would be an automated system that updates the metadata with a reason for deletion and compresses and archives each dataset upon deletion by the dataset owner.  The results page for any search on the portal could prompt users to rerun their search and include records of deleted datasets, if their search did not provide expected results.

Socrata and CKAN, two popular open government data portal platforms, both allow the deletion and recovery of datasets but neither provides a user-friendly tracking process.  Until an automated, user-focused solution appears, what can a portal steward do to maintain transparency and access while effectively removing or archiving datasets?

If storage is not a limiting factor, a portal curator could do the following:
1.	Request feedback from the dataset owner about upcoming changes to their dataset
2.	Replace the original dataset with an identical, but compressed version, or upload compressed format as a new version
3.	Note in the description why the data is being archived and where better data is located
4.	Change its category metadata element to ‘Archived’ or something similar

This solution would indicate to a user the status of the dataset both by the category of ‘Archived’ and the compressed data format, while also indicating why the dataset was archived and possibly indicating where better data is located.

As always, a system would need to work within the constraints of budgetary restrictions and portal curator time.  Developing something like this system will likely be one of my recommendations for how the State Library can help curate the Washington State open data portal, hopefully to create a system that remains both functional and efficient for data administrators and users alike.


[1] The ODL program is funded by the Institute of Museum and Library Services and works towards creative and realistic ways to help government agencies and libraries create or work with open data. 


Possible citations for [2]:

[Set appropriately ambitious timeline](https://opendatapolicyhub.sunlightfoundation.com/guidelines/27-timelines/)

[open by default](https://www.gov.uk/government/publications/open-data-charter/g8-open-data-charter-and-technical-annex)
