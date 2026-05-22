### 1) Sean A = { 1, 2, 3 } y B = { 2, 4, 6, 8 }
	- a) Indique la cantidad de pares del producto cartesiano, y la cantidad de relaciones diferentes que se pueden definir de A en B.
		- A X B = { (1,2) , (1,4) , (1, 6), (1, 8) , (2,2) , (2,4) , (2, 6), (2, 8) , (3,2) , (3,4) , (3, 6), (3, 8) }
		  |R| = 2 $^{3 * 4}$ = 2 $^{12}$ ***total de posibles relaciones***
	- b) Exprese cada una de las siguientes relaciones de A en B por extensión, indique 
	  dominio, imagen, relación inversa y relación complementaria:
		- R1 = {(x;y) ∈ A X B /  2 x ≤ y }
		  collapsed:: true
			- A → B = { (1,2) , (1,4) , (1,6) , (1,8) , (2,4) , (2,6) , (2,8) , (3,6) , (3,8) }
			  Dom(R) = { 1 , 2 , 3}
			  Im(R) = { 2 , 4 , 6 , 8 }
			  R $^{-1}$ = { (2,1) , (4,1) , (6,1) , (8,1) , (4,2) , (6,2) , (8,2) , (6,3) , (8,3) }
			  $\overline{R}$ = { (2,2) , (3,2) , (3,4) }
		- R2 = {(x;y) ∈ A X B /  x + y es par }
		  collapsed:: true
			- A → B = { (2,2) , (2,4) , (2, 6), (2, 8) }
			  Dom(R) = { 2 }
			  Im(R) = { 2 , 4 , 6 , 8 }
			  R $^{-1}$ = { (2,2) , (4,2) , (6, 2), (8, 2) }
			  $\overline{R}$ = { (1,2) , (1,4) , (1, 6), (1, 8) , (1,3) , (3,2) , (3,4) , (3, 6), (3, 8) }
		- R3 = {(x;y) ∈ A X B /  y = x $^{2}$ }
			- A → B = { (2,4) }
			  Dom(R) = { 2 }
			  Im(R) = { 4 }
			  R $^{-1}$ = { (4,2) }
			  $\overline{R}$ = { (1,2) , (1,4) , (1, 6), (1, 8) , (2,2) , (2, 6), (2, 8) , (3,2) , (3,4) , (3, 6), (3, 8) }
		- R4 = {(x;y) ∈ A X B /  y ≥ 7 }
		  collapsed:: true
			- A → B = { (1, 8) , (2, 8) , (3, 8) }
			  Dom(R) = { 1 , 2 , 3 }
			  Im(R) = { 8 }
			  R $^{-1}$ = { (8,1) , (8,2) , (8,3) }
			  $\overline{R}$ = { (1,2) , (1,4) , (1, 6) , (2,2) , (2,4) , (2, 6) , (3,2) , (3,4) , (3, 6) }
- ### 2) Dados los siguientes conjuntos:
         A = { 1, 2, 3 }     B = { x, y, z }    C = { m, n }    D = { a, b, c, d }
	- a) Indique si las siguientes relaciones son funciones. En caso afirmativo, clasifíquelas en inyectivas, sobreyectivas o biyectivas:
		- R1 : A → B / R1 = { (1;x) , (2;x) , (3;y) }
		  collapsed:: true
			- **Es función (No es ni inyectiva ni sobreyectiva)**
		- R2 : A → B / R2 = { (1;z) , (2;x) , (3;y) }
		  collapsed:: true
			- **Es función (Es biyectiva)**
		- R3 : A → B / R3 = { (1;x) , (1;y) , (2;x) , (3;z) }
		  collapsed:: true
			- **No es función**
		- R4 : A → C / R4 = { (1,m) , (2;n) }
		  collapsed:: true
			- **No es función**
		- R5 : A → C / R5 = { (1;n) , (2;n) , (3;n) }
		  collapsed:: true
			- **Es función (No es ni inyectiva ni sobreyectiva)**
		- R6 : A → C / R6 = { (1;m) , (2;m) , (3;n) }
		  collapsed:: true
			- **Es función (Es sobreyectiva)**
		- R7 : A → D / R7 = { (1;a) , (2;b) , (3;c) }
		  collapsed:: true
			- **Es función (Es inyectiva)**
		- R8 : A → D / R8 = { (1;a) , (2;b) , (3;c), (3;d) }
		  collapsed:: true
			- **No es función**
	- b) Complete: Para que exista una función biyectiva entre dos conjuntos finitos, sus cardinales deben ser **Iguales**
- ### 3) Siendo R: A → B  y S: A → B , indique valor de verdad, demuestre o justifique según corresponda:
	- a) │R│=│R $^{-1}$│
		- **Verdadero**
		  R = { (x;y) $\subseteq$ A X B }
		  R $^{-1}$ = { (y;x) ∈ B X A /  (x;y) ∈ R }
		  │R│=│R $^{-1}$│
		  │{ (x;y) $\subseteq$ A X B }│=│{ (y;x) ∈ B X A /  (x;y) ∈ R }│
		  │{ x ∈ A ∧ y ∈ B}│= │{ y ∈ B ∧ x ∈ A}│= (y;x) ∈ B X A
	- b) │R│=│ $\overline{R}$ │
		- **Falso**
		  Ver ejercicio 1 b R3
	- c) │R│ ≤ │R $\cup$ S│
		-
	- d) │R│> 0
	- e) Dom(R-1)  = Im(R)
	- f) Dom($\overline{R}$)  = A - dom(R)
	- g) ( R $\cap$ S )-1 =  R $^{-1}$ $\cap$ S $^{-1}$
	- h) R $\subseteq$ S  S $^{-1}$ $\subseteq$ R $^{-1}$