# @backstage/plugin-scaffolder-common

## 0.2.0

### Minor Changes

- 5e585bbc7f: **BREAKING**: Removed the `templateEntityV1beta3Schema` export

### Patch Changes

- e72d371296: Added `TemplateEntityV1beta2` which was moved here from
  `@backstage/plugin-scaffolder-common`. It has also been marked as deprecated in
  the process - please consider [migrating to `v1beta3`
  templates](https://backstage.io/docs/features/software-templates/migrating-from-v1beta2-to-v1beta3).
- Updated dependencies
  - @backstage/catalog-model@0.10.0

## 0.1.3

### Patch Changes

- Updated dependencies
  - @backstage/catalog-model@0.9.10

## 0.1.3-next.0

### Patch Changes

- Updated dependencies
  - @backstage/catalog-model@0.9.10-next.0

## 0.1.2

### Patch Changes

- d078377f67: Support navigating back to pre-filled templates to update inputs of scaffolder tasks for resubmission

## 0.1.1

### Patch Changes

- 10615525f3: Switch to use the json and observable types from `@backstage/types`
- Updated dependencies
  - @backstage/catalog-model@0.9.6
