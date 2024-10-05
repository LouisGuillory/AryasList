---
title: Git_Projet_Livrable_Guillory_Louis

---

* Mise en place de la clée SSH sur git pour lier le dépot local git du pc et le compte git pour les dépots distants.
![Capture d’écran 2024-09-28 210307](https://hackmd.io/_uploads/H1Z54ASAR.png)


* Création d'un dépot distant nommé `AryasList`, activation du read.me, et choix de la license `MIT License`.

![Capture d’écran 2024-09-28 210522](https://hackmd.io/_uploads/r1uWERB00.png)


* Création deux fichiers `TODO.md` et `DONE.md` via la commande `$touch`, qui contiendront ensuite respectivement les noms des personnages à éliminer et ceux déjà tués. 
*  Vérification des fichiers en cours de modification avec git.
* Ajout des fichiers à la zone d’index via `$git add`.
* Vérification de la présence des fichiers dans la zone d’index via `$git status`.
![Capture d’écran 2024-09-25 154822](https://hackmd.io/_uploads/SJzf_0hB00.png)

* Commit de “Chore: Initialisation des fichiers” via `$git commit`.
![Capture d’écran 2024-09-25 154746](https://hackmd.io/_uploads/SyWOA2HCA.png)

* Vérification de la présence du commit dans l’historique local via `$git log`. 
![Capture d’écran 2024-09-25 154959](https://hackmd.io/_uploads/SJb_AnrR0.png)

* Edition du fichier TODO.md via `$nano` pour ajouter ces trois personnages:
    - Joffrey Baratheon
    - Cersei Lannister
    - Ilyn Payne
![Capture d’écran 2024-09-25 155228](https://hackmd.io/_uploads/HyWuC2SRA.png)
![Capture d’écran 2024-09-25 155202](https://hackmd.io/_uploads/rJM_02rRA.png)

* Envoie du commit.
![Capture d’écran 2024-09-25 155643](https://hackmd.io/_uploads/SJMu02B0R.png)
![Capture d’écran 2024-09-25 155943](https://hackmd.io/_uploads/r1MdAnHAC.png)

* Modification en conséquence et faire le commit de fix du personnage d’Ilyn Payne du fait du cancer de l’acteur.
![Capture d’écran 2024-09-25 160034](https://hackmd.io/_uploads/B1GO02HRA.png)
![Capture d’écran 2024-09-25 160108](https://hackmd.io/_uploads/rylbuA3BAC.png)
![Capture d’écran 2024-09-25 160209](https://hackmd.io/_uploads/SJzORhHCA.png)

* Visualisation de l’historique pour identifier l’avancement de la branche locale par rapport à la branche distante.
![Capture d’écran 2024-09-25 160307](https://hackmd.io/_uploads/HkMzOAnSRR.png)

* Envoie de l’historique local sur la branche distante.
![Capture d’écran 2024-09-25 160447](https://hackmd.io/_uploads/BJgGOChrAA.png)
![Capture d’écran 2024-09-25 160524](https://hackmd.io/_uploads/ByGfd0nHAC.png)
![Capture d’écran 2024-09-25 160541](https://hackmd.io/_uploads/BJGf_AnHA0.png)

* Vérification du positionnement de la branche locale dans l’historique et constation que les deux branches locales et distantes n’ont plus de différence via `$git push origin main` ou `$git push origin`.
![Capture d’écran 2024-09-25 160929](https://hackmd.io/_uploads/BJefuA2BCR.png)

* Ajout de La Montagne et Meryn Trant dans la liste des personnes à éliminer. + commit
![Capture d’écran 2024-09-25 161051](https://hackmd.io/_uploads/HJxz_A2HAA.png)
![Capture d’écran 2024-09-25 161406](https://hackmd.io/_uploads/B1WzdC3HC0.png)

* modification des deux fichiers pour la mort de Joffrey Baratheon en spécifiant dans le fichier DONE.md que ce n’est pas Arya qui l’a empoisonné. + commit
![Capture d’écran 2024-09-28 183741](https://hackmd.io/_uploads/Bkzd03SC0.png)
![Capture d’écran 2024-09-28 183837](https://hackmd.io/_uploads/SJGzdRnBCR.png)
![Capture d’écran 2024-09-28 184805](https://hackmd.io/_uploads/rylfO0hS0A.png)
![Capture d’écran 2024-09-28 184934](https://hackmd.io/_uploads/ry-fOA2SRA.png)

* Envoie de l'historique sur la branch distante;
![Capture d’écran 2024-09-28 185051](https://hackmd.io/_uploads/rkbMO0nH00.png)

* Création d'une branche local feat/doneByArya et constation de l’historique pour vérifier sur quelle branche est placé le pointeur HEAD.
* Il est sur la branch main.
* Changement de position sur la nouvelle branche avec `$git switch`.
![Capture d’écran 2024-09-28 190334](https://hackmd.io/_uploads/HkbGuR2r00.png)

* Modification des fichiers pour la mort de Meryn Trant.
![Capture d’écran 2024-09-28 190718](https://hackmd.io/_uploads/ByWfd02BR0.png)
![Capture d’écran 2024-09-28 190737](https://hackmd.io/_uploads/SkeMdRhr0R.png)
![Capture d’écran 2024-09-28 191325](https://hackmd.io/_uploads/H1gM_R2rRR.png)
![Capture d’écran 2024-09-28 191625](https://hackmd.io/_uploads/HkGMu0hHA0.png)

* Tentative d'envoie de l’historique sur le dépôt distant.
* Création de la pull request.
![Capture d’écran 2024-09-28 191837](https://hackmd.io/_uploads/rk7GuCnrRR.png)
![Capture d’écran 2024-09-28 192731](https://hackmd.io/_uploads/HkmM_02rCC.png)
![Capture d’écran 2024-09-28 192809](https://hackmd.io/_uploads/HJmG_R3SAA.png)
![Capture d’écran 2024-09-28 192841](https://hackmd.io/_uploads/BJNzuChrCC.png)
![Capture d’écran 2024-09-28 192900](https://hackmd.io/_uploads/H1Qf_A3HAR.png)
* Merge de la pull request.
![Capture d’écran 2024-09-28 193001](https://hackmd.io/_uploads/BybfOChrCA.png)
![Capture d’écran 2024-09-28 193116](https://hackmd.io/_uploads/r17fu0nHC0.png)
![Capture d’écran 2024-09-28 193138](https://hackmd.io/_uploads/r1NGOCnSAC.png)

* Constat du merge dans l'historique local.
![Capture d’écran 2024-09-28 193243](https://hackmd.io/_uploads/HyEzdChSRA.png)

