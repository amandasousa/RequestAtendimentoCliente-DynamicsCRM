# Canal de Atendimento ao Cliente automático
## Projeto realizado no Microsoft Dynamics CRM 2011
Este repositório trata-se da criação de uma feature que faz a automação e centralização do atendimento ao cliente (escolas) dentro do Microsoft Dynamics CRM 2011.

Quando o cliente entra em contato via e-mail, é verificado se o remetente já pertence a um cliente, a partir daí é gerado automaticamente um registro dessa comunicação e uma ocorrência com essa troca de e-mails. 

Essa feature resolve um problema do solicitante:
 - Todos os e-mails enviados pelo cliente caem na mesma caixa, exemplo: atendimento@cliente.com.br.
 - Todos os assessores vêem todos os e-mails da caixa, indeferente se aquele cliente é da sua carteira ou não.
O objetivo principal da melhoria é:
 - Filtrar os e-mails recebidos para que cada assessor veja somente os e-mails dos seus clientes. 
 - Fazer a conexão entre Ocorrências, Telefonemas e E-mail recebidos.
 - Histórico de mensagens trocadas com a escola.

Requisitos técnicos que foram utilizados nessa feature:
- Criação e configuração de Perfil Servidor Exchange
- Criação de fila 
- Criação de entidades custom
- Criação de workflow
- Criação de view personalizada
- Criação de 3 plugins Async

# Data flow
![Data Flow](https://raw.githubusercontent.com/amandasousa/CanalAutomaticoAtendimentoCliente-DynamicsCRM/refs/heads/main/2%20-%20Processo%20de%20primeiro%20atendimento%20TO%20BE.png)
