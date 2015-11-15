# P R I M E R O S    P A S O S

# R como una Calculadora  


```r
1+2         # Sumas
```

```
## [1] 3
```

```r
2-4         # Restas
```

```
## [1] -2
```

```r
4*5         # Multiplicación
```

```
## [1] 20
```

```r
4/5         # División
```

```
## [1] 0.8
```

```r
5^2         # Potencia
```

```
## [1] 25
```

```r
5**2        # Otra de Potencia
```

```
## [1] 25
```

```r
sqrt(25)    # Raíz cuadrada
```

```
## [1] 5
```

```r
8^(1/3)     # Raíz cubica
```

```
## [1] 2
```

```r
factorial(5)
```

```
## [1] 120
```

```r
1*2*3*4*5   # Factorial
```

```
## [1] 120
```

```r
abs(-3)     # valor absoluto
```

```
## [1] 3
```

```r
exp(1)      # Exponencial "e"
```

```
## [1] 2.718282
```

```r
pi          # Valor de pi 
```

```
## [1] 3.141593
```

```r
sin(60)     # Seno
```

```
## [1] -0.3048106
```

```r
cos(60)     # Coseno
```

```
## [1] -0.952413
```

```r
tan(0.5)    # Tangente
```

```
## [1] 0.5463025
```
  
# Para generar secuencias  
  

```r
1:10  # secuencia del 1 al 10, en uno por uno
```

```
##  [1]  1  2  3  4  5  6  7  8  9 10
```

```r
10:1  # secuencia inversa
```

```
##  [1] 10  9  8  7  6  5  4  3  2  1
```

```r
-5:5
```

```
##  [1] -5 -4 -3 -2 -1  0  1  2  3  4  5
```

```r
seq(1,10,1)  # función para hacer secuencias 1 inicio, 10 final y 1 separación.
```

```
##  [1]  1  2  3  4  5  6  7  8  9 10
```

```r
seq(1,10,0.5)
```

```
##  [1]  1.0  1.5  2.0  2.5  3.0  3.5  4.0  4.5  5.0  5.5  6.0  6.5  7.0  7.5
## [15]  8.0  8.5  9.0  9.5 10.0
```

```r
seq(-5,5,0.2)
```

```
##  [1] -5.0 -4.8 -4.6 -4.4 -4.2 -4.0 -3.8 -3.6 -3.4 -3.2 -3.0 -2.8 -2.6 -2.4
## [15] -2.2 -2.0 -1.8 -1.6 -1.4 -1.2 -1.0 -0.8 -0.6 -0.4 -0.2  0.0  0.2  0.4
## [29]  0.6  0.8  1.0  1.2  1.4  1.6  1.8  2.0  2.2  2.4  2.6  2.8  3.0  3.2
## [43]  3.4  3.6  3.8  4.0  4.2  4.4  4.6  4.8  5.0
```

```r
rep(1,10)   # función que repite un valor o lectra, n-veces
```

```
##  [1] 1 1 1 1 1 1 1 1 1 1
```

```r
rep("A",5)
```

```
## [1] "A" "A" "A" "A" "A"
```

```r
rep(c("A","B","C"),3)
```

```
## [1] "A" "B" "C" "A" "B" "C" "A" "B" "C"
```

# Funciones para pedir ayuda
  

```r
?rnorm
```

```
## starting httpd help server ... done
```

```r
help(mean)
```

