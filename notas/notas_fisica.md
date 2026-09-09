# 1. Leyes deNewton


## 1.1 Aplicación de las leyes de Newton

#### Aplicar las leyes de Newton para resolver un problema sobre dinámica.
> Las leyes de Newton son las siguientes:
> - **Primera ley de Newton:** Un cuerpo en reposo o en movimiento tiende a conservar ese estado en ausencia de fuerzas externas.
> - **Segunda ley de Newton:** La fuerza aplicada sobre un cuerpo y su aceleración están en relación directamente proporcional, siendo la masa la constante de proporcionalidad.
>
> $$ \sum F = ma $$
>
> - **Tercera ley de Newton:** La fuerza aplicada por un cuerpo A sobre un cuerpo B es igual a la fuerza aplicada por el cuerpo B sobre el cuerpo A pero en el sentido opuesto.
>
> En el siguiente ejercicio, se quiere calcular la aceleración de dos masas unidas por una cuerda tensa y una polea sin masa, sobre un plano sin fricción:
>
> <img src="../static/dinamica.png" alt="Plano inclinado y polea con masas atadas por una cuerda" width="60%"/>
>
> Podemos empezar por calcular las fuerzas para la masa 1. Sea $\mathbf{T}$ la fuerza de tensión constante a lo largo de la cuerda. Tomando un eje que es positivo hacia arriba, tenemos:
>
> $$
> \begin{aligned}
> \sum \mathbf{F}_1 = m_1 \mathbf{a} \\
> \mathbf{T} + m_1 \mathbf{g} = m_1 \mathbf{a} \\
> ||T|| - m_1 ||g|| = m_1 a \\
> ||T|| = m_1 a + m_1 ||g|| \\
> \end{aligned}
> $$
>
> Ahora, para la masa 2, podemos tomar nuestro eje paralelo a la superficie, siendo positivo hacia la derecha. En la ecuación que se obtiene, podemos remplazar el valor encontrado previamente para la tensión.
>
> $$
> \begin{aligned}
> \sum \mathbf{F}_2 = m_2 \mathbf{a} \\
> \mathbf{T} + m_2 \mathbf{g} \sin(\theta) = m_2 \mathbf{a} \\
> -||T|| + m_2 ||g|| \sin(\theta) = m_2 a \\
> -(m_1 a + m_1 ||g||) + m_2 ||g|| \sin(\theta) = m_2 a \\
> -m_1 a - m_1 ||g|| + m_2 ||g|| \sin(\theta) = m_2 a \\
> -m_1 ||g|| + m_2 ||g|| \sin(\theta) = m_2 a + m_1 a \\
> ||g||(m_2 \sin(\theta) - m_1) = (m_2 + m_1) a \\
> a = \frac{m_2 \sin(\theta) - m_1}{m_2 + m_1} ||g|| \\
> \end{aligned}
> $$
>
> Notemos que $a$ no es la magnitud $||a||$. La magnitud siempre es positiva. En cambio, $a$ puede tomar valores positivos o negativos porque es la proyección del vector sobre el eje que estamos tomando en ambos sistemas de referencia. Si es positivo, quiere decir que la aceleración ocurre hacia arriba para la masa 1 y hacia la derecha (y abajo) para la masa 2. Si es negativo, indica lo contrario.



# 2. Trabajo y Energía


## 2.1 Conservación de la energía mecánica

#### Aplicar la ley de conservación de la energía mecánica en las siguientes situaciones: (1) un cuerpo en movimiento circular, (2) movimiento de un cuerpo en planos inclinados, (3) un choque elástico entre dos cuerpos.

