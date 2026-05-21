# ihcux-tele-pronto
Olavo Nicolas Queiroz de Paiva
# TelePronto

## Descrição
Este projeto é uma aplicação para atendimento médico digital, permitindo que usuários iniciem consultas, registrem sintomas e recebam suporte de forma rápida e segura.

## Tecnologias Utilizadas
- Linguagem de programação: Python, JavaScript, etc.
- Frameworks: Django, React, etc.
- Banco de dados: PostgreSQL, MongoDB, etc.
- Outras ferramentas: Docker, Git, etc.

## Análise de Acessibilidade
Nosso design considera usuários que possam estar com visão turva ou dedos trêmulos devido a mal-estar. Algumas medidas adotadas:
- Botões grandes e com espaçamento adequado para minimizar cliques errados.
- Contraste alto entre texto e fundo para facilitar a leitura.
- Mensagens de alerta claras e visíveis antes de ações críticas.
- Navegação simplificada, reduzindo a quantidade de passos necessários para iniciar tarefas importantes.

## Fluxo Crítico
O caminho para iniciar uma consulta de urgência é direto e seguro:
1. Acesse a tela inicial do aplicativo.
2. Clique no botão “Consulta de Urgência”.
3. Preencha informações básicas do paciente (nome, sintomas).
4. Confirme o envio da solicitação.
5. Aguardando confirmação do profissional de saúde.

## Prevenção de Erros
Para evitar que o usuário encerrasse uma consulta por acidente, implementamos:
- Botão de encerramento da consulta com confirmação dupla.
- Mensagem de aviso destacando que a ação é irreversível.
- Histórico visível do estado da consulta para o usuário acompanhar antes de finalizar.
- Desabilitação temporária de ações críticas até que todas as informações obrigatórias sejam preenchidas.
