## Project - "Evaluation of the results and correctness of the A/B test"
___
### Project description
The company conducted the A/B test "recommender_system_test". Based on the dataset with user actions, terms of reference and auxiliary datasets, it is necessary to evaluate the results of the A/B test and evaluate the correctness of its implementation.

___
### Data description
ab_project_marketing_events.csv - calendar of marketing events for 2020;
name — name of the marketing event;
regions — regions in which the advertising campaign will be carried out;
start_dt — campaign start date;
finish_dt — end date of the campaign.

final_ab_new_users.csv - all users who registered in the online store from December 7 to December 21, 2020;
user_id - user ID;
first_date — registration date;
region — user's region;
device - the device from which the registration took place.

final_ab_events.csv - all new user events from December 7, 2020 to January 4, 2021;
user_id - user ID;
event_dt - date and time of the event;
event_name - event type;
details — additional data about the event. For example, for purchases, purchase, this field stores the cost of the purchase in dollars.

final_ab_participants.csv - table of test participants.
user_id - user ID;
ab_test - test name;
group — user group.
___
### Used libraries/methods
Pandas, Matplotlib, SciPy, A/B testing, testing of statistical hypotheses
