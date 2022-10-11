# second-code
# You wanna check weather a number is a prime number?
def checker(number):
    prime = False
    for x in range(2, number-1):
        if number % x != 0:
            prime = True
    if prime:
        print("The number is a prime number")
    else:
        print("It's not a prime number")


n = int(input("check this number?"))
checker(number=n)
