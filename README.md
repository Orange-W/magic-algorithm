# magic-algorithm

## 相等
```
a==b => !(a^b)
a!=b => a^b
```

## 判断 num是否为2的幂次方
```
n > 0 and (n & (n - 1)) == 0
```

另一个作用:计算一个非负整数 n 的二进制表示中有多少个 1 。

```
return (n & (n - 1)) 
```

