n = int(input())
for i in range(n):
    u = int(input())
    count = 0
    for i in range(1, u+1):
        k = 0
        for j in range(1, i+1):
            if(i % j == 0):
                k += 1
        if(k == 2):
            count += 1
    print(count)
