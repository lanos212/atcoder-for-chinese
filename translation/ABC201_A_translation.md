## 题意

给出一个长度为 $3$ 的整数序列 $A$。
你可以重排 $A$ 中元素的位置，
问是否存在一种重排方式，使得 $A_3-A_2=A_2=A_1$。

## 数据范围

$1\le A_i\le 100$。

## 输入格式

三个整数，表示序列 $A$。
          
## 输出格式

一行 `Yes` 或 `No`，表示是否能满足条件。

## 样例

### 样例输入1
```
5 1 3
```

### 样例输出1
```
Yes
```

## 样例解释1

一种合法的重排后的 $A=1,3,5$。

### 样例输入2
```
1 4 3
```

### 样例输出2
```
No
```

### 样例输入3
```
5 5 5
```

### 样例输出3
```
Yes
```
