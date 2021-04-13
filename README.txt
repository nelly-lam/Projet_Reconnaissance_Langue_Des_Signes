1.4. Machines à vecteurs de support

Les machines à vecteurs de support (SVM) sont un ensemble de méthodes d'apprentissage supervisé utilisées pour la classification, la régression et la détection des aberrations.

Les avantages des machines à vecteurs de support sont les suivants :

        Efficaces dans les espaces à haute dimension.

        Toujours efficaces dans les cas où le nombre de dimensions est supérieur au nombre d'échantillons.

        Elles utilisent un sous-ensemble de points d'apprentissage dans la fonction de décision (appelés vecteurs de support), ce qui les rend également efficaces en termes de mémoire.

        Polyvalent : différentes fonctions de noyau peuvent être spécifiées pour la fonction de décision. Les noyaux courants sont fournis, mais il est également possible de spécifier des noyaux personnalisés.

Les inconvénients des machines à vecteurs de support sont les suivants :

        Si le nombre de caractéristiques est beaucoup plus grand que le nombre d'échantillons, il est crucial d'éviter le surajustement dans le choix des fonctions Kernel et du terme de régularisation.

        Les SVM ne fournissent pas directement d'estimations de probabilité, celles-ci sont calculées à l'aide d'une coûteuse validation croisée à cinq reprises (voir Scores et probabilités, ci-dessous).

Les machines à vecteurs de support de Scikit-learn prennent en charge les vecteurs d'échantillons denses (numpy.ndarray et convertibles en numpy.asarray) et épars (n'importe quel scipy.sparse) comme entrée. Cependant, pour utiliser un SVM pour faire des prédictions pour des données éparses, il doit avoir été ajusté sur de telles données. Pour des performances optimales, utilisez numpy.ndarray (dense) ou scipy.sparse.csr_matrix (sparse) ordonné en C avec dtype=float64.
