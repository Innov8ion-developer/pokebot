### Let's build a chatbot! ##

# Exercise 3 #

# Add a condition #
Right now, the chatbot can only send Pikachu as a response to the pokemon intent. To distinguish between different pokemon, additional conditions can be set for additional pokemon. Change the condition to check entity #pokemon.value. Enter pikachu as value. Now you only get Pikachu when he is asked for
![Alt text](/../screenshots/part3/actionTrigger1.png?raw=true "")

Check it: Try asking for a different pokemon. You will no longer get a response
![Alt text](/../screenshots/part3/actionTrigger2.png?raw=true "")

Let’s add Pidgey by adding a second MESSAGE GROUP and setting the condition specifically for pidgey and try again. Is it working?

You might be wondering why it's still not working for Pidgey.. Probably we need to identify him as a pokemon (i.e.: We need to add Pidgey to the intent synonyms)
![Alt text](/../screenshots/pidget.png?raw=true "")

Check it again: ask for pidgey. Now he should be recognized also!

# Add a requirement #
Next, we will use the memory functionality to confirm what a user says. 
Add a Requirement by drilling down into the skill you have created. Then go to the Build tab, then select the Requirements tab.
![Alt text](/../screenshots/part3/Picture32.png?raw=true "")


Now we can use it in our Conversation:
Add in your message:
> Ahh you want to know about {{memory.pokemon.value}}

![Alt text](/../screenshots/part3/Picture33.png?raw=true "")

# Test it #
![Alt text](/../screenshots/part3/Picture34.png?raw=true "")


You made it! :+1:
