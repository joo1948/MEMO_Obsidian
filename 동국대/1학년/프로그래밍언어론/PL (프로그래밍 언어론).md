2024113285 강주영

# 과제 1

## Lisp(함수형)

``` lisp
(defun add-two-numbers (a b)
  (+ a b))

(print (add-two-numbers 10 25))

```
[결과]
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

[결과]
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
[결과]
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

[결과]
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

[결과]
```
	10
	25
	35
```



# 과제 2
#### python 
![image](https://github.com/user-attachments/assets/821c227a-f0d3-4ede-9339-a50bdeab52ac)


#### C
![image](https://github.com/user-attachments/assets/228add8f-f97c-4c01-b2ab-ad9862161c0b)


#### JAVA
![image](https://github.com/user-attachments/assets/82938e16-1eca-49e9-a730-2b5e1360e601)
