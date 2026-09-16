# 5. Liquidation progressive et bandes de risque

Quand une position devient risquée, LLAMMA peut convertir progressivement le collatéral dans les bandes concernées. La liquidation partielle évite de fermer systématiquement toute la position et permet à l’emprunteur de rembourser ou de rajouter du collatéral.

Les scénarios de liquidation partielle décrivent les parcours de remboursement, tandis que les tests AMM couvrent la poussière, les invariants et le calcul du montant nécessaire pour atteindre un prix.

La mécanique dépend des arrondis, du prix courant, de la bande active et des frais. Ces paramètres sont indissociables : analyser une seule formule sans son contexte peut masquer le risque réel.

→ [Chapitre suivant : Llamalend](06-llamalend.md)
