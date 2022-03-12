# Three-Pairwise-Maximums
```python
t=int(input())
for ann in range(t):
    a,b,c=map(int,input().split())
    if a==b:
        if a<c:
            print("NO")
        else:
            print("YES")
            print(a,c,c)
    elif b==c:
        if b>a:
            print("YES")
            print(b,a,a)
        else:
            print("NO")
    elif a==c:
        if a>b:
            print("YES")
            print(a,b,b)
        else:
            print("NO")
    else:
        print("NO")
```
