son = int(input("Son kiriting : "))
b = 0
for a in range(2, son + 1) :
    for c in range(1, a + 1) :
        if a % c == 0 :
            b = b + 1
    if b == 2 :
        print(f"{a} tub son")
    else :
        print(f"{a} tub emas")
    b = 0
