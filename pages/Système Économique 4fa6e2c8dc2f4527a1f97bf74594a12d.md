# Système Économique

### Explications

Comme tout bon serveur RP, nous avons mis en place un système économique avancé. Sur le serveur vous rencontrerez deux type de monnaie :

- Monnaie physique : Cash du mod “Money Expansion"
- Monnaie virutelle : BinaryCurrency

Ces deux monnaies ont deux utilisations différentes:

- La monnaie physique a une `utilisation in-game` pour des `transactions entre joueurs`. C'est aussi ce type de monnaie que l'on récupère lorsque l’on procède à une vente d'un item (CF [page vente](Syste%CC%80me%20E%CC%81conomique%204fa6e2c8dc2f4527a1f97bf74594a12d.md))
- La monnaie virtuelle est utilisée pour faire des `achats sur le site web` du serveur (plus d'infos sur le site [ici](Syste%CC%80me%20E%CC%81conomique%204fa6e2c8dc2f4527a1f97bf74594a12d.md)). C'est aussi votre montant personnel en banque.

### Graphique des flux monétaires du serveur

![Untitled](Syste%CC%80me%20E%CC%81conomique%204fa6e2c8dc2f4527a1f97bf74594a12d/Untitled.png)

[FluxMonétaire.drawio](Syste%CC%80me%20E%CC%81conomique%204fa6e2c8dc2f4527a1f97bf74594a12d/FluxMontaire.drawio)

Voilà un graphique qui montre comment fonctionne l’économie. Chaque jour, la caisse gouvernementale verse un certain montant pour la caisse de la Police et la caisse EMS, elle verse aussi des potentiels salaires supplémentaires (configurés par le gouverneur sur le site). Ensuite, les caisses Police et EMS versent toutes deux les salaires. Comme déjà expliqué [ici](Le%20Site%20396bc00ea9744a21936f38ca118af44d/BinaryBank%20634059a71ed041f9aea53429fed5023b/Salaire%20c0cb71b6e34844d2b1e239621a106627.md), chaque joueur n’est pas forcément salarié. Puis, les actions des joueurs vont engendrer des mouvements d’argents, à chaque achat, un certain pourcentage du prix payé sera envoyé dans la caisse gouvernementale. La “Taxe” n’est pas visible par les joueurs, c’est à dire que les items ne sont pas plus chers. Ce système permet d’avoir une économie auto-suffisante. Il n’y aura aucun “give” d’argent. Je met entre guillemet le give car il sera possible, dans certains cas, de faire une injection de liquidité dans la caisse gouvernementale (un give en gros) de façon à ce que l’économie redevienne plus stable. (les taux des taxes pourront aussi être modifié mais cela n’aura aucun impact pour les joueurs).

### Questions Fréquentes

- **Comment convertir de l'argent ?**
    
    Sur le serveur se trouvent des ATM (Distributeur automatique de billets). Ceux-ci permettent de `déposer de l'agent` en banque ou, à l'inverse de `retirer de l'argent`. (tuto complet [ici](Syste%CC%80me%20E%CC%81conomique%204fa6e2c8dc2f4527a1f97bf74594a12d.md))