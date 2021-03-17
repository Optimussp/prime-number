# prime-number

a = int(input("Give me the number : "))

for i in range(2, a):
    print(i)
    if (a % i == 0) :
        print(a , "is not prime")
           
    else:
        print(a, 'is prime')
        break
  

    
