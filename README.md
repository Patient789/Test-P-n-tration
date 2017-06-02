Méthodologie de test de pénétration d'application Web

Pour effectue un test complet de pénétration d'applications Web pour réduire le risque de compromis et améliorer la conformité. 
La méthodologie est alignée sur les meilleures pratiques de NIST et OWASP. Le test de pénétration est effectué par les consultants supérieurs en sécurité avec les certifications CISSP, CISA, CISM, GCIH, GPEN, GWAPT, GXPN.

Principales caractéristiques et avantages:

        (1)Des tests complets de pénétration d'applications Web permettent de déterminer les problèmes de sécurité bien connus et "Zéro jour" sur le site Web cible
        (2)Une évaluation complète des risques permet de prioriser les actions d'assainissement
        (3)Le rapport de test de pénétration peut être utilisé pendant les processus externes de conformité et de certification, tels que les certifications ISO27001, PCI DSS, SOC 2, etc.

Le test est exécuté selon la méthodologie suivante:


      Étape 1. Recherche ciblée.

L'ingénieur  recevra les informations sur la cible que vous souhaitez évaluer. Les informations comprennent l'URL de l'application Web, les critiques, etc. L'ingénieur se connecte ensuite à la cible pour confirmer que le site Web peut être atteint et scanné. L'ingénieur fera également un exemple de vérification des pages et du sous-dossier pour s'assurer que le site Web cible fonctionne correctement. Au cours de cette étape, l'ingénieur déterminera également la technologie de backend utilisée pour l'application Web (Wordpress CMS, Drupal, Joomla, CMS commercial, etc.).

      Étape 2. Processus métier et gestion logique des applications

L'ingénieur de sécurité explore manuellement l'application et mappe les fonctions professionnelles qu'elle exécute et les processus qu'elle prend en charge. Selon le type d'application Web (portail Logiciel en tant que service, portail bancaire en ligne, boutique e-commerce, etc.), le testeur déterminera la matrice de contrôle d'accès et identifiera les niveaux de privilèges d'utilisateur, les actions autorisées et les résultats souhaités .

      Étape 3. Configuration du scanner d'application Web et modification.

Pour  utiliser plusieurs scanners de sécurité des applications Web pour évaluer la sécurité de l'application Web. La liste des scanners comprend à la fois des outils de sécurité commerciaux et gratuits utilisés par les professionnels de la sécurité et les pirates. Cette étape est essentielle pour s'assurer que le scanner couvre toute l'application et que chaque page est évaluée pour des problèmes de sécurité. L'ingénieur modifiera également le scanner en fonction de la technologie et du cadre du site (ASP.NET, PHP, AJAX, etc.). La configuration du scanner Web est un processus à forte intensité de main-d'œuvre et nos ingénieurs ont utilisé leur vaste expérience et leur connaissance des problèmes d'application Web afin d'optimiser les performances de l'analyse.

      Étape 4. Rechargement automatisé du site Web.

L'ingénieur  instruira ensuite le scanner d'application Web pour explorer le site Web et déterminer quelles pages sont disponibles pour un utilisateur non authentifié. Le scanner d'application Web visitera chaque page du site et déterminera l'arbre du site.

      Étape 5. Mise en page du site Web.

L'ingénieur de sécurité passera en revue l'arborescence du site qui a été construite lors de l'exploration automatique du site Web, puis vérifie-la manuellement. L'ingénieur va également explorer manuellement le site Web et déterminer les zones qui n'ont pas été vérifiées par le scanner automatisé. Si une application cible contient des formulaires d'authentification ou des zones restreintes, l'ingénieur s'identifie manuellement et assurez-vous que les zones restreintes sont rampées et ajoutées à l'arborescence du site.

      Étape 6. Analyse automatisée de la vulnérabilité Web non authentifiée.
  
 L'ingénieur va ensuite démarrer l'analyse automatisée de la sécurité afin de déterminer les problèmes de sécurité sur les pages identifiées. Le scanner teste toutes les entrées de la page Web pour les vulnérabilités communes de l'application Web, telles que l'injection SQL, Cross Site Scripting (XSS), Cross Frame Scripting, les inclusions de fichiers locaux (LFI), les inclusions de fichier distant (RFI), les répertoires par défaut et plusieurs Autres problèmes de sécurité du site Web. La numérisation sera exécutée de manière contrôlée et n'introduira qu'un impact de performance minimal sur votre application Web.
 
      Étape 7. Analyse automatisée de la vulnérabilité Web authentifiée.
     
