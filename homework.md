# 程式設計題

## 1.使用for 迴圈(loop)計算1+2+3+.....100
```
sum = 0

for x in range(1, 101):
  
  sum +=  x
print(sum)
```
## 2.使用for 迴圈(loop)計算1+3+5+7.....+99
```
sum = 0

for x in range(1, 101,2):
  
  sum +=  x
print(sum)
```
## 3.使用for 迴圈(loop)計算1*3*5*7.....*99
```
sum = 1

for x in range(1, 101,2):
  
  sum *=  x
print(sum)
```
## 4.使用while 迴圈(loop)計算1+2+3+.....100
```
sum = 0
x = 0

while x <= 100:
  sum += x
  x +=1
print(sum)

```
## 5.使用while 迴圈(loop)計算1+3+5+7.....+99
```
sum = 0
x = 1

while x <= 100:
  sum += x
  x +=2
print(sum)

```
## 6.使用while 迴圈(loop計算1*3*5*7.....*99
```
sum = 1
x = 1

while x <= 100:
  sum *= x
  x +=2
print(sum)
```
