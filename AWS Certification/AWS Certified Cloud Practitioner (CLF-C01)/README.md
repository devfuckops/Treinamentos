

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

 

**AWS Cloud Practitioner Essentials**✔

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

https://learn.acloud.guru/course/aws-certified-cloud-practitioner/dashboard **✔**



## UDEMY

[NEW] Ultimate AWS Certified Cloud Practitioner - 2021



# **Workshops**

https://maturitymodel.security.aws.dev/en/



# **Simulados**

## **Whizlabs**

https://www.whizlabs.com/learn/course/aws-certified-cloud-practitioner/219



# **Services (Serviços)**

![image-20211102181756497](./Imagans/image-20211102181756497.png)



## **Infrastructure Global (Infraestrutura Global)**	

### **Regions (Regiões)**

https://aws.amazon.com/pt/about-aws/global-infrastructure/regions_az/?p=ngi&loc=2

- Pode ter 2 ou mais AZ´s em uma região

  

  

### **Zonas de disponibilidades (AZ)**

https://aws.amazon.com/pt/about-aws/global-infrastructure/regions_az/?p=ngi&loc=2

![image-20211109204810592](./Imagans/image-20211109204810592.png)

- Interconectas por uma fibra
- Um ou mais DataCenters
- Pode ter 2 ou mais AZ´s em uma região
- As AZ´s são vinculadas a uma única região
- Conectividade redundante de baixa latência 



### **Edge Location - PoP - Pontos de Presenças**

- Cache
- CDN - Rede de Entrega de Conteúdo
- Reduz latência
- É como um mini datacenter, mas não tem infra como EC2



## **Analytics (Análise)**	

### **Athena**

### **Glue**

### **CloudSearch**

### **ElasticSearch**

### **EMR**

### **Glue**

### **Kinesis**

### **QuickSight**

https://aws.amazon.com/pt/quicksight/

- Criação de relatórios inteligentes

  

### **Redshift**

- Data warehouse

- PBs (Petabytes)

  





## **Storage (Armazenamento)** 	

### **Simple Storage Service (S3)**

https://aws.amazon.com/s3/



![image-20211102173111307](./Imagans/image-20211102173111307.png)

- Armazenamento a nível de objeto

- Upload de arquivos de até 5 TB

- Sites estáticos

- S3 Access Logs

- Serviço regional mas com o nome global

- Pode usar com o CloudFront, Redshift, Athena, Mobile applications

- Regional

- **AWS S3 Transfer Acceleration**

  - Transferências rápidas e seguras em longas distancias para bucket utilizando os pontos de presenças.

- **Classses de Armazenamento**

- https://aws.amazon.com/pt/s3/storage-classes/

  - **S3 Standard**

    - 11 - 9 - Durabilidade

    - Replicas em multi-az

    - **Recomentado para Acesso Frequente**

      


  - **S3 Intelligent-Tiering (Estratificação inteligente do S3)**

    - Ideal para dados com padrões de acesso desconhecidos ou em alteração

    - Requer uma pequena taxa mensal de monitoramento e automação por objeto
    - Rapidez quando necessário
    - Replicas em multi-az

    - **Recomentado para quando não se sabe o tipo de acesso**

      

  - **S3 Standard Infrequent Access (IA)**

    - Armazena dados em uma única zona de disponibilidade

    - Tem um preço de armazenamento menor do que o S3 Standard – IA
    - **Recomentado para Acesso Infrequente**

    

  - **S3 One Zone-Infrequent Access (S3 One Zone – IA)**

    - **Armazena dados em uma única zona de disponibilidade**

    - Tem um preço de armazenamento menor do que o S3 Standard – IA
    - **Recomentado para Acesso Infrequente**

  


  - **S3 Glacier**

    - Arquivamento e backup de dados

    - Criar cofres

    - Controles de escritas e leituras

    - Restore em minutos e horas

      

  - **AWS S3 Glacier Deep** **Archive**

    - Armazenamento mais barato 

    - Não faz upload de arquivos pela Console

    - Capaz de recuperar objetos em 12 horas ou 48 horas

      


  - **S3 Outposts**
    
    - Local S3
    
      

### **AMI**

- Imagens customizadas para EC2
- Podem ser copiadas entre regiões
- Pode criar uma AMI através de um snapshot



### **EC2 Image Builder**

