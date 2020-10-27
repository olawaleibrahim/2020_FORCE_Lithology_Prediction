# 2020_FORCE_Lithology_Prediction

## 2020 FORCE Machine Learning Contest - Final Model Submission ##


####  Machine Predicted Lithology ####
Overview at [contest website](https://xeek.ai/challenges/force-well-logs/overview)

This is a repo for the recently concluded FORCE machine learning lithology prediction competition which spanned from August to October.
This is my final submission file which have a score of -0.5118 and ranking 24th on the open test leaderboard.
Extensive validations were done using different sets wells which were randomly selected. 

Several ensemble techniques were tried but the final model which was the best on local validationn and open test LB -- was a single 10 stratified kfold xgboost model. 

FORCE_Submission_File.ipynb is the final notebook used in making predictions. Other notebooks were used earlier during the competitions for validations and trying out different techniques.

#### Licensing #### 
Copyright 2020 Olawale Ibrahim

This work is open source:

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Text is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"> CC BY 4.0 Creative Commons License</a>.

Code is Licensed under the [Apache License, Version 2.0]( http://www.apache.org/licenses/LICENSE-2.0)

As per [contest rules](https://xeek.ai/challenges/force-well-logs/rules): 
The well log labels used in this repo are licensed CC-BY-4.0.  The well log data used in this repo is licensed as [Norwegian License for Open Government Data (NLOD) 2.0](https://data.norge.no/nlod/en/2.0/).  Any publication involving the well log data must cite “Lithofacies data was provided by the FORCE Machine Learning competition with well logs and seismic 2020”.  For citation please use: Bormann P., Aursand P., Dilib F., Dischington P., Manral S. 2020. [2020 FORCE Machine Learning Contest](https://github.com/bolgebrygg/Force-2020-Machine-Learning-competition)

