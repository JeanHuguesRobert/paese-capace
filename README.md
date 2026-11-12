---
title: "Paese Capace — assistant de pré-dossier territorial"
description: "Prototype d'aide à la formulation de projets communaux ; déploiement public non encore confirmé."
author: unknown
affiliation: "Institut Mariani / C.O.R.S.I.C.A."
date: null
last_modified_at: "2026-11-13"
status: working-paper
language: fr
license: unknown
document_role: project
document_kind: project-readme
visibility: public
lifecycle_state: working
canonical_url: https://github.com/JeanHuguesRobert/paese-capace/blob/main/README.md
update_policy: UP-DEFAULT-REVIEWED
provenance:
  origin_type: repository
  origin_repository: JeanHuguesRobert/paese-capace
  origin_ref: unknown
  origin_date: unknown
  derived_from: []
review:
  status: unreviewed
  reviewed_by: []
---

# Paese Capace

Assistant de pré-dossier pour les petites communes corses souhaitant répondre aux appels à projets du dispositif **Territorii, Pieve è Paesi vivi**.

**Site public : non disponible au contrôle du 13 novembre 2026.** Le domaine envisagé `paesecapace.fractavolta.com` ne résout pas encore en DNS. Ne pas le présenter comme une application en service.

**Suivi du déploiement et de la recette :** [paese-capace #1](https://github.com/JeanHuguesRobert/paese-capace/issues/1).

## Objet

Paese Capace aide une commune, un élu, un secrétaire de mairie ou un citoyen engagé à transformer une idée de projet local en pré-dossier clair :

- problème concret ;
- projet envisagé ;
- bénéficiaires ;
- intérêt territorial ;
- compatibilité probable avec le dispositif ;
- pièces à réunir ;
- points de vigilance ;
- calendrier avant dépôt.

## Cadre de l’initiative

Paese Capace est une offre d’accompagnement bénévole proposée sous l’égide de l’Institut Mariani, émanation R&D de l’association C.O.R.S.I.C.A.

Les outils techniques sont mis gracieusement à disposition par la société SAS FractaVolta.

Il ne s’agit pas d’une prestation commerciale, ni d’un service mandaté par la Collectivité de Corse.

L’objectif est d’aider les petites communes à formuler plus clairement leurs projets, afin de faciliter leur compréhension, leur discussion et leur éventuelle instruction par les services compétents.

## Source officielle

Le dispositif Territorii, Pieve è Paesi vivi est présenté par la Collectivité de Corse ici :

https://www.isula.corsica/territorii

Cette page est la référence officielle.  
Paese Capace est seulement un outil d’aide à la formulation d’un pré-dossier.

## Deux chemins

### 1. Utilisateur à l’aise avec l’IA

L’utilisateur copie le prompt fourni dans `prompt.md`, puis le colle dans son agent IA préféré : ChatGPT, Claude, Mistral, Perplexity, etc.

### 2. Utilisateur souhaitant être accompagné

**Parcours envisagé, non vérifié en production :** l’utilisateur remplirait un formulaire simple pour qualifier la demande et amorcer un échange. Le fonctionnement réel du formulaire, ses garanties de confidentialité et tout éventuel acheminement de messages restent à vérifier avant leur annonce comme disponibles (voir [issue #1](https://github.com/JeanHuguesRobert/paese-capace/issues/1)).

## Principe

Paese Capace ne se substitue pas aux services instructeurs de la Collectivité de Corse.

Il vise seulement à rendre les projets plus lisibles, plus comparables et plus faciles à discuter avant leur dépôt.

Plus les besoins sont formulés tôt et clairement, plus les arbitrages deviennent visibles.

## État

MVP statique décrit dans ce dépôt ; accessibilité publique non établie.

Aucune base de données au départ.  
Le CRM viendra ensuite.