https://aws.amazon.com/pt/image-builder/

- Automatiza a criação, manutenção, validação e teste de AMI´s
- Para EC2 e Imagens de Containers



### **EC2 Instance Store**

- Ephemeral
- Buffer, cache e dados temporários 
- Melhor I/O




### **Elastic Block Store (EBS)**

https://aws.amazon.com/pt/ebs/

- Armazenamento a nível de bloco

- Independente da vida útil da instância

- É **automaticamente replicado** entre AZ´s

- **Mas é armazenado em uma única AZ** 

- Pode ser associado a uma única instancia

- Snapshot point-in-time

- Snapshots podem ser copiados entre Regiões

- Ate 16 TiB

- Flag - Delete on Termination 

  - Para deletar o EBS quando deleta a EC2
  - Não vem ativado por default

  

  



### **Elastic File System (EFS)**

https://aws.amazon.com/pt/efs/

- Compartilhamento de arquivos
- Sistema de Arquivos Linux
- Só funciona em SO Linux
- Regional
- NFS
- Paga por uso



### **Amazon FSx**

https://aws.amazon.com/pt/fsx/

- **Lustre**
  - HPC
- **Windows File Server**
  - Suporta SMB e Windows NTFS
  - Windows File Server
  - Integrado com Active Directory
- **NetApp**
- **OpenZFS**





### **Backup**

### **VMware Cloud on AWS**

### **Storage Gateway**

### **AWS Ground Station** 



## **Database (Banco de Dados)** 	

### **Aurora**

- Forcene poder computacional até 5x mais rápido que m bd mysql tradicional
- banco de dados relacional
- Mysql e PostgreSQL
- 6 Cópias
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

- 



![img](./Imagans/questions_dgdbva.png)





### **Plano de suporte Enterprise**

- Acesso a todos os itens do Trust Advidor

- TAM

  

### **Plano de suporte Bussines**

- Acesso a todos os itens do Trust Advidor



## **Compute (Computação)**	

### **EC2 Auto Scaling**

### **AWS Outposts**

https://aws.amazon.com/outposts/

- Infraestrutura da AWS no cliente





### **AWS Auto Scaling**

https://docs.aws.amazon.com/autoscaling/plans/userguide/what-is-aws-auto-scaling.html

![image-20211109195133948](./Imagans/image-20211109195133948.png)



- **Scaling Strategies** 

  - **Dynamic Scaling**

    - **Simple/Step Scaling**

      - Quando utilizamos alarmes do CloudWatch (CPU > 70%)

    - **Target Tracking Scaling**

      - Quando utilizamos a média de consumo do ASG

    - **Scheduled Scaling**

      - Quando o scheduler é feito por agendamento

    - **Predictive Scaling**

      - Utiliza Machine Learning

        

  - **Manual Scaling**

    - Quando alteramos na mão



- **Scaling-up** adciona mais recursos a uma instancia e **scaling-out** adciona mais instancias 
- **Scaling-up** - **Vertical Scaling** - Aumentar o tamanho da instancia
- **Scaling-out** - **Horizontal Scaling** - Aumenta o numero de instancias 







### **Batch**

https://aws.amazon.com/batch/

- Executar milhares de jobs



### **EC2 (Elastic Compute Cloud)**

- Serviço que vc tem controle total

- **EC2 Instance Connect** 

  - Connecta na EC2 via console AWS

    

- **EC2 UserData**

  - bootstrap

  - executa no primeiro boot

    

- **SO** 

  - Linux, Windows e MAcOS

    

- **Benefícios da EC2** 

  - Elasticidade, Flexível

  - Integração com demais serviços

  - Confiável

  - Seguro

  - Baixo Custo

    

