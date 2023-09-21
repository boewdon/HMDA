# HMDA.README
##
This is a project I am doing to practice Python and learn more about the public HMDA data. 

This project was created by myself in a Jupyter Notebook. 

I start by calling the FFIEC API for all first lien loans in every state and for the specific action types I am interested in. 
I initially ran into problems calling the API without a state parameter. To fix this, I used BeautifulSoup to scrap a table of state abbreviations and created a function to iterate through each state and from there I saved a CSV file locally for every 
states HMDA data with the parameters I was interested in. 

