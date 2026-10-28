# python-day-1
My first Madlibs game in python using: input(), variables(str(), int(), float(), bool(), and typecasting.


#Madlibs game code

noun = input("Write your favorite animal: ")
food = input("Enter any food you like: ")
time1 = int(input("Write a random number: "))
time2 = int(input("Write another random number: "))


print(f"Yesterday my {noun} ate the {food} i made")
print(f"He finished it within {time1} seconds")
print(f"I spent {time2} seconds doing the food")

operation = time2 - time1

if operation < 0:
    print("At least I didn´t waste time")
else:
    print(f"I wasted {operation} seconds of my life")
