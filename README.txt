Introduction
Ce projet implémente un système de contrôle d'accès en Java. Le système utilise des cartes et des codes pour accorder ou refuser l'accès et déclencher une alarme après plusieurs tentatives incorrectes. Ce projet se décompose en quatre étapes :

Spécification du Système avec la Logique Formelle

Modélisation du Système avec des Automates et Langages Formels

Conception de Circuits Logiques avec l'Algèbre de Boole

Vérification et Validation Formelle du Système

Structure du Code
Le code est structuré dans une seule classe principale ControlAccessSystem avec une méthode main pour exécuter toutes les étapes.

Étape 1 : Spécification du Système avec la Logique Formelle
Description : Spécifie les règles logiques du système.

Méthode : specificationLogiqueFormelle()

Étape 2 : Modélisation du Système avec des Automates et Langages Formels
Description : Modélise le système en utilisant des automates.

Méthode : modelisationAutomate()

Étape 3 : Conception de Circuits Logiques avec l'Algèbre de Boole
Description : Conçoit les circuits logiques et teste des combinaisons de cartes et de codes.

Méthode : conceptionCircuitsLogiques()

Étape 4 : Vérification et Validation Formelle du Système
Description : Vérifie que le système respecte les spécifications et exécute des tests de validation.

Méthode : verificationValidationFormelle()

Utilisation
Pour exécuter ce programme, il suffit de lancer la méthode main de la classe ControlAccessSystem.

java
public static void main(String[] args) {
    ControlAccessSystem system = new ControlAccessSystem();

    // Étape 1 : Spécification du Système avec la Logique Formelle
    system.specificationLogiqueFormelle();

    // Étape 2 : Modélisation du Système avec des Automates et Langages Formels
    system.modelisationAutomate();

    // Étape 3 : Conception de Circuits Logiques avec l'Algèbre de Boole
    system.conceptionCircuitsLogiques();

    // Étape 4 : Vérification et Validation Formelle du Système
    system.verificationValidationFormelle();
}
Exemple d'Entrée et de Sortie
Entrée : Identifiant de la carte et code d'accès.

Sortie : Messages indiquant si l'accès est accordé, refusé ou si l'alarme est déclenchée après plusieurs tentatives incorrectes.

Exemples
Carte : 1234, Code : MIAGE2025

Sortie : "Accès accordé"

Carte : 0000, Code : MIAGE2025

Sortie : "Accès refusé"

Carte : 1234, Code : incorrect (répété 5 fois)

Sortie : "Alarme déclenchée"

Tests
Des méthodes de test sont incluses pour valider le fonctionnement correct du système :

testAccesAccorde(ControlAccessSystem system)

testAccesRefuse(ControlAccessSystem system)

testAlarmeDeclenchee(ControlAccessSystem system)

Ces méthodes vérifient que le système accorde l'accès, refuse l'accès ou déclenche l'alarme selon les règles définies.

Conclusion
Ce projet implémente un système de contrôle d'accès complet en utilisant la logique formelle, les automates, les circuits logiques et la vérification formelle. Il offre un exemple pratique d'intégration de plusieurs concepts de l'informatique théorique et appliquée.
