# 2. LLAMMA : l’AMM de liquidation

LLAMMA est le cœur de la liquidation progressive. Au lieu d’attendre un seuil unique, le mécanisme organise une position autour de bandes de prix et échange graduellement le collatéral contre une exposition stable lorsque le marché baisse.

Les tests du dossier amm révèlent les invariants d’échange, la fonction de prix, le dépôt-retrait et la protection contre le share pump. Les fonctions de calcul relient réserves, bandes actives et variation de prix.

Cette structure cherche à réduire les ventes forcées en répartissant l’ajustement dans le temps. Elle reste sensible à la liquidité disponible, aux paramètres de bande et à la qualité de l’oracle.

→ [Chapitre suivant : positions et dette](03-positions-dette.md)
