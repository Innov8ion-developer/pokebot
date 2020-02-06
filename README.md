## Let's build a chatbot!
# Exercise 2 #

You now understand how to create a basic bot. You also know what entities, skills and intents are. Let's add them to our bot.

## Create Intent ##
Create an intent by clicking the create button on the intent tab
![Alt text](/../screenshots/part2/createIntent1.png?raw=true "")

Give the intent a meaningful name and press the CREATE INTENT button
![Alt text](/../screenshots/part2/Picture13.png?raw=true "")

Select the intent you created by clicking it in the list of intents
![Alt text](/../screenshots/part2/createExpressions1.png?raw=true "")

Train the intent by adding expressions to it. The chatbot can recognize these expressions when a user interacts with it. Add expressions by typing them in the input field and pressing enter
![Alt text](/../screenshots/part2/createExpressions2.png?raw=true "")


## Create Entity ##
Go to the entity tab and press the CREATE AN ENTITY button
![Alt text](/../screenshots/part2/createEntity1.png?raw=true "")

Call the entity pokemon and select the Restricted entity option
![Alt text](/../screenshots/part2/Picture16.png?raw=true "")

Click the entity you just created. Now add a few pokemon as synonyms to the entity by typing them in the input field and pressing enter
![Alt text](/../screenshots/part2/createEntity2.png?raw=true "")

Now that you have defined an entity, you can tag it in the expressions you have entered. Go back to the intent tab and select your intent. Now select an expression and highlight the pokemon in it. Tag it as a pokemon by clicking the #POKEMON option. Do this in all your expressions
![Alt text](/../screenshots/part2/tagExpressions1.png?raw=true "")

## Create a new skill ##

The chatbot can now understand some basic input from the user. Now we need to form an answer – SKILL time! 
To create a new skill, go to the build tab, on the canvas click the Create skill button. Give the skill a meaningful name and press the CREATE SKILL button
![Alt text](/../screenshots/part2/Picture22.png?raw=true "")

You should see this as result:
![Alt text](/../screenshots/part2/Picture23.png?raw=true "")


## let's trigger it ##
Click on the newly created skill on the canvas. Now go to the Triggers tab. In this view, you can set the trigger for this skill. In this case, we want the skill to be triggered when the get-pokemon entity is detected in a user input. Click the input field and select the @get-pokemon entry in the list. When you now press the SAVE button the correct trigger is set: If @get-pokemon is-present
![Alt text](/../screenshots/part2/skillTrigger1.png?raw=true "")

Add an action to the skill by going to the Actions tab. Press the ADD MESSAGE GROUP button. Set the same condition as you did in the previous step by pressing the ADD CONDITION text. Now select the SEND MESSAGE option
![Alt text](/../screenshots/part2/Picture25.png?raw=true "")

You can choose from a number of message types to send. A Card message type can contain an image, some text and buttons for the user to make some kind of selectionChoose to add a Card
![Alt text](/../screenshots/part2/Picture26.png?raw=true "")

Google a picture of pikachu and copy the picture url in the Your image url input field. Enter a basic description in the Title/Subtitle field. Now press the SAVE button
![Alt text](/../screenshots/part2/Picture27.png?raw=true "")


## Test your bot ##
Your chatbot can now recognize the pokemon you have defined in the pokemon entity. To see if this works, press the CHAT WITH YOUR BOT button. Go ahead and ask the chatbot about a pokemon you have specified
![Alt text](/../screenshots/part2/test0.png?raw=true "")

Click the yellow exclamation mark in the chatbot response. This will show a technical view of the response. You can now see that the chatbot recognized an intent (get-pokemon) and an entity (Magikarp)
![Alt text](/../screenshots/part2/test1.png?raw=true "")

If the user asks about a pokemon you did not specify, the chatbot will automatically switch to a fallback scenario. Try this out by clicking the CHAT WITH YOUR BOT button and asking about an unknown pokemon. Of course it is also possible to customize the fallback scenario to your own liking
![Alt text](/../screenshots/part2/test2.png?raw=true "")

Every question your chatbot gets is monitored. You can use this to analyze user interaction and to find error situations in the chatbot. Check the log by clicking on the Monitor tab
![Alt text](/../screenshots/part2/monitor1.png?raw=true "")

You can add more then one response to the same action of the skill. Try adding some more message types to see how they work
![Alt text](/../screenshots/part2/Picture28.png?raw=true "")

Next exercise:
[Continue to exercise 3](/../Exercise-3/README.md)
