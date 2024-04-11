# Sistema de Informação de Vagas de Emprego Online
JobHub: Sistema de Gestão de Vagas de Emprego Online

## Visão Geral
Este sistema é uma plataforma online para gerenciamento de vagas de emprego, permitindo que empresas publiquem vagas e candidatos se inscrevam nelas.

## Backlog

### API de Candidatos
- [ ] Criar modelo de dados para candidatos (Nome, E-mail, Telefone, Experiência, Habilidades, etc.)
- [ ] Implementar CRUD para candidatos (Criar, Ler, Atualizar, Deletar)
- [ ] Implementar endpoint para registro de candidatos
- [ ] Implementar endpoint para atualização de dados do candidato
- [ ] Implementar endpoint para exclusão de candidato
- [ ] Implementar endpoint para visualização dos dados de um candidato
- [ ] Implementar endpoint para listagem de todos os candidatos

### API de Vagas
- [ ] Criar modelo de dados para vagas (Título, Descrição, Requisitos, Salário, Localização, etc.)
- [ ] Implementar CRUD para vagas (Criar, Ler, Atualizar, Deletar)
- [ ] Implementar endpoint para criação de uma nova vaga
- [ ] Implementar endpoint para atualização de dados de uma vaga existente
- [ ] Implementar endpoint para exclusão de uma vaga
- [ ] Implementar endpoint para visualização dos detalhes de uma vaga
- [ ] Implementar endpoint para listagem de todas as vagas
- [ ] Implementar endpoint para busca de vagas por critérios (palavras-chave, localização, salário, etc.)

### Estrutura de Tópicos e Filas SNS/SQS
- [ ] Configurar tópico SNS para notificações de novas vagas de emprego
- [ ] Configurar fila SQS para processamento assíncrono de eventos de novas vagas
- [ ] Integrar API de Vagas para publicar eventos de novas vagas no tópico SNS
- [ ] Configurar fila SQS para processamento assíncrono de inscrições de candidatos em vagas
- [ ] Implementar serviço para processar inscrições de candidatos em vagas a partir da fila SQS

## Configuração do Ambiente
- [ ] Configurar AWS LocalStack para simulação de serviços AWS em ambiente local
- [ ] Configurar banco de dados MongoDB para armazenamento de dados
- [ ] Configurar Kubernetes para orquestração dos contêineres dos microserviços

## Execução e Testes
- [ ] Implementar testes unitários para as APIs de Candidatos e Vagas
- [ ] Implementar testes de integração para garantir a interação correta entre os microserviços
- [ ] Documentar os endpoints das APIs de Candidatos e Vagas

## Deploy
- [ ] Automatizar o processo de deploy dos microserviços no Kubernetes
- [ ] Configurar pipelines de CI/CD para garantir a integridade e atualização contínua dos serviços

## Contribuição
Contribuições são bem-vindas! Se você deseja contribuir com este projeto, siga as instruções de [contribuição](CONTRIBUTING.md).

## Licença
Este projeto está licenciado sob a licença [MIT](LICENSE).
