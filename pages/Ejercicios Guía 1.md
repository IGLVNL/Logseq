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
	  collapsed:: true
		- *Falso.* 
		  x = 1; 
		  y = 1; 
		  1 + 1 ≠ 8
	- b) ∀ x : ∃ y : p(x, y)
	  collapsed:: true
		- *Verdadero.*
		  x = 10; 
		  y = -2; 
		  10 + (-2) = 8
	- c) ∃ x : ∀ y : p(x, y)
	  collapsed:: true
		- *Falso.*
	- d) ∃ x : ∃ y : p(x, y)
	  collapsed:: true
		- *Verdadero.* 
		  x = 7; 
		  y = 1; 
		  7 + 1 = 8
- ### 13) Analice el valor de verdad de las siguientes proposiciones con dos cuantificadores:
	- a) ∀ x ∈ U : ∃ y ∈ U : (x < y ∨ x < y²)   en U = {1, -2, 3, -4, 5, 0}
	  collapsed:: true
		- *Verdadero.*
	- b) ∀ x ∈ ℝ : ∀ y ∈ ℝ : (x > y ⇒ x² > y²)
	  collapsed:: true
		- *Falso.*
		  x = 2;
		  y = -4;
	- c) ∃ x ∈ ℝ : ∀ y ∈ ℝ : (x² > y² ⇒ x > y)
	  collapsed:: true
		- *Verdadero.*
- ### 14) Sabiendo que t : [∀ x : ∃ y : p(x,y)] es verdadera, indique si se puede asegurar el valor de verdad de:
	- a) ∀ x : ∀ y : p(x,y)
	  collapsed:: true
		- *No se puede asegurar*
	- b) ∃ y : ∀ x : p(x,y)
	  collapsed:: true
		- *No se puede asegurar*
	- c) ∃ x : ∃ y : p(x,y)
	  collapsed:: true
		- *seguro es VERDADERA*
	- d) ∃ x : ∀ y : ~p(x,y)
	  collapsed:: true
		- *seguro es FALSA*
- ### 15) Indique el valor de verdad, demostrando o justificando correctamente:
	- a) ∃x: p(x) ∧ ∃x: q(x)    es equivalente a    ∃x: [p(x) ∧ q(x)]
	  collapsed:: true
		- *No son equivalentes*
	- b) ∃x: p(x) ∨ ∃x: q(x)    es equivalente a    ∃x: [p(x) ∨ q(x)]
	  collapsed:: true
		- *Son equivalentes*
	- c) ∀x: p(x) ∨ ∀x: q(x)    es equivalente a    ∀x: [p(x) ∨ q(x)]
	  collapsed:: true
		- *Np son equivalentes*
	- d) ∀x: p(x) ∧ ∀x: q(x)    es equivalente a    ∀x: [p(x) ∧ q(x)]
	  collapsed:: true
		- *Son equivalentes*
