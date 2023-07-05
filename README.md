# Detecció de patrons en l'autisme mitjançant ML no supervisat

L'autisme és un trastorn del desenvolupament neurològic que afecta la comunicació, les habilitats socials i el comportament. En aquest estudi, s'utilitza l'aprenentatge no supervisat per identificar patrons en un conjunt de dades relacionades amb l'autisme. 



Mètodes Utilitzats
--------------------------------------------------

• Algoritme K-means
• Algoritme de clustering jeràrquic
• Algoritme DBSCAN


Resultats 
-------------------------------------------------------


En aquest projecte s'ha utilitzat l'anàlisi de components principals (PCA) per reduir la dimensionalitat del conjunt de dades de l'autisme. S'ha aplicat el mètode del colze i un dendrograma per determinar el nombre òptim de clústers, i finalment s'ha utilitzat el mètode DBSCAN. El coeficient de silueta s'ha utilitzat per avaluar els models, i s'ha seleccionat el DBSCAN com el millor model amb un resultat més alt. L'anàlisi del clúster més gran ha permès identificar un perfil d'infant amb característiques específiques, incloent edat, idioma predominant, ubicació geogràfica, situació de l'habitatge i altres factors. Cal destacar que el DBSCAN ha mostrat un millor rendiment en comparació amb el k-means, reflectit en un coeficient de silueta més alt.
