## Portal and Dataset Assessment Methods

### Portal Assessment

Cleaned the 24 June csv dataset (downloaded from data.wa.gov- this is a private dataset) :

1. Fix the create and update date column formats
2. Delete obvious test datasets (search test and dummy, but watch out for lead test results from Asset_data sheet (the community datasets are still in there and also in the removed datasets sheet)
3. Remove community datasets, only use official, for PUBLISH sheet
4. Can't just rely on PUBLIC datasets because there are some not public ones that are accessed by public assets

The working list is Published assets that are official and are either public or not. All derived assets have a parent in the list

The complete catalog, or just the datasets, can be assessed for the following:

- Metadata completeness
- Download statistics by publisher
- Downloads versus Number of views
- Number of links to external sites for accessing data
- Summary statistics for category, downloads, agencies

- Available elements in Socrata: License, Categories, Description, Data Provided By, Row Label, Keywords, Source Link, Contact Email(Should not be assessed- this is only to replace the default email, I think), Period of Time, Posting Frequency, Originator, Metadata Language

- Core Elements outside the automatic or required ones in Socrata: Description, Category, Provided By, License


### Dataset Level Assessment

A sample of datasets will be used to assess more granular aspects such as aboutness and clarity in description.

I used a set from the asset list downloaded 18June

Aiming for 25% or ~125 datasets as a sample.  I will use a stratified random sample design:  The list of datasets will be divided into three levels based on the number of downloads and ~40 datasets from each level (distributed across 4 two-year groups) will be randomly selected and evaluated based on the variables listed below.

### Dataset Variables

Seems like these would be good to look at:

- File format
- Publishing Agency
- Number of downloads
- Date of publication
- Date updated
- Date metadata updated
- Percent column descriptions complete
- Is this a one year dataset that is part of ongoing data collection?
- Is the dataset description rich but understandable?


### Sample of datasets for assessment

Took 115 datasets from 12 groupings: 

Number of Downloads (<100, >101 but <1500, >1500)

Year Created (2012/2013, 2014/2015, 2016/2017, 2018/2019)

Assessment Elements:
Total of 25 points possible.
- Title Understandable (1-No, 2-Yes) - contains subject, context and important qualifiers (e.g. "Snake Barriers Removed" = 1, containes subject and qualifier but missing context; "Washington Fuel Tax Active Licensees" = 2, an informative title. 
- Description Understandable (0-absent, 1-No, 2-Yes) - explains purpose and history of dataset.  If missing either of those, 1.
- Each Row is… (0=none, 1=not understandable, or partial, 2=yes, understandable)
- DataDictionary (0=none, 1=not understandable, or partial, 2=yes, understandable)
- Spatial (0=none, 1=there but unclear, 2=all good) - spatial spread of data indicated somewhere (e.g. "Washington Fuel Tax Active Licensees")
- Temporal (0=none, 1=there but unclear, 2=all good) - either values in temporal element, title or description. give 1 if value is unclear or conflicts with other metadata
- Dataset Retreivable (0=no, 1=yes)
- Resource Retreivable (0=no, 1=yes)
- Data Understandable (Are the values in the cell understandable without a dictionary?=2 (money, counts, county names, etc) Ignore missing contextual metadata (e.g. okay if you don't know what the money value is for). 1=no, 0=missing)
- Cell Accuracy  (0=more than 10 col have acc issues, 1=4-10 col, 2=1-3 col, 3=all accurate) - same values spelled the same, consistancy in format within column
- Curation Needs  (0=more than 10 col need curation, 1=4-10 col, 2=1-3 col, 3=None needed) - summed colmns removal, summed rows removal, untidy data format, type formatting, special characters.
- Currancy/usefulness (0=old/needs update, 1 = old/still useful (like data about an event), 2= uptodate/useful) 
- Belongs on Portal? 1=yes, 0=no - is it data? more usable as a static webpage?
- Curation Notes



### Questions
