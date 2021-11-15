

# **AWS Certified Cloud Practitioner (CLF-C01)**



# **Documentação Oficial**

https://aws.amazon.com/pt/certification/certified-cloud-practitioner/?ch=tile&tile=getstarted

## **Guia do Exame**

https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf

![image-20211026190346276](./Imagans/image-20211026190346276.png)



**Domain 1: Cloud Concepts (26%)**

1.1 Definir a nuvem AWS e sua proposta de valor

1.2 Identificar aspectos da economia da nuvem AWS

1.3 Liste os diferentes princípios de design de arquitetura de nuvem



**Domain 2: Security and Compliance (25%)**

2.1 Definir o modelo de responsabilidade compartilhada da AWS

2.2 Definir os conceitos de segurança e conformidade da nuvem AWS

2.3 Identifique os recursos de gerenciamento de acesso da AWS

2.4 Identificar recursos para o suporte de segurança



**Domain 3: Technology (33%)**

3.1 Definir métodos de implantação e operação na nuvem AWS

3.2 Definir a infraestrutura global da AWS

3.3 Identificar os principais serviços da AWS

3.4 Identificar recursos para suporte de tecnologia



**Domain 4: Billing and Pricing (16%)**

4.1 Comparar os vários modelos de preços para AWS

4.2 Reconhecer as várias estruturas de conta em relação ao faturamento e preços da AWS

4.3 Identificar recursos disponíveis para suporte de faturamento





## **Perguntas exemplos**

https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Sample-Questions.pdf



# **Treinamentos**

Colocar ✔ quando concluído. 

## **AWS**

https://d1.awsstatic.com/training-and-certification/ramp-up_guides/Ramp-Up_Guide_CloudPractitioner.pdf



**AWS Partner - Accreditation Business** ✔

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/2427/aws-partner-accreditation-business-digital

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/2249/aws-partner-accreditation-business-digital-portuguese

 

**AWS Partner Accreditation - Technical** ✔

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/1096/aws-partner-accreditation-technical

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/2314/aws-partner-accreditation-technical-portuguese

 

**AWS Cloud Practitioner Essentials**

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/134/aws-cloud-practitioner-essentials

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/8287/aws-cloud-practitioner-essentials-portugues

 

 **AWS Cloud Practitioner Essentials - Final Assessment✔**

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/3010/aws-partner-aws-cloud-practitioner-essentials

