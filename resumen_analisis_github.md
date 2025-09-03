
# BLOQUE 1: ÁLGEBRA LINEAL

## 1. Espacio Vectorial
Un *espacio vectorial* sobre \( \mathbb{R} \) es un conjunto \( V \) junto con dos operaciones: suma de vectores y multiplicación por escalares, que cumplen ocho axiomas (asociatividad, conmutatividad, existencia de neutro y opuesto, distributividad, etc.). Ejemplo: \( \mathbb{R}^n \), espacio de funciones continuas, matrices de orden fijo.

## 2. Subespacios
Un subconjunto \( W \subseteq V \) es un *subespacio* si es cerrado bajo suma y multiplicación escalar, y contiene al vector cero. Todo subespacio de \( \mathbb{R}^n \) es un espacio vectorial.

## 3. Combinaciones Lineales y Generadores
Una *combinación lineal* de vectores \( v_1, \dots, v_k \) es una expresión del tipo \( \sum_{i=1}^k \alpha_i v_i \). El conjunto de todas las combinaciones lineales forma el *subespacio generado* por esos vectores.

## 4. Independencia Lineal
Un conjunto \( \{v_1, \dots, v_k\} \subset V \) es *linealmente independiente* si la única combinación lineal que da cero es la trivial (todas las constantes cero). Si existen coeficientes no todos cero que satisfacen \( \sum \alpha_i v_i = 0 \), los vectores son *dependientes*.

## 5. Base y Dimensión
Una *base* de un espacio vectorial \( V \) es un conjunto linealmente independiente que genera \( V \). La *dimensión* de \( V \) es el número de vectores en cualquier base.

## 6. Aplicaciones Lineales
Una *función lineal* (o aplicación lineal) \( T: V \to W \) cumple:

\(
T(\alpha u + \beta v) = \alpha T(u) + \beta T(v), \quad \forall u,v \in V, \alpha,\beta \in \mathbb{R}.
\)

- El *kernel* de \( T \) es el conjunto de vectores que van al cero: \( \ker(T) = \{v \in V : T(v) = 0\} \).
- La *imagen* de \( T \) es \( \text{Im}(T) = \{T(v) : v \in V\} \).

## 7. Teorema Fundamental del Álgebra Lineal
Si \( V \) es de dimensión finita, entonces:

\(
\dim(\ker T) + \dim(\text{Im} T) = \dim V.
\)

Este resultado permite conectar soluciones de sistemas lineales con la estructura del espacio.

## 8. Representación Matricial
Toda aplicación lineal entre espacios de dimensión finita se representa como multiplicación por una matriz: \( T(x) = A x \). Cambiar de base modifica la matriz asociada.

---

# BLOQUE 2: DIFERENCIABILIDAD EN \(\mathbb{R}\) Y \(\mathbb{R}^n\)

## 1. Derivada en \(\mathbb{R}\)
Para \( f: \mathbb{R} \to \mathbb{R} \), la derivada en \( a \in \mathbb{R} \) es el límite:

\(
f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}
\)

## 2. Derivadas Parciales y Gradiente
Para \( f: \mathbb{R}^n \to \mathbb{R} \), la derivada parcial respecto a \( x_i \) es:

\(
\frac{\partial f}{\partial x_i}(a) = \lim_{h \to 0} \frac{f(a + h e_i) - f(a)}{h}
\)

El gradiente es el vector:

\(
\nabla f(a) = \left( \frac{\partial f}{\partial x_1}(a), \dots, \frac{\partial f}{\partial x_n}(a) \right)
\)

## 3. Diferenciabilidad en \(\mathbb{R}^n\)
\(
\lim_{h \to 0} \frac{f(a + h) - f(a) - L(h)}{\|h\|} = 0
\)

Si existe tal transformación lineal \( L \), entonces \( f \) es diferenciable y \( L(h) = \nabla f(a) \cdot h \).

## 4. Teoremas: TVM y TVI

- **TVM en \(\mathbb{R}\):**
  \(
  f'(c) = \frac{f(b) - f(a)}{b - a}
  \)

- **TVM en \(\mathbb{R}^n\):**
  \(
  f(x) - f(a) = \nabla f(c) \cdot (x - a)
  \)

- **TVI:**
  \(
  \exists c \in (a,b) \text{ tal que } f(c) = y
  \)

---

_(El resto se continúa si lo deseas)_...
