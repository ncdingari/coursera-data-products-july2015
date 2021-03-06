**Description**

This simple Shiny application uses the data from Galton's 1886 study
(dataset `GaltonFamilies` in the [HistData](https://cran.r-project.org/web/packages/HistData/) R package), 
to try and predict (using a linear regression model), 
a child's height in centimeters, 
given the father's and mother's height, as well as the child's gender.

It is very interesting that even recent studies on this topic (like
the one by Yurii S Aulchenko, 2009) based con genetic marker data, do no better
for height prediction than Galton's simple procedure that uses the "mid-parent"
height for the same purpose.

Also, the application does not try to do range checks for the parent's heights,
so you will get an answer even with unlikely values. Perhaps, checks will be
implemented in a future version of this Shiny application.


**References**

- Galton, F. "Regression Towards Mediocrity in Hereditary Stature",
  The Journal of the Anthropological Institute of Great Britain and Ireland,
  Vol. 15 (1886), pp. 246-263, DOI: 10.2307/2841583
- Aulchenko, Y.S.; *et. al.* "Predicting human height by Victorian and genomic methods",
  European Journal of Human Genetics (2009) 17, 1070–1075,
  DOI: 10.1038/ejhg.2009.5