> En un movimiento circular, podemos plantear dos casos límites: uno en el que el movimiento es solo horizontal y otro en el que tiene una componente vertical. Para cualquier caso, tenemos que si la energía se conserva, entonces la energía va a ser igual en puntos arbitrarios de la trayectoria:
>
> $$
> \begin{aligned}
> E_1 = E_2 \\
> K_1 + E_{p1} = K_2 + E_{p2} \\
> \frac{1}{2}mv_1^2 + mgh_1 = \frac{1}{2}mv_2^2 + mgh_2 \\
> \end{aligned}
> $$
>
> Para el caso horizontal, la velocidad y la altura son constantes, por lo tanto, la energía mecánica se mantiene constante.
>
> $$ E = \frac{1}{2}mv^2 + mgh $$
>
> Para el caso vertical, podemos tomar convenientemente el punto más bajo como $h=0$ y el más alto como $h=2R$, donde $R$ es el radio de la circunferencia descrita, y encontrar la relación necesaria entre las velocidades para que se conserve la energía.
>
> $$
> \begin{aligned}
> \frac{1}{2}mv_1^2 + mgh_1 = \frac{1}{2}mv_2^2 + mgh_2 \\
> \frac{1}{2}mv_1^2 + mg(0) = \frac{1}{2}mv_2^2 + mg(2R) \\
> \frac{1}{2}mv_1^2 = \frac{1}{2}mv_2^2 + 2mgR \\
> \frac{1}{2}v_1^2 = \frac{1}{2}v_2^2 + 2gR \\
> v_1^2 = v_2^2 + 4gR \\
> v_1 = \sqrt{v_2^2 + 4gR} \\
> \end{aligned}
> $$
>
> Finalmente, encontramos la relación entre la velocidad más baja y la más alta necesaria para que se conserve la energía mecánica.
>
> Para un objeto sobre un plano inclinado, se requiere que no haya fricción para que se pueda conservar la energía. Independientemente del ángulo del plano, se mantienen las mismas ecuaciones para la energía mecánica. Si tomamos $h$ como la altura del objeto en el punto más alto del plano y 0 en el punto más bajo, tenemos:
>
> $$
> \begin{aligned}
> \frac{1}{2}mv_1^2 + mgh_1 = \frac{1}{2}mv_2^2 + mgh_2 \\
> \frac{1}{2}mv_1^2 + mg(0) = \frac{1}{2}mv_2^2 + mg(h) \\
> \frac{1}{2}mv_1^2 = \frac{1}{2}mv_2^2 + mgh \\
> \frac{1}{2}v_1^2 = \frac{1}{2}v_2^2 + gh \\
> v_1^2 = v_2^2 + 2gh \\
> v_1 = \sqrt{v_2^2 + 2gh} \\
> \end{aligned}
> $$
>
> En un choque elástico se conserva la energía del sistema y también el momento lineal.
>
> $$
> \begin{aligned}
> \frac{1}{2}mv_{1i}^2 + \frac{1}{2}mv_{2i}^2 = \frac{1}{2}mv_{1f}^2 + \frac{1}{2}mv_{2f}^2 \\
> \mathbf{p}_{1i} + \mathbf{p}_{2i} = \mathbf{p}_{1f} + \mathbf{p}_{2f} \\
> \end{aligned}
> $$
>


# 3. Ley de la gravitación universal


## 3.1 Gravitación

#### Emplear la ley de la gravitación universal.
> La ley de la gravitación universal se define como:
>
> $$ F_g = G \frac{m_1 m_2}{d^2} $$
>
> Siendo $m_1$ y $m_2$ las masas de los cuerpos, $d$ la distancia que separa sus centros de masa y $G$ la constante de gravitación universal dada por:
>
> $$ G =  6,67 \times 10^{-11} \, \text{N}\text{m}^2/\text{kg}^2\ $$
>



# 4. Termodinámica: temperatura, expansión térmica y gases ideales


## 4.1 Temperatura, calor y la ley cero

#### Calcular la variación de la temperatura y calor de sustancias que llegaron a un equilibrio térmico.
> - El calor es la transferencia de energía térmica en una sustancia y está dado por:
>
> $$ Q = mc \Delta T $$
>
> Donde $c$ es el calor específico de la sustancia. Un yvalor positivo de $Q$ significa que la sustancia ganó energía, y uno negativo que perdió energía. Dos sustancias en equilibrio térmico tienen la misma temperatura. En un sistema aislado, la energía que gana una sustancia es igual a la que pierde la otra.
>
> $$
> \begin{aligned}
> Q_1 = -Q_2 \\
> m_1 c_1 \Delta T_1 = - m_2 c_2 \Delta T_2 \\
> m_1 c_1 (T_{f} - T_{1i}) = - m_2 c_2 (T_{f} - T_{2i}) \\
> \end{aligned}
> $$


## 4.2 Gases ideales y ecuación de estado

#### Aplicar la ecuación de estado de los gases para calcular la relación entre presión, temperatura y volumen.
> - La ecuación que describe el comportamiento de un gas ideal está dada por:
>
> $$ PV = nRT $$
>
> donde $P$ es la presión, $V$ el volumen, $n$ el número de moles, $R$ la constante de los gases ideales y $T$ la temperatura.


## 4.3 La primera ley de la termodinámica

