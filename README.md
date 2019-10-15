### iTouch - chatbot exercises ##

# Exercise 3 #

Memory – **I only get Pikachu?** 


# Add a condition #
Add a condition for “Pokemon” – Now you only get Pikachu when he is asked for 
![Alt text](/../screenshots/Part3/Picture29.png?raw=true "")

Check it: ask for pidgey, you get nothing
![Alt text](/../screenshots/Part3/Picture30.png?raw=true "")


Let’s add Pidgey, just to be sure
![Alt text](/../screenshots/Part3/Picture31.png?raw=true "")

# Add a requirement #
Now we use the memory, to confirm what a user says. 
Add a Requirement
![Alt text](/../screenshots/Part3/Picture32.png?raw=true "")

Now we can use it in our Conversation:
Add in your message:
> Ahh you want to know about {{memory.pokemon.value}}

![Alt text](/../screenshots/Part3/Picture33.png?raw=true "")

Test it

![Alt text](/../screenshots/Part3/Picture34.png?raw=true "")
