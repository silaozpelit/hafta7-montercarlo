'''python
import random
def hilelizar(n):
    a = b = c = d = e = f = 0
    for i in range(n):
        x = random.randint(1, 6)
        if x == 1:
        a += 1
        elif x == 2:
        b += 1
        elif x == 3:
        c += 1
        elif x == 4:
        d += 1
        elif x == 5:
        e += 1
        elif x == 6:
        f += 1
            
    s = a + b + c + d + e + f

    print('1 olasılığı:', a / s)
    print('2 olasılığı:', b / s)
    print('3 olasılığı:', c / s)
    print('4 olasılığı:', d / s)
    print('5 olasılığı:', e / s)
    print('6 olasılığı:', f / s)

hilelizar(360000)

