# Project-File15
#Sample5
S1 = float(input("Enter first side"))
S2 = float(input("Enter second side"))
S3 = float(input("Enter third side"))
if S1==S2==S3:
    print("Equilateral triangle")
elif S1==S2 or S2==S3 or S1==S3:
    print("Isosceles triangle")
else:
    print("Scalene triangle")
  #Sample6
for num in range (100,200,10):
    Squared=num*num
print(num,"Squared is",Squared)
#Sample7
lst=[25,43,3.2,"dog",("a","b")]
for word in lst:
    print(word,type(word))
#Sample8
str="I am very happy"
wordlist =str.split()
print("words in list format",wordlist)
for word in wordlist:
    print(word)
 #Sample9   
Dict = {'S1':"Biology-Math", 'S2':"Math-Computer",'S3': "Biology-Physics", 'S4': "Math-AI"}
for key in Dict:
    print(Dict[key])
