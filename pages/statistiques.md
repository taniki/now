- [[mathématiques]]
- inférence causale
-
- ## notions
	- Pearson $\chi^2$ #card
	  card-last-score:: 1
	  card-repeats:: 1
	  card-next-schedule:: 2023-11-10T23:00:00.000Z
	  card-last-interval:: -1
	  card-ease-factor:: 2.5
	  card-last-reviewed:: 2023-11-10T08:21:50.339Z
	  collapsed:: true
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
	  card-last-interval:: -1
	  card-repeats:: 1
	  card-ease-factor:: 2.5
	  card-next-schedule:: 2023-11-10T23:00:00.000Z
	  card-last-reviewed:: 2023-11-10T08:23:14.441Z
	  card-last-score:: 1
	- AB test #card
	  card-last-interval:: -1
	  card-repeats:: 1
	  card-ease-factor:: 2.5
	  card-next-schedule:: 2023-11-10T23:00:00.000Z
	  card-last-reviewed:: 2023-11-10T08:23:17.731Z
	  card-last-score:: 1
		- $$
		  H_0 : P(A = B) \\
		  H_1 : P(A \neq B)
		  $$
		-
		-
	- degré de liberté #card
	  card-last-interval:: -1
	  card-repeats:: 1
	  card-ease-factor:: 2.5
	  card-next-schedule:: 2023-11-10T23:00:00.000Z
	  card-last-reviewed:: 2023-11-10T08:23:20.961Z
	  card-last-score:: 1
		- df
		- $\nu$
		-
		- voir aussi
			- https://fr.wikipedia.org/wiki/Degr%C3%A9_de_libert%C3%A9_(statistiques)
			- https://en.wikipedia.org/wiki/Degrees_of_freedom_(statistics)
	- loi normale #card
	  card-last-interval:: -1
	  card-repeats:: 1
	  card-ease-factor:: 2.5
	  card-next-schedule:: 2023-11-10T23:00:00.000Z
	  card-last-reviewed:: 2023-11-10T08:23:30.409Z
	  card-last-score:: 1
		- $$f(x) = \frac1{\sigma \sqrt{2\pi}}\operatorname e^{-\frac12\left(\frac{x-\mu}{\sigma}\right)^2}$$
		- $$X\sim\mathcal N(\mu,\sigma^2)$$
		-
	- régression linéaire #card
	  card-last-interval:: -1
	  card-repeats:: 1
	  card-ease-factor:: 2.5
	  card-next-schedule:: 2023-11-10T23:00:00.000Z
	  card-last-reviewed:: 2023-11-10T08:21:39.332Z
	  card-last-score:: 1
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
	  card-last-interval:: -1
	  card-repeats:: 1
	  card-ease-factor:: 2.5
	  card-next-schedule:: 2023-11-10T23:00:00.000Z
	  card-last-reviewed:: 2023-11-10T08:21:55.609Z
	  card-last-score:: 1
		- $$
		  F = \frac{MSST - MMSE}{MSSE}
		  $$
		- MMSE
		- MMST
		-
		- ressources
			- {{video https://www.youtube.com/watch?v=NF5_btOaCig}}
		-
-
- Coefficent de Gini #card
	- $$
	  G = \frac{2 \sum_{i=1}^n i y_i}{n \sum_{i=1}^n y_i} - \frac{n-1}{n}
	  $$
- ## ressources
	- ### Livres
		- [[Mostly Harmless Econometrics]]
	- ### sites
		- https://statquest.org/
		- Kahn academy