# Intégration au puzzle SIIAOS

```yaml
siiaos_puzzle_version: "2026-09-25"
integration_status: "SURFACE"
truth_status: "CODED"
authority: "none by default"
canonical_reference: "yannickaudubert/twinSIIAOS/docs/SIIAOS_PUZZLE.md"
```

## Rôle dans le SIIAOS

Surface de maturation, transmission et mise en commun des connaissances. Elle reçoit uniquement des objets dont la provenance, le statut et les droits permettent la diffusion.

## Ce que cette brique implique

- Une trace ou hypothèse ne devient pas savoir validé par publication.
- Le passage privé -> travail -> partage -> public doit être explicite.
- Les données client/personnelles restent hors du commun sauf base légale et autorisation explicites.

## Ce qui peut l'impliquer

- KnowledgeAdmission
- teaching/publication workflows
- commons production

## Capabilities fournies

- knowledge publication
- learning paths
- corpus
- governance of public/common knowledge
- pedagogical transformation

## Capabilities consommées

- KnowledgeAdmission
- sources/provenance
- validated methods
- public/reusable RETEX
- publication policies

## Interfaces et contrats

Les interfaces propres au dépôt restent valides dans leur périmètre, mais elles doivent pouvoir se rattacher aux objets SIIAOS pertinents : Identity, Authority, Mandate, Policy, NeedSpec, ContextPack, Capability, Mission, Decision, OperationRecord, Evidence, DesiredState, ObservedState et ChangeSet.

Aucune interface locale ne doit créer silencieusement une seconde source de vérité.

## Données, autorité et confidentialité

- Les accès sont explicitement bornés par identité, rôle, autorité, mandat et policy.
- `Identity != Role != Authority`.
- Les données client, personnelles, confidentielles ou secrètes restent dans leur périmètre d'autorité.
- Source originale, index, RAG, synthèse, interface et canon sont distincts.
- Une capacité technique ne crée jamais une permission.

## Evidence attendue

- Git provenance
- source links
- epistemic status
- review/publication decisions

Une capacité ne doit être déclarée opérationnelle qu'après preuve adaptée au risque.

## Non-rôles

- mémoire privée exhaustive
- RAG canonique
- autorité scientifique automatique
- réceptacle de données confidentielles

## Truth gates

Toujours distinguer :

`PROPOSÉ != CODÉ != TESTÉ != DÉPLOYÉ != OBSERVÉ != PROUVÉ`

et :

`DesiredState != ObservedState`

Les états runtime doivent être reliés à une preuve datée.

## Conditions de promotion

Une intégration peut progresser de CANDIDATE/CONVERGENCE vers ACTIVE lorsque ses contrats, permissions, données autorisées, tests, preuves, mécanismes de repli et conditions de retrait sont explicites et vérifiés.

## Retrait / rollback

La brique doit pouvoir être remplacée ou retirée sans perdre les sources, décisions, Evidence, provenance et capacité de reprise.

## Référence canonique

Le puzzle complet et le contrat documentaire commun vivent dans `twinSIIAOS/docs/`. Cette fiche locale explique uniquement la place de ce dépôt et ne remplace pas le document canonique.
