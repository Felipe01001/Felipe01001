# Automação de atendimento clínico

**Domínio:** saúde e operação de atendimento  
**Atuação:** desenvolvimento de backend, integrações, console desktop e infraestrutura

## Problema

Conectar o atendimento pelo WhatsApp à rotina da recepção e à agenda do sistema de gestão clínica, mantendo consistência entre disponibilidade, solicitações da paciente e registros de consultas.

## Minha contribuição

- Desenvolvimento de APIs e regras de agendamento, confirmação, cancelamento e reagendamento.
- Integração com a API oficial do WhatsApp e com o sistema externo de gestão clínica.
- Construção e evolução de um console desktop para conversas, consultas, pacientes e relatórios.
- Implementação de processamento assíncrono, controle de duplicidades e registro das operações.
- Evolução de testes automatizados e rotinas de implantação e atualização.

## Decisões de engenharia

**Separação de responsabilidades.** Arquitetura hexagonal para separar regras de negócio, persistência e integrações externas.

**Consistência entre sistemas.** Validação de disponibilidade e tratamento de falhas de sincronização para evitar apresentar uma operação pendente como concluída.

**Mensageria confiável.** Uso de outbox, processamento assíncrono e idempotência para lidar com reentregas de eventos e webhooks.

**Acesso aos dados.** Controle por perfil, isolamento de organizações no banco e cuidados com informações sensíveis.

## Stack

Rust, Elixir, PostgreSQL, RabbitMQ, Tauri, JavaScript, WhatsApp Cloud API, Docker, Linux e Ansible.

## Entrega

Sistema utilizado na operação de atendimento, com interface para a recepção e automações integradas à agenda. O desenvolvimento inclui manutenção e evolução do produto durante seu uso.

Esta apresentação não contém dados de pacientes, credenciais nem código proprietário. Não divulga métricas de disponibilidade ou economia sem medição correspondente.

[Voltar ao perfil](../README.md)
