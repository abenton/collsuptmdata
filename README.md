Authors:
adrian dot benton at gmail dot com
mpaul39 at gmail dot com
hancock dot braden gmail dot com
mark at dredze dot com

This distribution contains tweet IDs for each dataset reported in:

Adrian Benton, Michael J. Paul, Braden Hancock, Mark Dredze.
Collective Supervision of Topic Models for Predicting Surveys with Social Media.
Thirtieth AAAI Conference on Artificial Intelligence, 2016.

as well as predictions of support for universal background checks as displayed
in Figure 4.  Mapping from file to dataset described in the paper:

- *input.guncontrol.allfeatures.onlyids.txt.gz*: Guns
- *input.tobacco.allfeatures.onlyids.txt.gz*: Smoking
- *input.vaccine.allfeatures.onlyids.txt.gz*: Vaccines

Each file is tab-separated with the following columns:

- tweet ID
- hashtag-based PRO/ANTI-issue score (not used in the paper)
- state-level survey score
- county-level census score

All of these scores are z-score normalized.  Refer to the paper for semantics
of each form of supervision.

Predictions of proportion supporting universal background checks per state are in
*ubc_regression_predictions.txt*.  These are the values used to generate Figure 4.

If you would like access to the text associated with each of these tweet IDs,
please email adrian dot benton at gmail dot com
Due to the Twitter terms of service, we can only make the text of 50K tweets
available per day (and cannot have you clone the entire repository).

If you use these data, please cite:

Adrian Benton, Michael J. Paul, Braden Hancock, Mark Dredze.
Collective Supervision of Topic Models for Predicting Surveys with Social Media.
Thirtieth AAAI Conference on Artificial Intelligence, 2016.

