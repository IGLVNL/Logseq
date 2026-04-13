### 1) Indique cuales de los siguientes enunciados son proposiciones lógicas:
	- collapsed:: true
	  
	  a) *El año 2004 tuvo 366 días.*
		- **Es proposición.**
	- collapsed:: true
	  
	  b) *Los divisores positivos de 135*
		- **No es proposición ya que no puede ser V o F.**
	- collapsed:: true
	  
	  c) *No pisar el césped*
		- **No es proposición ya que no puede ser V o F.**
	- collapsed:: true
	  
	  d) *Los divisores positivos de 135 son 8 en total.*
		- **Es proposición.**
	- e) $$2x+5=8$$
	  collapsed:: true
		- **No es proposición ya que su valor de verdad depende del valor de X. Es una función proposicional.**
	- collapsed:: true
	  
	  f) *La frase del ítem “c” es proposición lógica.*
		- **Es proposición.**
	- g) ∃x ∈ Z : 2x+5=8
	  collapsed:: true
		- **Es proposición.**
	- h) La ecuación $$ 2x+5=8 $$ tiene solución en *R*.
	  collapsed:: true
		- **Es proposición.**
- ### 2)  De las siguientes proposiciones lógicas, analice cuales son condicionales, escríbalas de forma “ Si …… entonces …….”  e  indique antecedente y consecuente:
	- a) El cuadrado de todo número par es también par.
	  collapsed:: true
		- *Si un numero es par entonces su cuadrado también es par*
			- Antecedente: **un numero es par**
			- Consecuente: **su cuadrado también es par**
	- b) Algunos números pares son también divisibles por 3.
	  collapsed:: true
		- *No es un condicional*
	- c) Para cursar Análisis II es necesario tener aprobada Análisis I.
	  collapsed:: true
		- *Si apruebo Análisis 1 entonces puedo cursar Análisis 2*
			- Antecedente: **apruebo Análisis 1**
			- Consecuente: **puedo cursar Análisis 2**
	- d) El resto de dividir 23456 por cuatro es cero.
	  collapsed:: true
		- *No es un condicional*
	- e) Es suficiente tener 3 ejercicios correctos para aprobar el examen.
	  collapsed:: true
		- *Si quiero aprobar el parcial entonces necesito tener 3 ejercicios correctos*
			- Antecedente: **quiero aprobar el parcial**
			- Consecuente: **necesito tener 3 ejercicios correctos**
- ### 3)  Analice lo pedido:
	- a) Sea  t: ( p ^ q => ~r )  ^ ~p   Sabiendo que v(t) = V  ¿se puede saber si *r* es 
	  collapsed:: true
	  Verdadera o Falsa? Justifique.
		- Si v(t) = V significa que v(~p) = V y v(p ^ q => ~r ) = V, entonces v(p) = F,  por lo que para que v(p ^ q => ~r ) = V, se pueden dar las siguientes posibilidades:
			- | p ^ q | ~r | p ^ q => ~r |
			  | F | V | V |
			  | F | F | V |
			  | V | V | V |
			- esto significa que *r* podria ser V o F, lo que indica que no se puede saber v(r)
	- b) Sea  t: ( ~p v q => ~r )  ^ ~p   Sabiendo que v(t) = V  ¿se puede saber si *r* es 
	  collapsed:: true
	  Verdadera o Falsa? Justifique.
		- Si v(t) = V significa que v(~p) = V y v(p ^ q => ~r ) = V, entonces v(p) = F,  y v(~p v q) = V, por lo que si v(~p v q => ~r ) = V y  v(~p v q) = V, entonces v(~r) = V, lo que indica que v(r) = F.
