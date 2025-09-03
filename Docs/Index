
---
layout: default
---

<script type="text/javascript"
  async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# Resumen del curso de Análisis

## BLOQUE 1: ÁLGEBRA LINEAL

### 1. Espacio Vectorial
Un *espacio vectorial* sobre \( \mathbb{R} \) es un conjunto \( V \) junto con dos operaciones: suma de vectores y multiplicación por escalares, que cumplen ocho axiomas. Ejemplo: \( \mathbb{R}^n \).

### 2. Subespacios
\( W \subseteq V \) es subespacio si está cerrado bajo suma y multiplicación escalar, y contiene el vector cero.

### 3. Combinaciones Lineales
\( \sum_{i=1}^k \alpha_i v_i \) es una combinación lineal. El conjunto de estas forma el subespacio generado.

### 4. Independencia Lineal
\( \{v_1, ..., v_k\} \) es independiente si \( \sum \alpha_i v_i = 0 \) solo si todos los \( \alpha_i = 0 \).

### 5. Base y Dimensión
Una base es un conjunto generador e independiente. Su tamaño es la dimensión del espacio.

### 6. Aplicaciones Lineales
\[
T(\alpha u + \beta v) = \alpha T(u) + \beta T(v)
\]
- Núcleo: \( \ker T = \{v : T(v) = 0\} \)
- Imagen: \( \text{Im}(T) = \{T(v)\} \)

### 7. Teorema Fundamental
\[
\dim(\ker T) + \dim(\text{Im} T) = \dim V
\]

### 8. Representación Matricial
\( T(x) = A x \)

---

## BLOQUE 2: DIFERENCIABILIDAD EN \(\mathbb{R}\) Y \(\mathbb{R}^n\)

### 1. Derivada en \(\mathbb{R}\)
\[
f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}
\]

### 2. Derivadas Parciales y Gradiente
\[
\frac{\partial f}{\partial x_i}(a) = \lim_{h \to 0} \frac{f(a + h e_i) - f(a)}{h}
\]
\[
\nabla f(a) = (\partial f / \partial x_1, ..., \partial f / \partial x_n)
\]

### 3. Diferenciabilidad
\[
\lim_{h \to 0} \frac{f(a+h) - f(a) - L(h)}{\|h\|} = 0
\]

### 4. Teoremas Clave

- **TVM** en \(\mathbb{R}\):  
  \[
  f'(c) = \frac{f(b) - f(a)}{b - a}
  \]

- **TVM** en \(\mathbb{R}^n\):  
  \[
  f(x) - f(a) = \nabla f(c) \cdot (x - a)
  \]

- **TVI**:  
  \[
  \exists c \in (a,b): f(c) = y
  \]

---

## BLOQUE 3: TEOREMAS CLÁSICOS

### 1. Teorema de Schwarz
\[
\frac{\partial^2 f}{\partial x_i \partial x_j} = \frac{\partial^2 f}{\partial x_j \partial x_i}
\]

### 2. Función Implícita
Si \( D_yF \) es invertible, existe \( y = g(x) \) tal que \( F(x, g(x)) = 0 \).

### 3. Función Inversa
Si \( J_f(a) \) es invertible, \( f \) es localmente invertible y \( f^{-1} \in C^1 \).

---

## BLOQUE 4: TAYLOR Y PUNTOS CRÍTICOS

### 1. Hessiana
\[
H_f(a) = \left( \frac{\partial^2 f}{\partial x_i \partial x_j}(a) \right)
\]

### 2. Teorema de Taylor
\[
f(a+h) = f(a) + \nabla f(a) h + \frac{1}{2} h^T H_f(a) h + o(\|h\|^2)
\]

### 3. Clasificación de puntos críticos
- \( Q(h) > 0 \): mínimo
- \( Q(h) < 0 \): máximo
- \( Q \) cambia de signo: punto silla

---

## BLOQUE 5: INTEGRALES

### 1. Integral definida
\[
\int_a^b f(x)\,dx
\]

### 2. Teorema Fundamental
\[
F(x) = \int_a^x f(t)\,dt \Rightarrow F'(x) = f(x)
\]

### 3. Integral doble
\[
\iint_D f(x,y)\,dxdy
\]

### 4. Cambio de Variable
\[
\iint_D f(x,y)\,dxdy = \iint_U f(\phi(u,v)) |\det J_\phi|\,dudv
\]
