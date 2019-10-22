# 4x4
## Noms :
* Gauche a droite 
 * > L l r R
 * > L = Sens Haut vers bas 
 * > R = Sens Bas vers haut
* Haut en bas
 * > U u d D
 * > U = Sens R vers L 
 * > D = Sens L vers R 
* Face profondeur 
 * > F f b B
 * > F = Sens horraire 
 * > B = Sens anti Horraire
* 2 du haut 
 * > Uw2 
## Algs : 
* Parite deux a retourner ( OLL ) 
 * > (r' U2 l F2 l' F2)( r2 U2 r U2 r' U2)(F2 r2 F2)
* Pariete Opposés ( PLL ) 
 * > (Uw2 r2 U2 )r2 (U2 r2 Uw2)
