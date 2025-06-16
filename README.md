# Repeated Adjustment of Measurement Protocols (RAMP) suppplementary materials

This repository contains data for use alongside the article titled:

*The Repeated Adjustment of Measurement Protocols (RAMP) method for developing high-validity text classifiers*

The repository contains:

1. Supplementary materials A: The RAMP method codebook used for manual coding.
2. Supplementary materials B: The non-iterative method codebook used for manual codebook.
3. A Python notebook for replicating results (created using Google Colab).
4. All data required for replication.

*NOTE* The notebook was designed on Google Colab and can be run using the free GPU (Nvidia T4). However, it does require a Google account. The code will also work offline although it would require installing all the packages *used* in the notebook (not just the ones installed by the notebook). To open in colab, simply click on the notebook file and in the left hand corner, a small button should say "open in colab". The code and models are all downloaded directly into the notebook, so there should be no need to run/download anything locally. 

# Data for replication
The data for replicating the results of the article are availble through an OSF repository [DOI 10.17605/OSF.IO/PE4JY](https://doi.org/10.17605/OSF.IO/PE4JY) under a C-By Attribution 4.0 International license. The data is split into four different files.

1.	train_test.csv The raw text data as well as manual coding for misunderstandings and the train/test split for both One-shot and RAMP groups.
2.	RAMP_Stage1.csv Contains details of all the manual coding iterations over the inference loop for the RAMP group, including the final shared set used to calculate reported inter-rater reliability. Also includes the manual coding for the One-shot group.
3.	RAMP_Stage2.csv Contains a record of classifier runs (predictive accuracy and adjustments to protocols) for RAMP.
4.	RAMP_Stage3.csv Contains the final classifications of all classifiers on the RAMP test data.
5.	results_OneShot.csv Contains the classification results of all classifiers on the One-shot test data.

## Data details
The full dataset contains 21,994 sentences coded for misunderstanding. All author names and sentences have been anonymized. This dataset is comprised of:
1.	Reddit data: This data was downloaded through the Reddit API for the purposes of this study.
2.	Twitter Customer Support (Thought Vector & Axelbrooke, 2017): This data was downloaded from: [https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter](https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter) (Copyright: CC BY-NC-SA 4.0).
3.	Wikipedia Talk Pages (Danescu-Niculescu-Mizil et al., 2012): This data was downloaded using Cornell University's ConvoKit Python package (see: [https://convokit.cornell.edu/documentation/wiki.html](https://convokit.cornell.edu/documentation/wiki.html) (Copyright: CC BY 4.0)

References:
Danescu-Niculescu-Mizil, C., Lee, L., Pang, B., & Kleinberg, J. (2012). Echoes of power: Language effects and power differences in social interaction. Proceedings of the 21st International Conference on World Wide Web, 699–708. https://doi.org/10.1145/2187836.2187931
Thought Vector, & Axelbrooke, S. (2017). Customer Support on Twitter (v10).
