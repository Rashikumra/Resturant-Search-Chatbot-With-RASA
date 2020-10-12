## Resturant-Search-Chatbot-With-RASA

### Problem Statement

An Indian startup named 'Foodie' wants to build a conversational bot (chatbot) which can help users discover restaurants across several Indian cities. 

The main purpose of the bot is to help users discover restaurants quickly and efficiently and to provide a good restaurant discovery experience.

 
#### Inputs from the user:

1. City: Take the input from the customer as a text field. For example:

Bot: In which city are you looking for restaurants?

User: anywhere in Delhi

2. Cuisine Preference: Take the cuisine preference from the customer. The bot should list out the following six cuisine categories (Chinese, Mexican, Italian, American, South Indian & North Indian) and the customer can select any one out of that. Following is an example for the same:

Bot: What kind of cuisine would you prefer?

Chinese
Mexican
Italian
American
South Indian
North Indian
User: I’ll prefer Italian!


3. Average budget for two people: Segment the price range into three price categories: lesser than 300, 300 to 700 and more than 700. The bot should ask the user to select one of the three price categories. For example:

Bot: What price range are you looking at?

Lesser than Rs. 300
Rs. 300 to 700
More than 700
User: in range of 300 to 700

While showing the results to the user, the bot should display the top 5 restaurants in a sorted order (descending) of the average Zomato user rating (on a scale of 1-5, 5 being the highest). The format should be: {restaurant_name} in {restaurant_address} has been rated {rating}.


Finally, the bot should ask the user whether he/she wants the details of the top 10 restaurants on email. If the user replies 'yes', the bot should ask for user’s email id and then send it over email. Else, just reply with a 'goodbye' message. The mail should have the following details for each restaurant:

1. Restaurant Name
2. Restaurant locality address
3. Average budget for two people
4. Zomato user rating

#### Goals :


1. NLU training: 
2. Build actions for the bot. 
3. Creating more stories: 
4. Deploy the model on Slack
