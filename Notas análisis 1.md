# Notas análisis

### Vectores y Geometría del espacio

#### Distancia entre dos puntos

* Teorema de Pitágoras:
	$$
	d^2 = (a_2 - a_1)^2 + (b_2 - b_1)^2
	$$

+ DEF *dist(P, Q):* $\sqrt((a_1-a_2)^2 + (b_1 - b_2)^2)$

#### Círculos y Discos

* $P_0 = (a_0, b_0)$ ; $P = (x, y)$; $r > 0$

  El círculo de centro $P_0$ y radio r es el conjunto de todos los puntos P tales que $dist(p, p_0) = r$

$$
(x-a_0)^2 + (y-b_0)^2 = r^2
$$

#### Vectores

* Longitud: $\sqrt(a^2 + b^2 + c^2)$

  Si a es un vector no nulo, busco un vector de igual longitud y sentido de longitud 1. 
  $$
  u = \frac{a}{|a|}
  $$
  
* 

### Producto interno

$$
a, b \in \R^2\ \lor \R^3 \\
a \cdot b\\
a = <x_1, y_1, x_1>\\
b = <x_2, y_2, z_3>\\
a \cdot b = x_1*x_2 + y_1*y_2+z_1+z_2
$$

##### Propiedades:

* $a*a = |a| ^2$
* $a*b = b*a$
* $a*(b+c) = a*b + a*c$
* $(ta)*b = t(a*b)$

#### Teorema del coseno

$$
c^2 = a^2 + b^2 - 2 a b cos\theta
$$

$$
a \cdot b = |a||b|cos\theta
$$

donde $\theta$ es el ángulo más chico que forman los vectores.

##### Corolarios

* si $a, b \neq 0$

  * $$
    cos \theta = \frac{a\cdot b}{|a||b|}
    $$

* a y b ortogonales $\iff$ $a\cdot b = 0$

## Práctica 1

## ![image-20220706190321857](/home/juli/.config/Typora/typora-user-images/image-20220706190321857.png)

