# 深度学习中一些常见函数
**squeeze()：** 所有长度为1的维度都会被移除

- squeeze(0)：删去第0个维度

## numpy的一些常见函数
**np.vstack()**：按垂直方向（行顺序）堆叠数组构成一个新的数组

*堆叠的数组需要具有相同的维度*

```
a=np.array([[1,2,3]])
b=np.array([[3,4,5]])
c=np.vstack((a,b))
# array([[1,2,3], 
         [3,4,5]  ])
```

**np.hstack()**：按水平方向堆叠

```
a=np.array([1,2,3])
b=np.array([0] * 10)
c=np.hstack((a,b))# array([1, 2, 3, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0])
```

## torch的一些常见函数
**x.view()：** 就是对tensor进行reshape。

