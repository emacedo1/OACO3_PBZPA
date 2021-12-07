# OACO3_PBZPA

Projeto para lidar com tramites tramites de emissao de minutas de Autorizacao de PBZPA a Operadores de Aerodomos e Prefeituras.

Migração do projeto desktop "DocPB" (monolitico) para um projeto web baseado em microservicos.

O DocPB consiste de:

1. uma aplicação principal responsável por:

- a controlar a geração de minutas de aprovação de PBPZA/H para Requerentes e Prefeituras;
- controlar operações CRUD para Requerentes (Operadores e/ou Prefeituras).

Na aplicação OACO3_PBZPA, as funcionalidades acima serão separadas em microserviços

- Serviço (de Controle) Minutas
- Serviço (de Controle) de Requerentes.
