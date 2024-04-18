## Document Explorer - Resume Filtering and Clustering Application
With new jobs being created every day and hiring demands steadily rising, today’s recruiters need tools that help them successfully compete for talent and need tools that are both effective and affordable.

Resume explorer is an application from which a recruiter can explore by filtering thousands and thousands of resumes with ease and search for required skills from all those applications. The resumes are filtered and clustered based on skills by using Apache solr an open-source enterprise-search platform and Carrot² an open source search results clustering engine.

## Parsing the Documents
* Parsed resumes in various formats using tika library in python
* Stored them in postgresql using docker

## Indexing using solr
* Indexed the parsed resume data using apache solr
* Searching over the indexed data

## Clustering using Carrot2
* Clustered the search result using Carrot2
* Learned about visualizing the clusters using Carrot2 FoamTree

## Visualizing Clusters
* Visualise clusters using FoamTree

## Architecture Diagram
![image](https://github.com/deepaknn/Document-Explorer/assets/43431474/50e86461-acc6-468a-9129-e9ccffef55da)
