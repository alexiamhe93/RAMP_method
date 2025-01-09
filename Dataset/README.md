# Data for replication

This folder contains two zip files containing the data required to replicate the article's results. This data is used in the Python notebooks included within the repository.

The file "data.zip" contains four csv files:

1. **train_test.csv** The raw text data as well as manual coding for misunderstandings and the train/test split for both One-shot and RAMP groups.

2. **RAMP_Stage1.csv** Contains details of all the manual coding iterations over the inference loop for the RAMP group, including the final shared set used to calculate reported inter-rater reliability. Also includes the manual coding for the One-shot group.

3. **RAMP_Stage2.csv** Contains a record of classifier runs (predictive accuracy and adjustments to protocols) for RAMP.

4. **RAMP_Stage3.csv** Contains the final classifications of all classifiers on the RAMP test data.

5. **results_OneShot.csv** Contains the classification results of all classifiers on the One-shot test data.

# Data details

This includes the full dataset coded for the analysis. The full dataset contains 21,994 sentences coded for misunderstanding. All author names and sentences have been anonymized.
This dataset is comprised of:

1. **Reddit data**: This data was downloaded through the Reddit API for the purposes of this study.

2. **Twitter Customer Support** (Thought Vector & Axelbrooke, 2017): This data was downloaded from: https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter (Copyright: CC BY-NC-SA 4.0).

3. **Wikipedia Talk Pages** (Danescu-Niculescu-Mizil et al., 2012): This data was downloaded using Cornell University's ConvoKit Python package (see: https://convokit.cornell.edu/documentation/wiki.html) (Copyright: CC BY 4.0)

# References: 

Danescu-Niculescu-Mizil, C., Lee, L., Pang, B., & Kleinberg, J. (2012). Echoes of power: Language effects and power differences in social interaction. Proceedings of the 21st International Conference on World Wide Web, 699–708. https://doi.org/10.1145/2187836.2187931

Thought Vector, & Axelbrooke, S. (2017). Customer Support on Twitter (v10). https://kaggle.com/thoughtvector/customer-support-on-twitter
