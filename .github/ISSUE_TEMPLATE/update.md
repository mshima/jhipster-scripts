---
name: Update blueprints version
about: Track blueprints update.
title: 'Update blueprints to generator-jhipster v8.x.x'
labels: ''
assignees: ''
body:
  - type: dropdown
    id: repository
    attributes:
      label: Repository
      description: 'What repository do you want to update?'
      options:
        - generator-jhipster-native
        - generator-jhipster-migrate
        - generator-jhipster-entity-audit
        - generator-jhipster-ionic
        - generator-jhipster-react-native
        - generator-jhipster-micronaut
        - generator-jhipster-nodejs
        - generator-jhipster-quarkus
        - generator-jhipster-jooq
        - generator-jhipster-tenantview
        - generator-jhipster-es-reindexer
        - jhipster-dotnetcore
      default: 0
    validations:
      required: true
  - type: dropdown
    id: owner
    attributes:
      label: Owner
      description: 'What owner to use the repository as reference?'
      options:
        - jhipster
        - mshima
      default: 0
    validations:
      required: true

---

