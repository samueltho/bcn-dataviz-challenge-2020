# bcn-dataviz-challenge-2020
Code used to generate the findings in our submission to the World Data Viz challenge 2020 (Barcelona-Kobe)

# Goals:
- Highlight gender inequality in the namings of streets in Barcelona
- A basic forecast of where inequality might be by 2030


# edaNamesShared3.Rmd
This file will:
- Clean and join the input files
- Extract strings from the streets description
- Query wikidata for any items matching either the extracted strings or the name of the street
- Query wikidata for the gender and birthyear of the items matched
- Append the gender and the birthyear to the data set
- Generate various findings that were needed for our visualisation
- Generate a tidy CSV file (necessary for the submission)
- Download all of the availble wikidata images for matched women
