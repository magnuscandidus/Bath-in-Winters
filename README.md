# Bath-in-Winters
# cook your dish here
for i in range (int(input())):
    x,y = map(int,input().split())
    a = 2*y
    if(x>=a):
        print(int(x/a))
    else:
        print("0")
