### Amazon AppFlow

#### 1. Qual das opções abaixo descreve melhor o Amazon AppFlow?
- [ ] A) Um serviço para processar grandes volumes de dados em tempo real  
- [x] B) Um serviço para automatizar a transferência de dados entre aplicações SaaS e AWS  
- [ ] C) Uma ferramenta para gerenciar filas de mensagens assíncronas  
- [ ] D) Um sistema de notificações para usuários finais  

**Explicação:** O **Amazon AppFlow** permite integrar e transferir dados de aplicações SaaS para serviços AWS sem necessidade de código personalizado.  

**Por que as outras estão incorretas?**  
- **A)** O **AWS Kinesis** é usado para processamento de grandes volumes de dados em tempo real.  
- **C)** O **Amazon SQS** gerencia filas de mensagens assíncronas.  
- **D)** O **Amazon SNS** gerencia notificações para usuários finais.  

#### 2. Um analista precisa sincronizar dados entre o Salesforce e o Amazon S3 de forma automática. Qual serviço AWS ele deve usar?
- [x] A) Amazon AppFlow  
- [ ] B) AWS Glue  
- [ ] C) Amazon EventBridge  
- [ ] D) Amazon SNS  

**Explicação:** O **Amazon AppFlow** permite transferências de dados automatizadas entre aplicações SaaS como Salesforce e serviços AWS como S3.  

**Por que as outras estão incorretas?**  
- **B)** O **AWS Glue** é voltado para ETL e processamento de dados, não para sincronização direta entre SaaS e AWS.  
- **C)** O **Amazon EventBridge** gerencia eventos, mas não faz sincronização de dados SaaS.  
- **D)** O **Amazon SNS** é para notificações, não para transferência de dados.  

---

### Amazon EventBridge

#### 1. Qual das opções abaixo descreve melhor o Amazon EventBridge?
- [ ] A) Um serviço para enfileirar mensagens entre microsserviços  
- [ ] B) Uma ferramenta para envio de e-mails transacionais  
- [x] C) Um barramento de eventos que conecta aplicações AWS e SaaS  
- [ ] D) Um sistema de notificações push para usuários móveis  

**Explicação:** O **Amazon EventBridge** é um barramento de eventos que permite conectar aplicações AWS e SaaS, respondendo a eventos em tempo real.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SQS** é o serviço adequado para enfileirar mensagens.  
- **B)** O **Amazon SES** é responsável por e-mails transacionais.  
- **D)** O **Amazon SNS** é usado para notificações push.  

#### 2. Uma equipe de DevOps deseja criar regras para disparar eventos automatizados entre serviços AWS e aplicações SaaS. Qual serviço AWS é mais adequado?
- [ ] A) Amazon SQS  
- [x] B) Amazon EventBridge  
- [ ] C) AWS Lambda  
- [ ] D) AWS Step Functions  

**Explicação:** O **Amazon EventBridge** permite criar regras de roteamento de eventos entre serviços AWS e aplicações externas, facilitando automação.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SQS** gerencia filas de mensagens, mas não roteia eventos automaticamente.  
- **C)** O **AWS Lambda** pode processar eventos, mas não gerencia regras de roteamento.  
- **D)** O **AWS Step Functions** orquestra fluxos de trabalho, mas não gerencia eventos entre sistemas.  

---

### Amazon MQ

#### 1. Qual das opções abaixo descreve melhor o Amazon MQ?
- [ ] A) Um serviço de mensagens altamente escalável baseado em filas distribuídas  
- [ ] B) Um serviço para monitorar logs de aplicações  
- [x] C) Um serviço gerenciado para middleware de mensagens como ActiveMQ e RabbitMQ  
- [ ] D) Um barramento de eventos que roteia notificações em tempo real  

**Explicação:** O **Amazon MQ** fornece um serviço gerenciado para **ActiveMQ e RabbitMQ**, facilitando a comunicação entre aplicações com baixa latência.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SQS** é um serviço de filas altamente escalável, mas não é um broker compatível com protocolos de middleware tradicionais.  
- **B)** O **AWS CloudWatch Logs** é usado para monitorar logs, não para comunicação entre aplicações.  
- **D)** O **Amazon EventBridge** gerencia eventos, mas não substitui um middleware de mensagens.  

#### 2. Uma empresa precisa migrar um ambiente on-premises que usa RabbitMQ para um serviço gerenciado na AWS. Qual serviço AWS é o mais indicado?
- [ ] A) Amazon SQS  
- [ ] B) Amazon SNS  
- [x] C) Amazon MQ  
- [ ] D) AWS Step Functions  

**Explicação:** O **Amazon MQ** oferece suporte a **RabbitMQ e ActiveMQ**, facilitando a migração de aplicações legadas para a AWS.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SQS** usa um modelo de filas distribuídas, mas não é compatível com RabbitMQ.  
- **B)** O **Amazon SNS** envia notificações, mas não gerencia mensagens em filas complexas.  
- **D)** O **AWS Step Functions** é para orquestração de workflows, não para filas de mensagens.  

---

### Amazon SNS (Simple Notification Service)

#### 1. Qual das opções abaixo descreve melhor o Amazon SNS?
- [ ] A) Um serviço de enfileiramento de mensagens entre microsserviços  
- [ ] B) Um serviço para monitorar logs de aplicações  
- [x] C) Um serviço de mensagens pub/sub para envio de notificações em tempo real  
- [ ] D) Um serviço para orquestração de fluxos de trabalho na AWS  

