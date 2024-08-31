    # |. TEXT CELLS
    
        # Parth Mangukiya
        # [24-2-24]

print('Parth Mangukiya')

name=input("What is your name?: ")
print("Hello", name)


First = int(input("Enter the first number: "))
Second = int(input("Enter the first number: "))
result = First + Second
print("sum:", result)


a=100
b=29

f=(a+b)
z=(f*3)
i=(a+b)*3
Exponent_result=z**2
Exponent_result1=i**2
print('The Result of the calculation was:',Exponent_result)
print('The result of the calculation was:',Exponent_result1)


name=input('Enter your name: ')
your_brith_year=int(input('Enter your birth year:'))
age=int(input("Enter your age:"))
last_two_digites=str(your_brith_year)[-2:]
first_three_letter=str(name)[:3]
power_of_age=str(age**2)
password=last_two_digites + first_three_letter + power_of_age
print('Password:', password)


a=int(input('First number is : '))
b=int(input('Second number is : '))
      
if a%2==0 and b%2==0:
    print('Both Number is Even:')
elif a%2==0 or b%2==0:
    print('One is the number is even:')
else:
    print('Both Number are odd:')
    


x=int(input('Enter the number:'))

sum_of_all_numbers = 0


for i in range(x):
    sum_of_all_numbers += i
    

print('The sum is: ',sum_of_all_numbers)



import random


def play_guessing_game():
    number_to_guess = random.randint(0, 10)
    print("Dealer has selected a number. Try to guess!")

    guess = -1
    tries = 0

    while guess != number_to_guess:
        guess = int(input("Player: "))
        tries += 1

        if guess < number_to_guess:
            print("Try a greater number.")
        elif guess > number_to_guess:
            print("Try a smaller number.")

    print("That's right! Number of tries:", tries)
    return tries

print("Player 1's turn:")
tries_player1 = play_guessing_game()

print("\nPlayer 2's turn:")
tries_player2 = play_guessing_game()

if tries_player1 < tries_player2:
    print("Winner is Player 1")
elif tries_player1 > tries_player2:
    print("Winner is Player 2")
else:
    print("It's a tie!")


        
