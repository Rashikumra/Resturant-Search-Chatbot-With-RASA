## interactive_story_2
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_check_location
    - slot{"location": "Bangalore"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "harry_vbps@yahoo.co.in"}
    - slot{"email": "harry_vbps@yahoo.co.in"}
    - slot{"email": "harry_vbps@yahoo.co.in"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart   <!-- predicted: action_listen -->


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Rishikesh"}
    - slot{"location": "Rishikesh"}
    - slot{"location": "Rishikesh"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_service_not_available
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location   <!-- predicted: utter_ask_cuisine -->
    - slot{"location": "noida"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine   <!-- predicted: utter_ask_price -->
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "harish.janagam@gyansys.com"}
    - slot{"email": "harish.janagam@gyansys.com"}
    - slot{"email": "harish.janagam@gyansys.com"}
    - action_email_restaurant_details
    - action_restart   <!-- predicted: action_listen -->
    - action_listen   <!-- predicted: action_email_restaurant_details -->


## interactive_story_2
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mubaim"}
    - slot{"location": "mubaim"}
    - slot{"location": "mubaim"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location   <!-- predicted: utter_ask_cuisine -->
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine   <!-- predicted: utter_ask_price -->
* restaurant_search{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - slot{"cuisine": "north indian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - action_listen   <!-- predicted: utter_ask_mail -->