- **Tipos de Instâncias** 

  https://aws.amazon.com/pt/ec2/instance-types/

  - **General Purpose**

    - Instâncias de uso geral fornecem um equilíbrio de recursos de computação, memória e rede e podem ser usadas para diversas cargas de trabalho. 

      

  - **Compute Optimized**

    - As instâncias otimizadas para computação são ideais para aplicativos vinculados a computação que se beneficiam de processadores de alto desempenho. 

      - Batch

      - Media

      - HPC

      - Machine Learning

        

  - **Memory Optimized**

    - As instâncias otimizadas de memória são projetadas para fornecer desempenho rápido para cargas de trabalho que processam grandes conjuntos de dados na memória.

      

  - **Accelerated Computing**

    - Instâncias de computação aceleradas usam aceleradores de hardware, ou coprocessadores, para executar funções, como cálculos de número de ponto flutuante, processamento de gráficos ou correspondência de padrões de dados, mais eficientemente do que é possível no software em execução nas CPUs.

      

  - **Storage Optimized**

    - As instâncias otimizadas para armazenamento são projetadas para cargas de trabalho que exigem acesso de leitura e gravação sequencial alto a conjuntos de dados muito grandes no armazenamento local. Elas

      

  - **Instances Features**

  - **Measuring Instance Performance**

    

- **EC2 Dedicated Hosts**

  - https://aws.amazon.com/pt/ec2/dedicated-hosts/
  - Podem utilizar licenças de software existentes no cliente - BYOL




- **EC2 Dedicated Instances**

  - https://aws.amazon.com/pt/ec2/pricing/dedicated-instances/

  - Roda em hardware dedicado mas vc não tem acesso 

    

- **Preços**

  - **Sob-Demanda** 

    - por hora ou por segundo

      

  - **Saving Plans** 

    - 1 ou 3 anos 

    - até 70% de desconto comparado ao sob-demanda

    - EC2, Fargate e Lambda

      

  - **Instancias Reservadas**

    - 1 ou 3 Anos

    - Standard, Convertable ou Scheduled

      

  - **Instâncias Spot**

    - Aviso de até **2 minutos**
    - até 90% de desconto comparado ao sob-demanda
    - Cargas de trabalhos em lote

    

    




### **AWS Cloud Adoption Framework**

https://d1.awsstatic.com/whitepapers/aws_cloud_adoption_framework.pdf

- **Perspectiva de operações** do AWS Cloud Adoption Framework também inclui princípios para operar na nuvem usando melhores práticas ágeis.
- **A Perspectiva de Negócios** ajuda você a mudar de um modelo que separa as estratégias de negócios e TI para um modelo de negócios que integra a estratégia de TI.
- **A Perspectiva de Pessoa**s ajuda os funcionários de Recursos Humanos (RH) a prepararem suas equipes para adoção da nuvem, atualizando processos organizacionais e habilidades de equipe para incluir competências baseadas em nuvem.
- **A Perspectiva de Governança** ajuda você a entender como atualizar as habilidades da equipe e os processos organizacionais necessários para garantir a governança de negócios na nuvem.







### **Lightsail**

https://aws.amazon.com/lightsail/

- Projetos pequenos
- Deployments rápidos
- wordpress por exemplo
- Similar ao Quick Starts



### **Elastic Load Balancing (ELB)**	

https://aws.amazon.com/pt/elasticloadbalancing/

- **Tipos** 
  - **Gateway** 
  - **Application** 
    - (http/https only) 
    - Layer 7
  - **Network** 
    - (ultra-high performance / TCP) 
    - Layer 4
  - **Classic** 
    - (Layer 4 and Layer 7)

- É regional
- É altamente disponível 





### **Lambda**

https://aws.amazon.com/pt/lambda/

- **Serverless**

- Escalável e disponível 

- Executar em até **15 minutos** (timeout)

- Resposta a eventos (trigger)

- Free Tier - 1 Million rrequest each month 

  

### **App Runner** 

### **ECR Elastic Container Registry** 

### **ECS Elastic Container Service** 

- Ferramenta de orquestração de container
- Gerencia a EC2



### **EKS Elastic Kubernets Service**

https://aws.amazon.com/pt/eks/

- Ferramenta de orquestração de container

- Gerencia a EC2

  

### **Fargate**

https://aws.amazon.com/fargate/

- **Serveless**
- Para ECS e EKS
- Escala automaticamente
- **Não Gerencia a EC2**
- 

### **API Gateway**	





## **Envolvimento Cliente** 	

Connect 

### **SES Simple Email Services**

- Configurar um **VPC Endpoint com AWS PrivateLink** para alcançar dentro da VPC



## **Developer Tools(Ferramentas Desenvolvedor)** 	

### **Cloud9**

### **CodeArtifact**

### **CodeBuild**

https://docs.aws.amazon.com/codebuild/latest/userguide/welcome.html



### **CodeCommit**

https://aws.amazon.com/pt/codecommit/

