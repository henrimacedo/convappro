# Bienvenue sur le guide de convappro! (sujet 31)
Convappro a pour objectif de donner avec la plus grande précision la valeur approximative du sinus de tout nombre réel (angle en radians modulo 2pi).

Cette précision théorique est de l'ordre de 10<sup>-100<sup> et utilise les formules de Taylor-Lagrange pour les développements limités et les suites de Cauchy pour en certifier la convergence (la stabilité et la précision).

Comme but scolaire, ce module a été réalisé par Henri MACEDO GONÇALVES, Alexandre RAMDOO, NOVERRAZ Marion et HAGHVIRDILOO Mostafa.

##Consignes d'utilisation

### 1. Installation
```shell script
pip install appromath
``` 
ou encore
```shell script
python3 -m pip install appromath
```

### 2. Utilisation
Soit vous utilisez le main à disposition:

- Dans le terminal, allez sur le répertoire de convappro et tapez:
```
  ./convappro/code.py
```

Soit vous utilisez manuellement:
```python3
from code import calculs
```

### 3. Les fonctions

Vous avez à votre disposition les fonctions suivantes:

Initialisation:
```
  calculs(x)
```

Certificat de convergence d'une suite (r(n))_n de l'ordre x:
```
  conv(x)
```

Suite (r(n)_n):
```
  suiteR(x)
```

Preuve de Cauchy:
```
  preuveCauchy(x)
```

Tronque x à 10<sup>-p<sup> près
```
  tronque(x,p)
```

## DISCLAIMER
Ce module n'a pas vocation à remplacer le module de base math. Il est réalisé à titre scolaire et les auteurs ne sauraient en aucun cas être tenus responsables de sa mauvaise utilisation.
