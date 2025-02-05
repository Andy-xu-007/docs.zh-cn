# cosh

## 功能

计算输入数值的双曲余弦值。

## 语法

```Haskell
DOUBLE cosh(DOUBLE arg)
```

### 参数说明

`arg`：指定一个数值。该函数在计算输入数值的双曲余弦值之前，会先把数值转换为 DOUBLE 类型的值。

## 返回值说明

返回一个 DOUBLE 类型的值。

## 使用说明

如果入参指定为非数值，则返回 `NULL`。

## 示例

```Plain
mysql> select cosh(-1);
+--------------------+
| cosh(-1)           |
+--------------------+
| 1.5430806348152437 |
+--------------------+

mysql> select cosh(0);
+---------+
| cosh(0) |
+---------+
|       1 |
+---------+

mysql> select cosh(1);
+--------------------+
| cosh(1)            |
+--------------------+
| 1.5430806348152437 |
+--------------------+

mysql> select cosh("");
+----------+
| cosh('') |
+----------+
|     NULL |
+----------+
```

## 关键字

COSH
