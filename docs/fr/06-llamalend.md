# 6. Llamalend et marchés de prêt

Llamalend ajoute des marchés de prêt autour de crvUSD et de collatéraux comme ETH, wstETH ou WBTC. Les fichiers de déploiement décrivent les marchés, les fabriques et les zaps qui relient le prêt au reste de l’écosystème Curve.

Le modèle sépare les paramètres d’un marché des contrats génériques. Cette séparation facilite des configurations différentes, mais impose de vérifier chaque marché avant de comparer deux environnements.

Les callbacks et les scénarios de dette montrent que les intégrations externes font partie du périmètre de sécurité.

→ [Chapitre suivant : protections](07-protections.md)
