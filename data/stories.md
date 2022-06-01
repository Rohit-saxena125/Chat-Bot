
## PM-KUSUM-Scheme
* greet
  - utter_greet
* PM-KUSUM-Scheme
  - utter_PM-KUSUM-Scheme

## eligibility
* greet
  - utter_greet
* eligibility
  - utter_eligibility

## information
* greet
  - utter_greet
* information
  - utter_information  
## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
