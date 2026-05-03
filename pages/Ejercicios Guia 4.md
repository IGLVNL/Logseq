### 1) Halle cociente y resto de la división entera de a por b en los siguientes casos:
	- Nota: 
	       A = c * B + r
	       c = ent( A / B )
	       r = mant( A / B ) * B
	- a) a = 3456  b = 35         
	    ***Ambos Positivos*: la mantisa es la parte decimal**
		- c = ent( 3456 / 35 ) = 98
		  r = mant( 3456 / 35 ) * 35 = 26
	- b) a = 1898  b = -41        
	    ***Divisor Negativo*: se le cambia el signo al cociente**
		- c' = ent( 1898 / 41) = 46 ⇒ c = -46
		  r = mant( 1898 / 41) * 41= 12
	- c) a = -836   b = 21          
	   ***Dividendo Negativo*: 
	        La mantisa es lo que le falta para llegar al entero siguiente hacia los negativos
	        La parte entera es el entero siguiente hacia los negativos**
		- c = ent( -836/ 21) = -40
		  r = mant( -836/ 21) * 21 = 4
	- d) a = -915   b = -63
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
- ### Analice la validez de las siguientes proposiciones, demostrando o justificando:
	- a) ∀ a, b, c ∈ ℤ:  a │ (b + c) ⇒ a │ b ∨ a │ c
		- *Contraejemplo:* 5 | (7 + 3) ⇒ 5 | 7 ∨ 5 | 3
		  `Falso`
	- b) ∀ x, y  ∈ ℤ:  x │ y ∧ y │ x  ⇒  x = y
		- ∀ x, y  ∈ ℤ: x │ y ∧ y │ x  ⇒
		  y = x * a ∧ x = y * b ∧ a, b ∈ ℤ ⇒
		  y - x = x * a - y * b ∧ a, b ∈ ℤ ⇒
	- c) ∀ m, n, p  ∈ ℤ:  m │ n   ∧  m │ p  ⇒  m │ ( n – p )
	- d) ∀ x, y, c  ∈ ℤ:    x │ y  ⇒  x │ c y
	- e) ∀ a, b, c ∈ ℤ:   a ≠ 0  ∧  a │ ( b+c )   ∧  a │ b  ⇒  a│c
	- f) ∀ a, b, n  ∈ ℤ:  n │ x y  ⇒  n │ x   ∨   n │ y
	- g) ∀ a, b, c  ∈ ℤ:  a | b   ∨  a | c  ⇒  a | (b + c)