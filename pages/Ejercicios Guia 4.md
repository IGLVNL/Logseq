### 1) Halle cociente y resto de la división entera de a por b en los siguientes casos:
	- Nota: 
	       A = c * B + r
	       c = ent( A / B )
	       r = mant( A / B ) * B
	- a) a = 3456  b = 35         
	  collapsed:: true
	    ***Ambos Positivos*: la mantisa es la parte decimal**
		- c = ent( 3456 / 35 ) = 98
		  r = mant( 3456 / 35 ) * 35 = 26
	- b) a = 1898  b = -41        
	  collapsed:: true
	    ***Divisor Negativo*: se le cambia el signo al cociente**
		- c' = ent( 1898 / 41) = 46 ⇒ c = -46
		  r = mant( 1898 / 41) * 41= 12
	- c) a = -836   b = 21          
	  collapsed:: true
	   ***Dividendo Negativo*: 
	        La mantisa es lo que le falta para llegar al entero siguiente hacia los negativos
	        La parte entera es el entero siguiente hacia los negativos**
		- c = ent( -836/ 21) = -40
		  r = mant( -836/ 21) * 21 = 4
	- d) a = -915   b = -63
	  collapsed:: true
	  ***Ambos Negativos*: 
	        La mantisa es lo que le falta para llegar al entero siguiente hacia los negativos
	        La parte entera es el entero siguiente hacia los negativos**
		- c' = ent( -915 / -63) = 14 ⇒ c = -15
		  r = mant( -915 / -63) * 63 = 30
- ### 2) Responder las siguientes cuestiones, justificando:
	- a) Si el cociente y el resto de la división entera entre “b” y 8 son q y k, respectivamente 
	  collapsed:: true
	  ¿cuál es el cociente y el resto de la división por 8 de 8.b - 75?
		- b = 8 * q + k
		  D = 8 * b -75
		  D = 8 * c + r
		  r = ?
		  c = ?
		  8 * b -75 = 8 * c + r
		  8 * (8 * q + k) -75 = 8 * c + r
		  8 * (8 * q + k) -80 + 5 = 8 * c + r
		  8 * (8 * q + k) - 80 = 8 * c   ∧   r  =  5
		  ` 8 * q + k - 10 = c   ∧   r  =  5 `
	- b) Si el resto de la división entera entre “b” y 6 es 2 , ¿cuál es el resto de la división entre 4.b - 22 y 3?
	  collapsed:: true
		- b = 6 * c + 2
		  D = 4 * b - 22
		  D = 3 * c' + r
		  r = ?
		  c' = ?
		  4 * b - 22 = 3 * c' + r
		  4 * (6 * c + 2) - 22 = 3 * c' + r
		  4 * (6 * c + 2) - 23 + 1 = 3 * c' + r
		  4 * (6 * c + 2) - 23 = 3 * c' ∧  r = 1
		  4 * 6 * c + 4 *2 - 23 = 3 * c' ∧  r = 1
		  24 * c + 8 - 23 = 3 * c' ∧  r = 1
		  24 * c - 15 = 3 * c' ∧  r = 1
		  `8 * c - 5 = c' ∧  r = 1`