- Armazenamento de código fonte

  

### **CodeDeploy**

https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html

- Automatizar a instalação de um conjunto de aplications em EC2 e em Servidores Locais

  

### **CodePipeline**

### **CodeStar**







### **Interface da Linha de Comando da AWS (CLI)**

- Acesso programático
- Acesso por um terminal ou comando
- SDK 
  - Java, Python, C++ e etc
  - Mobile SDM
  - IoT Device SDK




### **AWS CloudShell**

- Terminal shell da AWS



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



## **Deployment and Infrastructure Management**



### **CloudFormation**

https://aws.amazon.com/cloudformation/features/

- **Cloudformation Change Sets** 
  - Pode ser usado para visualizar as alterações nos recursos
- Infraestrutura como codigo - JSON/YAML
- Formato declarativo



### **Elastic Beanstalk**

https://aws.amazon.com/elasticbeanstalk/?p=tile

- Implemantação rápida de recursos que podem usar diferentes linguagens de programação como .NET e JAVA
- Baseado em EC2
- Controle dos recursos 



### **OpsWorks**

- Gerencia aplicativos no datacenter através de SO Linux conectados em **Endpoints públicos** AWS
- Agent do OpsWorks instalados nas instancias Linux
- Automatizar a configuração de um software e replicar **em outras 400**



## **Auditing, Monitoring and Logging**



### **CloudTrail** 

https://aws.amazon.com/pt/cloudtrail/

- Auditoria de API
- Savla log´s em bucket S3





### **X-Ray**

https://aws.amazon.com/pt/xray/

- Monitorar microserviços 
- Detecta problemas de desempenho em app no Lambda



### **CloudWatch**

- Coleta métricas e Logs 

- Coleta On-premisse





## **Management (Governaça)**	





### **SDK**

- Kit de desenvolvimento

  

### **AWS Config**

 É um serviço que permite acessar, auditar e avaliar as configurações dos recursos da AWS.

https://aws.amazon.com/pt/config/

- Controla as alterações de configuração nos recuros 

  

### **Console de gerenciamento**

- Ambiente Web

- Acesso via root ou user IAM

  

### **Interface de linha de comando (CLI)**

- Chamadas de API

  

### **License Manager** 

### **AWS Organizations** 

https://aws.amazon.com/pt/organizations/

![image-20211115182718982](./Imagans/image-20211115182718982.png)



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

https://aws.amazon.com/pt/premiumsupport/technology/trusted-advisor/

- Checar os softlimits 

- Recomendações de Segurança e Otimização de custos

- Para receber notificações deve-se configura-las na console

- Cost Optimization, Performance, Secutiry, Fault Tolerance and Service Limits

- Algumas verificações são gratuitas

  
  
  

### **AWS Well-Architected Framework**

https://wa.aws.amazon.com/index.pt_BR.html

