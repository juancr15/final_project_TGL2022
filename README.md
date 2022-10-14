# Top Gun Lab Python 2022 - Final Project
The goal of data analysis is to discover useful information, answer key questions that aid decision-making, and draw conclusions. With this project, it is possible to determine the trends of the subtopics covered in documents published over time, as well as which journals are the most influential in the field of Artificial Intelligence.
- [Jupyter Notebook](https://nbviewer.org/github/juancr15/final_project_TGL2022/blob/main/src/analisis_Journals_IA.ipynb)
## Jump to
- [Set Up](#set-up)
- [Viz Context](#viz-context)
- [Final Thoughts](#final-thoughts)
- [Challenges](#challenges)


## Set Up

### Requirements
- Pandas
- Seaborn
- Matplotlib
- Opendatasets
- Ipykernel
- Ipywidgets
- Pandas-profiling
- Pandasql

```
pip install -r requirements.txt
```

## The Dataset
## Viz Context
The problem we posed ourselves in order to create these visualizations was to discover which journals occupied the top 5 positions in the SCImagor Journal Rank each year and to derive additional data from this, both from the specific journal and in general.

The dashboard is comprised of six visualizations, divided into two interactions. The first is orchestrated through the 'Year' filter, which in a bar graph titled 'Top Journals' displays the top five journals with the greatest scientific influence as defined by the Scimagor Journal Rank, which catalogs them by the average number of weighted citations received during the year.

The second interaction is orchestrated by the specific selection of one of the journals that are located in the 'Top Journals', allowing more information from this publication to be used in the lower table. 

It also orchestrates the results of the line graphs that show the 'Total Documents' of that journal in relation to the range of years in which it was published (taking into account the limitation of the dataset that only covers records from 2000 to 2021) and the 'Scimagor Journal Rank', which shows the rank variation in which this journal has been located over time.  In addition to this, we can see the geographical position of the journal and the keywords of the investigations on the wordcloud.

As an added value, the map visualization shows how the majority of publications in the area of ​​artificial intelligence research we can see by geographical location and the subdivision into quartiles that also show the prestige of their research.

Furthermore, the Wordcloud is filtered by the 'categories' column, which reveals the keywords of the research, allowing us to identify a tendency toward certain approaches on which technology has advanced both theoretically and practically.

As an added value, the visualization of the map shows how the majority of publications in the field of Artificial Intelligence are found by geographical location; and the subdivision into quartiles shows the prestige of their research.

## Final Thoughts

## Challenges
- Understand and materialize the requirements from the client (us) for this analysis
- Understand the dataset
- Building a specific strategy for the treatment of the dataset
- Being creative when building the visualizations on Power BI