- ### 3) Analice la validez de las siguientes proposiciones, demostrando o justificando:
	- a) ∀ a, b, c ∈ ℤ:  a │ (b + c) ⇒ a │ b ∨ a │ c
	  collapsed:: true
		- *Contraejemplo:* 5 | (7 + 3) ⇒ 5 | 7 ∨ 5 | 3
		  `Falso`
	- b) ∀ x, y  ∈ ℤ:  x │ y ∧ y │ x  ⇒  x = y
	  collapsed:: true
		- *Contraejemplo:* 1 | -1 ∧ -1 │ 1 ⇒ 1 = -1
		  `Falso`
	- c) ∀ m, n, p  ∈ ℤ:  m │ n   ∧  m │ p  ⇒  m │ ( n – p )
	  collapsed:: true
		- ∀ m, n, p  ∈ ℤ:  m │ n ∧ m │ p  ⇒
		  n = m * k ∧ p = q * m ∧ k, q ∈ ℤ⇒
		  (n - p) = (m * k - q * m) ∧ k, q ∈ ℤ⇒
		  (n - p) = m * (k - q) ∧ k, q ∈ ℤ⇒
		  (n - p) = m * j ∧ j ∈ ℤ⇒
		   m | (n - p)
		  `Verdadero`
	- d) ∀ x, y, c  ∈ ℤ:  x │ y  ⇒  x │ c * y
	  collapsed:: true
		- ∀ x, y, c  ∈ ℤ:  y = x * q  ⇒  c * y = x * k
		  ⇒ c * y
		  ⇒ c *  (x * q)     **por hipótesis**
		  ⇒ x * c * q
		  ⇒ x * k
		  `Verdadero`
	- e) ∀ a, b, c ∈ ℤ:   a ≠ 0  ∧  a │ ( b+c )   ∧  a │ b  ⇒  a│c
	  collapsed:: true
		- ∀ a, b, c ∈ ℤ:   a ≠ 0  ∧  a │(b + c) ∧ a │ b  ⇒  a│c
		  a │(b + c) ∧ a │ b ⇒
		  b + c = a * k ∧ b = a * q  ∧ k, q ∈ ℤ ⇒
		  b - b + c = a * k - a * q  ∧ k, q ∈ ℤ ⇒
		   c = a * (k - q)  ∧ k, q ∈ ℤ ⇒
		   c = a * j ∧ j ∈ ℤ ⇒
		   a | c
		  `Verdadero`
	- f) ∀ a, b, n  ∈ ℤ:  n │ x * y  ⇒  n │ x ∨ n │ y
	  collapsed:: true
		- 6 | 2 * 3   ⇒  6 │ 2 ∨ 6 │ 3
		  id:: 69f77b8a-6456-4b27-a31c-2a7cd9269aa9
		  `Falso`
	- g) ∀ a, b, c  ∈ ℤ:  a | b   ∨  a | c  ⇒  a | (b + c)
	  collapsed:: true
		- 2 | 2 ∨ 2 | 3 ⇒  2 | (2 + 3)
		  `Falso`
- ### 4) Indique de las siguientes opciones, la que se desprende necesariamente de: 
                                          *a | r ∧ a | s  en  ℤ – {0}*
	- a) a  |  (r + s –1)
	  collapsed:: true
		- 3 | 6 ∧ 3 | 12 ⇒ 3 | 6 + 12 -1
		  `Falso`
	- b) a  |  (r$^2$ + 3.s + 1)
	  collapsed:: true
		- 3 | 3 ∧ 3 | 12 ⇒ 3 | 3 $^2$ + 3*12 + 1 = 9 + 36 + 1 = 
		  `Falso`
	- c) a  |  r $^2$ + 3.s
	  collapsed:: true
		- r = a * k ∧ s = a * q ∧ k, q ∈ ℤ  – {0} ⇒ r $^2$ + 3.s = a * m ∧ m ∈ ℤ 
		  r = a * k ∧ s = a * q ⇒
		  r$^2$ = a$^2$ * k$^2$ ∧ 3 * s =  3 * a * q ⇒
		  r$^2$ = a * a * j ∧ 3 * s =  a * (3 * q) ⇒
		  r$^2$ = a * N ∧ 3 * s =  a * L ⇒
		  r$^2$ + 3 * s =  a * N + a * L ⇒
		  r$^2$ + 3 * s =  a * (N + L) ⇒
		  r$^2$ + 3 * s =  a * O ⇒
		  a | r$^2$ + 3 * s
		  `Verdadero`
	- d) a  |  r. s + 1
	  collapsed:: true
		- 3 | 3 ∧ 3 | 12 ⇒ 3 | 3 * 12 + 1 = 37
		  `Falso`