[assessment](https://explore.skillbuilder.aws/learn/course/3010/play/11028/aws-partner-aws-cloud-practitioner-essentials-assessment)

 

**AWS Cloud Practitioner - Exam Guide**✔

https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf

https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf

 

**AWS Cloud Practitioner - Sample Questions✔**

https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Sample-Questions.pdf

https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Sample-Questions.pdf

 

## ACLOUDGURU

https://learn.acloud.guru/course/aws-certified-cloud-practitioner/dashboard



# **Workshops**

https://maturitymodel.security.aws.dev/en/

# **Simulados**

## **Whizlabs**

https://www.whizlabs.com/learn/course/aws-certified-cloud-practitioner/219



# **Services (Serviços)**

![image-20211102181756497](./Imagans/image-20211102181756497.png)



## **Infrastructure Global (Infraestrutura Global)**	

### **Regions (Regiões)**

- Pode ter 2 ou mais AZ´s em uma região

### **Zonas de disponibilidades (AZ)**

![image-20211109204810592](./Imagans/image-20211109204810592.png)

- Interconectas por uma fibra
- Um ou mais DataCenters
- Pode ter 2 ou mais AZ´s em uma região

### **Edge Location - PoP - Pontos de Presenças**

- Cache
- CDN - Rede de Entrega de Conteudo



## **Analytics (Análise)**	

### **Athena**

### **CloudSearch**

### **ElasticSearch**

### **EMR**

### **Glue**

### **Kinesis**

### **QuickSight**

- Criação de relatórios inteligentes

  

### **Redshift**

- Data warehouse

- PBs

  





## **Storage (Armazenamento)** 	

### **Simple Storage Service (S3)**

![image-20211102173111307](./Imagans/image-20211102173111307.png)

- Armazenamento a nivel de objeto

- Upload de arquivos de até 5 TB

- Sites estaticos

- Regional

  

- **S3 Standard**

  - 11 - 9 - Durabilidade
  - Replicas em 3 az´s

  

  

- **S3 IA**

  - Rapidez quando necessário
  - Acesso infrequente




- **S3 One Zone-Infrequent Access (S3 One Zone – IA)**
  - Armazena dados em uma única zona de disponibilidade
  - Tem um preço de armazenamento menor do que o S3 Standard – IA



- **S3 Intelligent-Tiering (Estratificação inteligente do S3)**
  - Ideal para dados com padrões de acesso desconhecidos ou em alteração
  - Requer uma pequena taxa mensal de monitoramento e automação por objeto



-  **AWS S3 Transfer Acceleration**

  - Tranferencias rapidas e seguras em longas distanticas para bucket utilizando os pontos de presenças.

    


- **S3 Glacier**

  - Arquivamento e backup de dados

  - Criar cofres

  - Controles de escritas e leituras

  - Restore em minutos e horas

    

- **AWS S3 Glacier Deep** Archive
  - Armazenamento mais barato 
  - Não faz upload de arquivos pela Console
  - Capaz de recuperar objetos em 12 horas







### **Elastic Block Store (EBS)**

- Armazenamento a nivel de bloco

- Independente da vida util da instancia

- É automaticamente replicado entre AZ´s

- **Mas é armazenado em uma unica AZ** 

- Pode ser associado a uma unica instancia

- Snapshot point-in-time

- Snapshots podem ser copiados entre Regiões

- Replicação do mesmo volume entre AZ´s

- Ate 16 TiB

  

  



### **Elastic File System (EFS)**

- Compartilhamento de arquivos

- Sistema de Arquivos Linux

- Regional

  

### **Backup**

### **Família Snow**

- AWS Snowball 

  

### **Storage Gateway**





## **Database (Banco de Dados)** 	

### **Aurora**

- Forcene poder computacional até 5x mais rápido que m bd mysql tradicional
- banco de dados relacional
- Mysql e PostgreSQL
- 6 copias
- 15 replicas de leitura
- Bkp continuo no S3





### **DynamoDB**

- Banco de dados NOSQL
- Serverless
- **DynamoDB Accelerator(DAX)** 
  - Aprimora o desempenho de leitura, leitura pesada
  - Cache

- Não suportam um esquema pre-definido
- Oferecem atomicidade
- Modelo de dados flexiveis e latencia de milissegundos de um digito
- Para jogo on-line, Fortimente Consistente





### **ElastiCache**

- Cache

- Pode colocar na frente do banco

- Redis / Memcached

  

### **Neptune**

- Banco de dados em Grafos



### **Amazon Managed Blockchain**





### **Amazon Quantum Ledger Database (QLDB)**

- Imutavel 





### **RDS**

- São beneficios Patches e backups automatizados

- São beneficios o redimencionamento da capacidade de acordo com uso

- MySQL, Oracle, PostgreSQL

  

  



## **Planos de suporte AWS**

![img](./Imagans/questions_dgdbva.png)



## **Compute (Computação)**	

### **Auto Scaling**

### **AWS Auto Scaling**

https://docs.aws.amazon.com/autoscaling/plans/userguide/what-is-aws-auto-scaling.html

![image-20211109195133948](./Imagans/image-20211109195133948.png)

- **Scaling-up** adciona mais recursos a uma instancia e **scaling-out** adciona mais instancias 
- **scaling-up** - vertical scaling
- **scaling-out** - horizontal scaling

### **Batch**

### **EC2 (Elastic Compute Cloud)**

- Serviço que vc tem controle total

- **Beneficios da EC2** - Elasticidade, Flexivel, Integração com demais serviços, Confiavél, Seguro, Baixo Custo

- **Tipos de Instancias** - General Purpose, Compute Optimized, Memory Optimized, Accelerated Computing, Storage Optimized

- **Hosts Dedicados** - Podem utilizar licenças de software existentes no cliente.

- **Preços**

  - **Sob-Demanda** (por hora ou por segundo)

  - **Instancias Reservadas**

  - **Instancias Spot**

    - Aviso de até **2 minutos**
    - até 90% de desconto comparado ao sob-demanda
    - Cargas de trabalhos em lote

  - **Saving Plans** 

    - 1 ou 3 anos 

    - até 70% de desconto comparado ao sob-demanda

    - EC2, Fargate e Lambda


### **Elastic Beanstalk**

https://aws.amazon.com/elasticbeanstalk/?p=tile

- Implemantação rápida de recursos que podem usar diferentes linguagens de programação como .NET e JAVA
- Baseado em EC2
- Controle dos recursos 



### **OpsWorks**

- Gerencia aplicativos no datacenter atravez de SO Linux conectados em Endpoints publicos AWS
- Agent do OpsWorks instalados nas instancias Linux
- Automatizar a configuração de um software e replicar



### **Lightsail**

### **Elastic Load Balancing (ELB)**	

- **Tipos** - Application, Network e Classic 
- É regional
- É altamente disponivel 

### **Lambda**

- Serverless

- Escalavél e disponivel 

- Executar em até **15 minutos**

  

### **App Runner** 

### **ECR Elastic Container Registry** 

### **ECS Elastic Container Service** 

- Ferramenta de orquestração de container
- Gerencia a EC2

### **EKS Elastic Kubernets Service**

- Ferramenta de orquestração de container
- Gerencia a EC2

### **Fargate**

- Serveless
- Para ECS e EKS
- **Não Gerencia a EC2**

### **API Gateway**	





## **Envolvimento Cliente** 	

Connect 

### **SES Simple Email Services**

- Configurar um VPC Endpoint com AWS PrivateLink para alcançar dentro da VPC



## **Ferramentas Desenvolvedor** 	

Cloud9

CodeArtifact

CodeBuild

### **CodeCommit**

- Armazenamento de codigo fonte

### **CodeDeploy**

- Automatizar a instalação de um conjunto de aplications em EC2 e em Servidores Locias

CodePipeline

**CodeStar**

- 



Ferramentas e SDKs da AWS

Interface da Linha de Comando da AWS

### **X-Ray**

- Monitorar microserviços 
- Detecta problemas de desempenho em app no Lambda



## **Gerenciamento Financeiro** 	

### **Budgets**

- Pode configurar alertas de orçamentos

- Usa informações fornecidas pelo AWS Cost Explorer

  

### **Cost Explorer** 

![Exemplo do painel do AWS Cost Explorer, exibindo custos mensais para instâncias do Amazon EC2 em um período de seis meses](./Imagans/VhcqUjh9EBPpO6NY_pS6DLACY5OOiDZZb.png)

- Fornece previsões baseadas no uso de custos estimados de faturamento e uso para os proximos meses

- 12 meses de dados historicos

  



### **Faturamento consolidado**

- Usa bucket s3 direto da conta mestre





## **Management (Governaça)**	

### **CloudFormation**

https://aws.amazon.com/cloudformation/features/

- **Cloudformation Change Sets** 
  - Pode ser usado para visualizar as alterações nos recursos

- Infraestrutura como codigo - JSON/YAML
- Formato declarativo





### **CloudTrail** 

- Auditoria de API

- Savla log´s em bucket S3

  



### **CloudWatch**

- Coleta métricas e Logs 

- Coleta On-premisse

  

### **SDK**

- Kit de desenvolvimento

  

### **AWS Config**

- Controla as alterações de configuração nos recuros 

  

### **Console de gerenciamento**

- Ambiente Web

  

### **Interface de linha de comando (CLI)**

- Chamadas de API

  

### **License Manager** 

### **AWS Organization** 

- Para automatizar a criação de AWS Accounts

- Gerenciamento centralizado de todas as contas

- Faturamento consolidado e desconto em massa

- Agrupamento - OU

- Controle de serviços/API por conta 

- SCP´s

  



### **AWS Service Catalog** 

### **AWS System Manager** 

https://aws.amazon.com/systems-manager/

- Permite que os usurios controlem seus recursos unificando serviços onde ele podem visualizar, monitorar e automatizar

  

### **AWS Personal Health Dashboard**

https://aws.amazon.com/premiumsupport/technology/personal-health-dashboard/

- Visão sobre a disponibilidade e desenpenho dos servios AWS

- Avisa o usuário com alertas e notificações sobre atividades agendadas

  

### **Trusted Advisor**

- Checar os softlimits 

- Recomendações de Segurança e Otimização de custos

- Para receber notificações deve-se configura-las na console

- Cost Optimization, Performance, Secutiry, Fault Tolerance and Service Limits

- Algumas verificações são gratuitas

  
  
  

### **AWS Well-Architected Framework**

https://wa.aws.amazon.com/index.pt_BR.html

- [Excelência operacional](https://wa.aws.amazon.com/wat.pillar.operationalExcellence.pt_BR.html)
- [Segurança](https://wa.aws.amazon.com/wat.pillar.security.pt_BR.html)
- [Confiabilidade](https://wa.aws.amazon.com/wat.pillar.reliability.pt_BR.html)
- [Eficiência de performance](https://wa.aws.amazon.com/wat.pillar.performance.pt_BR.html)
- [Otimização de custos](https://wa.aws.amazon.com/wat.pillar.costOptimization.pt_BR.html)





## **Integração** 	

### **AppFlow**

### **AppSync**

### **EventBridge**

### **MQ**

### **SNS**	

- Envia notificações aos usuários finais

  

### **SQS**

- Envia, armazena e receba sem perder a mensagem em qualquer volume

- Mensagens são colocadas até que sejam processadas

  

### **Step Functions** 



## **Machine Learning**	

Forecast

Fraud Detector 

SageMaker



## **Migration (Migração)**	

### **Estratégias de Migração (6R´s)**

https://aws.amazon.com/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/

![image-20211102183406187](./Imagans/image-20211102183406187.png)



- Rehost (Lift and Shift)
- Refactory (Refatorar)
- Replatform





### **Database Migration Service (DMS)**

- Migra bd do local para AWS
- Migra bd da AWS para Local
- Migra bd do EC2 para RDS
- Migra Redshift para DynamoDB
- O banco de dados de origem permanece operacional durante a migração
- Consolidação de banco de dados
- DR





### **DataSync**

- Maneira mais simples e rápida de migrar grandes quantidades de dados entre o local e S3, EFS ou FSx. 



### **Server Migration Service**



## **Networking (Rede)**	

### **Cloud Map**

### **AWS Outposts**

- Infraestrutura da AWS no cliente



### **CloudFront**

https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html

- Pode usar TTL para habilitar o cache de conteudo dinamico

- Pode ser S3, EC2, ELB, Route 53

- Usa **Edge Location** para distribuir conteudo 

- Dados, videos aplicações e API

- CDN

- Arquivos estaticos 

  

### **Global Accelerator**

https://aws.amazon.com/global-accelerator/faqs/

- Usam a rede global AWS de alta velocidade e as tecnicas de roteamento anycast para melhorar a disponibildiade e desempenho do app do cliente
- Não inclui recursos de cache de conteudo
- São adequados para VOIP, MTTQ

### **Route 53**

- Politica de Roteamento de Latencia para melhor performance de usuários globais

- Geolocalização

- Pode registrar nomes de dominios

  

### **Virtual Private Cloud - VPC**

- Uma rede virtual dedicada a sua conta

- Subnets - Publica e Privada

- route-tables

- Virtual Private Gateway - VPN

- vpc-flowlogs - Captura trafego da vpc, subnet e armazena no cloudwatch logs

  

### **Security Group  (Grupo de Segurança)**

- **Segurança a nivel da instancia**

- Grupo de segurança default é todo bloqueado de entrada

- De saida é tudo liberado 

- **Stateful** - Não verifica o trafego de retorno pois reconheçe que é o mesmo pacote

  

### **Network ACL - NACL**

- Pode ser configurada adcionalmente a nível de subnet para controlar o **tráfego de entrada e saida**. 
- **Segurança a nivel da subnet**
- Por padrão é tudo liberado 
- **Stateless** - checa entrada e saida 



### **Direct Connect**

- Conexão dedicada com a AWS



## **Security (Segurança)**	

### **IAM (Identity & Access Management)**

- Controle de acesso para recursos

- MFA

- Analise de acesso

- Por padrão um usuário não tem permissões - tudo negado por default

- **Policy** 

  - json
  
- **Grupos** 

  - Agurpamentos de usuários com permissões em comum

- **Roles** 

  - Identidades que podem assumir
  - assumidas temporária
  - permissoes associadas 

  

### **Shared Responsability  (Modelo de Responsabilidade Compartilhada)**

https://aws.amazon.com/compliance/shared-responsibility-model/

![image-20211102181239562](./Imagans/image-20211102181239562.png)

- Infraestrutura Global não faz parte dos controles compartilhados entre Cliente e AWS



### Artifact

- Acesso aos relatorios emitidos pelo auditor da AWS



### **Audit Manager**

### **KMS**

https://aws.amazon.com/kms/features/

- Usa Envelope Encryption



### **Certification Manager**

- Pode atualizar e renover certificados



### **Penetration Testing**

https://aws.amazon.com/security/penetration-testing/

- Pode ser executado, desde que a AWS autorize. 



### **Certificate Manager**

### **Cognito**

https://aws.amazon.com/cognito/

- Federação de identidade web   Facebook



### **Firewall Manager**

### **AWS Inspector**

- Realiza verificações nas instancias EC2 em relação a modelos de segurança

- Analisa vulnerabilidades

- Agente AWS na EC2

  

### **GuardDuty**

- Detecção de ameaças
- Logs DNS, flow logs e cloudtrail



### **Key Management Service**	

- Gerencia chave de criptografia

  

### **Macie**

### **Detective**

- Serviço persistente orientado a Machine Learning

  

### **Network Firewall**

### **Resource Access Manager**



### **Secrets Manager**

### **Shield and Shield Advanced**

- Usa machine learning



### **WAF**

- Firewall aplicação web





# **Links** 

https://jayendrapatil.com/aws-certified-cloud-practitioner-exam-learning-path/#AWS_Certified_Cloud_Practitioner_Exam_CLF-C01_Learning_Path

https://jayendrapatil.com/aws-certified-cloud-practitioner-exam-learning-path/#AWS_Certified_Cloud_Practitioner_Exam_Contents

https://github.com/brunokktro/auladobruno



