# 1. Álgebra y Geometría Analítica


## 1.1 Exponenciación, funciones logarítmicas

#### Emplear las reglas logarítmicas y las exponenciales.
> Reglas de los exponentes:
> - **Multiplicación de bases iguales:** Es igual a la base elevada a la suma de los exponentes.

> $$ {b^x}{b^y} = b^{x+y} $$

> - **División de bases iguales:** Es igual a la base elevada a la resta de los exponentes.

> $$ \frac{b^x}{b^y} = b^{x+y} $$

> - **División de bases iguales:** Es igual a la base elevada a la resta de los exponentes.

> $$ \frac{b^x}{b^y} = b^{x+y} $$

> - **Potencia de una potencia:** Es igual a la base elevada al producto de los exponentes.

> $$ (b^x)^{y} = b^{xy} $$

> - **Exponente cero:** Es igual a 1, siempre y cuando la base no sea 0.

> $$ b^0 = 1 $$

> - **Exponente negativo:** Es igual a 1 dividido entre la base con el exponente positivo (o en general, del signo opuesto).

> $$ b^{-x} = \frac{1}{b^x} $$

> Reglas de los logaritmos:
> - **Suma de bases iguales:** Es igual al logaritmo sobre la misma base de la multiplicación de los argumentos.

> $$ \log_b(x) + \log_b(y) = \log_b(x \cdot y) $$

> - **Resta de bases iguales:** Es igual al logaritmo sobre la misma base de la división de los argumentos.

> $$ \log_b(x) - \log_b(y) = \log_b\left(\frac{x}{y}\right) $$

> - **Logaritmo multiplicado por un número:** Es igual al logaritmo sobre la misma base del argumento elevado al número.

> $$ \log_b(x^k) = k \cdot \log_b(x) $$

> - **Cambio de base:** La división de logaritmos con la misma base es igual al logaritmo del argumento del numerador con base en el argumento del denominador.

> $$ \log_a(x) = \frac{\log_b(x)}{\log_b(a)} $$

> - **Logaritmo de la base:** Es igual a 1 siempre y cuando el argumento (y la base) no sea 0.

> $$ \log_b(b) = 1 $$

> - **Logaritmo de 1:** Es igual a 0 siempre y cuando la base no sea 0.

> $$ \log_b(1) = 0 $$


## 1.2 Ecuación de la recta

#### Obtener los parámetros que definen las ecuaciones de rectas.
> La ecuación de la recta está dada por:

> $$ y = mx + b $$

> donde $x$ y $y$ son las posiciones en los respectivos ejes, $m$ la pendiente de la recta y $b$ el punto donde la recta intercepta al eje $y$.


## 1.3 Ecuaciones de parábolas e hipérbolas

#### Obtener los parámetros que definen las ecuaciones de parábolas e hipérbolas.
> La ecuación canónica de una parábola horizontal, que abre hacia la izquierda o hacia la derecha, está dada por:

> $$ (y-k)^2 = 4p(x-h) $$

> donde $x$ y $y$ son las posiciones en los respectivos ejes, $h$ y $k$ las coordenadas del vértice y $p$ la distancia del vértice al foco.
Para una parábola vertical, que abre hacia arriba o hacia abajo, está dada por:

> $$ (x-h)^2 = 4p(y-k) $$

> <img src="../static/parabola.png" alt="Parábola" width="60%"/>

> La ecuación canónica de la hipérbola está dada por:

> $$ \frac{(x-h)^2}{a^2} - \frac{(y-k)^2}{b^2} = 1 $$

> donde $x$ y $y$ son las posiciones en los respectivos ejes, $h$ y $k$ las coordenadas del centro geométrico de la hipérbola. Si dibujamos un rectángulo cuyas esquinas estén sobre las asíntotas y dos de sus lados opuestos tocando los vértices de la hipérbola, tenemos que $a$ es la distancia del centro (sobre el eje transversal) a cualquiera de los vértices y $b$ es la distancia del centro a los otros 2 lados del rectángulo (sobre el eje conjugado).

> <img src="../static/hiperbola.png" alt="Hipérbola" width="60%"/>


## 1.4 Trigonometría

#### Resolver problemas de trigonometría.

> Un triángulo rectángulo tiene un ángulo de 90°. Sea $\alpha$ uno de los otros ángulos, $a$ el lado adyacente al ángulo, $b$ el lado opuesto y $h$ la hipotenusa, tenemos que se relacionan por las siguientes ecuaciones:

> $$ \cos(\alpha) = \frac{a}{h} $$

> $$ \sin(\alpha) = \frac{b}{h} $$

> $$ \tan(\alpha) = \frac{b}{a} $$

> <img src="../static/triangulo_rectangulo.png" alt="Hipérbola" width="60%"/>

También tenemos la ecuación de Pitágoras que relaciona los tres lados:

> $$ h^2 = a^2 + b^2 $$

Además, podemos aprovechar la identidad fundamental de la trigonometría:

> $$ \sin^2(\alpha) + \cos^2(\alpha) = 1 $$



# 2. Álgebra Lineal


## 2.1 Sistemasde ecuaciones lineales

#### Resolver sistemas de ecuaciones lineales.