- ### 5) Halle m.c.d.(a, b) y m.c.m.(a,b) para los siguientes casos y escriba cada uno de los m.c.d. calculados como combinación lineal entera de a y b:
	- a) a=224    b=120
	  collapsed:: true
		- a = 224 = 2$^4$ * 7
		  b = 120 = 2$^3$ * 5 * 3
		  mcm = 7 * 5 * 3 * 2$^4$
		  `mcm = 1680`
		  |224 * 120| = mcm * mcd
		  mcd = |224 * 120| / mcm  =  26880 / 1680
		  `mcd = 16`
	- b) a=300    b=168
	  collapsed:: true
		- a = 300 = 3 * 5$^2$ * 2$^2$
		  b = 168 = 7 * 3 * 2$^3$
		  mcm = 7 * 3 * 2$^3$ * 5$^2$
		  `mcm = 4200`
		  |300 * 168| = mcm * mcd
		  mcd = |300 * 168| / mcm  =  50400 / 4200
		  `mcd = 12`
	- c) a=162    b=-48
	  collapsed:: true
		- a = 162 = 3$^4$ * 2
		  b = -48 = 3 * 2$^4$
		  mcm = 3$^4$ * 2$^4$
		  `mcm = 1296`
		  |162* 48| = mcm * mcd
		  mcd = |162* 48| / mcm  =  7776 / 1296
		  `mcd = 6`
	- d) a=525    b=-124
	  collapsed:: true
		- a = 525= 3 * 7 * 5$^2$
		  b = 124= 31 * 2$^2$
		  mcm = 3 * 7 * 5$^2$ * 31 * 4
		  `mcm = 65100`
		  |162* 48| = mcm * mcd
		  mcd = |525* 124| / mcm  =  65100/ 65100
		  `mcd = 1`   **Son Coprimos**
- ### 6) Calcule los enteros a y b sabiendo que son coprimos y que los cocientes sucesivos de la aplicación del Algoritmo de Euclides para hallar el m.c.d.(a,b) son: 2, 5, 11, 1, 1 y 3 (incluyendo la que da resto cero).
  collapsed:: true
	- *Planteo inicial*
	  collapsed:: true
		- b = a * 2 + r1
		  a = r1 * 5 + r2
		  r1 = r2 * 11 + r3
		  r2 = r3 * 1 + r4
		  r3 = r4 * 1 + r5
		  r4 = r5 * 3 + r6
	- *Resolución (despejando de atrás hacia adelante)*
	  collapsed:: true
		- b = a * 2 + r1 ⇒ b = 412 * 2 + 81 ⇒ `b = 905`
		  a = r1 * 5 + r2 ⇒ a = 81 * 5 + 7 ⇒ `a = 412`
		  r1 = r2 * 11 + r3 ⇒ r1 = 7 * 11 + 4 ⇒ r1 = 81
		  r2 = r3 * 1 + r4 ⇒ r2 = 4 * 1 + 3 ⇒ r2 = 7
		  r3 = r4 * 1 + 1 ⇒ r3 = 3 * 1 + 1 ⇒ r3 = 4
		  r4 = 1 * 3 + 0 ⇒ r4 = 3
- ### 7) Siendo Dn= { x ∈ ℕ / x│n}:
	- a) Halle D75, D36, D42
	  collapsed:: true
		- D75 = {1 , 3 , 5 , 15 , 25 , 75}
		- D36 = {1 , 2 , 3 , 4 , 6 , 9 , 12 , 18 , 36}
		- D42 = {1 , 2 , 3 , 6 , 7 , 14 , 21 , 42}
	- b) Encuentre el menor número natural n tal que │Dn│ = 8  y halle un valor de n natural y n > 100 tal que  │Dn│ = 2
	  collapsed:: true
		- D24= {1 , 2 , 3 , 4 , 6 , 8 , 12 , 24} `n = 24`
		- D101 = {1 , 101} `n = 101`
	- c) Si consideramos el conjunto de divisores positivos propios de n, es decir todos menos 
	  collapsed:: true
	  el mismo n:   D*$_{n}$ = { x ∈ ℕ / x │ n ∧ x < n}, halle algún número perfecto sabiendo 
	  que se llama así a los que son iguales a la suma de sus divisores positivos propios.
		- D*$_{6}$ = {1 , 2 , 3}
- ### 8) Indique el valor de verdad de las siguientes proposiciones, justificando o demostrando:
	- a) Es posible hallar dos enteros no coprimos a y b tales que 1 = s a + t b  con s,t ∈ ℤ
	  collapsed:: true
		- `Falso` 
		  Si a y b son coprimos, entonces, por Teorema de Bezout, se puede escribir una ecuación formada por la combinación lineal entre a y b, ambos multiplicados por 2 enteros s y t, igualada a 1
	- b) [ ∃ s, t ∈ ℤ / 3 = s a + t b ] ⇒ m.c.d.(a,b) = 3
	  collapsed:: true
		- `Falso`
		  3 =  2 * 2 - 1 * 1⇒ m.c.d.(2,1) ≠ 3
	- c) ∀ a, b ∈ ℕ:  si a y b son coprimos ∧ c | a  entonces b y c son coprimos.
	  collapsed:: true
		- ∀ a, b ∈ ℕ:  m.c.d.(a,b) = 1 ∧ c | a ⇒ m.c.d.(c,b) = 1
		  ∀ a, b ∈ ℕ:  (1 = a * s + b * t) ∧ (a = c * k) ⇒ (1 = c * n + b * m)
		  1 ⇒
		  a * s + b * t ⇒          **por hipotesis**
		  c * k * s + b * t ⇒        **por hipotesis**
		  c * n + b * t
		  `Verdadero`
	- d) ∀ a, b  ∈ ℤ:  m.c.d.(2a, 4b) = 4 ⇒ m.c.d.(a,b) = 2
	  collapsed:: true
		- m.c.d.(2*2, 4*3) = 4 ⇒ m.c.d.(2,3) = 1
		  m.c.d.(4, 12) = 4 ⇒ m.c.d.(2,3) ≠ 2
		  `Falso`
	- e)  ∀ a, b  ∈ ℤ:  m.c.d.(a, b) = 1 ⇒ m.c.d.(a+b , ab) = 1
		- ∀ a, b  ∈ ℤ:  a*n + b*m = 1 ⇒ (a+b)*k + (a*b)*J = 1
		  1 = (a + b - b) * n + b * m = 
		  a * n  + b * n  - b * n + b * m =
		  (a + b) * n  + b * (m - n)
		  
		  1 = a * n + (a - a + b) * m =     **análogamente**
		  a * n + a * m - a * m + b * m =
		  a * (n - m) + (a + b) * m =
		  a * (n - m) + (a + b) * m
		  **multiplicando ambos resultados**
		  (a + b) * n *  a * (n - m)  + b * (m - n) *  a * (n - m) + (a + b) * n * (a + b) * m  + b * (m - n) * (a + b) * m    =
		  (a + b) * n *  a * (n - m) +(a + b) * n * (a + b) * m +b * (m - n) * (a + b) * m + b * (m - n) *  a * (n - m)   =
		  (a + b)$^2$ * n * m     +     (a + b) * (n - m) * [n *  a  -   b  * m]    +     a * b * (n - m)$^2$    =
		- `PREGUNTAR`
	- f) ∀ a, b ∈ ℕ  (a>b) :  m.c.d.(a,b) =1 ⇒ m.c.d.(a, a-b) = 1
	  collapsed:: true
		- m.c.d.(a,b) = 1 ⇒ m.c.d.(a, a-b) = 1
		  a * J + b * k = 1 ⇒ a * n + (a-b) * m = 1
		  a * J + b * k = 1 ⇒
		  a*J  + (a - a + b) * k = 1 ⇒
		  a*J  + a*k - a*k + b*k  = 1 ⇒
		  a*(J + k) + (-a + b)*k  = 1 ⇒
		  a*(J + k) - (a - b)*k  = 1 ⇒
		  a*n + (a - b)*L  = 1 ⇒
		  m.c.d.(a, a-b)  = 1
		  `Verdadero`
	- g)  Si a = b q + r  con 0 $\leq$ r < b  ⇒ m.c.d.(a,b) = m.c.d.(b,r)
	  collapsed:: true
		- b | a ⇒ m.c.d.(a,b) = m.c.d.(b,r)
		  `Verdadero`  **por propiedad**
	- h) Sea d = m.c.d.(a,b) ⇒ Los enteros x = a/d  y   z = b/d  son coprimos
	  collapsed:: true
		- d = a*J + b*R ⇒ a/d * n + b/d * m = 1
		  d/d = a*J/d + b*R/d ⇒
		  1 = a/d*J + b/d*R ⇒
		  1 = mcd(a/d+ b/d)
		  `Verdadero`
	- i) ∀ a ∈ ℤ:  x =(a+1)$^2$  e  y= a(a+2)  son coprimos
	  collapsed:: true
		- x = (a+1)$^2$ ∧ y = a*(a+2) ⇒ x * n + y*m = 1
		  a$^2$ + 2*a + 1 -  a$^2$-2*a = 1 ⇒ 
		  x - y = 1 ⇒
		  1*x + (-1)*y = 1
		  `Verdadero`