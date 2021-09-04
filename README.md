<h1>
<div align="center">
KonorySis | Application CRUD de gestion des étudiants 
</div>
</h1>

<h2>
Description du cahier de charge 
</h2>
<p>Ce projet académique et tutoré est centré autour de la création d'une application de gestion des étudiants scindée en deux interfaces graphiques d'authentification :
  <li>Une interface professeur</li>
  <li>Une interface coordinateur</li>
  </p>
  <p>
  Il s'agit alors d'informatiser les plans d'étude instaurés par le service de scolarité en laissant le plein droit aux professeurs et aux coordinateurs d'apporter leur champ de modification au niveau des attributions de notes, de la décision du jury ainsi que de la consultation de leur emploi du temps.
 </p>

<p><ins>Les professeurs doivent pouvoir :</ins>
  <li>Renseigner la liste d’absence des bacheliers.</li>
  <li>Paramétrer et indexer la grille d’évaluation de leur propre module 
(coefficient de TP et des partiels, quantifier le nombre de séances 
selon sa nature : CM, TD, TP…)</li>
    <li>Renseigner les notes finales de chaque étudiant selon la session 
choisie (session normale ou session de rattrapage) et y émettre le 
verdict du jury de délibération (Validé, non validé, passage en session 
de rattrapage…), le tout sous un format PDF imprimable.</li>
   <li>Consulter l’emploi du temps d’affectation de chacun des cours ou TD
prodigués.</li>
 </p>
 <p><ins>Les coordinateurs doivent pouvoir :</ins>
  <li>Procéder à l’ajout ou la suppression d’un étudiant de la liste des 
bacheliers (admission parallèle ou cas de démission ou d’ajournement 
définitif des élèves)</li>
  <li>Paramétrer et indexer la grille d’évaluation de leur propre module 
(coefficient de TP et des partiels, quantifier le nombre de séances 
selon sa nature : CM, TD, TP…)</li>
    <li>Modifier les informations personnelles ou les informations d’état d’un 
bachelier</li>
   <li>Modifier les informations personnelles ou les informations d’état d’un 
professeur</li>
  <li>Consulter l’historique des modifications établies par le professeur</li>
 </p>
<h3>Fonctionnement et arborescence</h3>
<p><strong>Diagramme de décomposition d'événements</strong></p>
<img class="fit-picture"
     src="https://scontent.frba1-2.fna.fbcdn.net/v/t1.15752-9/241366898_596721574673301_6880587538151448141_n.png?_nc_cat=110&ccb=1-5&_nc_sid=ae9488&_nc_eui2=AeG58dcZDNvnTOCxwF1GTX9sMByNElVstHIwHI0SVWy0cpMimsyxTyWBwWdA-QMDXUjVcSvFsnskAFQSdbPk_Y7h&_nc_ohc=n9m7kTDEz3cAX9wnuy1&_nc_ht=scontent.frba1-2.fna&oh=0b98c77209c2384f7533fb34a5416ec2&oe=6159D944">
<p><strong>Diagramme de contexte</strong></p>
<img class="fit-picture"
     src="https://user-images.githubusercontent.com/75435299/132094649-7d51dc2e-6c8f-43c7-92c7-827c3bbb5534.png">

<h3>
 Technologies et frameworks
</h3>
<li>Front-end : JavaFX + Scene Builder </li>
<li> Back-end : JDBC + MySQL (SGBD) </li>
<img class="fit-picture" width="100px"
     src="https://scontent.frba1-2.fna.fbcdn.net/v/t1.15752-9/148523929_156818559589293_5681294237760392390_n.png?_nc_cat=105&ccb=1-5&_nc_sid=ae9488&_nc_eui2=AeH0rRCjSazi1PB1b9bkhbcP9m6aSwRgLwP2bppLBGAvA2s4XUGrAo-wZdhwfUd94SpNtq_1KduZIoQ1eLyafj8k&_nc_ohc=yWa3vlgtHCgAX_Vghwr&_nc_ht=scontent.frba1-2.fna&oh=fa3b1ab78e9c5fd8f0ebca624ef91f06&oe=615AF56D"><img class="fit-picture" width="100px"
     src="https://scontent.frba1-1.fna.fbcdn.net/v/t1.15752-9/241405486_213198240828603_534336563863857931_n.png?_nc_cat=103&ccb=1-5&_nc_sid=ae9488&_nc_eui2=AeEl0G1cZbJnv9S2cMypuGWwI4Aooxt5dvsjgCijG3l2-xjuhQ5jZJ6kVdG2N2AQYPgs90aNc8Wd0yRcwaRFisYp&_nc_ohc=eYvuMkDh2MIAX8XPZtw&_nc_ht=scontent.frba1-1.fna&oh=12ab91b824eebb5a198b597f2d1dc48a&oe=61582FA1">
