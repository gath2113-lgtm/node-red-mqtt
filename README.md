# Projeto Node-RED: Comunicação MQTT e Endpoints HTTP (RSFI)

Repositório dedicado às atividades práticas de Sistemas e Protocolos (RSFI), focado no uso do protocolo MQTT e integração com serviços web via Node-RED.

---

## Estrutura de Arquivos
- README.md: Guia explicativo dos exercícios praticados.
- flows/: Arquivos de fluxo JSON prontos para serem importados no Node-RED.

---

## Lista de Fluxos Desenvolvidos

| Arquivo / Fluxo | Tópico Principal | Descrição do Fluxo |
|---|---|---|
| 01-exercicio-mqtt-pub-sub.json | Publicação e Subscrição MQTT | Fluxo básico enviando dados para o tópico ifsp/turma-x/teste via broker HiveMQ. |
| 02-recipes-mqtt-json-retained.json | Mensagens Retidas & JSON | Envio de estrutura de dados de sensores em formato JSON com flag retained ativa. |
| 03-desafio-http-endpoint.json | Integração HTTP & API Externa | Endpoint de consulta de status (/api/status) e requisição para API REST externa. |

---

## Instruções de Execução

1. Inicialize a aplicação pelo terminal executando: node-red
2. Acesse a interface web no seu navegador: http://127.0.0.1:1880
3. Acesse o menu principal (canto superior direito) > Importar.
4. Selecione os arquivos de fluxo desejados contidos no diretório flows/.
5. Clique em Deploy no canto superior para ativar as rotas e tópicos.
