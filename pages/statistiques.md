- [[mathématiques]]
- inférence causale
-
- ## méthodologie de test d'hypothèse
	- Pearson $\chi^2$ #card
		- données catégoriques
		- $N$ observations
		- hypothèse nulle
			- $$
			  H_0 = Multinomial(N;p_1,...,p_n)
			  $$
		- test
			- $$
			  \chi^2 := \sum_i \frac{(O_i - Np_i)^2}{Np_i}
			  $$
			- exemple
			- voir aussi
				- valeur-p/p-value
	- Student t-test #card
	- AB test #card
		- $$
		  H_0 : P(A = B) \\
		  H_1 : P(A \neq B)
		  $$
		-
		-
	- degré de liberté #card
		- df
		- $\nu$
		-
		- voir aussi
			- https://fr.wikipedia.org/wiki/Degr%C3%A9_de_libert%C3%A9_(statistiques)
			- https://en.wikipedia.org/wiki/Degrees_of_freedom_(statistics)
	- loi normale #card
		- $$f(x) = \frac1{\sigma \sqrt{2\pi}}\operatorname e^{-\frac12\left(\frac{x-\mu}{\sigma}\right)^2}$$
		- $$X\sim\mathcal N(\mu,\sigma^2)$$
		-
	- régression linéaire #card
		- best-fit line
			- $$ y = mx + c$$
			- intercept
				- $$
				  c = \bar{y} - m\bar{x}
				  $$
			- slope
				- $$
				  m = \frac{\sum_{i=1}^n (y_i - \bar{y})(x_i - \bar{x})}{\sum_{i=1}^n (x_i - \bar{x})}
				  $$
	- ANOVA #card
		- F
		- MMSE
		- MMST
-
- ## ressources
	- ### Livres
		- [[Mostly Harmless Econometrics]]
	- ### sites
		- https://statquest.org/
		- Kahn academy