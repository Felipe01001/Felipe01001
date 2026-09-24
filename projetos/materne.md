# Materne — operação de eventos

**Domínio:** eventos e gestão de participantes  
**Atuação:** desenvolvimento da aplicação e dos fluxos de operação

## Problema

Permitir que a equipe organize inscrições e acompanhe participantes durante o evento, utilizando celulares para validar acessos e registrar interações.

## Minha contribuição

- Implementação de inscrições e emissão de QR Code individual.
- Leitura de QR Code pela câmera do celular e alternativa de entrada manual.
- Fluxos de check-in, check-out e cadastro de participantes no local.
- Captura de informações por estande e consulta pela equipe responsável.
- Dashboard com indicadores, gráficos e exportação de dados.

## Decisões de engenharia

**Operação em dispositivos comuns.** O uso da câmera do celular permite executar o fluxo sem leitores dedicados.

**Fluxos por função.** Telas e permissões adequadas às atividades de administração, recepção e estandes.

**Persistência e controle de capacidade.** PostgreSQL e transações para apoiar o registro de inscrições e a operação.

## Stack

Erlang/OTP, Cowboy, JavaScript, Next.js, PostgreSQL e Docker.

## Entrega

Sistema utilizado na operação de um evento com mais de **2.000 inscritos**, reunindo inscrições, controle de acesso e informações para a organização.

[Voltar ao perfil](../README.md)
