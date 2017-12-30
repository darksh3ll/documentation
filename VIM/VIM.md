#Vim

---- 

**INSERTION**

Désignations | keymaps | 
|--------------|-----------|
 Inséré du texte avant le curseur | i | 
 inséré du texte après curseur | a | 
 Inséré fin de ligne|A
 Inséré début de ligne|I
 Inséré en dessous | o | 
 Inséré au-dessus|O

---- 
**DÉPLACEMENT**



Désignations | keymaps | 
|---------|----------|
 Fin de ligne | $  | 
 Début de ligne | 0| 
 Début du fichier | gg | 
 fin du fichier|G| 
  Déplacement d'un mot vers l'avant|w| 
  Déplacement d'un mot vers l'arrière|b|
 Place le curseur à la fin du mot|e|
 Aller à la ligne N°|CTRL G|
 Déplacement vers le Haut|k|
 Déplacement vers le Bas|j|
 Déplacement vers le Gauche|h|
 Déplacement vers le Droite|L|
 
---- 
**EFFACER**

On peut combiner les touches et passer en mode insertion

exemple:

    cb supprime le mot précèdent et passe en mode insertion
    dw efface le mot et passe en mode insertion


Désignations | keymaps | 
|---------|----------|
Efface le caractère sur le curseur | x | 
Supprime le mot précédent |db| 
efface un mot à partir du curseur jusqu'à la fin du mot | dw| 
efface un mot à partir du curseur | daw| 
Efface la ligne courante | dd | 
efface jusqu'à la fin de ligne|D ou d$
efface jusqu'à début de ligne|d0(zéro) 
Supprime jusqu'à la prochaine occurrence de p|df(p)
Supprime le mot  " { ( ' |di " ou di { ou di {

---- 

 **MODIFIER**



Désignations | keymaps | 
|---------|----------|
 Remplace un caractère| r | 
 Modifier un mot | cw| 
 Modifie la ligne courante | cc |
substitution de caractère efface le caractère et insère un nouveau | s |
 modifie la ligne courante | cc |




---- 

 **COPIER-COLLER**

Désignations | keymaps | 
|---------|----------|
Copie un mot| yw | 
Copie la ligne courant | yy| 
Colle la ligne courant | p | 

--------------------------


 **RECHERCHER REMPLACER**

Désignations | keymaps | 
|---------|----------|
Remplace la première occurrence de la ligne ou se trouve le curseur|:s/ancien/nouveau | 
Remplace toutes les occurrences de la ligne ou se trouve le curseur|:s/ancien/nouveau/g | 
Remplace toutes les occurrences dans les lignes n° # a # du fichiers|:#,#s/ancien/nouveau/g | 
Remplace toutes les occurrences dans tout le fichier|:%s/ancien/nouveau/g | 
Rechercher un mot| /motARechercher |

---- 

 **INDENTATIONS**

Désignations | keymaps | 
|---------|----------|
Reindente tout le document|gg=G
indente la ligne|== (double égale) 
Indente a gauche| < 
Indente a Droite| > 

-------------------

 **DIVERS**

Désignations | keymaps | 
|---------|----------|
Va aux accolades et parenthèses fermantes et ouvrantes |%
Sélectionne entre les parenthèses|vib 
Sélectionne entre les accolades|vIb 
Supprime un bloc de code entre {}|daB 
passe le mot en MAJUSCULES|gUw 
passe le mot en minuscules|guw 
annuler l'action|u  
défaire|CTRL Z  
Occurrence de mot|*  
Refaire l'action précédente|.  
Inclémente le nombre sous le curseur|CTRL + a  
décrémente le nombre sous le curseur|CTRL + x  
Entourer un mot de quotes|ciw"" ESC P 


