# AI Digital Backbone propulsé par InterSystems

[English version](README.md)

## L’idée en un paragraphe

La plupart des organisations construisent leur IA projet par projet. Chaque projet a sa propre copie de données, sa propre intégration et sa propre gouvernance. Les pilotes s’enlisent avant le passage à l’échelle, et chaque nouveau cas d’usage ajoute de la fragmentation. Le problème n’est pas le modèle d’IA, c’est l’architecture qui le sous-tend.

Un **digital backbone** (colonne vertébrale numérique) est une couche de données unifiée : une source unique pour accéder à la vérité. Ce n’est pas un produit. C’est une **discipline d’architecture**, une façon de construire qui permet à l’IA de passer à l’échelle.

## Ce qui en fait une colonne vertébrale

Deux capacités :

1. **Une interopérabilité inégalée.** N’importe quel système, n’importe quel modèle de données, n’importe quel format, connecté une seule fois. La santé en est la preuve : HL7 v2, documents CDA, FHIR, DICOM, X12, flux de dispositifs, fichiers et texte libre, avec 48 ans d’expérience de la connexion des données de santé (1978 à 2026).
2. **Une gestion des données en temps réel.** Un plan de données commun où les données sont à jour dès qu’elles changent, dédupliquées, et projetées plutôt que copiées. Les transferts en masse conviennent à l’analytique. L’IA a besoin des données au fil de l’eau.

Résultat : des données qui comprennent ce qui est connecté, qui sont interrogeables et analysables, et qui servent plusieurs cas d’usage en même temps.

## Le parcours : enregistrement, analyse, intelligence

| Étape | Ce qu’elle vous dit | S’appuie sur |
| --- | --- | --- |
| Systèmes d’enregistrement | Ce qui s’est passé | L’interopérabilité |
| Systèmes d’engagement / d’analyse | Ce que cela signifie | La gestion des données en temps réel |
| Systèmes d’intelligence | Quoi faire ensuite | Outils et agents d’IA, sous le contrôle des personnes |

## Les quatre piliers

Pour déployer l’IA à grande échelle, il faut quatre conditions :

- **Confiance.** La confiance comme capacité : un accès fiable aux données structurées, semi-structurées et en texte libre, au même endroit.
- **Calcul.** Amener le calcul aux données. Recherche vectorielle, RAG avancé, gestion des prompts, Python, JSON, API d’IA et MCP fonctionnent sur la même couche de données, sans déplacement de données.
- **Gouvernance.** Gouvernez une fois, déployez partout. Moins de points de contact, protection unifiée, règles d’accès définies une fois et réutilisées, meilleur audit.
- **Coûts maîtrisés.** Pas de prolifération de bases de données, de licences et de services d’IA. Réutilisez l’existant et n’achetez que le nécessaire.

## Connectez une fois, réutilisez partout

Les sources alimentent des adaptateurs santé. Les services FHIR exposent ensuite les données à tous les consommateurs : applications cliniques, portails et applications patients, outils et agents d’IA, partenaires et réseaux régionaux, analytique. Chaque nouveau cas d’usage réutilise ce qui existe déjà, ce qui fait baisser le coût du suivant.

## La santé comme preuve

La santé est un secteur très réglementé, aux données fragmentées et sensibles au temps, avec une marge d’erreur faible. La présentation déroule des exemples concrets :

- **InterSystems IntelliCare** (un DPI natif IA) pilote l’activité et joue le rôle de colonne vertébrale du dossier. Le Digital Backbone étend sa portée aux systèmes qui l’entourent (dispositifs, CRM, ERP et finance, payeurs, registres, imagerie, génomique, action sociale).
- **HealthShare** offre une vue unique du patient et un plan de soins partagé. La colonne vertébrale y ajoute l’organisation autour : qui est en retard, combien coûte la prochaine étape, si la capacité existe.
- **Des scénarios en direct** (tournée du matin, urgences, administration et gestion des lits, etc.) montrent des agents d’IA à l’œuvre sur une seule couche gouvernée, avec un humain qui valide les décisions importantes.

Le même schéma s’applique aux services financiers, au secteur public et à l’industrie : données de confiance, gouvernance intégrée et une seule fondation sous de nombreux cas d’usage.

## Le dossier économique en une page

Le retour sur investissement enchaîne cinq facteurs : **volume x référence x effet x adoption = bénéfice**. Pour l’établissement type (100 000 consultations externes par an), le scénario de base donne :

- environ 6 570 heures cliniques libérées par an (environ 4,3 ETP) ;
- environ 2,67 M£ de valeur de capacité par an (fourchette prudente à optimiste de 1,32 M£ à 3,50 M£) ;
- une baisse de 13,1 % de l’attente moyenne.

Il s’agit de capacité libérée, pas de trésorerie, et de bénéfices potentiels issus de données publiées, pas de prévisions. Les chiffres du parcours cancer sont illustratifs. La présentation propose des curseurs interactifs pour chaque famille de cas d’usage.

## La question de conclusion

Arrêtez de vous demander « quelle IA construire ensuite ? ». Demandez-vous plutôt : « sur quelle fondation construisons-nous ? »
