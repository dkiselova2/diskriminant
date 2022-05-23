Kvadrātsaknes.

Sprecifikacija.
 mūsu problēma bija tāda, ka nevarējām atrast kvadrātvienādojuma saknes, mēs to atrisinājām, izmantojot programmu un izveidojām kodu, lai bērni un pieaugušie varētu ātri atpazīt diskriminantu un vienādojumā ir saknes.
 https://miro.com/app/board/uXjVOz43zDE=/  
vietne, kurā mēs definējām lomas un amatus.
https://docs.google.com/forms/d/1LwV7_VIN4m-Tuxbu8KL9EhotYWuf-Fo4xX3fZN3YVQw/edit#responses  aptauja par mūsu tēmu.
https://ukit.com/sites/url/u1z7bbx83/pages/id/index/constructor vietne, kurā mēs strādājām skolēniem, aprēķinot diskriminantu.
import math
 
print("Введите коэффициенты для уравнения")
print("ax^2 + bx + c = 0:")
a = float(input("a = "))
b = float(input("b = "))
c = float(input("c = "))
 
discr = b ** 2 - 4 * a * c
print("Дискриминант D = %.2f" % discr)
 
if discr > 0:
    x1 = (-b + math.sqrt(discr)) / (2 * a)
    x2 = (-b - math.sqrt(discr)) / (2 * a)
    print("x1 = %.2f \nx2 = %.2f" % (x1, x2))
elif discr == 0:
    x = -b / (2 * a)
    print("x = %.2f" % x)
else:
    print("Корней нет")
