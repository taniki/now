- ## probabilités
	- geometric probability #card
	  card-last-interval:: -1
	  card-repeats:: 1
	  card-ease-factor:: 2.5
	  card-next-schedule:: 2023-11-08T23:00:00.000Z
	  card-last-reviewed:: 2023-11-08T07:20:56.884Z
	  card-last-score:: 1
		- https://en.wikipedia.org/wiki/Geometric_probability
		- https://archive.org/details/GeometricProbability/mode/2up
		- https://brilliant.org/wiki/1-dimensional-geometric-probability/
	- generating function #card
	  card-last-interval:: -1
	  card-repeats:: 1
	  card-ease-factor:: 2.5
	  card-next-schedule:: 2023-11-08T23:00:00.000Z
	  card-last-reviewed:: 2023-11-08T07:21:00.226Z
	  card-last-score:: 1
		- https://en.wikipedia.org/wiki/Generating_function
	- Bayes #card
	-
- ## statistiques
  id:: 079ec455-406a-4efe-a716-25cda57608d8
	- méthodologie de test d'hypothèse
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