### Sujet - Co2



Mon projet est donc parti d’une question simple :

Les grands événements internationaux peuvent-ils vraiment infléchir les trajectoires d’émissions des pays les plus pollueurs ? avec l'envie d'avoir une vision plutôt optimiste du sujet



Pour y répondre, j’ai étudié l’évolution des émissions de CO₂ dans plusieurs grands pays producteurs (États-Unis, Chine, Inde, Russie, etc.) autour de trois jalons internationaux clés :



&nbsp;	- La mise en application des Accords de Kyoto (2005, signature en 2008) – premier traité mondial engageant les pays industrialisés à réduire leurs émissions.



&nbsp;	- La signature des Accords de Paris (2015 - mise en place en 2016) – renforcement des engagements et apparition de trajectoires différenciées par pays.



&nbsp;	- La pandémie de COVID-19 (2020) – événement exogène brutal qui a temporairement bouleversé les modèles économiques.







### Traitement des données - Phase la plus longue



SelectRows pour filtrer les lignes avec des valeurs nulles dans les colonnes clés.



Transformation des types de nombreuses colonnes (ex. Int64.Type, type number, Percentage.Type, etc.).



Calcul de pourcentages pour plusieurs parts mondiales (en divisant par 100 les colonnes de type share\_global\_\*).



Suppression des colonnes inutiles pour alléger la table.



Renommage des colonnes en français pour plus de lisibilité dans Power BI et pour gagner du temps au final.



Ajout de colonnes personnalisées avec des calculs de croissance ou d’indicateurs spécifiques.



Filtrer un sous-ensemble de pays d’intérêt 



Recatégoriser les pays par continents dans la colonne "Zone géographique".



Exclure des années pivots de l’analyse (1990–1999, 2005, 2015, 2020)



Ajouter une colonne "Événement" en catégorisant les années restantes selon des jalons historiques (Kyoto, Paris, Covid).



Supprimer de nombreuses colonnes non essentielles pour alléger la table et pour se concentrer sur certains types d’émissions ou indicateurs (comme les émissions de CO₂ hors LUC par exemple).



Exclure la ligne "World", pour ne conserver que les pays.





### Dashboard interactif 



> Un choix d'un nombre limité de KPI pour ne pas surchager le Dashboard



> sur ce sujet la cartographie est un choix naturel



> Un suivi des trajectoires d’émissions par pays avant/après événement, avec des marqueurs temporels pour situer chaque événement avec: 



&nbsp;	- Des KPIs qui quantifient l’impact de chaque événement : Co2 médian/ hab + production moyenne de Cà2 ; 



&nbsp;	- Une visualisation cartographique avant/après qui montre par zone et par pays où les engagements ont été tenus… ou pas.



&nbsp;	- Chaque filtre (événement ou région) a été pensé pour offrir à l’utilisateur une lecture fluide et pédagogique,.



&nbsp;	- Une frise chronologique pour situer lkes événements et les années utilisées pour les KPI





### Conclusion



mon titre intial était plus optimiste: UN CHANGEMENT EST POSSIBLE- Zoom sur 3 événements majeurs 



j'ai finalement opté pour un titre plus factuel car la production de Co2 sur l'échantillon de pays a fortement progressé, production portée par L'Asie.



si certaines région ont une évolution ponctuellement favorable ces événements sont insuffisants pour fléchir la tendance



A creuser : est ce que certaines baisses sont en fait une "exportation" de la production de Co2











