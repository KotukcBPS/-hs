# --- Блок 1 ---
x = 0
msg = f"11P {x}"
if x < 0:
    print(f"{msg} отрицательно")
elif x > 0:
    print(f"{msg} положительно")
else:
    print(f"{msg} равно нулю")

print("-" * 20)

# --- Блок 2 ---
x = 20
y = 20
msg = f"11P {x} и {y}"
if x < y:
    print(f"{msg}: x меньше y")
elif x > y:
    print(f"{msg}: x больше y")
else:
    print(f"{msg}: x равно y")

print("-" * 20)

# --- Блок 3 ---
x = 3
msg = f"11P {x} (r=5-10)"
if 5 <= x <= 10:
    print(f"{msg}: попал!")
else:
    print(f"{msg}: не попал!")

print("-" * 20)

# --- Блок 4 ---
x = 4
y = 4
z = 4
msg = f"11P xyz: {x}, {y}, {z}"

if x == y == z:
    print(f"{msg} - треугольник равносторонний")
elif x == y or y == z or x == z:
    print(f"{msg} - треугольник равнобедренный")
else:
    print(f"{msg} - треугольник разносторонний") # Исправил "все стороны равны" на правильный смысл
