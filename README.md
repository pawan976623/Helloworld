# Helloworld
python
a=int(input("Enter no1 "))
b=int(input("Enter no2 "))
temp=a
a=b
print(temp)
print(a)
a=a-b
b=a+b
b=b-a
print(a)
print(b)
def tree(a,b,c):
   if(a>b):
     if(a>c):
       print(a," is greater")
     else:
         print(c," is greater")
  else:
      if(b>c):
        print(b," is greater")
      else:
          print(c," is greater")
