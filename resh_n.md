# Решение задач 905–912

Все задачи решаются методом линеаризации (теорема Ляпунова об устойчивости по первому приближению).

---

## Задача 905

$$\dot{x} = \text{tg}(z - y) - 2x, \quad \dot{y} = \sqrt{9 + 12x} - 3e^y, \quad \dot{z} = -3y$$

Точка $(0,0,0)$ — положение равновесия. Матрица Якоби:

$$A = \begin{pmatrix} -2 & -1 & 1 \\ 2 & -3 & 0 \\ 0 & -3 & 0 \end{pmatrix}$$

Характеристическое уравнение:

$$\det(A - \lambda I) = -\lambda^3 - 5\lambda^2 - 8\lambda - 6 = 0 \;\Rightarrow\; (\lambda+3)(\lambda^2+2\lambda+2)=0$$

Корни: $\lambda_1 = -3,\; \lambda_{2,3} = -1 \pm i$.

Все $\text{Re}\,\lambda_i < 0$ $\Rightarrow$ **нулевое решение асимптотически устойчиво**.

---

## Задача 906

$$\dot{x} = e^x - e^{-3z}, \quad \dot{y} = 4z - 3\sin(x+y), \quad \dot{z} = \ln(1+z-3x)$$

Матрица Якоби в нуле:

$$A = \begin{pmatrix} 1 & 0 & 3 \\ -3 & -3 & 4 \\ -3 & 0 & 1 \end{pmatrix}$$

Характеристическое уравнение (разложение по 2-му столбцу):

$$(3+\lambda)(\lambda^2 - 2\lambda + 10) = 0$$

Корни: $\lambda_1 = -3,\; \lambda_{2,3} = 1 \pm 3i$.

Есть корни с $\text{Re}\,\lambda > 0$ $\Rightarrow$ **нулевое решение неустойчиво**.

---

## Задачи 907–912 (параметры $a$, $b$)

Условия асимптотической устойчивости для $2\times 2$ матрицы $A$: $\text{tr}\,A < 0$ и $\det A > 0$.

### Задача 907

$$A = \begin{pmatrix} a & -2 \\ 1 & 1 \end{pmatrix}, \quad \text{tr} = a+1,\quad \det = a+2$$

$$\boxed{-2 < a < -1}$$

### Задача 908

$$A = \begin{pmatrix} a & 1 \\ 1 & a \end{pmatrix}, \quad \text{tr} = 2a,\quad \det = a^2 - 1$$

$$\boxed{a < -1}$$

### Задача 909

$$A = \begin{pmatrix} 1 & a \\ b & -3 \end{pmatrix}, \quad \text{tr} = -2 < 0,\quad \det = -3 - ab$$

$$\boxed{ab < -3}$$

### Задача 910

Линеаризация: $\sin x \approx x$,

$$A = \begin{pmatrix} 1 & 1 \\ a & b \end{pmatrix}, \quad \text{tr} = 1+b,\quad \det = b - a$$

$$\boxed{a < b < -1}$$

### Задача 911

$$A = \begin{pmatrix} -2 & -a/4 \\ 1 & a \end{pmatrix}, \quad \text{tr} = a-2,\quad \det = -2a + \frac{a}{4} = -\frac{7a}{4}$$

$$\boxed{a < 0}$$

### Задача 912

$$A = \begin{pmatrix} a/e & -1 \\ b & 1 \end{pmatrix}, \quad \text{tr} = \frac{a}{e}+1,\quad \det = \frac{a}{e} + b$$

$$\boxed{a < -e \quad \text{и} \quad b > -\frac{a}{e}}$$
