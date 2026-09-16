# 3. Créer, gérer et rembourser une position

Une position de dette associe un collatéral, un montant de crvUSD et des paramètres de risque. Le contrôleur vérifie les limites avant de permettre la création d’un prêt, l’ajout de dette, le remboursement ou le retrait.

Les scénarios de stableborrow documentent la conservation des intérêts et les cas limites. Le packing des paramètres réduit le coût de stockage, mais rend la lecture des champs encodés particulièrement importante.

Le parcours opérationnel est donc : déposer, emprunter, surveiller le ratio, rembourser ou accepter une liquidation. Les zaps ajoutent une couche d’orchestration pour regrouper plusieurs étapes.

→ [Chapitre suivant : oracle](04-oracle.md)