- ### 16) Escriba en lenguaje simbólico los siguientes razonamientos, indicando el diccionario utilizado, y luego analice la validez de los mismos, demostrando por reglas de inferencia en caso de ser válidos y justificando en caso de ser inválidos:
	- a) Si me pagan el aguinaldo hoy, pagaré la deuda. Si me 
	  collapsed:: true
	  pagan el sueldo hoy, compraré los pasajes. Me pagan el 
	  sueldo o el aguinaldo hoy. Por lo tanto pagaré la deuda o 
	  compraré los pasajes.
		- p: *me pagan el aguinaldo hoy*
		  d: *pago deuda*
		  s: *me pagan el sueldo hoy*
		  c: *compro pasajes*
		  **p ⇒ d ; s ⇒ c ; s ∴ d ∨ c**
		  *v(s) = V*
		  *v(c) = V*
		  *v(p ⇒ d) = V*
		  *v(d) = F o V*
		  *v(d ∨ c) = V*
		  **El razonamiento es Valido**
	- b) Si no llueve y no hay viento entonces vuelo en el avión. 
	  collapsed:: true
	  Siempre que llueve me siento mal. Ayer no volé en el avión 
	  y me sentí bien. Por lo tanto, ayer estuvo ventoso.
		- e: *no llueve*
		  v: *no hay viento*
		  a: *vuelo en el avión*
		  m: *me siento mal*
		  **e ∧ v ⇒ a ; ~e ⇒ m ; ~a ∧ ~m ∴ ~v**
		  *v(~a ∧ ~m) = V*
		  *v(~a) = V*
		  *v(a) = F*
		  *v(~m) = V*
		  *v(m) = F*
		  *v(~e ⇒ m) = V*
		  *v(~e) = F*
		  *v(e) = V*
		  *v(e ∧ v ⇒ a) = V*
		  *v(e ∧ v) = F*
		  *v(v) = F*
		  *v(~v) = V*
		  **El razonamiento es Valido**
	- c) Si llueve, Pablo va al cine. Siempre que Pablo va al cine, 
	  collapsed:: true
	  compra pochoclo o helado. Pablo compra pochoclo. Por lo tanto, 
	  llueve.
		- v: *llueve*
		  c: *Pablo va al cine*
		  p: *compra pochoclo*
		  h: *compra helado*
		  **v ⇒ c ; c ⇒ p ∨ h ; p ∴ v**
		  *v(p) = V*
		  *v(v ⇒ c) = V*
		  *v(c) = V o F*
		  *v(v) = F o V*
		  **El razonamiento es Invalido**
	- d) El planeta Kamino no figura en los Archivos. Si un 
	  collapsed:: true
	  planeta no figura en los Archivos, es porque no existe o 
	  bien porque alguien lo borró. El planeta Kamino existe. 
	  Por lo tanto, alguien lo debe haber borrado del Archivo.
		- f: *no figura en los Archivos*
		  e: *no existe*
		  b: *alguien lo borró*
		  **f ; f ⇒ e ∨ b ; ~e ∴ b**
		  *v(~e) = V*
		  *v(e) = F*
		  *v(f) = V*
		  *v(f ⇒ e ∨ b) = V*
		  *v(e ∨ b) = V*
		  *v(b) = V*
		  **El razonamiento es Valido**
- ### 17) Analice si los siguientes razonamientos son válidos o inválidos, demostrando o justificando según corresponda por el método del condicional asociado:
	- a) ~p ; q ⇒ t ∨ r ; t ⇒ p ∴ q ⇒ r
	  collapsed:: true
		- (~p) ∧ (q ⇒ t ∨ r) ∧ (t ⇒ p) ⇒ (q ⇒ r)
		  ~p ⟶ V, **p ⟶ F**
		  q ⇒ r ⟶ F, ***q ⟶ V***, **r ⟶ F**
		  t ⇒ p ⟶ V, **t ⟶ F**
		   q ⇒ t ∨ r ⟶ V, t ∨ r ⟶ F, ***q ⟶ F***
		  *Contradicción en q*
		  **El razonamiento es Válido**.
	- b) (p ∧ q) ⇒ r ; ~r ∨ t ; ~t ∴ ~p
	  collapsed:: true
		- [(p ∧ q) ⇒ r] ∧ (~r ∨ t) ∧ ~t ⇒ ~p
		  ~p ⟶ F, **p ⟶V**
		  ~t ⟶ V, **t ⟶ F**
		  (~r ∨ t) ⟶ V, ~r ⟶ V, **r ⟶ F**
		   (p ∧ q) ⇒ r ⟶ V,  (p ∧ q) ⟶ F, **q ⟶ F**
		  *Tautología*
		  **El razonamiento es Inválido**.
	- c) a ⇒ b ; ~b ∨ ~c ; d ⇒ a ∨ c ∴ ~d
	  collapsed:: true
		- (a ⇒ b) ∧ (~b ∨ ~c) ∧ (d ⇒ a ∨ c) ⇒ ~d
		  ~d ⟶ F, **d ⟶V**
		  d ⇒ a ∨ c ⟶ V, a ∨ c⟶ V
		  a ⟶ V, c ⟶ F o V , a ⇒ b ⟶ V, **b ⟶ V**
		  ~b ∨ ~c ⟶ V, ~b ⟶ F, **b ⟶ V**
		  ~c ⟶ V , **c ⟶ F**
		  *Tautología*
		  **El razonamiento es Inválido**.
	- d) p ⇒ q ∨ r ; p ∨ (~t ∨ s) ; ~q ∧ ~s ; s ⇒ ~t ∴ ~t
	  collapsed:: true
		- {p ⇒ q ∨ r} ∧ (p ∨ ~t ∨ s) ∧ (~q ∧ ~s) ∧ (s ⇒ ~t) ⇒ ~t
		  ~t ⟶ F, **t ⟶ V**
		  s ⇒ ~t⟶ V, **s ⟶ F**
		  ~s ⟶ V, ~q ∧ ~s ⟶ V, ~q⟶ V, **q ⟶ F**
		  p ∨ ~t ∨ s ⟶ V, **p ⟶ V**
		  p ⇒ q ∨ r ⟶ V, q ∨ r ⟶ V, **r ⟶ V**
		  *Tautología*
		  **El razonamiento es Inválido**.
