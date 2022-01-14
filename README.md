import math
a = int(input("введите длину первой стороны: "))
b = int(input("введите длину второй стороны: "))
h = math.sqrt(a**2 + b**2)
h = (a**2 + b**2)**0.5
h = math.hypot(a, b)
print("Итого: ", h)
