Movie recommendation:
===

#### Objectives: 
Give 5 recommendations from 1 user entry

#### How:
- Datasource: file "movie_metadata.csv" + OMDB API
- Notebook: "Cleaning_Exploration" : relevant filters & preparing data
- Notebook "<b>Recommendation_engine</b>": content based recomendation using:
	- k nearest neighbours (w/ jaccard similarity)
	- ponderated by movie_year
	- sorted by imdb_score
	- with fuzzywuzzy filter on saga, prequel, sequel, trilogy, etc. 

#### Conclusion:
Brief summary available in PDF french report: "P3 - Rapport d'analyse FR.pdf"
