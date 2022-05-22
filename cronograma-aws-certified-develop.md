# cronograma-aws-certified-develop
Cronograma de estudo para prova

| Domínio                                                |  % do exame  |
| ------------------------------------------------------ | -----------  |
| Domínio 1: Implantação                                 | 22%          |
| Domínio 2:  Segurança                                  | 26%          |
| Domínio 3:  Desenvolvimento com os produtos da AWS     | 30%          |
| Domínio 4:  Refatoração                                | 10%          |
| Domínio 5:  Monitoramento e resolução de problemas     | 12%          |
| TOTAL                                                  | 100%         |                                      

### Domínio 1: Implantação

#### 1.1 Implantar código escrito na AWS usando pipelines, processos e padrões de CI/CD existentes.
- [ ] Confirmar o código em um repositório e invocar ações de construção, teste e/ou implantação
- [ ] Usar rótulos e ramificações para o gerenciamento de versões e releases
- [ ] Usar o AWS CodePipeline para orquestrar fluxos de trabalho em diferentes ambientes
- [ ] Aplicar os serviços AWS CodeCommit, AWS CodeBuild, AWS CodePipeline, AWS CodeStar
e AWS CodeDeploy para fins de CI/CD
- [ ] Executar um plano de reversão com base na política de implantação de aplicações

#### 1.2 Implantar aplicações usando o AWS Elastic Beanstalk.
- [ ] Utilizar ambientes compatíveis existentes para definir uma nova pilha de aplicações
- [ ] Empacotar a aplicação
- [ ] Apresentar uma nova versão da aplicação no ambiente do Elastic Beanstalk
- [ ] Utilizar uma política de implantação para uma versão da aplicação (ou seja, implantação
“todas de uma vez”, contínua, contínua com lotes, imutável)
- [ ] Validar a integridade da aplicação usando o painel do Elastic Beanstalk
- [ ] Usar o Amazon CloudWatch Logs para instrumentar o registro em log de aplicações

#### 1.3 Preparar o pacote de implantação de aplicações a ser implantado na AWS.
- [ ] Gerenciar as dependências do módulo de código (como variáveis de ambiente, arquivos de
configuração e arquivos de imagem estática) dentro do pacote
- [ ] Descrever a estrutura de diretórios de pacote/contêiner e organizar os arquivos
adequadamente
- [ ] Traduzir os requisitos de recursos de aplicação para os parâmetros de infraestrutura da
AWS (por exemplo, memória, núcleos)

1.4 Implantar aplicações sem servidor
- [ ] Com base em um caso de uso, implementar e iniciar um modelo do AWS Serverless
Application Model (AWS SAM)
- [ ] Gerenciar ambientes em produtos individuais da AWS (por exemplo, diferenciar entre
desenvolvimento, teste e produção no Amazon API Gateway)

### Domínio 2: Segurança

#### 2.1 Fazer chamadas autenticadas para produtos da AWS
- [ ] Comunicar a política necessária com base nos privilégios mínimos exigidos pela aplicação.
- [ ] Assumir uma função do IAM para acessar um serviço
- [ ] Usar o provedor de credenciais do kit de desenvolvimento de software (SDK) on-premises ou
na nuvem para acessar os produtos da AWS (credenciais locais versus funções de instância)

#### 2.2 Implementar criptografia usando os produtos da AWS.
- [ ] Criptografar dados em repouso (lado do cliente; lado do servidor; criptografia de envelope)
usando produtos da AWS
- [ ] Criptografar dados em trânsito

#### 2.3 Implementar a autenticação e a autorização de aplicações.
- [ ] Adicionar a funcionalidade de cadastro e login de usuários para aplicações com grupos de
usuários ou de identidades do Amazon Cognito
- [ ] Usar as credenciais fornecidas pelo Amazon Cognito para escrever código capaz de acessar
os produtos da AWS.
- [ ] Usar a sincronização do Amazon Cognito para sincronizar dados e perfis de usuários
- [ ] Usar identidades autenticadas pelo desenvolvedor para promover a interação entre os
dispositivos de usuário final, a autenticação de backend e o Amazon Cognito

### Domínio 3: Desenvolvimento com os produtos da AWS

