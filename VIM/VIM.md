### Vim
---- 

**Insertion**

Désignations | keymaps | 
|--------------|-----------|
 Inserer du texte avant le curseur | i | 
 inserer du texte apres curseur | a | 
 Inserer fin de ligne|A
 Inserer debut de ligne|I
 Inserer en dessous | o | 
 Inserer au dessus|O

---- 
**DÉPLACEMENT**



Désignations | keymaps | 
|---------|----------|
 Fin de ligne | $  | 
 Debut de ligne | 0| 
 Debut du fichier | gg | 
 fin du fichier|G
 Deplacement d'un mot vers l'avant|w
 Deplacement d'un mot vers l'arriere|b
 Place le curseur a la fin du mot|e
 Aller a la ligne N°|CTRL G
 Déplacement vers le Haut|k
 Déplacement vers le Bas|j
 Déplacement vers le Gauche|h
 Déplacement vers le Droite|L
---- 
**EFFACER**


Désignations | keymaps | 
|---------|----------|
Efface le caratére sur le curseur | x | 
Supprime le mot précedent |db| 
efface un mot a partir du curseur jusqu'a la fin du mot | dw| 
efface un mot a partir du curseur | daw| 
Efface la ligne courante | dd | 
efface j'usqua la fin de ligne|D ou d$
efface jusqua debut de ligne|d0(zéro) 
Supprime jusqu'a la prochaine occurence de p|df(p)
---- 
 **MODIFIER**



Désignations | keymaps | 
|---------|----------|
 Remplace un caractere| r | 
 Modifier un mot | cw| 
 Modifie la ligne courante | cc |
subsitution de caractere efface le caractere et insere un nouveau | s |
 modifie la ligne courante | cc |




---- 
 **COPIER COLLER**

Désignations | keymaps | 
|---------|----------|
Copie un mot| yw | 
Copie la ligne courant | yy| 
Colle la ligne courant | p | 
--------------------------

 **RECHERCHER REMPLACER**

Désignations | keymaps | 
|---------|----------|
Remplace la premiere occurence de la ligne ou se trouve le curseur|:s/ancien/nouveau | 
Remplace toutes les occurence de la ligne ou se trouve le curseur|:s/ancien/nouveau/g | 
Remplace toutes les occurence dans les lignes n° # a # du fichiers|:#,#s/ancien/nouveau/g | 
Remplace toutes les occurence dans tous le fichiers|:%s/ancien/nouveau/g | 
Rechercher un mot| /motARechercher |
---- 
 **INDENTATIONS**

Désignations | keymaps | 
|---------|----------|
Reindente tous le document|gg=G
Indente la ligne|== (double egale) 
Indente a gauche| < 
Indente a Droite| > 
-------------------
 **DIVERS**

Désignations | keymaps | 
|---------|----------|
vas au acooclades et parentheses fermante et ouvrante |%
Selectionne entre les parenteses|vib 
Selectionne entre les accolades|vIb 
Supprime un bloc de code entre {}|daB 
Passe le mot en MAJUSCULES|gUw 
Passe le mot en minuscules|guw 
Annuler l'action|u  
defaire|CTRL Z  
Occurence de mot|*  
Refaire l'action précédente|.  
Incremente le nombre sous le curseur|CTRL + a  
Décremente le nombre sous le curseur|CTRL + x  


