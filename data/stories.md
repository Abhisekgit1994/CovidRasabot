## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy


## covid details path
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* covid_details
  - action_covid_details
* deny
  - utter_goodbye


## covid path2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* covid_details
  - action_covid_details
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
