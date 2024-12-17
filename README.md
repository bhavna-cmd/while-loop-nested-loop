# while-loop-nested-loop
******
*****
****
***
**
*
# Loop to print the pattern
for i in range(6, 0, -1):
    print('*' * i)
----*
---**
--***
-****
*****
# Loop to print the pattern
for i in range(1, 6):
    print('-' * (5 - i) + '*' * i)
1
10
101
1010
10101
# Loop to print the pattern
for i in range(1, 6):
    print(''.join(['1' if j % 2 == 1 else '0' for j in range(1, i + 1)]))
____1
___01
__101
_0101
10101
# Loop to print the pattern
for i in range(1, 6):
    # Print leading underscores
    print('_' * (5 - i) + ''.join(['1' if j % 2 == 1 else '0' for j in range(1, i + 1)]))
    
*********
-*******
--*****
---***
----*
# Loop to print the pattern
for i in range(9, 0, -2):
    print('-' * (9 - i) + '*' * i)
