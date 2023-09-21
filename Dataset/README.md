# Data for replication

This folder contains two zip files containing the data required to replicate the analysis. This data is used in the Python notebooks included within the repository.
There are two zip files containing the relevant data required.

## Zipfile 1 ("data_to_use.zip")

This zip file contains two spreadsheets containing the empirical data used in the analysis.

### Spreadsheet 1 ("train_test.csv") 

This includes the full dataset coded for the analysis. This spreadsheet is comprised of:

1. Data downloaded through the Reddit API

This data was downloaded for the purposes of this study.

2. Twitter Customer Support (Thought Vector & Axelbrooke, 2017)

This data was downloaded from: https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter (Copyright: CC BY-NC-SA 4.0).

3. Wikipedia Talk Pages (Danescu-Niculescu-Mizil et al., 2012)

This data was downloaded using Cornell University's ConvoKit Python package (see: https://convokit.cornell.edu/documentation/wiki.html) (Copyright: CC BY 4.0)

The full dataset contains 21,994 sentences coded for misunderstanding. All author names and sentences have been anonymized.

### Spreadsheet 2 ("IRR_data.csv") 

This comprises of a subset of the dataset used for calculating inter-rater reliability statistics. The two csv files can be recombined using the 'Turn_id' column.

# Zipfile 2 ("Dictionary.zip)

This zip file also contains two spreadsheets used in a phrase-based dictionary classifier. 

### Spreadsheet 1 ("Misunderstanding_dictionary.csv")

This spreadsheet contains a list of phrases indicating misunderstandings. 

### Spreadsheet 2 ("Augmenting_dictionary.csv")

This spreadsheet comprises of synonyms or alternative words to augment the list of phrases in the main dictionary.

# References: 

Danescu-Niculescu-Mizil, C., Lee, L., Pang, B., & Kleinberg, J. (2012). Echoes of power: Language effects and power differences in social interaction. Proceedings of the 21st International Conference on World Wide Web, 699–708. https://doi.org/10.1145/2187836.2187931

Thought Vector, & Axelbrooke, S. (2017). Customer Support on Twitter (v10). https://kaggle.com/thoughtvector/customer-support-on-twitter
