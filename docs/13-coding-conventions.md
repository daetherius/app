# Coding conventions

- DO NOT repeat yourself
- USE PSR-2

## Confiuration

- MUST NOT contain secrects

## Docker

- all containers SHOULD keep running, eg. data-containers with `tail -f /dev/null`

## Database (MySQL)

- camelCase_id
- MUST USE non-project specific default values
- SHOULD have an idempotent setup (see `BaseAppCommand`)

## PHP

### Classes

- MUST USE English names

### Variables

- camelCase
- $this->table_field;

### Yii 

- SHOULD use `Yii::info()` or `Yii::trace()`, NOT `Yii::getLogger->(..., ..., ...)`
- SHOULD NOT use `application.language = null` with `codemix/yii2-localeurls`

### Giiant (Backend CRUD)

- providers MUST NOT be copied into the project, may can extend a new class
- SHOULD contain `Id` columns


## CSS

## JavaScript

## bash

