#Présentation Sqlite3

### Installation de Sqlite3 ######################

1-Téléchargement des fichiers a l'adresse  https://www.sqlite.org/download.html (Vous prenez "Precompiled Binaries for Windows =>sqlite-dll-win32-x86-3350400.zip & sqlite-tools-win32-x86-3350400.zip")

2-Déziper les deux fichier .zip puis crée un dossier a la racine du disc C

3-Inserer les fichier contenue dans .zip  dans le nouveau dossier crée

4-Puis clique droite sur le "Ce PC" => propriété ==> paramètre du système avancés==> variable environement puis vous ajoutez le lien "C:\sqlite" dans la variable environement

5- Lacement de l'invité de commande cmd pour excecuter Sqlite3

6-On ce place dans le dossier Sqlite Crée a la racine du disc C

7-Taper la commande slqite3 pour excecuter 

8-Pour voire les differentes commande de sqlite3 vous taper .help

9-Pour ouvrire ou crée une base de données on tape la commande .open nom_base_donnees.db

10-verifier que le fichier a été bien crée dans le dossier sqlite crée a la racine

11-Pour voire la base qui est selectioné on tape la commande .show

12-Lien de la documentation pour voire le fonctionement du scripte sqlite3 https://www.sqlite.org/docs.html

12-lien pour apprendre les commande sql afin d ebien maitriser le sqlite3 https://sql.sh/

13-Pour crée une table on utilise la Syntaxe create table users(id integer primary key autoincrement, nom text, prenom text, age float, numero numeric);

14 . selectionne ma base de données avec la syntaxe select*from users;

15. Pour afficher le nom de la table on ecrire .tables;

16- ouverture du logiciel DB Browser for SQLite pour vursualiser ma base de donnée crée

17-Pour insérer les données dans notre table crée. taper la syntaxe insert into users(nom,prenom,age,numero) values('keita', 'abdou karim', 25, 09909290);



18-télécharger & insatller le logiciel  a l'adresse  https://sqlitebrowser.org/dl/ => DB Browser for SQLite - Standard installer for 64-bit Windows.

19- Entrainer vous avec les commande sql......................

