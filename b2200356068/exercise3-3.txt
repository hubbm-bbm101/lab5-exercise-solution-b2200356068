import random

low = int(input("please enter the minimum of the random set"))
high = int(input("please enter the maximum of the random set"))
number = random.randint(low,high)
guess_number = 0
while guess_number != number:
        guess_number = int(input("please enter your guess number as an integer"))
        if  guess_number == number:
          print("Congrats!You guessed right!")
          break
        elif guess_number > number:
          print("please decrease your guess number")

        elif guess_number < number:
              print("please increase your guess number")

