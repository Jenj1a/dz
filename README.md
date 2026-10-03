n = raw_input()
k = {}
for key in n:
    if key in k:
        k[key] += 1
    else:
        k[key] = 1
print(k)
