a = [1, 4, 9, 10, 16, 20, 25, 30, 36]

result = [x for x in a if int(x**0.5)**2 == x]

print("Perfect square numbers:", result)