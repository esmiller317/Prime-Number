# Prime-Number
#This program tells you if your input is prime. If the input is a non-integer value,
#it will say the input is invalid and request another input value.

    divideBy = 2

    for queries in range (10):
        print('Enter a query number.')
        queryString = input()
        global primeTack
        primeTrack = 0

        try:
            queryNumber = int(queryString)
            for divideBy in range(2, queryNumber):
                if (queryNumber % divideBy) == 0:
                    print(str(queryNumber) + ' is divisible by ' + str(divideBy))
                    divideBy += 1
                    primeTrack += 1
                elif (queryNumber % divideBy) == 0:
                    #print(str(queryNumber) + ' is not divisible by ' + str(divideBy))
                    divideBy += 1
            if primeTrack == 0:
                print(str(queryNumber) + ' is a prime number.')

        except ValueError:
                print('You did not enter a compatable value.'
    print('Done')
    