- ### 4)  Haciendo las tablas de verdad de las siguientes proposiciones, indique cuales son tautologías, contradicciones o contingencias:
	- a) q ∨ (q ∧ ~p ⇒ p)
	  collapsed:: true
		- | q | p |  ~p | q ∧ ~p | q ∧ ~p ⇒ p | q ∨ (q ∧ ~p ⇒ p) |
		  | F | V | F | F | V | V |
		  | F | F | V | F | V | V |
		  | V | V | F | F | V | V |
		  | V | F | V | V | F | V |
		- ***Tautología***
	- b) (p ⇒ q ∨ r) ∧ ~q ⇒ ~p ∨ r
	  collapsed:: true
		- | p | q |  r | ~p| ~q | ~p ∨ r | q ∨ r | p ⇒ q ∨ r | (p ⇒ q ∨ r) ∧ ~q | (p ⇒ q ∨ r) ∧ ~q ⇒ ~p ∨ r | 
		  | F | F | F | V | V | V | F | V | V | V |
		  | F | F | V | V | V | V | V | V | V | V |
		  | F | V | F | V | F | V | V | V | F | V |
		  | F | V | V | V | F | V | V | V | F | V |
		  | V | F | F | F | V | F | F | F | F | V |
		  | V | F | V | F | V | V | V | V | F | V |
		  | V | V | F | F | F | F | V | V | F | V |
		  | V | V | V | F | F | V | V | V | F | V |
		- ***Tautología***
	- c) ~(p ∧ q ⇒ r) ∧ (r ∨ ~p)
	  collapsed:: true
		- | p | q | r | ~p | r ∨ ~p | p ∧ q | p ∧ q ⇒ r | ~(p ∧ q ⇒ r) | ~(p ∧ q ⇒ r) ∧ (r ∨ ~p) |
		  | F | F | F | V | V | F | V | F | F |
		  | F | F | V | V | V | F | V | F | F |
		  | F | V | F | V | V | F | V | F | F |
		  | F | V | V | V | V | F | V | F | F |
		  | V | F | F | F | F | F | V | F | F |
		  | V | F | V | F | V | F | V | F | F |
		  | V | V | F | F | F | V | F | V | F |
		  | V | V | V | F | V | V | V | F | F |
		- ***Contradicción***
	- d) (p ⇒ q) ⇔ (q ⇒ p)
	  collapsed:: true
		- | p | q | p ⇒ q | q ⇒ p | (p ⇒ q) ⇔ (q ⇒ p) |
		  | F | F | V | V | V |
		  | F | V | V | F | F |
		  | V | F | F | V | F |
		  | V | V | V | V | V |
		- ***Contingencia***
	- e) (p ∨ q) ∧ ~(p ∧ q) ∧ (p ⇔ q)
	  collapsed:: true
		- | p | q | p ∨ q | p ∧ q | ~(p ∧ q) | p ⇔ q | (p ∨ q) ∧ ~(p ∧ q) ∧ (p ⇔ q) |
		  | F | F | F | F | V | V | F |
		  | F | V | V | F | V | F | F |
		  | V | F | V | F | V | F | F |
		  | V | V | V | V | F | V | F |
		- ***Contradicción***
- ### 5)  Utilizando las leyes lógicas, simplifique:
	- a) (p ∨ q) ⇒ [p ∨ (p ⇔ q)]
	  collapsed:: true
		- ~(p ∨ q) v  p ∨ (p ⇔ q)                        ***(equiv. condicional)***
		  id:: 69dc1ebe-4ff7-483a-8fa0-16d2265afcd0
		  ~(p ∨ q) v  p ∨ [(p ⇒ q) ^ (q ⇒ p)]       ***(equiv. bicondicional)***
		  (~p ^ ~q) v p ∨ [(p ⇒ q) ^ (q ⇒ p)]       ***(de Morgan)***
		  [(~p v p) ^ (~q v p)] ∨ [(p ⇒ q) ^ (q ⇒ p)]       ***(distributividad)***
		  [V ^ (~q v p)] ∨ [(p ⇒ q) ^ (q ⇒ p)]       ***(Tercero excluido)***
		  (~q v p) ∨ [(p ⇒ q) ^ (q ⇒ p)]                ***(Identidad)***
		  [~q v p ∨ (p ⇒ q)] ^ [~q v p ∨ (q ⇒ p)]       ***(distributividad)***
		  (~q v p ∨ ~p v q) ^ (~q v p ∨ ~q v p)     ***(equiv. condicional)***
		  (~q v V v q) ^ (~q ∨ ~q v p v p)   ***(Tercero excluido y Conmutatividad)***
		  V ^ (~q v p)      ***(Dominación e Idempotencia)***
		  ~q v p     ***(Identidad)***
	- b) ~[p ∨ (q ⇒ r)] ∨ ~q
	  collapsed:: true
		- ~(p ∨ ~q v r) ∨ ~q     ***(equiv. condicional)***
		  (~p ^ q ^ ~r) ∨ ~q      ***(de Morgan)***
		  (~p ∨ ~q) ^ (q ∨ ~q) ^ (~r ∨ ~q) ∨ ~q      ***(distributividad)***
		  (~p ∨ ~q) ^ V ^ (~r ∨ ~q)     ***(Tercero excluido)***
		  (~p ∨ ~q) ^ (~r ∨ ~q)     ***(Identidad)***
		  (~p ^ ~r ) ∨ ~q    ***(distributividad)***
		  ~(p v r ) ∨ ~q    ***(de Morgan)***
		  ~[(p v r) ^ q]    ***(de Morgan)***
	- c) (p ⇒ r ∨ q) ∧ (~q ∨ r)
	  collapsed:: true
		- (~p v r ∨ q) ∧ (~q ∨ r)     ***(equiv. condicional)***
		  [~p ∧ (~q ∨ r)] v [r ∧ (~q ∨ r)] ∨ [q ∧ (~q ∨ r)] ***(distributividad)***
		  [(~p ∧ ~q) ∨ (~p ∧ r)] v [(r ∧ ~q) ∨ (r ∧ r)] ∨ [q ∧ ~q ∨ (q ∧ r)] ***(distributividad)***
		  [(~p ∧ ~q) ∨ (~p ∧ r)] v [(r ∧ ~q) ∨ r] ∨ [F ∨ (q ∧ r)] ***(Ley de No Contradicción)***
		  (~p ∧ ~q) ∨ (~p ∧ r) v [(r ∧ ~q) ∨ r] ∨ (q ∧ r) ***(Identidad)***
		  (~p ∧ ~q) ∨ (~p ∧ r) v [(r v r) ^ (~q v r)] ∨ (q ∧ r) ***(distributividad)***
		  (~p ∧ ~q) ∨ (~p ∧ r) v [r ^ (~q v r)] ∨ (q ∧ r) ***(Idempotencia)***
		  (~p ∧ ~q) ∨ (~p ∧ r) v r ∨ (q ∧ r)     ***(Absorción)***
		  (~p ∧ ~q) ∨ (~p ∧ r) v r        ***(Absorción)***
		  (~p ∧ ~q) ∨ r        ***(Absorción)***
		  ~(p v q) ∨ r        ***(de Morgan)***
