# pyramid shape
r= int(input())
for i in range (r):
    for j in range (i):
        print(' ',end = '')
    for j in range (2*(r-i-1)+1):
        print('*',end='')
    print()
