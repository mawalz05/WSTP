# WSTP
Contains the code for producing sustainability scores using the FAMD algorithm. This algorithm reduces the dimensions for environmental, social, and economic sustainability down to a single score, then aggregates the score using pre-defined weights to produce an overall score.

Also contains the code for the NLP model. The NLP model uses pre-trained transfer learing with transfomrers (BERT) to determine whether a sentence is sustainable or not. This trained model is then used on new data scraped from company websites to determine the proportion of sustainable sentences out of all sentences in the About Us page.
