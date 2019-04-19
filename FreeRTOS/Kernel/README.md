MISE AU POINT
=============

Configuration CubeMX
--------------------
0) Création du projet CubeMX "from scratch"
1) L'horloge FreeRTOS est calée sur TIMER2
2) Conséquence ; Clock Solver asked lorsque je sélectionne l'onglet "Clock Configuration" => Automatiquement, les divisieurs se cales et la Clock System passe à 50 MHz.


Projet Atollic
--------------
1) Il a fallu aller dans Menu => File => Import => Existing project into workspace
		sinon ça plante!


Code source
-----------
1) 1er lancement Ok
2) Implémentation de 
	a) allumage de USER LED Red au lancement de StartDefaultTask
	b) allumage de USER LED Blue au lancement de StartTask02 puis blink LED à l'infini



