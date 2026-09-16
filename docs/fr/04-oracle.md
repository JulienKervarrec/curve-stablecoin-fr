# 4. Oracle, prix EMA et résistance aux manipulations

Le protocole ne dépend pas seulement d’un prix instantané. Les tests d’oracle examinent des prix moyens, des changements contrôlés et des comparaisons avec le spot afin d’éviter qu’une variation brève ne déclenche une décision disproportionnée.

Les intégrations couvrent les pools StableSwap NG et les oracles construits depuis des pools Curve. Une moyenne mobile réduit le bruit, mais introduit un délai : le risque doit donc être calibré avec la vitesse de correction du marché.

Les contrôleurs et fabriques doivent aussi appliquer les autorisations de changement d’oracle. La documentation du code est la référence pour distinguer une valeur de marché, une valeur EMA et la valeur effectivement utilisée.

→ [Chapitre suivant : liquidation](05-liquidation.md)
