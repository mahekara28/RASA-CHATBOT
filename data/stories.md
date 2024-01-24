## sick path 1
*  greet
 - utter_greet
* i_am_sick 
 - utter_i_am_sick
* fever
 - utter_fever
 - utter_fever_medicines


## story: sick path 2
*  greet
 -  utter_greet
*   i_am_sick
-  utter_sick
*  cold and cough
 -  utter_cc
 -  utter_cc_medicines

## sick path 3
*  greet
 -  utter_greet
*  i_am_sick
 - utter_sick
*  headache
 - utter_headache
 - utter_headache_medicines

## sick path 4
*  greet
 - utter_greet
*  i_am_sick
 - utter_sick
*  sunstroke
 - utter_sunstroke
 - utter_sunstroke_medicines

## sick path 5

*  greet
 -  utter_greet
*  i_am_sick
 - utter_sick
*  flu
 - utter_flu
 - utter_flu_medicines

## sick path 6
 
*  greet
 - utter_greet
*  i_am_sick
 - utter_sick
*  stoamchache
 - utter_stomachache
 - utter_stomachache_medicines

## sick path 7

*  greet
  - utter_greet
*  i_am_sick
  - utter_sick
*  weakness
  - utter_weakness
  - utter_weakness_medicines


## sick path 9

*  greet
  - utter_greet
*  i_am_sick
  - utter_sick
*  throat_pain
  - utter_throat_pain
  - utter_throat_pain_medicines

## sick path 10
*  greet
  - utter_greet
*  i_am_sick
  - utter_sick
*  food_poisioning
  - utter_food_poisioning
  - utter_food_poisioning_medicines

## sick path 11

*  greet
  - utter_greet
*  i_am_sick
  - utter_sick
* acidity
  - utter_acidity
  - utter_acidity_medicines


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

## livescore details
* live_score
  - utter_live_score	 

## custom hellowrold actions
* helloworld_action
  - action_hello_world_program
