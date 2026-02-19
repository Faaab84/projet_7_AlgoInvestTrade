# AlgoInvest & Trade – Optimisation d'investissement (Projet 7 OpenClassrooms)

Programme Python visant à maximiser le profit sur deux ans d'investissement en actions, dans le cadre d'un budget maximal de 500 € par client.

**Contraintes respectées**  
- Chaque action ne peut être achetée qu'une seule fois  
- Pas d'achat fractionnaire  
- Budget maximum : 500 €  

**Approches implémentées**  

1. **Brute-force** (section 1) : exploration exhaustive de toutes les combinaisons valides  
2. **Optimisation dynamique** (section 2) : algorithme de sac à dos (0/1 Knapsack) pour un excellent compromis temps / profit  
3. **Backtesting & comparaison** (section 3) : mesure du temps d'exécution, profit obtenu et analyse Big-O  

**Fichiers principaux**  
- `bruteforce.py`          → solution exhaustive  
- `optimized.py`           → solution dynamique (sac à dos)  
- `sienna.py` / `dataset.py` → versions avec données Sienna / autres datasets  
- `utils/`                 → fonctions de lecture CSV, calcul de profit, chronométrage  

**Données** : fichiers CSV fournis (non inclus dans le dépôt – à placer dans `/data/`)  
**Exécution** : `python bruteforce.py` ou `python optimized.py`

Le projet démontre la progression de la complexité algorithmique et l’importance de l’analyse de performance (Big O).
Programme développé pour une société d'investissement financier fictive.  
AlgoInvest&Trade est une société financière spécialisée dans l’investissement.  
La société cherche à optimiser ses stratégies d’investissement à l’aide d’algorithmes, afin de dégager davantage de bénéfices pour ses clients.  
  
2 algorithmes ont été développés. 

## Contraintes

- La valeur d'un portefeuille ne doit pas dépasser 500€.  
- Une même action ne doit pas être achetée 2 fois.  
- Il n'est pas possible d'acheter des fractions d'action.


## Installation & lancement:
Commencez tout d'abord par installer Python 3.10.  
Lancez ensuite la console, placez-vous dans le dossier de votre choix puis clonez ce repository :
```
git clone https://github.com/Faaab84/projet_7.git
```
Placez vous dans le dossier projet_7:
```
cd projet_7 
```

Il ne reste plus qu'à lancer par la commande :
```
python bruteforce.py
```
ou :
```
python optmized.py
```

Vous pouvez egalement changer la valeur CSV_FILE pour utiliser votre fichier de données dans le repertoire data