- ### 18) Dado el siguiente razonamiento complete con una conclusión válida y demuestre por reglas de inferencia:  “Si él iba solo y desarmado, su jefe no lo mataría. Para suplicarle perdón era necesario ir desarmado. Le suplicó pero igualmente su jefe lo mató.” ¿Por qué?
  collapsed:: true
	- s: *El iba solo*
	  d: *El iba desarmado*
	  j:  *Su jefe no lo mata*
	  p: *El suplica perdón*
	  **s ∧ d ⇒ j ; p ⇒ d ; p ∧ ~j ∴ ?**
	  1) p ⇒ d           (*premisa*)
	  2) p ∧ ~j         (*premisa*)
	  3) ~j                 (*Simplificación 2*)
	  4) s ∧ d ⇒ j     (*premisa*)
	  5) ~(s ∧ d)      (*Modus Tollens 4 y 3*)
	  6) ~s ∨ ~d      (*de Morgan*)
	  7) p                 (*Simplificación 2*)
	  8) d                 (*Modus Ponens 7 y 1*)
	  9) ~s               (*Silogismo disyuntivo 8 y 6*)
	  ∴
	  **~s (El iba solo)**
- ### 19) Escriba en forma simbólica, previa definición de un diccionario y de un conjunto universal, y analice la validez de los siguientes razonamientos categóricos, demostrando por reglas de inferencia o justificando correctamente
	- a) Todos los grafos completos son conexos. Existen grafos simples que no son conexos. Por lo tanto, existen grafos simples que no son completos.
	  collapsed:: true
		- A: (x / x es un grafo)
		  P(x): *x es completo*
		  S(x): *x es simple*
		  Q(x): *x es conexo*
		  **∀x : P(x) ⇒ Q(x) ;  ∃ x : S(x) ∧ ~Q(x) ∴ ∃ x : S(x) ∧ ~P(x)**
		  1) ∀x : P(x) ⇒ Q(x)           (*premisa*)
		  2) ∃ x : S(x) ∧ ~Q(x)       (*premisa*)
		  3)  S(b) ∧ ~Q(b)              (*Particularización existencial 2*)
		  4)  ~Q(b)                         (*Simplificación 3*)
		  5)  S(b)                            (*Simplificación 3*)
		  6)  P(b)⇒Q(b)                 (*Particularización universal 1*)
		  7)  ~P(b) ∨ Q(b)             (*Equiv. condicional  6*)
		  8)  ~P(b)                       (*Silogismo disyuntivo 7 y 4*)
		  9)  S(b) ∧ ~P(b)            (*Ley de Combinación 8 y 5*)
		  10)  ∃ x : S(x) ∧ ~P(x)    (*Generalización existencial 9*)
		  ∴ **El razonamiento es Valido**
	- b) Algunos invitados son ingenieros. Algunos ingenieros dan clases en la facultad. Por lo tanto, algunos invitados dan clases en la facultad.
	  collapsed:: true
		- A: (x / x es una persona)
		  S(x): *x es invitado*
		  P(x): *x es ingeniero*
		  Q(x): *x da clases en la facultad*
		  **∃ x S(x) ∧ P(x) ;  ∃ x P(x) ∧ Q(x) ∴ ∃ x : S(x) ∧ Q(x)**
		  Juan es invitado e ingeniero.        S(x) es V pero Q(x) es F
		  María es ingeniera y da clases      P(x) es V pero S(x) es F
		  ∴ **El razonamiento es Invalido**
	- c) Todos los bebés de Terapia estaban en incubadora o con respirador. Los que estaban en incubadora eran prematuros y de bajo peso. Lucio, uno de los bebés de Terapia, tenía buen peso. Por lo tanto, al menos un bebé de Terapia estaba con respirador.
	  collapsed:: true
		- A: (x / x es un bebe de terapia)
		  N(x): *x esta en incubadora*
		  R(x): *x esta con respirador*
		  P(x): *x es con prematuro*
		  B(x): *x es de bajo peso*
		  **∀x: N(x) ∨ R(x) ;  ∀x: N(x) ⇒ P(x) ∧ B(x) ; ~B(Lucio) ∴ ∃ x : R(x)**
		  1) ∀x: N(x) ⇒ P(x) ∧ B(x)                                              (*premisa*)
		  2) ~B(Lucio)                                                                   (*premisa*)
		  3) ∀x: N(x) ∨ R(x)                                                          (*premisa*)
		  4) N(Lucio) ⇒ P(Lucio) ∧ B(Lucio)                               (*Particularización universal 1*)
		  5) ~N(Lucio) ∨ (P(Lucio) ∧ B(Lucio))                           (*equiv. del condicional 4*)
		  6) (~N(Lucio) ∨ P(Lucio)) ∧ (~N(Lucio) ∨ B(Lucio))   (*Distributividad 5*)
		  7) ~N(Lucio) ∨ B(Lucio)                                                (*Simplificación 6*)
		  8) ~N(Lucio)                                                                   (*Silogismo disyuntivo 7 y 2*)
		  9) N(Lucio) ∨ R(Lucio)                                                   (*Particularización universal 3*)
		  10) R(Lucio)                                                                     (*Silogismo disyuntivo 9 y 8*)
		  ∴ **El razonamiento es Invalido**
	- d) Todas las matrices que tienen dos filas iguales no son inversibles. Las matrices 
	  collapsed:: true
	  inversibles tienen determinante distinto de cero. El determinante de la matriz “A” es 
	  cero. Por lo tanto, la matriz “A” tiene dos filas iguales.
		- A: (x / x es una matriz)
		  F(x): *x tienen dos filas iguales*
		  N(x): *x es inversible*
		  D(x): *x tiene determinante distinto de cero*
		  **∀x: F(x) ⇒ ~N(x) ;  ∀x: N(x) ⇒ D(x) ; ~D(A) ∴ F(A)**
		  1) ∀x: F(x) ⇒ ~N(x)                                            (*premisa*)
		  2)  F(A) ⇒ ~N(A)                                                 (*Particularización universal 1*)
		  3)  ∀x: N(x) ⇒ D(x)                                             (*premisa*)
		  4)  N(A) ⇒ D(A)                                                   (*Particularización universal 3*)
		  5) ~D(A)                                                               (*premisa*)
		  6)  ~N(A)                                                               (*Modus Tollens 5 y 4*)
		  ∴ **El razonamiento es Invalido**
	- ### 20) Indique un conjunto Universal y una interpretación de los esquemas proposicionales para comprobar la invalidez del siguiente razonamiento: 
	  ∀ x : [ d(x) ⇒ c(x) ] ; ∃ x : [ ~c(x) ∧ p(x) ] ∴ ∀ x : [ c(x) ∨ p(x) ]