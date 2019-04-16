Découvrir l'embarqué avec un blink LED
======================================

Heartbeat 1
-----------
utilisation d'un compteur logiciel : la mauvaise méthode à faire une fois!
Donne un cas interessant de l'utilisation de 'volatile' et permet de jouer avec l'optimisation du code '-Os'
==> Introduction de la notion de ressources limitées : possibilité de demander une optimisation du code (binaire à faire rentrer au chausse pied)

Heartbeat 2
-----------
Utiliser un compteur issu des ressources hardware et des librairies disponibles du µC (HAL_Delay)
==> On privilégie l'utilisation de ressources hardware

Heartbeat 3
-----------
Implémentation de la fonction marche/arrêt sur le clignotement en partant de l'exercice précédent : bouton poussoir en interruption
==> On ralentit le clignotement pour s'apercevoir que la réaction de l'appuis bouton ne provoque pas l'arrêt immédiat du blink 
==> Rentrer dans HAL_Delay() avec les étudiants pour confirmer qu'elle est bloquante

Heartbeat 4
-----------
Résoud le problème précédent en utilisant un Timer du µC programmé en interruption
==> Introduction de la notion de temps réel (relative).
==> 1er notion de parallélisation hardware/software
==> On enfonce le clou sur l'utilisation de ressources hardware
