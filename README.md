Gestion de Salles avec Hibernate et JPA

 Description

Ce projet est un TP pratique de mise en œuvre de Hibernate et JPA . Il permet de gérer des salles et des utilisateurs avec des opérations CRUD complètes et des validations.

 Objectifs du TP

Ce TP nous a permis de :

1.  Créer un projet Maven avec Hibernate 
2.  Configurer la génération automatique du schéma avec `hibernate.hbm2ddl`
3.  Créer deux entités (`Salle` et `Utilisateur`) avec des validations
4.  Implémenter des services pour les opérations CRUD
5.  Tester les opérations CRUD via une application principale et des tests unitaires

 Prérequis

- **Java** 8 ou supérieur
- **Maven** 3.6 ou supérieur
- Un IDE IntelliJ IDEA
<img width="1026" height="517" alt="Capture d’écran 2026-02-18 184109" src="https://github.com/user-attachments/assets/9716573b-0be6-42c8-9563-6fa00e7e07a0" />

Les Entités
Entité Salle
<img width="1026" height="692" alt="Capture d’écran 2026-02-18 190016" src="https://github.com/user-attachments/assets/022cc821-cabd-4d68-92e9-6fcd8fe14434" />
<img width="959" height="677" alt="Capture d’écran 2026-02-18 185713" src="https://github.com/user-attachments/assets/ad42254c-ba23-4ad8-8267-1319b32e477d" />
<img width="1026" height="717" alt="Capture d’écran 2026-02-18 190403" src="https://github.com/user-attachments/assets/be726c53-b8d4-4c4f-8786-597525c49a9a" />
<img width="1026" height="269" alt="Capture d’écran 2026-02-18 185628" src="https://github.com/user-attachments/assets/297ed41f-264a-440c-9d8f-b49a92c943d8" />
<img width="1026" height="316" alt="Capture d’écran 2026-02-18 190107" src="https://github.com/user-attachments/assets/dc06c2d2-9384-4d25-9da6-1a52b03bcf26" />
<img width="1026" height="340" alt="Capture d’écran 2026-02-18 190146" src="https://github.com/user-attachments/assets/2ac6ba74-77af-4e8f-8642-3940856eb02a" />
<img width="1020" height="531" alt="Capture d’écran 2026-02-18 183624" src="https://github.com/user-attachments/assets/a345ffcf-ae6f-42ca-9529-3c9607edb49d" />
<img width="1014" height="259" alt="Capture d’écran 2026-02-18 185327" src="https://github.com/user-attachments/assets/01db7969-bd3f-4c3b-9e24-2992a911ae66" />


 Entité Utilisateur

<img width="1026" height="581" alt="Capture d’écran 2026-02-18 184240" src="https://github.com/user-attachments/assets/45c3c996-5aed-4edf-8de9-fcb148136c7c" />
<img width="1022" height="285" alt="Capture d’écran 2026-02-18 190445" src="https://github.com/user-attachments/assets/86f01640-1235-4cf8-afe6-79a7326c173f" />
<img width="953" height="460" alt="Capture d’écran 2026-02-18 184420" src="https://github.com/user-attachments/assets/46ba6004-7afe-4718-8fec-a466ffc5b7c5" />
<img width="1026" height="267" alt="Capture d’écran 2026-02-18 184031" src="https://github.com/user-attachments/assets/6b4c6708-a0dd-40fb-9087-3ecd91ec6d27" />
<img width="1023" height="290" alt="Capture d’écran 2026-02-18 184148" src="https://github.com/user-attachments/assets/5669d5a2-4a33-4fbd-8732-292b5222eae1" />
<img width="1026" height="611" alt="Capture d’écran 2026-02-18 184500" src="https://github.com/user-attachments/assets/439ad119-2945-458e-85ed-b733f20ff57c" />
<img width="1026" height="258" alt="Capture d’écran 2026-02-18 184959" src="https://github.com/user-attachments/assets/c004b107-441e-4d11-9f4d-a19bde98a2e4" />

 Fonctionnalités Implémentées
Opérations CRUD
Pour Salle :
✅ Créer une salle
✅ Lire une salle par ID
✅ Mettre à jour une salle
✅ Supprimer une salle
✅ Lister toutes les salles
Pour Utilisateur :
✅ Créer un utilisateur
✅ Lire un utilisateur par ID
✅ Mettre à jour un utilisateur
✅ Supprimer un utilisateur
✅ Lister tous les utilisateurs

Les tests couvrent :
La création d'entités
La lecture d'entités
La mise à jour d'entités
La suppression d'entités
Les validations de contraintes
 Technologies Utilisées
Java : Langage de programmation
Maven : Gestion de dépendances et build
Hibernate : ORM (Object-Relational Mapping)
JPA : Java Persistence API

realisee par NESSAIBA MESSAADIYENE 
