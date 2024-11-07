# Note de calcul de fixation

## Documentation Technique : Pièce de Support pour Dispositif de Fixation

### 1. Description du Projet

Ce document décrit les spécifications et les calculs nécessaires pour la fabrication d'une pièce de support destinée à un dispositif de fixation pour une machine industrielle. La pièce doit être robuste, légère, et résistante aux contraintes mécaniques. Elle sera imprimée en 3D en utilisant du **PLA** en raison de ses propriétés adéquates pour cette application.

#### Objectifs :

* Créer une pièce support capable de supporter une charge maximale de 50 kg.
* Minimiser le poids de la pièce tout en assurant une résistance adéquate.

### 2. Spécifications Techniques

| Paramètre                 | Valeur     |
| ------------------------- | ---------- |
| Matériau                  | PLA        |
| Volume de la pièce        | 150 cm³    |
| Densité du PLA            | 1.25 g/cm³ |
| Résistance en traction    | 60 MPa     |
| Coût du PLA               | 0.02 €/g   |
| Temps d'impression estimé | 5 heures   |
| Épaisseur des parois      | 2 mm       |
| Précision de l'impression | ± 0,1 mm   |

### 3. Calcul de la Masse de la Pièce

La masse de la pièce peut être calculée à partir de son volume et de la densité du matériau.

#### Formule :

$$
Masse = volume * densité
$$

#### Application :

* Volume de la pièce : V=150 cm3
* Densité du PLA : ρ=1.25 g

$$
Masse =  150 * 1,25 = 187,5g
$$

### 4. Calcul du Coût de Production

Le coût total de production comprend le coût du matériau et, si applicable, les coûts supplémentaires liés à l'énergie et au travail.

#### Coût du Matériau :

$$
Cout = Masse * {Cout par gramme}
$$

#### Application :

* Masse : 187.5 g
* Coût par gramme : 0.02 €/g

$$
Cout = 197,5 * 0,02 = 3,75
$$

**Coût total du matériau : 3.75 €**

#### Coût Total de Production

En supposant un coût énergétique moyen pour l'imprimante de **0.15 €/heure** :

$$
Cout Energie = 5h * 0,15€/h =0,75€
$$

#### Coût Total :

$$
CoutTotal = 3,75 + 0,75 = 4,5€
$$

**Coût total estimé de production : 4.5 €**

### 5. Résistance Mécanique

Pour valider la conception, une estimation de la résistance en traction est effectuée en se basant sur la section transversale effective.

#### Hypothèses :

* Section de la pièce : 10 cm2
* Résistance du PLA : 60 MPa60

#### Calcul :

$$
F_t = section * resistance
$$

#### Application :

$$
F_t =10 * 60 = 600N
$$

La pièce peut supporter une charge jusqu'à 600 N, soit environ **61 kg**, ce qui dépasse l’objectif de 50 kg.
