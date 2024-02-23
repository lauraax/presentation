# PYTHON OR JAVA CODING STANDARDS


## Whitespace in Expressions and Statements

### Python
Avoid:

- 
>Yes: spam(ham[1], {eggs: 2})
No:  spam( ham[ 1 ], { eggs: 2 } )
-
>Yes: if x == 4: print x, y; x, y = y, x
No:  if x == 4 : print x , y ; x , y = y , x
-
Yes
>ham[1:9], ham[1:9:3], ham[:9:3], ham[1::3], ham[1:9:]
ham[lower:upper], ham[lower:upper:], ham[lower::step]
ham[lower+offset : upper+offset]
ham[: upper_fn(x) : step_fn(x)], ham[:: step_fn(x)]
ham[lower + offset : upper + offset]

No
>ham[lower + offset:upper + offset]
ham[1: 9], ham[1 :9], ham[1:9 :3]
ham[lower : : upper]
ham[ : upper]
-
>Yes: spam(1)
No:  spam (1)

>Yes: dct['key'] = lst[index]
No:  dct ['key'] = lst [index]

Other recomendations:
- assignment (=), augmented assignment (+=, -= etc.), comparisons (==, <, >, !=, <>, <=, >=, in, not in, is, is not), Booleans (and, or, not).
-
Yes:
>-i = i + 1
submitted += 1
x = x*2 - 1
hypot2 = x*x + y*y
c = (a+b) * (a-b)

No:
>i=i+1
submitted +=1
x = x * 2 - 1
hypot2 = x * x + y * y
c = (a + b) * (a - b)

### Java
1.
>while (true) {
    ...
}
2.
>objeto.unMetodo(a, b, c);
3.
>a += b + c;
a = (a + b) / (c + d);
contador++;
4.
for (expresion1; expresion2; expresion3)
5. 
>Unidad unidad = (Unidad) objeto;