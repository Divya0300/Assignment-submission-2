# Assignment-submission-2

Program : 

import random

maxTicketsAvalibale = int(input("Enter the maximum tickets avaiable "))

participants = [] 

for temp in range(maxTicketsAvalibale):
  st = "Ënter the participant name - "+ str(temp + 1) + " - "
  name = input(st)
  participants.append(name)

print("All our participants of lottery ticket  - ",participants)

n = random.randint(0,maxTicketsAvalibale-1)

print("Winner of the lottery ticket - ",participants[n])

Output : 

Enter the maximum tickets avaiable 2 
Ënter the participant name - 1 - Geetha
Ënter the participant name - 2 - Appu
All our participants -  ['Geetha', 'Appu']
Winner of the lottery -  Geetha 