- [Excelência operacional](https://wa.aws.amazon.com/wat.pillar.operationalExcellence.pt_BR.html)
  - Executar cargas de trabalho de forma eficaz
  - obter insights sobre suas operaçõe

- [Segurança](https://wa.aws.amazon.com/wat.pillar.security.pt_BR.html)
- [Confiabilidade](https://wa.aws.amazon.com/wat.pillar.reliability.pt_BR.html)
  - concentra na capacidade de uma carga de trabalho executar de forma consistente e correta as funções pretendidas.

- [Eficiência de performance](https://wa.aws.amazon.com/wat.pillar.performance.pt_BR.html)
  - Concentra no uso eficiente dos recursos de computação para atender aos requisitos do sistema 
  - Manter essa eficiência à medida que a demanda muda e as tecnologias evoluem.

- [Otimização de custos](https://wa.aws.amazon.com/wat.pillar.costOptimization.pt_BR.html)
  - concentra na capacidade de executar sistemas para fornecer valor comercial com o preço mais baixo.






## **Integração** 	

### **AppFlow**

### **AppSync**

### **EventBridge**

### **MQ**

**Step Functions** 





## **Messaging and Integration** 

### **SNS**	

- Envia notificações aos usuários finais

  

### **SQS**

https://aws.amazon.com/pt/sqs/

- Envia, armazena e receba sem perder a mensagem em qualquer volume

- Mensagens são colocadas até que sejam processadas

  

### 



## **Machine Learning**	

### **Forecast**

### **Fraud Detector** 

### **SageMaker**

### **Augmented AI**

https://aws.amazon.com/pt/augmented-ai/

- Fornece fluxos de trabalho de revisão humana integrados para casos de uso comuns de machine learning, como moderação de conteúdo e extração de texto de documentos

### **AWS Deep Racer**

### **Amazon Lex**

- Alexa

### **Textract**

- Extração de texto
- Extrai automaticamente texto e dados de documentos digitalizados.



## **Migration (Migração)**	

### **Estratégias de Migração (6R´s)**

https://aws.amazon.com/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/

![image-20211102183406187](./Imagans/image-20211102183406187.png)



- Rehosting (Lift and Shift)
  - Mais fácil

- Replatforming (Lift and Reshape)
- Repurchasing
- Refactory (Refatorar)
- Retain - Manter
- Retire - Aposentar





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



### **Família Snow**

https://aws.amazon.com/pt/snow/

- Criptograia 256 Bits

- Pode usar KMS

- **AWS Snow Mobile**

  - Caminhão

  - 100 PT - (100.000 TB)

    

- **AWS Snowball Edge**

  - **Snowball Edge otimizado para armazenamento** 

    são ideais para migrações de dados de grande escala e fluxos de trabalho de transferência recorrentes, em além da computação local com necessidades maiores de capacidade. 

    - Armazenamento: **80 TB de capacidade HDD para volumes de blocos e armazenamento de objeto compatível com Amazon S3, além de 1 TB de SSD SATA para volumes de blocos.** 
    - Computação: 40 vCPUs e 80 GiB de memória para dar suporte a instâncias sbe1 do Amazon EC2 (equivalente a C5).

  -  **Snowball Edge otimizado para computação** 

    fornece recursos de computação poderosos para casos de uso, como machine learning, análise de vídeo em movimento completo, análise e pilhas de computação locais. 

    - Armazenamento: **capacidade de HDD utilizável de 42 TB** para armazenamento de objeto compatível com Amazon S3 ou volumes de blocos compatíveis com Amazon EBS e também 7,68 TB de capacidade de SSD NVMe utilizável para volumes de blocos compatíveis com Amazon EBS. 
    - Computação: 52 vCPUs, 208 GiB de memória e uma GPU NVIDIA Tesla V100 opcional. Os dispositivos executam as instâncias sbe-c e sbe-g do Amazon EC2, que são equivalentes às instâncias C5, M5a, G3 e P3.

  - Otimizado para Armazenamento

  - Encaixa em Rack Existente

  - Pode usar Lamba

  - EC2 e IoT

  - Captura de IoT, Compressão de imagem, Sinalização industrial

    

- **AWS Snowcone**

  - 8 TB

  - Edge Compute (EC2 - IoT)

  - Copia para um bucket S3

    



## **Content Delivery**

### **CloudFront**

https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html

- Pode usar TTL para habilitar o cache de conteudo dinamico

- Pode ser S3, EC2, ELB, Route 53

- Usa **Edge Location** para distribuir conteudo 

- Dados, vídeos aplicações e API

- CDN

- Arquivos estáticos 

- **NÃO usa UNICAST**

  

### **Global Accelerator**

https://aws.amazon.com/global-accelerator/faqs/

- Usam a rede global AWS de alta velocidade e as técnicas de roteamento **Anycast** para melhorar a disponibilidade e desempenho do app do cliente
- Não inclui recursos de cache de conteudo
- São adequados para VOIP, MTTQ e Jogos



## **Networking (Rede)**	

### **Cloud Map**



### **Route 53**

https://aws.amazon.com/pt/route53/

https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html

- Pode registrar nomes de domínios

- **Roteamento de Latência** 

  - Para melhor performance de usuários globais

- **Roteamento de Geolocalização**

- **Roteamento de Ponderado**

- **Roteamento de Geoproximidade**

  

  

### **Virtual Private Cloud VPC)**

- Uma rede virtual dedicada a sua conta

- Subnets - Publica e Privada

- route-tables

- Virtual Private Gateway - VPN

- vpc-flowlogs - Captura trafego da vpc, subnet e armazena no cloudwatch logs

- **Network ACL - NACL**

  - Pode ser configurada adcionalmente a nível de subnet para controlar o **tráfego de entrada e saida**. 

  - **Segurança a nivel da subnet**

  - Por padrão é tudo liberado 

  - **Stateless** - checa entrada e saída 

    

- **Security Group  (Grupo de Segurança)**

  - https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/VPC_SecurityGroups.html
  - **Segurança a nível da instância**
  
  
    - Por default é **todo bloqueado de entrada (Inbound) e tudo liberado na saída (Outbound)**
    - Pode ser atachado em multiplas instancias
    - Baseado em Região/VPC
  
  
    - **Stateful** - Não verifica o trafego de retorno pois reconhece que é o mesmo pacote
  
  
    - Referencia IP ou Security Group
  
      ![image-20211207213551384](./Imagans/image-20211207213551384.png)
  


### **Virtual Private Network(VPN)**

### **Direct Connect**

https://aws.amazon.com/pt/directconnect/

- Conexão dedicada com a AWS
- Taxa de transferência alta
- Estabelecer uma **conexão privada dedicada** entre o seu datacenter e a VPC. 



## **Security (Segurança)**	

### **IAM (Identity & Access Management)**

- Controle de acesso para recursos

- MFA

  - Virtual MFA Devices (Google Autenticator or Authy)

  - Universal 2nd Factor (U2F) Security Key - **Phisical Device**

  - Hardware Key Fob MFA Device

  - Hardware Key Fob MFA Device for AWS GovCloud (US)

    

- Serviço Global

- Analise de acesso

- Por padrão um usuário não tem permissões - **tudo negado por default**

- **Users** 

  - Podemos ter um usuário em mais de um grupo

    

- **Policy** 

  - json

  - Estrutura de uma Policy

    ![image-20211207201651694](./Imagans/image-20211207201651694.png)

- **Grupos** 

  - Agrupamentos de usuários com permissões em comum

  - Grupos só tem usuários e não pode ter outros Grupos

    

- **Roles** 

  - Identidades que podem assumir

  - Assumidas temporária

  - Permissões associadas 

  - Não podem ser utilizadas por usuários, somente por **AWS Services**

    


- **Security Tools**

  - **IAM Credentials Report (account-level)**

    - Report que lista todos os usuários de sua conta e o status de suas várias credenciais

    - É armazenado por até quatro horas

      

  - **IAM Access Advisor (user-level)**

    - Mostra os serviços que este usuário pode acessar e quando esses serviços foram acessados pela última vez

    - Lista atividades de ate 4 horas

      

### **Shared Responsability  (Modelo de Responsabilidade Compartilhada)**

https://aws.amazon.com/compliance/shared-responsibility-model/

![image-20211102181239562](./Imagans/image-20211102181239562.png)

- **Infraestrutura Global** não faz parte dos controles compartilhados entre Cliente e AWS.



### Artifact

https://aws.amazon.com/pt/artifact/

- Acesso aos relatorios emitidos pelo auditor da AWS



### **Audit Manager**

### **KMS**

https://aws.amazon.com/kms/features/

- Usa Envelope Encryption



### **Certificate Manager**

É um serviço que permite provisionar, gerenciar e implantar facilmente certificados Secure Sockets Layer (SSL)/Transport Layer Security (TLS) para uso com os serviços da AWS e os recursos internos conectados. 

https://aws.amazon.com/pt/certificate-manager/

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

https://aws.amazon.com/pt/guardduty/

- Detecção de ameaças
- Logs DNS, flow logs e cloudtrail



### **Key Management Service**	

- Gerencia chave de criptografia

  

### **Macie**



### **Amazon Detective**

https://docs.aws.amazon.com/detective/latest/adminguide/what-is-detective.html

- Serviço persistente orientado a **Machine Learning**

  

### **Network Firewall**

### **Resource Access Manager**



### **Secrets Manager**

### **Shield and Shield Advanced**

- Usa machine learning



### **WAF**

https://docs.aws.amazon.com/waf/latest/developerguide/waf-chapter.html

- Firewall aplicação web





# **Links** 

https://jayendrapatil.com/aws-certified-cloud-practitioner-exam-learning-path/#AWS_Certified_Cloud_Practitioner_Exam_CLF-C01_Learning_Path

https://jayendrapatil.com/aws-certified-cloud-practitioner-exam-learning-path/#AWS_Certified_Cloud_Practitioner_Exam_Contents

https://github.com/brunokktro/auladobruno



