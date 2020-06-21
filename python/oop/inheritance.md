```python

class c1:
    def __init__(self):
        self.a = 'a'

class c2(c1):
    def __init__(self):
        self.b = 'b'
        super(c2, self).__init__()
        
c = c2()
print(c.a)
print(c.b)

```
