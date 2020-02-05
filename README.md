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

Now that you have defined an entity, you can tag it in the expressions you have entered. Go back to the intent tab and select your intent. Now select an expression and highlight the pokemon in it. Tag it as a pokemon by clicking the #POKEMON option. Do this in all your expressions.
![Alt text](/../screenshots/part2/tagExpressions1.png?raw=true "")

Now ask a question about a Pokemon you did not train. This will trigger a default fallback scenario
![Alt text](/../screenshots/part2/Picture20.png?raw=true "")

Check the bot log on the "Monitor" tab
![Alt text](/../screenshots/part2/Picture21.png?raw=true "")

## Create a new skill ##

Now we need to form an answer – SKILL time! 
Let's create a new Business Skill. Go to the build tab, on the canvas click the 'create skill' button
![Alt text](/../screenshots/part2/Picture22.png?raw=true "")

You should see this as result:
![Alt text](/../screenshots/part2/Picture23.png?raw=true "")

## let's trigger it ##


Double click on the newly created skill in the diagram.
In this new view, set the trigger – 
The trigger is when the user fires the “Get-Pokemon” intent.
![Alt text](/../screenshots/part2/Picture24.png?raw=true "")

Add an action
![Alt text](/../screenshots/part2/Picture25.png?raw=true "")



Add a Card
![Alt text](/../screenshots/part2/Picture26.png?raw=true "")



Find a cool picture of Pikachu and copy Image Address
![Alt text](/../screenshots/part2/Picture27.png?raw=true "")


## Test your bot ##
Add some info and test the bot!
![Alt text](/../screenshots/part2/Picture28.png?raw=true "")


Next exercise:
[Continue to exercise 3](/../Exercise-3/README.md)
