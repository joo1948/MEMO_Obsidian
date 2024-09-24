2024113285 강주영
# 과제 1

## Lisp(함수형)

``` lisp
(defun add-two-numbers (a b)
  (+ a b))

(print (add-two-numbers 10 25))
```
```
	35
```

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
```
	10 25
	35
```

## Python(객체)
```python
def input_and_add():

	num1 = int(input())
	num2 = int(input())
  
	result = num1 + num2
  
	print(f"두 숫자의 합은: {result}")

input_and_add()

```
``` 
	10
	25
	두 숫자의 합은: 35
	
```
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
```
	10
	25
	35
```


## Prolog(논리형)
``` prolog
add(A, B, Sum) :- Sum is A + B.

?- read(A), 
   read(B), 
   add(A, B, Sum), 
   write(Sum), nl.
```

```
	10
	25
	35
```


———————————————————————————————————————————————
# 과제 2
#### python 
![image](https://github.com/user-attachments/assets/fc7ddc93-0be9-4634-b82c-3ee29891a9a2)


#### C
![image](https://github.com/user-attachments/assets/7fdc6076-8239-4ee4-ab34-09919afd1df9)


#### JAVA
![image](https://github.com/user-attachments/assets/5137fd8d-27d4-49f1-ab5c-d71eee91d319)
