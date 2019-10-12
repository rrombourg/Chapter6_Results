Vous trouverez dans ces dossiers toutes les figures relatives aux résultats 
présentés dans le Chapitre 6 de ma thèse.

Dans le dossier "Regression_analysis" se trouvent les résultats relatifs à l'analyse par régression
Dans le dossier "ROC_analysis" se trouvent les résultats relatifs à l'analyse ROC

Dans les dossiers "Mixed_point_detector" se trouvent les résultats du détecteur de points mixtes.
Dans les dossiers "Sky_detector" se trouvent les résultats du détecteur de points de ciel

Dans chancun de ces dossiers vous trouverez les dossiers relatifs aux formes étudiées.
Dans les dossiers "Cylinders" (présent dans les dossiers "Mixed_point_detector" et "Sky_detector")
se trouvent les résultats sur les cylindres.
Dans les dossiers "Holes" (présents dans les dossiers "Sky_detector") se trouvent les résultats sur les trous.


----------------------------------------------------------------------------------------
Pour l'analyse par régression :
----------------------------------------------------------------------------------------
Dans chancun de ces dossiers vous trouverez les dossiers relatifs aux métriques calculées.
Dans les dossiers "Intercept" se trouvent les résultats de mesure l'intercept des régressions. 
Dans les dossiers "RMSE" se trouvent les résultats de mesure du RMSE des régressions. 
Dans les dossiers "slope" se trouvent les résultats de mesure la pente des régressions. 

Convention de nommage dans chaque dossier de résultats :
les fichiers se nomment :
"XXX_heatmap_YYY_ZZZ.png"
où :
- XXX est la mesure : "Itercept", "RMSE" ou "Coeff" (pour slope)
- YYY est soit "U" pour la résolution Ultra, soit "H" pour la résolution "High", soit "M" pour la résolution "Medium"
ou "L" pour la résolution "Low".
- ZZZ est la couleur du papier : "Brown" (albedo = 21%), "Green" (albedo = 9%) ou "White" (albedo = "94%")

----------------------------------------------------------------------------------------
Pour l'analyse ROC
----------------------------------------------------------------------------------------
Dans chancun de ces dossiers vous trouverez les dossiers relatifs aux métriques calculées.
Dans les dossiers "false_positive_rates" se trouvent les résultats de mesure de taux de faux positifs. 
Dans les dossiers "Number_of_data" se trouvent images donnant le nombre de données utilisées par cas.
Dans les dossiers "score" se trouvent les résultats de mesure du score (comme définit dans la thèse).
Dans les dossiers "true_positive_rates" se trouvent les résultats de mesure de taux de vrai positifs.

Convention de nommage dans chaque dossier de résultats :
les fichiers se nomment :
"ROC_heatmap_XXX_YYY_WZZZ.png"
où :
- XXX est soit "U" pour la résolution Ultra, soit "H" pour la résolution "High", soit "M" pour la résolution "Medium"
ou "L" pour la résolution "Low".
- YYY est la couleur du papier : "Brown" (albedo = 21%), "Green" (albedo = 9%) ou "White" (albedo = "94%")
- ZZZ est le paramètre de fenêtre utilisé et W appartient à [3,15] avec W impair.
 

