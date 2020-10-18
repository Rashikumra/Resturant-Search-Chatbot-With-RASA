## intent:affirm
- yes
- yep
- yeah
- indeed
- that's right
- ok
- great
- right, thank you
- correct
- great choice
- sounds really good
- thanks
- send
- send me details at [harry_vbps@yahoo.co.in](email)
- thanks bye

## intent:goodbye
- bye
- goodbye
- good bye
- stop
- end
- farewell
- Bye bye
- have a good one
- thanks bye

## intent:greet
- hey
- howdy
- hey there
- hello
- hi
- good morning
- good evening
- dear sir
- hola
- hello !
- hey bot

## intent:restaurant_search
- i'm looking for a place to eat
- I want to grab lunch
- I am searching for a dinner spot
- I am looking for some restaurants in [Delhi](location).
- I am looking for some restaurants in [Bangalore](location)
- show me [chinese](cuisine) restaurants
- show me [chines](cuisine:chinese) restaurants in the [New Delhi](location:Delhi)
- show me a [mexican](cuisine) place in the [centre](location)
- i am looking for an [north indian](cuisine) spot called olaolaolaolaolaola
- search for restaurants
- anywhere in the [west](location)
- I am looking for [south indian](cuisine) food
- I am looking a restaurant in [294328](location)
- in [Gurgaon](location)
- [South Indian](cuisine)
- [North Indian](cuisine)
- [Italian](cuisine)
- [Chinese](cuisine:chinese)
- [chinese](cuisine)
- [Lithuania](location)
- Oh, sorry, in [Italy](location)
- in [delhi](location)
- I am looking for some restaurants in [Mumbai](location)
- I am looking for [mexican indian fusion](cuisine)
- can you book a table in [rome](location) in a [moderate](price:mid) price range with [british](cuisine) food for [four](people:4) people
- [central](location) [north indian](cuisine) restaurant
- please help me to find restaurants in [pune](location)
- Please find me a restaurantin [bangalore](location)
- [mumbai](location)
- show me restaurants
- please find me [chinese](cuisine) restaurant in [delhi](location)
- can you find me a [chinese](cuisine) restaurant
- [delhi](location)
- please find me a restaurant in [ahmedabad](location)
- please show me a few [italian](cuisine) restaurants in [bangalore](location)
- can you fine me a [chinese](cuisine) restaurant
- [lesser than Rs. 300](price)
- [less than Rs. 300](price:lesser than 300)
- [<300](price:lesser than 300)
- [< 300](price:lesser than 300)
- [less than 300 rupees](price:lesser than 300)
- [not more than 300](price:lesser than 300)
- [>300](price:between 300 to 700)
- [between 300 to 700](price)
- [no limit](price:more than 700)
- [asd@asd.com](email)
- send it to [aasa@asdas.com](email)
- forward it to [whatever@whs.in](email)
- range [300-700](price)
- im hungry
- looking for restaurant in [bangalore](location)
- [north indian](cuisine)
- [more than 700](price)
- im looking for restaurants
- [Chandigarh](location)
- im hungry, looking for some restaurants
- [bengaluru](location:bangalore)
- [Bangalore](location)
- Can you suggest some good restaurants in [Rishikesh](location)
- okay , [Allahabad](location)
- okay , show me in [noida](location)
- [south indian](cuisine)
- im looking our for some restaurants
- in [mubaim](location)
- in [mumbai](location)
- [lesser than 300](price)
- looking for [american](cuisine) restaurants in [delli](location:Delhi)
- looking for [chinese](cuisine) restaurants
- looking for restaurants in [ludhiana](location)
- [italian](cuisine)
- show me [north indian](cuisine) restaurants in [mysuru](location:mysore)
- [more than 700](price)
- looking for restaurants in new [delhi](location:Delhi)
- [mexican](cuisine)
- looking for restaurants in [delio](location)
- [delhi](location:Delhi)
- [american](cuisine)

## intent:deny
- no
- dont send
- no thanks
- no mail

## intent:send_mail
- [some@soasda.in](email)
- [asd@aasaf.com](email)
- [what@yahoo.com](email)
- [gsg.gg07@gmail.com](email)
- [harry_vbps@yahoo.co.in](email)
- [harish.janagam@gyansys.com](email)
- [sachinshhulmani@gmail.com](email)
- [harry_vbps@yahoo.co.in](email)
- [hasd@asaa.com](email)

## synonym: between 300 to 700
- 300 to 700
- 300 - 700
- 300-700
- 300-700 range

## synonym: more than 700
- >700
- > 700
- above 700
- greater than 700

## synonym:4
- four

## synonym:Delhi
- New Delhi
- delli
- Delli
- delhi
- new delhi

## synonym:bangalore
- bengaluru
- Bengaluru
- bglr

## synonym:baroda
- Baroda
- Vadodara
- vadodara

## synonym:between 300 to 700
- >300

## synonym:calcutta
- kolkata

## synonym:chennai
- madras
- Madras

## synonym:chinese
- chines
- Chinese
- Chines

## synonym:cochin
- kochi

## synonym:gurgaon
- gurugram

## synonym:lesser than 300
- less than Rs. 300
- <300
- < 300
- less than 300 rupees
- not more than 300

## synonym:mid
- moderate

## synonym:more than 700
- no limit

## synonym:mumbai
- bombay
- bambai

## synonym:mysore
- mysuru

## synonym:vegetarian
- veggie
- vegg

## regex:email
- [A-Z0-9a-z._%+-]+@[A-Za-z0-9.-]+\\.[A-Za-z]{2,64}

## regex:greet
- hey[^\s]*

## regex:pincode
- [0-9]{6}