Le testeur effectuera alors le test de sécurité automatisé sur les parties de l'application Web cible qui nécessite la connexion. Les exemples incluent les zones d'adhésion, les zones de réservation en ligne, les formulaires de collecte de données, les sites Web de promotion, etc. L'analyse est contrôlée pour s'assurer que L'impact minimal est effectué sur le système de production ou sur l'infrastructure du serveur.

      Étape 8. Test de vulnérabilité Web manuel.

Cette étape comprend les actions et les tests pour identifier les vulnérabilités non saisies par le scanner de sécurité automatisé. L'ingénieur utilisera les outils écrits personnalisés et les tests manuels pour diffuser l'application et déterminer les lacunes dans la logique de l'application. Les tests prendront en compte les fonctions et les processus opérationnels de l'application. Les problèmes communs identifiés lors de cette étape sont les problèmes de gestion de mot de passe, les problèmes de gestion du cycle de vie des comptes, les problèmes de contrôle d'accès, les dérivations de restrictions d'application, etc.

      Étape 9. Exploitation de vulnérabilité Web.
     
Le testeur de sécurité tentera alors d'exploiter les problèmes de sécurité identifiés pour déterminer le risque commercial de la découverte. Les consultants utilisent des exploits écrits, commerciaux et personnalisés pour extraire les données d'une application. 
Par exemple, en utilisant l'injection SQL, il est possible de décharger toutes les informations de la base de données SQL backend ou même de prendre le contrôle d'un serveur Web entier. Si le testeur trouve la fonctionnalité de téléchargement du fichier non protégé, il est possible de télécharger le shell Web pour exécuter les commandes du système. L'exploitation se fait manuellement dans un environnement contrôlé pour assurer la sécurité des données extraites. Le testeur demandera également une autorisation explicite avant d'exploiter la vulnérabilité.

      Étape 10. Examen des résultats, élimination des triages et des faux positifs

Les scanners de vulnérabilité automatisés du site Web produisent souvent de faux positifs. L'ingénieur inspectera et validera manuellement les problèmes de sécurité pour supprimer ces faux positifs. L'ingénieur effectuera également un triage des constatations de sécurité afin de déterminer le risque, l'impact et le risque de sécurité du problème de sécurité identifié. Cette étape nous aide également à modifier le système afin de minimiser l'apparition de faux positifs dans les analyses futures.

      Étape 11. Évaluation des risques commerciaux.

Sur la base des résultats de l'analyse automatisée de la sécurité et des tests de pénétration manuelle, le consultant en sécurité déterminera les risques commerciaux des vulnérabilités. Plusieurs facteurs sont pris en compte: le type de données auxquelles le testeur pourrait avoir accès, la facilité d'exploitation et la probabilité que quelqu'un trouve le problème. Utiliser la méthodologie globale d'évaluation des risques basée sur les meilleures pratiques de l'industrie pour déterminer le risque commercial.

      Étape 12. Publication des résultats.
 
Lorsque le test de pénétration de l'application Web est terminé, les résultats sont publiés sur le tableau de bord basé sur le Cloud sécurisé des clients . Les clients peuvent se connecter en ligne et examiner les résultats de leur évaluation de sécurité. Le tableau de bord permet aux clients d'exporter les résultats au format CSV, PDF ou HTML pour la distribution hors ligne. 
