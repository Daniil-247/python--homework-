R = 3 
C = 3 
m1 = []
m2 = []
m3 = [[],[],[]]
print("Через Enter введите члены 1-ой матрицы, начиная с 1-ой строчки слева направо, далее 2-ая строчка и 3-я.")
for i in range(R):                      #Вводим 1-ую матрицу.
    a =[]                         
    for j in range(C):    
        a.append(int(input())) 
    m1.append(a)   
for i in range(R):          #Вывод 1-ой матрицы для проверки.
    for j in range(C): 
        print(m1[i][j], end = " ") 
    print()
print('Умножить/Сложить')
otvet = str(input())
if otvet == 'Умножить':
            print("Через Enter введите чдены 1-го столбца 2-ой матрицы, далее 2-ой столбец и 3-ий.")
            for i in range(R):          #Вводим 2-ую матрицу.
                b =[] 
                for j in range(C):            
                    b.append(int(input())) 
                m2.append(b)   
            for i in range(R):          #Вывод 2-ой матрицы для проверки.
                for j in range(C): 
                    print(m2[j][i], end = " ") 
            print()
            p = 0
            for i in range(1):          #Я еще подумаю,как загнать вычисления не в 9 циклов, а в 3 цикла.
                for k in m1[0]:
                    while i<3:
                      p += (m1[0][i]*m2[0][i])    
                      i += 1
                m3[0].append(p)
            h =0
            for i in range(1):
                for k in m1[0]:
                    while i<3:
                      h += (m1[0][i]*m2[1][i])
                      i += 1
                    m3[0].append(h)
            l = 0
            for i in range(1):
                for k in m1[0]:
                    while i<3:
                      l += (m1[0][i]*m2[2][i])
                      i += 1
                m3[0].append(l)
            m = 0
            for i in range(1):
                for k in m1[0]:
                    while i<3:
                      m += (m1[1][i]*m2[0][i])
                      i += 1
                m3[1].append(m)
            f = 0
            for i in range(1):
                for k in m1[0]:
                    while i<3:
                      f += (m1[1][i]*m2[1][i])
                      i += 1
                m3[1].append(f)
            o = 0   
            for i in range(1):
                for k in m1[0]:
                    while i<3:
                      o += (m1[1][i]*m2[2][i])
                      i += 1
                m3[1].append(o)
            v = 0
            for i in range(1):
                for k in m1[0]:
                    while i<3:
                      v += (m1[2][i]*m2[0][i])
                      i += 1
                m3[2].append(v)
            x = 0
            for i in range(1):
                for k in m1[0]:
                    while i<3:
                      x += (m1[2][i]*m2[1][i])
                      i += 1
                m3[2].append(x)
            z = 0
            for i in range(1):
                for k in m1[0]:
                    while i<3:
                      z += (m1[2][i]*m2[2][i])
                      i += 1
                m3[2].append(z)
            print("Ответ:")
            for i in range(R):
                for j in range(C): 
                    print(m3[i][j], end = " ") 
                print()
elif otvet == "Сложить":
    print("Через Enter введите члены 1-го столбца, далее 2-го и 3-го.")
    for i in range(3):                      #Вводим 2-ую матрицу.
        a =[]                         
        for j in range(3):    
            a.append(int(input())) 
        m2.append(a)
    for i in range(3):          #Вывод 2-ой матрицы для проверки.
        for j in range(3): 
            print(m2[i][j], end = " ") 
        print()
    m4 = []
    for i in range(3):
        a =[] 
        for j in range(3):      
            a.append(m1[0][j]+m2[0][j])
            j += 1
    m4.append(a)
    for i in range(3):
        a =[] 
        for j in range(3):      
            a.append(m1[1][j]+m2[1][j])
            j += 1
    m4.append(a)
    for i in range(3):
        a =[] 
        for j in range(3):      
            a.append(m1[2][j]+m2[2][j])
            j += 1
    m4.append(a)
    print("Ответ:")
    for i in range(R):
        for j in range(C): 
            print(m4[i][j], end = " ") 
        print()
