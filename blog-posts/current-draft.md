## Working Draft


Open government data portals can be a terrific resource for diverse public sector information in a structured format —water quality test results, licenses data for contractors and healthcare providers, lobbyist spending, et cetera. However, these data sets often vary widely in quality and utility. This is especially true where agencies publish directly to the portal without a central entity curating each dataset (e.g. unmediated deposits), leading to lots of data that may or may not be what people are looking for.  Although a decentralized approach [to what?]  can lower costs and other barriers for data publishing, it also means that the steward of the open data portal needs to periodically weed the data produced in order to maintain a more accessible collection for the public and other users.  So, how do you know which data are the “weeds” and which are the ones you want to keep?? [ State the question more exactly ... Part of the value to writing is to clarify your own thoughts, and this to me seems a bit jargony and unclear ]

As an intern for the Open Data Literacy (ODL) program with the University of Washington iSchool [1], I have been working with the Washington State Library to assess the state’s open data portal and offer recommendations for curating this important resource. After seven years of growth, the Washington State open data portal is now in need of curation and the State Library is the perfect institution for the task. [Why?] 

As open data portals have expanded throughout all levels of our government, advocates have mostly focused on convincing agencies and departments to publish as much of what they can, when they can, using whatever means possible [citation needed].  However, after years of successful application in hundreds of city, state, and international portals,  the open government data movement now faces the problem of nearly drowning in oceans of poor-quality data and metadata [citation needed]. A clear and broadly applicable policy on the criteria for removing a dataset, as well as a system to track removals has yet to emerge. And yet, this activity seems essential for any institution charged with publishing and maintianing data for public use. Weeding out low-quality datasets not only strengthens the reputation of quality for any data repository, but it [can] also makes it easier for users of any type to find data that is current and relevant to their needs.  However, in removing datasets, we [who is we?] run the risk of cutting off sources of information that users may have grown accustomed to using in the past, and there is also a concern that removing data from an open government portal could be seen as a step away from transparency, no matter how rational the decision to remove it. To the portal curator, a dataset on barrier removals in a river from 2012 might seem like an easy candidate for removal—but what if that old dataset is the source for charts in a rarely used but important fisheries website used by a state agency? [don't ask hypothetical's like this - state this is a use case and then state the problem]

Despite its importance, there has been very little focus on this topic in research or literature [You said this earlier, yes? might not need to state again]. In looking for examples we could use for Washington State, New York City may have one of the clearest, and only publicly viewable, policies available.  

Their process works like this: 
1.	Data is identified for removal either by the dataset owner or portal curators.  Candidates include data that does not meet the definition of data or is not updated and not analytically useful.
2.	After confirmatory discussion with the dataset owner, the dataset is unpublished for three months and then deleted [from a portal entry, not deleted completely, right?].  
3.	A small portion of that dataset’s metadata and the reason for removal is added to a dataset available on the portal. 
4.	 The dataset may be archived or completely deleted. 

This is a thorough solution, but it requires quite a bit of human labor and only works when a portal is curated by a central department.  Ultimately, deleted data may never be recoverable if it is ever needed again. [Are you sure this is the case? It seems another open question is what "small portion of metadata" is necessary to accurately document and communicate the contents of the removed dataset]  

An ideal solution for a more decentralized portal would be an automated system that updates the metadata with a reason for deletion and compresses and archives each dataset upon deletion by the dataset owner.  Portal users could then search metadata for deleted datasets if searching published datasets did not return the expected results. [ This seems important - but you may want to clarify are these two different searches? 

Socrata and CKAN, two popular open government data portal platforms, both allow the deletion and recovery of datasets but neither provides a user-friendly tracking process.  Until an automated, user-focused solution appears, what can a portal steward do to maintain transparency and access?

If storage is not a limiting factor, a portal curator could do the following:
1.	Request feedback from the dataset owner about upcoming changes to their dataset
2.	Compress and re-upload the dataset [ Unclear - why is the original dataset being re-uploaded?]
3.	Note in the description why the data is being archived and where better data is located
4.	Change its category metadata element to ‘Archived’

[Is this archiving or removing from catalog though?] 

This solution would indicate to a user the status of the dataset both by the category of ‘Archived’ and the compressed data format, while also indicating why the dataset was archived and possibly indicating where better data is located.

As always, a system would need to work within the constraints of budgetary restrictions and portal curator time.  Developing something like this system will likely be one of my recommendations for how the State Library can help curate the Washington State open data portal, hopefully to create a system that remains both functional and efficient for data administrators and users alike.


[1] The ODL program is funded by the Institute of Museum and Library Services and works towards creative and realistic ways to help government agencies and libraries create or work with open data. 
