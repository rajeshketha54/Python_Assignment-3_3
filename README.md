# Python_Assignment-3_3
def string(str):                                   #Sample input: The quick Brow Fox
    upper=0
    lower=0
    for x in range(len(str)):
        if str[x].isupper():
            upper+=1                               #Expected output:
        elif str[x].islower():                         #No. of Upper case characters : 3
            lower+=1                                   #No. of Lower case Characters : 12
    print("No. of Upper case characters :",upper)
    print("No. of Lower case Characters :",lower)  #My output:
                                                       #No. of Upper case Characters : 3
                                                       #No. of Lower case Characters : 12
string(input())
