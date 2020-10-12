## Complete path 1
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart



## Complete path 2
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart


## Complete path 3
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mbusmkwoid"}
    - slot{"location": "mbusmkwoid"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart



## Complete path 4
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "mbumkdjjo"}
    - slot{"location": "mbumkdjjo"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart


## Complete path 5
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "rishikesh"}
    - slot{"location": "rishikesh"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_service_not_available
* restaurant_search{"location": "hyderabad"}
    - slot{"location": "hyderabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart



## Complete path 6
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "haridwar"}
    - slot{"location": "haridwar"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_service_not_available
* restaurant_search{"location": "allahabad"}
    - slot{"location": "allahabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart


## Complete path 7
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "surat"}
    - slot{"location": "surat"}
    - action_check_location
    - slot{"location": "surat"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart



## Complete path 8
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "ooty"}
    - slot{"location": "ooty"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_service_not_available
* restaurant_search{"location": "bangalore"}
    - slot{"location": "bangalore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
	- utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart




## Complete path 9
* greet
    - utter_greet
* restaurant_search{"location": "delhi"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart


## Complete path 10
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart



## Complete path 11
* greet
    - utter_greet
* restaurant_search{"location": "manali"}
    - slot{"location": "manali"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_service_not_available
* restaurant_search{"location": "srinagar"}
    - slot{"location": "srinagar"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
	- utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart



## Complete path 12
* greet
    - utter_greet
* restaurant_search{"location": "pune"}
    - slot{"location": "pune"}
    - action_check_location
    - slot{"location": "pune"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart


## Complete path 13
* greet
    - utter_greet
* restaurant_search{"location": "mbunvkdi"}
    - slot{"location": "mbunvkdi"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "mysore"}
    - slot{"location": "mysore"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart



## Complete path 14
* greet
    - utter_greet
* restaurant_search{"location": "graaar"}
    - slot{"location": "graaar"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "agra"}
    - slot{"location": "agra"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart


## Complete path 15
* greet
    - utter_greet
* restaurant_search{"location": "jaipur"}
    - slot{"location": "jaipur"}
    - action_check_location
    - slot{"location": "jaipur"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart


## Complete path 16
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart


## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "goa"}
    - slot{"cuisine": "italian"}
    - slot{"location": "goa"}
    - action_check_location
    - slot{"location": "goa"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart


## interactive_story_2
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "ptnsneha"}
    - slot{"cuisine": "italian"}
    - slot{"location": "ptnsneha"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "patna"}
    - slot{"location": "patna"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart


## interactive_story_3
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "haridwar"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "haridwar"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_service_not_available
* restaurant_search{"location": "allahabad"}
    - slot{"location": "allahabad"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart


## interactive_story_4
* greet
    - utter_greet
* restaurant_search{"location": "kolkata"}
    - slot{"location": "kolkata"}
    - action_check_location
    - slot{"location": "kolkata"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart



## interactive_story_5
* greet
    - utter_greet
* restaurant_search{"cuisine": "south indian", "location": "ooty"}
    - slot{"cuisine": "south indian"}
    - slot{"location": "ooty"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_service_not_available
* restaurant_search{"location": "bengaluru"}
    - slot{"location": "bengaluru"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart


## interactive_story_6
* greet
    - utter_greet
* restaurant_search{"cuisine": "american", "location": "rohtak"}
    - slot{"cuisine": "american"}
    - slot{"location": "rohtak"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "chandigarh"}
    - slot{"location": "chandigarh"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
	- utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart


## interactive_story_7
* greet
    - utter_greet
* restaurant_search{"location": "hdsgfjsdvf"}
    - slot{"location": "hdsgfjsdvf"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "jammu"}
    - slot{"location": "jammu"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "lesser than 300"}
    - slot{"price": "lesser than 300"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart


## interactive_story_8
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "gwalior"}
    - slot{"location": "gwalior"}
    - action_check_location
    - slot{"location": "gwalior"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
	- utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart


## interactive_story_9
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "filmkidiejf"}
    - slot{"location": "filmkidiejf"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "faridabad"}
    - slot{"location": "faridabad"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
	- utter_ask_mail
* deny
    - utter_bye
    - action_restart



## interactive_story_10
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese", "location": "delhi"}
    - slot{"cuisine": "chinese"}
    - slot{"location": "delhi"}
    - action_check_location
    - slot{"location": "delhi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
	- utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart

## interactive_story_11
* greet
    - utter_greet
* restaurant_search{"cuisine": "italian", "location": "shdgsdd"}
    - slot{"cuisine": "italian"}
    - slot{"location": "shdgsdd"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "notfound"}
    - utter_location_not_found
* restaurant_search{"location": "madurai"}
    - slot{"location": "madurai"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart


## interactive_story_12
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Chandigarh"}
    - slot{"location": "Chandigarh"}
    - action_check_location
    - slot{"location": "Chandigarh"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "gsg.gg07@gmail.com"}
    - slot{"email": "gsg.gg07@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
	- action_restart



## interactive_story_2
* greet
    - utter_greet
* restaurant_search
    - utter_ask_location
* restaurant_search{"location": "Bangalore"}
    - slot{"location": "Bangalore"}
    - action_check_location
    - slot{"location": "Bangalore"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "harry_vbps@yahoo.co.in"}
    - slot{"email": "harry_vbps@yahoo.co.in"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"location": "Rishikesh"}
    - slot{"location": "Rishikesh"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_service_not_available
* restaurant_search{"location": "noida"}
    - slot{"location": "noida"}
    - action_check_location
    - slot{"location": "noida"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "south indian"}
    - slot{"cuisine": "south indian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "harish.janagam@gyansys.com"}
    - slot{"email": "harish.janagam@gyansys.com"}
    - action_email_restaurant_details
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "american", "location": "Delhi"}
    - slot{"cuisine": "american"}
    - slot{"location": "Delhi"}
    - action_check_location
    - slot{"location": "Delhi"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "sachinshhulmani@gmail.com"}
    - slot{"email": "sachinshhulmani@gmail.com"}
    - action_email_restaurant_details
* goodbye
    - utter_bye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "chinese"}
    - slot{"cuisine": "chinese"}
    - utter_ask_location
* restaurant_search{"location": "mumbai"}
    - slot{"location": "mumbai"}
    - action_check_location
    - slot{"location": "mumbai"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "between 300 to 700"}
    - slot{"price": "between 300 to 700"}
    - action_restaurant
    - utter_ask_mail
* deny
    - utter_bye
* goodbye
    - action_restart

## interactive_story_2
* greet
    - utter_greet
* restaurant_search{"location": "ludhiana"}
    - slot{"location": "ludhiana"}
    - action_check_location
    - slot{"location": "ludhiana"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "italian"}
    - slot{"cuisine": "italian"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_mail
* deny
    - utter_bye
* goodbye
    - action_restart

## interactive_story_1
* greet
    - utter_greet
* restaurant_search{"cuisine": "north indian", "location": "mysore"}
    - slot{"cuisine": "north indian"}
    - slot{"location": "mysore"}
    - action_check_location
    - slot{"location": "mysore"}
    - slot{"location_found": "found"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "harry_vbps@yahoo.co.in"}
    - slot{"email": "harry_vbps@yahoo.co.in"}
    - action_email_restaurant_details
* affirm
    - utter_bye
    - action_restart

## interactive_story_2
* restaurant_search{"location": "Delhi"}
    - slot{"location": "Delhi"}
    - action_check_location
    - slot{"location": "Delhi"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "mexican"}
    - slot{"cuisine": "mexican"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_mail
* deny
    - utter_bye
    - action_restart

## interactive_story_3
* restaurant_search{"location": "delio"}
    - slot{"location": "delio"}
    - action_check_location
    - slot{"location": null}
    - slot{"location_found": "tier3"}
    - utter_service_not_available
* restaurant_search{"location": "Delhi"}
    - slot{"location": "Delhi"}
    - action_check_location
    - slot{"location": "Delhi"}
    - slot{"location_found": "found"}
    - utter_ask_cuisine
* restaurant_search{"cuisine": "american"}
    - slot{"cuisine": "american"}
    - utter_ask_price
* restaurant_search{"price": "more than 700"}
    - slot{"price": "more than 700"}
    - action_restaurant
    - utter_ask_mail
* send_mail{"email": "hasd@asaa.com"}
    - slot{"email": "hasd@asaa.com"}
    - action_email_restaurant_details
* affirm
    - utter_bye
    - action_restart