**Explicação:** O **Amazon SNS** permite o envio de mensagens no modelo **"publicar-assinar" (pub/sub)**, enviando notificações a múltiplos assinantes simultaneamente.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SQS** é usado para enfileiramento de mensagens.  
- **B)** O **AWS CloudWatch Logs** monitora logs, não envia notificações.  
- **D)** O **AWS Step Functions** orquestra workflows, não envia notificações.  

#### 2. Uma empresa deseja enviar alertas críticos via SMS e e-mail sempre que um sistema falhar. Qual serviço AWS é mais adequado?
- [x] A) Amazon SNS  
- [ ] B) Amazon SQS  
- [ ] C) Amazon SES  
- [ ] D) AWS Step Functions  

**Explicação:** O **Amazon SNS** suporta **múltiplos protocolos de entrega**, incluindo SMS, e-mail e HTTP, ideal para alertas.  

**Por que as outras estão incorretas?**  
- **B)** O **Amazon SQS** gerencia filas, mas não envia notificações diretas.  
- **C)** O **Amazon SES** envia e-mails transacionais, mas não SMS ou mensagens para múltiplos assinantes.  
- **D)** O **AWS Step Functions** gerencia workflows, não notificações.  

---

### Amazon SQS (Simple Queue Service)

#### 1. Qual das opções abaixo descreve melhor o Amazon SQS?
- [x] A) Um serviço de enfileiramento de mensagens distribuídas  
- [ ] B) Um sistema de notificações push para usuários móveis  
- [ ] C) Um serviço de orquestração de fluxos de trabalho  
- [ ] D) Um serviço para envio de e-mails em massa  

**Explicação:** O **Amazon SQS** permite **fila de mensagens distribuídas**, ajudando a desacoplar componentes de aplicações.  

**Por que as outras estão incorretas?**  
- **B)** O **Amazon SNS** é responsável por notificações push.  
- **C)** O **AWS Step Functions** gerencia workflows, não filas.  
- **D)** O **Amazon SES** envia e-mails, não gerencia filas de mensagens.  

#### 2. Um desenvolvedor precisa garantir que mensagens sejam processadas **exatamente uma vez** e na ordem correta. Qual opção ele deve escolher?
- [ ] A) Amazon SNS  
- [x] B) Amazon SQS FIFO  
- [ ] C) Amazon MQ  
- [ ] D) AWS Step Functions  

**Explicação:** O **Amazon SQS FIFO** garante **ordem exata e processamento único** de mensagens.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SNS** não armazena mensagens em fila.  
- **C)** O **Amazon MQ** é um broker tradicional, mas não tem a mesma garantia de ordem do SQS FIFO.  
- **D)** O **AWS Step Functions** gerencia workflows, não filas de mensagens.  

---

### Amazon SES (Simple Email Service)

#### 1. Qual das opções abaixo descreve melhor o Amazon SES?
- [ ] A) Um serviço para envio de notificações push  
- [ ] B) Um serviço de mensagens pub/sub para comunicação assíncrona  
- [x] C) Um serviço de envio e recebimento de e-mails transacionais e marketing  
- [ ] D) Um serviço de gerenciamento de filas de mensagens  

**Explicação:** O **Amazon SES** permite **envio e recebimento de e-mails transacionais e marketing**, incluindo relatórios de entrega.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SNS** envia notificações push, não e-mails.  
- **B)** O **Amazon SNS** faz pub/sub, mas não gerencia e-mails.  
- **D)** O **Amazon SQS** gerencia filas de mensagens, não e-mails.  

#### 2. Um aplicativo precisa enviar confirmações de compra por e-mail para clientes. Qual serviço AWS é mais indicado?
- [ ] A) Amazon SNS  
- [ ] B) Amazon SQS  
- [x] C) Amazon SES  
- [ ] D) Amazon EventBridge  

**Explicação:** O **Amazon SES** é otimizado para **envio de e-mails transacionais**, como confirmações de compra.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SNS** envia notificações, mas não e-mails estruturados.  
- **B)** O **Amazon SQS** enfileira mensagens, mas não envia e-mails.  
- **D)** O **Amazon EventBridge** gerencia eventos, não envio de e-mails.  

---

### AWS Step Functions

#### 1. Qual das opções abaixo descreve melhor o AWS Step Functions?
- [ ] A) Um serviço para envio de e-mails em massa  
- [ ] B) Um sistema de enfileiramento de mensagens  
- [ ] C) Um barramento de eventos para conectar aplicações  
- [x] D) Um serviço de orquestração de fluxos de trabalho baseado em estados  

**Explicação:** O **AWS Step Functions** permite criar **workflows de orquestração**, coordenando serviços AWS automaticamente.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SES** é para e-mails, não para workflows.  
- **B)** O **Amazon SQS** enfileira mensagens, mas não gerencia workflows.  
- **C)** O **Amazon EventBridge** gerencia eventos, não workflows.  

#### 2. Um desenvolvedor precisa coordenar múltiplos serviços AWS em um fluxo automatizado para processar arquivos. Qual serviço ele deve usar?
- [ ] A) Amazon SQS  
- [ ] B) Amazon SNS  
- [x] C) AWS Step Functions  
- [ ] D) Amazon EventBridge  

**Explicação:** O **AWS Step Functions** permite **orquestração de serviços AWS** para executar tarefas complexas em sequência.  

**Por que as outras estão incorretas?**  
- **A)** O **Amazon SQS** enfileira mensagens, mas não orquestra serviços.  
- **B)** O **Amazon SNS** envia notificações, mas não gerencia workflows.  
- **D)** O **Amazon EventBridge** gerencia eventos, mas não cria fluxos de trabalho estruturados.  