#### Aplicar la primera ley de la termodinámica para calcular variaciones de energía, calor o trabajo.
> De acuerdo con la primera ley de la termodinámica, la energía no se crea ni se destruye, solo se transforma. Tenemos entonces:
>
> $$ \Delta E = Q + W $$
>
> El aumento de energía en un sistema corresponde al calor que entra menos el trabajo que realiza el sistema. Tenemos además que el trabajo realizado por un gas está dado por:
>
> $$ W = - \int_{V_i}^{V_f} P \mathrm{d}V $$
>
> Por lo tanto, tenemos que:
>
> $$ \Delta E = mc \Delta T - \int_{V_i}^{V_f} P \mathrm{d}V $$



# 5. Electricidad


## 5.1 Ley de Coulomb

#### Usar la ley de Coulomb para solucionar un problema.
> La ley de Coulomb mide la fuerza eléctrica entre dos partículas cargadas. Sea $q_1$ y $q_2$ las cargas eléctricas de dos partículas, $d$ la distancia que las separa y $k$ la constante de Coulomb, el módulo de la fuerza eléctrica está dada por:
>
> $$ F_e = k_e \frac{|q_1 q_2|}{d^2} $$
>
> El valor de la constante de Coulomb está dado por:
>
> $$ k_e = 9 \times 10^9 \text{N} \cdot \text{m}^2 / \text{C}^2 $$
>
> La dirección del vector fuerza depende de si las cargas tienen el mismo signo o no. Si tienen signos iguales, se repelen y opuestos se atraen. Luego, podemos definir el vector unitario $\mathbf{\hat{r}}_{2}$ como aquel que apunta del objeto 1 al 2. La fuerza que el objeto 1 ejerce sobre el objeto 2 está dada por:
>
> $$ \mathbf{F}_{12} = k_e \frac{q_1 q_2}{d^2} \mathbf{\hat{r}}_{2} $$



## 5.2 Carga eléctrica y el campo eléctrico: expresión y cálculo del campo eléctrico

#### Calcular el campo eléctrico en el caso unidimensional a partir de la carga de la partícula y de la fuerza que se ejerce sobre ella.
> La ecuación del campo eléctrico detectado por una carga eléctrica de prueba $q_0$ está dado por:
>
> $$ \mathbf{E} = \frac{\mathbf{F}}{q_0} $$
>
> En una dimensión, esto es igual a:
>
> $$ E = \frac{F}{q_0} $$


## 5.3 Corriente eléctrica: Ley de Ohm

#### Aplicar la ley de Ohm en circuitos simples.
> - La ley de Ohm relaciona el voltaje y la corriente eléctrica a través de una constante de proporcionalidad que es la resistencia.
>
> $$ \Delta V = IR $$
>
> En un circuito en serie, la corriente se mantiene igual, mientras que el voltaje depende de cada elemento del circuito. La resistencia total se calcula sumando las resistencias individuales. Conociendo la corriente, se puede calcular la caída de voltaje para cada resistencia.
>
> $$ R_T = \sum R $$
>
> En un circuito en paralelo, el voltaje se mantiene igual y la corriente se divide entre los dos caminos, manteniendo el total.
>
> $$ I_T = \sum I $$
>
> El recíproco de la resistencia total es igual a la suma de los recíprocos de las resistencias individuales.
>
> $$ \frac{1}{R_T} = \sum \frac{1}{R} $$
>


# 6. Magnetismo


## 6.1 Ley de Ampere

#### Resolver la ley de Ampere.
> La ley de Ampère relaciona el campo magnético a lo largo de un trayecto cerrado con la corriente que pasa a través de ese trayecto.
>
> $$ \oint \mathbf{B} \cdot \mathrm{d} \mathbf{s} = \mu_0 I $$
>
> Si tomamos por ejemplo un cable coaxial de longitud infinita y hacemos pasar por él una corriente constante $I$. Entonces, el campo magnético generado forma círculos concéntricos alrededor del cable. Los vectores $\mathbf{B}$ y $\mathrm{d} \mathbf{s}$ son paralelos y apuntan en el mismo sentido en cualquier punto. Además la magnitud $B$ es constante a lo largo de cualquier circunferencia. Entonces, tenemos:

> $$
> \begin{aligned}
> \oint \mathbf{B} \cdot \mathrm{d} \mathbf{s} = \mu_0 I \\
> \oint B \mathrm{d} s = \mu_0 I \\
> B \oint \mathrm{d} s = \mu_0 I \\
> 2 \pi r B = \mu_0 I \\
> B = \frac {\mu_0 I}{2 \pi r} \\
> \end{aligned}
> $$
>