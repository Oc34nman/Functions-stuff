# Functions-stuff


def findsmallest(x, y, z):
    if x > y and x > z:
        print(x, "is the biggest of the three (or x)")
        return x
    elif y > x and y > z :
        print(y, "is the biggest of the three (or x)")
        return y
    else:
        print(z, "is the biggest of the three (or z)")
        return z
    
result = findsmallest(5, 4, 2)

#----------------------------------

def customsheepcall(vowel, count):
     amount = []
     for i in range(count):
         amount.append(vowel)
     print("b", *amount)
customsheepcall("e", 3)

#first line
#print B
#for loop that runs count times
#print vowel

#call it

#----------------------------------
def Sumevennumbers(maxnum):
    NumList = []
    for j in range(1, maxnum+1):
        if j % 2 == 0:
            NumList.append(j)
    print(NumList)
        
            
Sumevennumbers(10)
   
