# Spongebob Analysis
The following is an analysis of what influences the rating of a Spongebob episode.

The sources for this analysis are episode transcripts from [Kaggle](https://www.kaggle.com/datasets/mikhailgaerlan/spongebob-squarepants-completed-transcripts)
and episode ratings scraped from [IMDB](https://www.imdb.com/search/title/?series=tt0206512&sort=release_date,asc&start=1&ref_=adv_nxt).

The first notebook, `imdb_scrape.ipynb`, is how the episode titles and ratings were scraped from IMDB using BeautifulSoup.

The second notebook, `merger.ipynb`, involves merging the imdb scrape with the text files. This involved some title manipulation, but eventually every script was successfully merged with its respective title.

The notebook `line_share_analysis.ipynb` sought to investigate whether the share of how much a particular titular character spoke affected the overall rating of the episode. As an added bonus, it also investigated if the primary episode setting (Home/Krusty Krab/Other) had an effect on the rating.

The notebook `appearance_analysis.ipynb` sought to investigate whether a particular character's appearance had an effect on the title. It also analyzed whether the word counts of a particular character were correlated with higher ratings.

The notebook `flesch_score.ipynb` used the Flesch Reading Score to evaluate the complexity of the episode scripts, and then tested whether a difference in complexity made a significant impact on the rating. Furthermore, the investigation was applied to see if the way a particular character talks has an effect on the episode rating.
