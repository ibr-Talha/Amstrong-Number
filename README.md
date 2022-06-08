# Amstrong-Number
#Amstrong Number

while True : #Amstrong Number bulma
    number = input("Enter a positive integer number :")
    digit = len(number)
    summ = 0
    
    if not number.isdigit() :
        print(number, " is invalid. Please enter valid input :")
    
    elif int(number) >= 0 :
        for i in range(len(number)) :
            summ = summ + int(number[i]) ** digit
    
        if summ == int(number) :
            print(number, " is an Amstrong Number")
            break
        else :
            print(number, " is NOT an Amstrong Number")
            break
