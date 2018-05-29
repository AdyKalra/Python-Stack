
# higher order fn
- is one that takes a fn as  a parameter or returns a fn as a result or both

## Composition 
- def f(x)
-   return x+2

- def g (h,x)
-   return h (x) * 2

- print (g (f,42))

## Closure
- def addx (x)
-    def _(y)
-       return x+y
-    return _


