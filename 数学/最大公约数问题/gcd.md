# 辗转相除法
```python
def solve(a,b):
    return a if b==0 else solve(b,a%b)
```
这里需要加个判断a>b，否者交换a,b，保证大数除以小数
# 其他方法
- 穷举法
- 辗转相减法