#### 3.1 Escrever código para aplicações sem servidor.
- [ ] Comparar e contrastar o modelo baseado em servidor com o modelo sem servidor (por
exemplo, microsserviços, a natureza sem estado de aplicações sem servidor, a
escalabilidade de aplicações sem servidor e o desacoplamento de camadas de aplicações
sem servidor)
- [ ] Configurar as funções do AWS Lambda definindo variáveis e parâmetros de ambiente (por
exemplo, memória, tempo de espera, tempo de execução, manipulador)
- [ ] Criar um endpoint de API usando o Amazon API Gateway
- [ ] Criar e testar ações de API apropriadas, como GET e POST usando o endpoint da API
- [ ] Aplicar conceitos do Amazon DynamoDB (por exemplo, tabelas, itens e atributos)
- [ ] Calcular unidades de capacidade de leitura/gravação para o Amazon DynamoDB com base
nos requisitos da aplicação
- [ ] Associar uma função do AWS Lambda a uma fonte de eventos da AWS (por exemplo,
Amazon API Gateway, Amazon CloudWatch Events, eventos do Amazon S3, Amazon
Kinesis)
- [ ] Invocar uma função do AWS Lambda de forma síncrona e assíncrona

#### 3.2 Traduzir requisitos funcionais para o design de aplicações.
- [ ] Determinar se deve ser usado o processamento em tempo real ou o processamento em lote
para um dado caso de uso
- [ ] Determinar se a forma síncrona ou assíncrona é a mais adequada para um dado caso de
uso
- [ ] Determinar se o uso de evento ou da programação/sondagem é mais adequado para um
dado caso de uso
- [ ] Considerar as vantagens e as desvantagens dos modelos de consistência em um design de
aplicação

#### 3.3 Implementar o design da aplicação em seu próprio código.
- [ ] Escrever código para utilizar serviços de sistema de mensagens (por exemplo, SQS, SNS)
- [ ] Usar o Amazon ElastiCache para criar um cache de banco de dados
- [ ] Usar o Amazon DynamoDB para indexar objetos no Amazon S3
- [ ] Escrever uma função sem estado do AWS Lambda
- [ ] Escrever uma aplicação Web com servidores Web sem estado (externalizar estado)

#### 3.4 Escrever código capaz de interagir com os produtos da AWS usando APIs, SDKs e a AWS CLI.
- [ ] Escolher as APIs, os kits de desenvolvimento de software (SDKs) e os comandos da CLI
apropriados para os componentes de código
- [ ] Escrever código resiliente capaz de lidar com falhas ou exceções (ou seja, novas tentativas
com jitter e recuo exponencial)

### Domínio 4: Refatoração

#### 4.1  Otimizar a aplicação para usar melhor os recursos e produtos da AWS.
- [ ] Implementar serviços de armazenamento em cache da AWS para otimizar a performance
(por exemplo, Amazon ElastiCache, cache do Amazon API Gateway)
- [ ] Aplicar um esquema de nomenclatura do Amazon S3 para uma performance de leitura ideal

#### 4.2 Migrar o código de aplicação existente para executar na AWS.
- [ ] Isolar dependências
- [ ] Executar a aplicação como um ou mais processos sem estado
- [ ] Desenvolver visando habilitar a escalabilidade horizontal

- [ ] Externalizar o estado

### Domínio 5: Monitoramento e resolução de problemas

#### 5.1 Escrever código passível de monitoramento.
- [ ] Criar métricas personalizadas do Amazon CloudWatch
- [ ] Executar o registro em log de maneira disponível para os operadores de sistemas
- [ ] Instrumentar o código-fonte da aplicação para habilitar o rastreamento no AWS X-Ray

#### 5.2 Executar análise de causa raiz em falhas encontradas em testes ou na produção.
- [ ] Interpretar as saídas do mecanismo de registro na AWS para identificar erros em logs
- [ ] Verificar o histórico de construção e testes nos produtos da AWS (por exemplo, AWS
CodeBuild, AWS CodeDeploy, AWS CodePipeline) para identificar problemas
- [ ] Utilizar os produtos da AWS (por exemplo, Amazon CloudWatch, VPC Flow Logs e AWS XRay) para localizar um componente defeituoso específico
