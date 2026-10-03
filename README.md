# GENEVIEVE Animals / Animal Sense

This repository is the **family index** for the GENEVIEVE animal ecosystem. It is not an application deployment repository.

## Canonical active modules

### Dog Park
Canonical repository: `tracey727/Genevieve-Tracey-Gruff-dog-park-app`

Purpose: dog-park, journey, park-safety and dog-owner experience.

### Kennels / Catteries
Canonical repository: `tracey727/Genevieve-Tracey-kennels-live-demo`

Purpose: kennel/cattery operations, Cats & Dogs interface, staff/owner/transport workflows and safety command.

## Animal Sense

**Animal Sense** is the shared family concept for animal safety, compatibility, care signals and evidence-led alerts that can be reused across approved animal modules. It is a product-family boundary, not a reason to copy whole applications between repositories.

Shared family principles:
- preserve human owner/staff authority;
- label uncertainty rather than guessing;
- keep emergency/safety escalation visible;
- minimise personal/animal data;
- keep module-specific data isolated;
- reuse shared concepts deliberately rather than duplicating entire repositories.

## Preserved archived modules awaiting deliberate extraction

### Animal Nutrition / Feeding / Allergy V1
Historical source package: `tracey727/Genevieve-Business-Deployment/02_ACTIVE_DEPLOYMENTS_NEXT/genevieve_animal_nutrition_feeding_allergy_v1.zip`

This package contains a distinct animal-care module with diet, allergy, feeding schedule, supplement, weight, stock, staff tick-off, incident, emergency and trust screens plus an animal nutrition/allergy schema. It is not present in either current canonical Dog Park or Kennels repository.

**Status:** preserve as a family module candidate. Do not treat the archived ZIP as production-ready. Extract into its own canonical repository before active development or deployment.

### Animal Developer Handover / Technical Architecture V1
Historical source package: `tracey727/Genevieve-Business-Deployment/01_COMPANY_MASTER_FILES/genevieve_animal_developer_handover_technical_architecture_v1.zip`

This is architecture/handover material covering modules, data, API, security, build phases, testing, production warnings and build-lock guidance. It belongs to the Animal Sense family as engineering reference material rather than a deployable animal application.

**Status:** preserve as shared family architecture source. Reuse deliberately; do not copy old deployment assumptions into current builds.

## Repository rule

New animal work should start from one of the two canonical module repositories above, or from a deliberately created shared Animal Sense component. Do not resume development from older Dog Park/Cats & Dogs snapshot repositories.

The previous Dog Park V4 snapshot that was stored on this repository's `main` branch has been removed from the active tree as duplicate historical material. It remains available in Git history.
