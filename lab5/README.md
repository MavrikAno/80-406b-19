## Вариант 2

### Задание
Используя явную и неявную конечно-разностные схемы, а также схему Кранка - Николсона, решить начально-краевую задачу для дифференциального уравнения параболического типа. Осуществить реализацию трех вариантов аппроксимации граничных условий, содержащих производные: двухточечная аппроксимация с первым порядком, трехточечная аппроксимация со вторым порядком, двухточечная аппроксимация со вторым порядком. В различные моменты времени вычислить погрешность численного решения путем сравнения результатов с приведенным в задании аналитическим решением U(x, t). Исследовать зависимость погрешности от сеточных параметров tau, h.

du/dt = a * (d^2u)/(dx^2), a > 0,

u(0,t) = 0,

u(1,t) = 1,

u(x,0) = x + sin(pi * x),

Аналитическое решение:
U(x, t) = x + exp(-pi^2 * a * t)* sin(pi * x)