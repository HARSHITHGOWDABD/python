# 1.Sequential 
```
x=2
print(x)
x=x+2
print(x)
```
## Output
```
2
4
```
# 2. Conditional
```
x=25
if x<10:
    print('small')
if x>20:
    print('bigger')
print('finish')
```
## Output
```
bigger
finish
```
# 3. Repetative
```
n=5
while n>0:
    print(n)
    n=n-1
print('blastoff')
```
## Output
```
5
4
3
2
1
blastoff
```
# 4.Break working
```
while True:
    line =input(' ')
    if line== 'done':
        break
    print(line)
print('Done!')
```
## Output
```
 done
Done!
```

# 5.Working of break and continue 
```
while True:
    line =input(' ')
    if line[0] == '#' :
        continue
    if line == 'done' :
        break
    print(line)
print('done')
```
## Output
```
harshi
harshi
 #harshi
 #hARSHI
 done
done
```
# for loop working
```
for i in [5,4,3,2,1]:
    print(i)
print('blastoff!')
```
## Output
```
5
4
3
2
1
blastoff!
```

# ASSIGNMENT-1

# 1.Program to check the number is even or odd

```
n= input(' ')

m=int(n)
if m%2==0:
    print('even number')
    
else:
    print('odd number')
```
## Output
```
6
even number
```
# 2.Program to find the maximum of the number 
```
num=[1,6,78, 89 ,54 ]
maximum =num[0]
minimum =num[0]
for n in num:
    if n >maximum:
        maximum=n
print(maximum)

for n in num:
    if n < minimum:
        minimum=n
print(minimum)

```
## Output
```
89
1

```
# 3.Program to find fabinocci series
```
series_num =int (input('enter a number : '))
a,b=0,1
count =0

if(series_num<0):
    print(" its a negative number ")

elif series_num==1:
    print( a )
    
else:
    print('the fabinocci')
    while count <series_num:
        print(a)
        a,b=b,b+a
        count=count+1
```
## Output 
```
enter a number : 5
the fabinocci
0
1
1
2
3
```
# 4. TO Compute the gross pay of the user 
```
hours = int(input('enter the hours you worked '))
rate  = 40
grosspay = hours*rate
print('the grosspay amount is ',grosspay)
```
## Output
```
enter a number : 5
the fabinocci
0
1
1
2
3
```


