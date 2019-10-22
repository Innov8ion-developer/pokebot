## Let's build a chatbot! - iTouch event ##

# Exercise 2 #

If you now understood how create a basic bot, and what entities, skills and intents are, let's add them to our bot.



Create an intent

![Alt text](/../screenshots/part2/Picture13.png?raw=true "")

Train the intent – normally you would check with your users/call logs

![Alt text](/../screenshots/part2/Picture14.png?raw=true "")


## Create a Entity ##

![Alt text](/../screenshots/part2/Picture15b.png?raw=true "")

Call it Pokemon and use “Restricted”
![Alt text](/../screenshots/part2/Picture16.png?raw=true "")

Add a few pokemon as synonyms to the entity
![Alt text](/../screenshots/part2/Picture17.png?raw=true "")

Add some expressions like "Who is Pikachu?", like the screenshot below.

Now you have Entities, you can tag them in your Intent, see also screenshot below
![Alt text](/../screenshots/part2/Picture19.png?raw=true "")

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
