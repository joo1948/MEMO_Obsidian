# 과제 1

## Lisp(함수형)

``` lisp
(defun add-two-numbers (a b)
  (+ a b))

(print (add-two-numbers 10 25))
```
### 결과값 : 35
## C(절차형)
``` C
#include <stdio.h>

int add(int a, int b) {
    return a + b;
}

int main() {
    int a, b;
    scanf("%d %d", &a, &b);
    printf("%d\n", add(a, b));
    return 0;
}
```
### 결과값 : 35
## Python(객체)
```Python
class Adder:
    def __init__(self, a, b):
        self.a = a
        self.b = b

    def add(self):
        return self.a + self.b

a = int(input())
b = int(input())
adder = Adder(a, b)
print(adder.add())
```
### 예시 입력값 : 10 
### 예시 입력값 : 25
### 결과값 : 35
## Prolog(논리형)
``` prolog
add(A, B, Sum) :- Sum is A + B.

?- read(A), 
   read(B), 
   add(A, B, Sum), 
   write(Sum), nl.
```
### 예시 입력값 : 10
### 예시 입력값 : 25
### 결과값 : 35

--—————————————————————————————————
# 과제 2
#### python 
![[IMG_0261.jpeg]]

#### C
![[IMG_0263.jpeg]]

#### JAVA
