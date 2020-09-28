## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## sad path1

* greet
    - utter_greet
* mood_unhappy
    - action_utter_cheer_up
    - utter_did_that_help
* affirm
    - utter_happy

## sad path2

* greet
    - utter_greet
* mood_unhappy
    - action_utter_cheer_up
    - utter_did_that_help
* deny
    - utter_goodbye