- ### 6)  Pruebe mediante el uso de leyes lógicas que las siguientes proposiciones son TAUTOLOGÍAS (Indique la ley usada en cada paso):
	- a) (p ⇒ q) ∧ t ⇔ ~(t ⇒ p) ∨ (q ∧ t)
	  collapsed:: true
		- | p | q | t | p ⇒ q |  (p ⇒ q) ∧ t  | t ⇒ p | ~(t ⇒ p) | q ∧ t | ~(t ⇒ p) ∨ (q ∧ t) | a) |
		  | F | V | F | V | F | V | F | F | F | V |
		  | F | V | V | V | V | V | F | V | V | V |
		  | F | F | F | V | F | V | F | F | F | V |
		  | F | F | V | V | F | V | F | F | F | V |
		  |V | V | F | V | F | V | F | F | F | V |
		  | V | V | V | V | V | V | F | V | V | V |
		  | V | F | F | F | F | V | F | F | F | V |
		  | V | F | V | F | F | V | F | F | F |  V |
	- b) ~(t ⇒ b) ∨ (a ∧ t) ⇔ t ∧ (b ⇒ a)
	  collapsed:: true
		- | a | b | t | t ⇒ b | ~(t ⇒ b) | a ∧ t | ~(t ⇒ b) ∨ (a ∧ t) | b ⇒ a | t ∧ (b ⇒ a) | b) |
		  | F | V | F | V | F | F | F | F | F | V |
		  | F | V | V | V | F | F | F | F | F | V |
		  | F | F | F |  V | F | F | F | V | F | V |
		  | F | F | V |  F | V | F | V | V | V | V |
		  | V | V | F |  V |  F | F | F | V | V | V |
		  | V | V | V | V | F | V | V | V | V | V |
		  | V | F | F |  V | F | F | F | V | V | V |
		  | V | F | V |  F | V | V | V | V | V | V |
	- c) [~(p ⇒ q) ∨ (p ∧ q) ⇔ q] ⇒ (~q ∨ p)
	  collapsed:: true
		- | p | q | p ⇒ q | ~(p ⇒ q) | p ∧ q | ~(p ⇒ q) ∨ (p ∧ q) | ~(p ⇒ q) ∨ (p ∧ q) ⇔ q | ~q | ~q ∨ p | c) |
		  | F | F | V | F  | F | F | V | V | V | V |
		  | F | V | V | F  | F | F | F | F | F | V |
		  | V | F | F |  V | F | V | F | V | V | V |
		  | V | V | V |  F | V | V | V | F | V | V |