> **Método de sustitución:** Consiste en despejar una de las variables y luego remplazarla en la otra ecuación. También se puede aplicar en sistemas de ecuaciones lineales con más de 2 variables. Ejemplo:
>
> $$
> \begin{aligned}
> [1] \space 4x - 2y = 8 \\
> [2] \space 3x + y = 2 \\
> \end{aligned}
> $$
>
> Despejamos por ejemplo, $y$ en la ecuación 2:
>
> $$
> \begin{aligned}
> 3x + y = 2 \\
> [3] \space y = -3x + 2 \\
> \end{aligned}
> $$
>
> Ahora, podemos remplazar $y$ en la ecuación 1:
>
> $$
> \begin{aligned}
> 4x - 2y = 8 \\
> 4x - 2(-3x + 2) = 8 \\
> 4x + 6x - 4 = 8 \\
> 4x + 6x = 8 + 4 \\
> 10x = 12 \\
> x = \frac{12}{10} \\
> x = \frac{6}{5} \\
> \end{aligned}
> $$
>
> Finalmente, podemos remplazar $x$ en la ecuación 3:
>
> $$
> \begin{aligned}
> y = -3x + 2 \\
> y = -3 \left ( \frac{6}{5} \right ) + 2 \\
> y = - \frac{18}{5} + 2 \\
> y = - \frac{8}{5} \\
> \end{aligned}
> $$
>
> ---
> **Método de igualación:** Consiste en despejar la misma variable en ambas ecuaciones y luego igualarlas para despejar la otra. En sistemas de ecuaciones con más de 2 variables, hay que combinarlo con otros métodos. Ejemplo:
>
> $$
> \begin{aligned}
> [1] \space 4x - 2y = 8 \\
> [2] \space 3x + y = 2 \\
> \end{aligned}
> $$
>
> Podemos retomar la ecuación 3 del método de sustitución, calculada a partir de la ecuación 2:
>
> $$
> \begin{aligned}
> [3] \space y = -3x + 2 \\
> \end{aligned}
> $$
>
> Y ahora despejamos $y$ de la ecuación 1:
>
> $$
> \begin{aligned}
> 4x - 2y = 8 \\
> 4x = 8 + 2y \\
> 2y = 4x - 8 \\
> y = \frac{4}{2} x - \frac{8}{2} \\
> [4] \space y = 2x - 4 \\
> \end{aligned}
> $$
>
> Entonces podemos igualar las ecuaciones 3 y 4:
>
> $$
> \begin{aligned}
> -3x + 2 = 2x - 4 \\
> -3x - 2x = -4 - 2 \\
> -5x = -6 \\
> x = \frac{6}{5} \\
> \end{aligned}
> $$
>
> Y finalmente, se obtiene $y$ remplazando $x$ en cualquier ecuación como en el método de sustitución.
>
> ---
> **Método de reducción:** Consiste en multiplicar ambas ecuaciones para que al sumarlas, se pueda anular alguna de las variables. Ejemplo:
>
> $$
> \begin{aligned}
> [1] \space 4x - 2y = 8 \\
> [2] \space 3x + y = 2 \\
> \end{aligned}
> $$
> Multiplicamos la ecuación 1 por 1 y la ecuación 2 por 2, para obtener $-2y$ y $2y$.
> $$
> \begin{aligned}
> [\times 1] \space 4x - 2y = 8 \\
> [\times 2] \space 3x + y = 2 \\
> \end{aligned}
> $$
>
> $$
> \begin{aligned}
> 4x - 2y = 8 \\
> 6x + 2y = 4 \\
> \hline
> 10x + 0 = 12 \\
> \end{aligned}
> $$
>
> Finalmente, despejamos $x$ y remplazamos como en los métodos anteriores
>
> $$
> \begin{aligned}
> 10x = 12 \\
> x = \frac{12}{10} \\
> x = \frac{6}{5} \\
> \end{aligned}
> $$

## 2.2 Polinomios y ecuación cuadrática

#### Resolver polinomios cuadráticos.
> - [APUNTES]

#### Aplicar reglas de factorización para simplificar polinomios.
> - [APUNTES]



# 3. Cálculo Diferencial e Integral


## 3.1 Funciones, límites y continuidad

#### Comprender gráficamente el concepto de función.
> - [APUNTES]

#### Calcular límites de funciones algebraicas básicas.
> - [APUNTES]


## 3.2 Derivación

#### Calcular derivadas de funciones analíticas.
> - [APUNTES]


## 3.3 Máximos y mínimos

#### Calcular máximos y mínimos de una función.
> - [APUNTES]


## 3.4 Integración

#### Calcular integrales de funciones analíticas.
> - [APUNTES]

#### Interpretar la representación geométrica de la integral.
> - [APUNTES]



# 4. Probabilidad y Estadística


## 4.1 Probabilidad

#### Aplicar las reglas básicas de la probabilidad.
> - [APUNTES]


## 4.2 Distribuciones de probabilidad

#### Comprender las relaciones entre moda, mediana y media, dada una función de distribución de probabilidad.
> - [APUNTES]


## 4.3 Medidas de tendencia central y dispersión

#### Interpretar el concepto de varianza, diagrama de Tukey (caja y bigotes) e intervalos de confianza.
> - [APUNTES]


## 4.4 Regresión lineal simple y Correlación

#### Reconocer la diferencia entre regresión y correlación.
> - [APUNTES]

#### Interpretar la significancia estadística de una línea de regresión.
> - [APUNTES]
