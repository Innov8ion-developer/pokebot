### iTouch - chatbot exercises ##

# Exercise 3 #

# Add a condition #
Add a condition for “Pokemon” – Now you only get Pikachu when he is asked for 
![Alt text](/../screenshots/part3/Picture29.png?raw=true "")



Check it: ask for Pidgey, you get nothing
![Alt text](/../screenshots/part3/Picture30.png?raw=true "")


Let’s add Pidgey and try again. Still not working?
![Alt text](/../screenshots/part3/Picture31.png?raw=true "")

You might be wondering why it's still not working for Pidgey...
Probably we need to identify as a pokemon (i.e.: We need to add Pidgey to the intent).

![Alt text](/../screenshots/pidget.png?raw=true "")

Check it again: ask for pidgey.
# Add a requirement #
Now we use the memory, to confirm what a user says. 
Add a Requirement
![Alt text](/../screenshots/part3/Picture32.png?raw=true "")



Now we can use it in our Conversation:
Add in your message:
> Ahh you want to know about {{memory.pokemon.value}}

![Alt text](/../screenshots/part3/Picture33.png?raw=true "")

# Test it #

![Alt text](/../screenshots/part3/Picture34.png?raw=true "")


You made it! :+1:
