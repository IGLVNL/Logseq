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
                                          a | r ∧ a | s  en  ℤ – {0}
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