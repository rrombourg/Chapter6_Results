Vous trouverez dans ces dossiers toutes les figures relatives aux r�sultats 
pr�sent�s dans le Chapitre 6 de ma th�se.

Dans le dossier "Regression_analysis" se trouvent les r�sultats relatifs � l'analyse par r�gression
Dans le dossier "ROC_analysis" se trouvent les r�sultats relatifs � l'analyse ROC

Dans les dossiers "Mixed_point_detector" se trouvent les r�sultats du d�tecteur de points mixtes.
Dans les dossiers "Sky_detector" se trouvent les r�sultats du d�tecteur de points de ciel

Dans chancun de ces dossiers vous trouverez les dossiers relatifs aux formes �tudi�es.
Dans les dossiers "Cylinders" (pr�sent dans les dossiers "Mixed_point_detector" et "Sky_detector")
se trouvent les r�sultats sur les cylindres.
Dans les dossiers "Holes" (pr�sents dans les dossiers "Sky_detector") se trouvent les r�sultats sur les trous.


----------------------------------------------------------------------------------------
Pour l'analyse par r�gression :
----------------------------------------------------------------------------------------
Dans chancun de ces dossiers vous trouverez les dossiers relatifs aux m�triques calcul�es.
Dans les dossiers "Intercept" se trouvent les r�sultats de mesure l'intercept des r�gressions. 
Dans les dossiers "RMSE" se trouvent les r�sultats de mesure du RMSE des r�gressions. 
Dans les dossiers "slope" se trouvent les r�sultats de mesure la pente des r�gressions. 

Convention de nommage dans chaque dossier de r�sultats :
les fichiers se nomment :
"XXX_heatmap_YYY_ZZZ.png"
o� :
- XXX est la mesure : "Itercept", "RMSE" ou "Coeff" (pour slope)
- YYY est soit "U" pour la r�solution Ultra, soit "H" pour la r�solution "High", soit "M" pour la r�solution "Medium"
ou "L" pour la r�solution "Low".
- ZZZ est la couleur du papier : "Brown" (albedo = 21%), "Green" (albedo = 9%) ou "White" (albedo = "94%")

----------------------------------------------------------------------------------------
Pour l'analyse ROC
----------------------------------------------------------------------------------------
Dans chancun de ces dossiers vous trouverez les dossiers relatifs aux m�triques calcul�es.
Dans les dossiers "false_positive_rates" se trouvent les r�sultats de mesure de taux de faux positifs. 
Dans les dossiers "Number_of_data" se trouvent images donnant le nombre de donn�es utilis�es par cas.
Dans les dossiers "score" se trouvent les r�sultats de mesure du score (comme d�finit dans la th�se).
Dans les dossiers "true_positive_rates" se trouvent les r�sultats de mesure de taux de vrai positifs.

Convention de nommage dans chaque dossier de r�sultats :
les fichiers se nomment :
"ROC_heatmap_XXX_YYY_WZZZ.png"
o� :
- XXX est soit "U" pour la r�solution Ultra, soit "H" pour la r�solution "High", soit "M" pour la r�solution "Medium"
ou "L" pour la r�solution "Low".
- YYY est la couleur du papier : "Brown" (albedo = 21%), "Green" (albedo = 9%) ou "White" (albedo = "94%")
- ZZZ est le param�tre de fen�tre utilis� et W appartient � [3,15] avec W impair.
 

