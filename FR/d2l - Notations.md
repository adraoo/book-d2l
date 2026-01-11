## Notations

Dans tout cet ouvrage, nous adoptons les conventions de notation suivantes. Notez que certains symboles servent de *placeholders* (variables génériques), tandis que d’autres désignent des objets spécifiques. En règle générale, l’article indéfini « un/une » indique souvent que le symbole est un *placeholder* et que des symboles de même forme peuvent désigner d’autres objets du même type. Par exemple, « (x) : un scalaire » signifie que les lettres minuscules représentent généralement des valeurs scalaires, tandis que « (\mathbb{Z}) : l’ensemble des entiers » renvoie spécifiquement au symbole (\mathbb{Z}). 

### Objets numériques

* (x) : un scalaire
* (\mathbf{x}) : un vecteur
* (\mathbf{X}) : une matrice
* (\mathsf{X}) : un tenseur général
* (\mathbf{I}) : la matrice identité (d’une dimension donnée), c.-à-d. une matrice carrée dont les éléments diagonaux valent 1 et les éléments hors diagonale valent 0
* (x_i), ([\mathbf{x}]_i) : le (i)-ème élément du vecteur (\mathbf{x})
* (x_{ij}), (x_{i,j}), ([\mathbf{X}]*{ij}), ([\mathbf{X}]*{i,j}) : l’élément de la matrice (\mathbf{X}) à la ligne (i) et à la colonne (j) 

### Théorie des ensembles

* (X) : un ensemble
* (\mathbb{Z}) : l’ensemble des entiers
* (\mathbb{Z}^+) : l’ensemble des entiers positifs
* (\mathbb{R}) : l’ensemble des réels
* (\mathbb{R}^n) : l’ensemble des vecteurs réels de dimension (n)
* (\mathbb{R}^{a\times b}) : l’ensemble des matrices réelles à (a) lignes et (b) colonnes
* (|X|) : la cardinalité (nombre d’éléments) de l’ensemble (X)
* (A \cup B) : l’union des ensembles (A) et (B)
* (A \cap B) : l’intersection des ensembles (A) et (B)
* (A \setminus B) : la différence ensembliste de (A) par (B) (contient seulement les éléments de (A) qui n’appartiennent pas à (B)) 

### Fonctions et opérateurs

* (f(\cdot)) : une fonction
* (\log(\cdot)) : le logarithme népérien (base (e))
* (\log_2(\cdot)) : le logarithme en base 2
* (\exp(\cdot)) : la fonction exponentielle
* (\mathbf{1}(\cdot)) : la fonction indicatrice ; vaut 1 si l’argument booléen est vrai, et 0 sinon
* (\mathbf{1}_X(z)) : indicatrice d’appartenance à l’ensemble ; vaut 1 si l’élément (z) appartient à (X), et 0 sinon
* ((\cdot)^\top) : la transposée d’un vecteur ou d’une matrice
* (\mathbf{X}^{-1}) : l’inverse de la matrice (\mathbf{X})
* (\odot) : produit de Hadamard (élément par élément)
* ([\cdot,\cdot]) : concaténation
* (|\cdot|_p) : norme (\ell_p)
* (|\cdot|) : norme (\ell_2)
* (\langle \mathbf{x}, \mathbf{y} \rangle) : produit scalaire (dot product) des vecteurs (\mathbf{x}) et (\mathbf{y})
* (\sum) : somme sur une collection d’éléments
* (\prod) : produit sur une collection d’éléments
* (\stackrel{\mathrm{def}}{=}) : égalité posée comme définition du symbole au membre de gauche 

### Calcul

* (\dfrac{dy}{dx}) : dérivée de (y) par rapport à (x)
* (\dfrac{\partial y}{\partial x}) : dérivée partielle de (y) par rapport à (x)
* (\nabla_{\mathbf{x}} y) : gradient de (y) par rapport à (\mathbf{x})
* (\int_a^b f(x),dx) : intégrale définie de (f) de (a) à (b) par rapport à (x)
* (\int f(x),dx) : intégrale indéfinie de (f) par rapport à (x) 

### Probabilités et théorie de l’information

* (X) : une variable aléatoire
* (P) : une loi (distribution) de probabilité
* (X \sim P) : la variable aléatoire (X) suit la loi (P)
* (P(X=x)) : probabilité de l’événement « (X) prend la valeur (x) »
* (P(X\mid Y)) : loi conditionnelle de (X) sachant (Y)
* (p(\cdot)) : densité de probabilité (PDF) associée à la loi (P)
* (\mathbb{E}[X]) : espérance de la variable aléatoire (X)
* (X \perp Y) : (X) et (Y) sont indépendantes
* (X \perp Y \mid Z) : (X) et (Y) sont conditionnellement indépendantes sachant (Z)
* (\sigma_X) : écart-type de (X)
* (\mathrm{Var}(X)) : variance de (X), égale à (\sigma_X^2)
* (\mathrm{Cov}(X,Y)) : covariance de (X) et (Y)
* (\rho(X,Y)) : coefficient de corrélation de Pearson entre (X) et (Y), égal à (\dfrac{\mathrm{Cov}(X,Y)}{\sigma_X \sigma_Y})
* (H(X)) : entropie de (X)
* (D_{\mathrm{KL}}(P|Q)) : divergence de KL (ou entropie relative) de la loi (Q) vers la loi (P) 
