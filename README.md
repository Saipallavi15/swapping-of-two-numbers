# swapping-of-two-numbers
a=int(input("enter a "))
b=int(input("enter b "))
print("a=", a)
print("b=", b)
def swap(a,b):
a=a+b
b=a-b
a=a-b
print("after")
print("a=", a)
print("b=", b)
swap(a,b)

