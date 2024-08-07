Computational complexity indicates how much effort is needed to apply an algorithm or how costly it is. This cost can be measured in a variety of ways, and the particular context determines its meaning. 
### Big-O Notation (Upper Bounds)
This is the most commonly used notation to specify asymptotic complexity (which basically means rate of growth of the function.) Paul Bachman introduced this in 1894. 

```
Given two positive valued functions f and g, consider:
	f(n) is O(g(n)) 
	if there exists positive number c and N such that
		f(n) <= cg(n) for all n >=N
```

#### Properties of Big-O
1. O(O(g(n))) = O(g(n))
2. If f(n) is O(h(n)) and g(n) is O(h(n)), then f(n) + g(n) is O(h(n))
3. The function ank is O(nk)
4. The function nk is O(nk+j) for any positive j
5. If f (n) = cg(n), then f (n) is O(g(n))
6. The function loga n is O(logb n) for any positive numbers a and b ≠ 1
7. loga n is O(lg n) for any positive a ≠ 1, where lg n = log2 n

### Big-Omega Notation (Lower Bound)
```
Given two positive valued functions f and g, consider:
	The function f (n) is Ω(g(n)) 
		if there exist positive numbers c and N
		such that f (n) ≥ cg(n) for all n ≥ N
```

### Big-Theta Notation (Average Solution)