- ### 7) Indique cuáles de las siguientes frases son funciones proposicionales o predicados, en caso afirmativo indique de cuántas variables y un conjunto universal:
	- a) x es un número positivo.
	  collapsed:: true
		- *Es función proposicional.* U : ($$x ∈ R^+$$)
	- b) 2x + 5 = y
	  collapsed:: true
		- *Es función proposicional de 2 variables.*  U : ($$x,y ∈ R $$)
	- c) La suma de x más el cuadrado de y
	  collapsed:: true
		- *No es función proposicional.*
	- d) x es de color blanco
	  collapsed:: true
		- *Es función proposicional.*  U : (todos los objetos de color)
	- e) 3(x + 4) - x² + 9
	  collapsed:: true
		- *No es función proposicional.*
	- f) x es hijo de y
	  collapsed:: true
		- *Es función proposicional de 2 variables.* U : (todas las personas de un edificio)
- ### 8) Dado el siguiente predicado:   p(x): “x es un número primo”, se pide:
	- a) Escribir las particularizaciones p(8), p(13) y p(1) e indicar sus valores de verdad.
	  collapsed:: true
		- p(8): 8 es un número primo
		  p(13): 13 es un número primo
		  p(1): 1 es un número primo
	- b) Escribir un conjunto U formado por 4 elementos en el cual  ∀x: p(x)  sea verdadera.
	  collapsed:: true
		- U : {1 , 2 , 3 , 5}
	- c) Escribir un conjunto U formado por 4 elementos en el cual  ∃x: p(x)  sea falsa.
	  collapsed:: true
		- U : {1 , 2 , 3 , 4}
- ### 9) Escriba en lenguaje simbólico usando cuantificadores y funciones proposicionales, las siguientes proposiciones, indicando asimismo el conjunto Universal correspondiente:
	- a) Todos los alumnos del curso K-10 trabajan por la mañana.
	  collapsed:: true
		- ∀x ∈ A: p(x) = x trabajan por la mañana. 
		  *A : (x / x es alumno del curso K-10)*
	- b) Algunos datos de los clientes están incompletos o desactualizados.
	  collapsed:: true
		- p(x) = x está incompleto, 
		  q(x) =  x está desactualizado,
		  ∃x ∈ A : [p(x) v q(x)]
		  *A : (x / x es un dato de los clientes)*
	- c) Los libros de la biblioteca tienen un código identificador y figuran en los archivos.
	  collapsed:: true
		- p(x) = x tiene un código identificador, 
		  q(x) =  x figura en los archivos,
		  ∀x ∈ A : [p(x) ∧ q(x)]
		  *A : (x / x es un libros de la biblioteca)*
- ### 10) Indique el valor de verdad, justificando:
	- a) ∃ x ∈ ℤ : 3x + 11 = 20
	  collapsed:: true
		- *Verdadero.* x = 3
	- b) ∀ x ∈ U : x² > 2   siendo U = {2, 3, -1, 5}
	  collapsed:: true
		- *Falso.* $$(-1)^2 < 2$$
	- c) ∀ x ∈ ℤ : x + x² es par
	  collapsed:: true
		- *Verdadero.*
	- d) ∃ x ∈ ℝ : x⁴ + 16 = 0
	  collapsed:: true
		- *Falso.*
- ### 11) Escriba la negación de las siguientes proposiciones:
	- a) ∃ x ∈ ℝ : x² = -9
	  collapsed:: true
		- $$∀ x ∈ ℝ : x²≠ -9$$
	- b) ∀ n ∈ ℕ : n + 4 < n³
	  collapsed:: true
		- $$∃ n ∈ ℕ : n + 4 >= n³$$
	- c) ∀ x ∈ ℝ : (x² > 0 ∨ x = 0)
	  collapsed:: true
		- $$∃x ∈ ℝ :  \sim(x² > 0 ∨ x = 0)$$
	- d) ∃ x ∈ ℤ : (x < 3 ⇒ x + 1 < 0)
	  collapsed:: true
		- $$∀ x ∈ ℤ : \sim(x < 3 ⇒ x + 1 < 0)$$
- ### 12) Considere el predicado o función proposicional:  p(x,y): x + y = 8   con dominio en el conjunto de los números enteros ℤ. Analice el valor de verdad de:
	- a) ∀ x : ∀ y : p(x, y)
		-
	- b) ∀ x : ∃ y : p(x, y)
	- c) ∃ x : ∀ y : p(x, y)
	- d) ∃ x : ∃ y : p(x, y)