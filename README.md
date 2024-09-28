# Soma de Matrizes

A soma de matrizes é uma operação matemática que consiste em adicionar duas matrizes de mesmas dimensões. Para que a soma seja válida, ambas as matrizes devem ter o mesmo número de linhas e colunas.

## Como Funciona

Dadas duas matrizes \( A \) e \( B \), onde:

$$
A = \begin{pmatrix}a_{11} & a_{12} & \ldots & a_{1n} \\a_{21} & a_{22} & \ldots & a_{2n} \\\vdots & \vdots & \ddots & \vdots \\a_{m1} & a_{m2} & \ldots & a_{mn}\end{pmatrix}
$$$$
B = \begin{pmatrix}b_{11} & b_{12} & \ldots & b_{1n} \\b_{21} & b_{22} & \ldots & b_{2n} \\\vdots & \vdots & \ddots & \vdots \\b_{m1} & b_{m2} & \ldots & b_{mn}\end{pmatrix}
$$

A soma \( C = A + B \) resulta em uma nova matriz \( C \) dada por:

$$
C = \begin{pmatrix}c_{11} & c_{12} & \ldots & c_{1n} \\c_{21} & c_{22} & \ldots & c_{2n} \\\vdots & \vdots & \ddots & \vdots \\c_{m1} & c_{m2} & \ldots & c_{mn}\end{pmatrix}
$$

onde cada elemento \( c_{ij} \) é calculado da seguinte forma:

$$
c_{ij} = a_{ij} + b_{ij}
$$

## Exemplo

Se temos as matrizes:

$$
A = \begin{pmatrix}1 & 2 \\3 & 4\end{pmatrix}
$$$$
B = \begin{pmatrix}5 & 6 \\7 & 8\end{pmatrix}
$$

A soma \( C = A + B \) é:

$$
C = \begin{pmatrix}1 + 5 & 2 + 6 \\3 + 7 & 4 + 8\end{pmatrix} = \begin{pmatrix}6 & 8 \\10 & 12\end{pmatrix}
$$

## Propriedades

1. **Comutativa**: \( A + B = B + A \)
2. **Associativa**: \( (A + B) + C = A + (B + C) \)
3. **Elemento Neutro**: Existe uma matriz zero \( O \) tal que \( A + O = A \).
4. **Inverso Aditivo**: Para cada matriz \( A \), existe uma matriz \( -A \) tal que \( A + (-A) = O \).

Essas propriedades tornam a soma de matrizes uma operação bem estruturada e fundamental na álgebra linear!
