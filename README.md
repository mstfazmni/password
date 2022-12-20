# password generator
import random
listt=["a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p",\
    "q","r","s","t","u","v","w","x","y","z","!","@","#","$","%","&",\
    0,1,2,3,4,5,6,7,8,9]
k = 0
listt2 = []
print("welcom to password generator!")
print("press 0 to quit.")
user = int(input("choose lenght of the password:  "))
while k < user :
    x=random.choice(listt)
    k+=1
    listt2.append(x)
i=0
while i<len(listt2) :
    print(listt2[i], end='')
    i+=1
    if user == 0:
        break
