# 輸入與輸出(Input and Output)
```
單元學習目標:
python輸入:input()
python輸出: print()
python格式化輸出技術
```

# 基本輸入:讀取使用者的輸入
```
使用input時，會從標準輸入(stdin)中讀取輸入資料
這些資料是string字串型態{重要}
stdin==Standard Input
```
### 程式範例 
```
x = input('Enter your name:')
print('Hello, ' + x)
```
```
Enter your name:龍大大
Hello, 龍大大
```
### 程式範例 
```
a = input("請輸入：")
a
```
```
請輸入：100
'100'
```

Python內建的type()函數可以顯示資料型態
```
type(a)
```
str

### [程式除錯題]錯誤的做法：請指出底下程式的錯誤
```
a = input("請輸入：")
a
b=a+1
b
```
```
若輸入 100請問答案為何?
```

### 讀取使用者輸入的整數==>使用eval()函數
```
a = eval(input("請輸入："))
a
```
```
請輸入：100
100
```
```
b=a+1
b
```
### 超級重要:可以一次輸入多（兩）個資料
```
a,b = eval(input("請輸入兩個數位："))
a,b
```
```
請輸入兩個數位：12,23
(12, 23)
```
```
