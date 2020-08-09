# Zindi_Collab
Team thinkingface working on the second Zindi Mentorship challenge.

## Structure:

- data: contains the data from Zindi as it is provided
- eda: Different explorations of the data by our team members
- feature_engineering: contains code to transform the raw data in 'data/' and generate modified train and test CSVs for use in modelling
- images: Pictures to use in notebooks or the readme
- model: contains a starter model (catboost) that can be used to benchmark different features and see if they are useful. Will also host modelling notebooks from each team member that can be run to generate a submission. We can ensemble the submissions in the final step.

## Tracking

#### EDA Key Insights:

Most trips come from business accounts:
![Business Type](/images/eda2.png)

They tend to stick mainly to business hours:
![Trips by hour](/images/eda1.png)

And are mostly on weekdays:
![Trips by day](/images/eda3.png)

(Edit the readme to see how to add images etc like this)

#### Features

| Feature | Description | File showing code | Inprovement over baseline |
| :---:   | :----: | :-: | :-: |
|??? | ??? | ??? | ???|


#### Model Scores

|Model | Local Score(no CV) |Local score (5 fold CV) | Score on Zindi| Features Used |
| :---:  | :--: | | :--: | :--: | :---: |
|Model from Emmanuella | 758.2808335 (RMSE)| ??? | 1157.914| Dropped 'Time from Pickup to Arrival','Arrival at Destination - Day of Month','Arrival at Destination - Weekday (= 1)','Arrival at Destination - Time' and 'Precipitation' |
|Starter Model | ??? | ??? | ???| List of usefule features |
