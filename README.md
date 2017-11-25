# rockpaperscissor
Make a two-player Rock-Paper-Scissors game. (Hint: Ask for player plays (using input), compare them, print out a message of congratulations to the winner, and ask if the players want to start a new game)


#Rock beats scissors
#Scissors beats paper
#Paper beats rock
import random as f


x="rock"#1
y="paper"#2
z="scissor"#3

while True:
	print("lets play rock paper scissors")
	u=input("enter your choice ")
	t=f.randint(0,4)
	if t==1:
		if u==y:
			print("I chose rock , You win")
			continue
		else:
		    print("I chose rock, you lost")
		    continue	    		
	if t==2:
		if u==z:
			print("I chose paper you won")
			continue
		else:
			print("I chose paper you lose")
			continue
	if t==3:
		if u==x:
			print("I chose scissors ,you won")
			continue
		else:
			print("I chose scissors ,you lose")
			continue	    
			    
.
