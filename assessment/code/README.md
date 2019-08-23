## README

This folder contains various Jupyter notebooks that harvest and process metadata from data.wa.gov and other Socrata portals 

**metadata-assessment-socrata

This is the main assessment tool and should be run several times a year from the same directory to track change over time.

**Change-over-time

To be used once metadata-assessment-socrata.ipynb has been run several times.  This uses a log file that metadata-assessment-socrata.ipynb updates.

**get-keywords.ipynb

This is a file modified from the [josephlei/socrata-meta github repository](https://github.com/josephlei/socrata-meta). It creates a list of keywords.

**portal-comparisons

Takes the top datasets from 16 Socrata state portals and saves them as a csv file. Also gets top datasets from about 30 city portals.

