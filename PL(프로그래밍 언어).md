# Lisp(함수형)

``` lisp
(defun add-two-numbers (a b)
  (+ a b))

(print (add-two-numbers 10 25))
```

# C(절차형)
``` C
	(defun add-two-numbers (a b)
  (+ a b))

(print (add-two-numbers 10 25))
```
# Python(객체)
```Python
class Adder:
    def __init__(self, a, b):
        self.a = a
        self.b = b

    def add(self):
        return self.a + self.b

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
adder = Adder(a, b)
print("Sum:", adder.add())
```
# Prolog(논리형)
``` prolog
add(A, B, Sum) :- Sum is A + B.

?- write('Enter first number: '), read(A), 
   write('Enter second number: '), read(B), 
   add(A, B, Sum), 
   write('Sum: '), write(Sum), nl.
```

