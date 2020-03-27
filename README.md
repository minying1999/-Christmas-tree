# -Christmas-tree
# A simple Christmas tree with basic codes
import numpy as np
from numpy import sqrt
c=int(input())
C=int(c/2)
b=int(sqrt(c))
def tree(Height):
    print('\n\n\n\n\n')
    print('Merry Christmas!')
    for i in range(Height):
        print((Height-i)*2*' '+'o'+ i*'~X~o')
        print(((Height-i)*2-1)*' '+(i*2+1)*'/'+'|'+(i*2+1)*'\\')
    return
tree(c)
Height=c
for  i in range(b):
    print(((Height-i)*2-1)*' '+(i*2+1)*' '+'|'+(i*2+1)*' ')
print(2*c*'_'+'|'+2*c*'_')
