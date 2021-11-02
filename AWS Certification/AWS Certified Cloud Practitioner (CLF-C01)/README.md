

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

## AWS

https://d1.awsstatic.com/training-and-certification/ramp-up_guides/Ramp-Up_Guide_CloudPractitioner.pdf



**AWS Partner - Accreditation Business** ✔

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/2427/aws-partner-accreditation-business-digital

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/2249/aws-partner-accreditation-business-digital-portuguese

 

**AWS Partner Accreditation - Technical**

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/1096/aws-partner-accreditation-technical

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/2314/aws-partner-accreditation-technical-portuguese

 

**AWS Cloud Practitioner Essentials**

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/134/aws-cloud-practitioner-essentials

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/8287/aws-cloud-practitioner-essentials-portugues

 

 **AWS Cloud Practitioner Essentials - Final Assessment**

https://explore.skillbuilder.aws/learn/course/internal/view/elearning/3010/aws-partner-aws-cloud-practitioner-essentials

[assessment](https://explore.skillbuilder.aws/learn/course/3010/play/11028/aws-partner-aws-cloud-practitioner-essentials-assessment)

 

**AWS Cloud Practitioner - Exam Guide**

https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf

https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Exam-Guide.pdf

 

**AWS Cloud Practitioner - Sample Questions**

https://d1.awsstatic.com/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Sample-Questions.pdf

https://d1.awsstatic.com/pt_BR/training-and-certification/docs-cloud-practitioner/AWS-Certified-Cloud-Practitioner_Sample-Questions.pdf

 

## **ACLOUDGURU**

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

### **Zonas de disponibilidades (AZ)**

- Interconectas por uma fibra
- Pode ter 2 ou mais AZ´s em uma região

### **PoP - Pontos de Presenças**

- Cache



## **Analytics (Análise)**	

Athena
CloudSearch
ElasticSearch
EMR
Glue
Kinesis
QuickSight
Redshift

## **Storage (Armazenamento)** 	

### **Simple Storage Service (S3)**

- Armazenamento a nivel de objeto
- Arquivos de até 5 TB

![image-20211102173111307](./Imagans/image-20211102173111307.png)

### **Elastic Block Store (EBS)**

- Armazenamento a nivel de bloco
- Independente da vida util da instancia
- É automaticamente replicado entre AZ´s
- Pode ser associado a uma unica instancia
- Snapshot point-in-time
- Snapshots podem ser copiados entre Regiões

### **S3 Glacier**

- Arquivamento e backup de dados



### **Elastic File System (EFS)**

**Backup**

### **Família Snow**

**Storage Gateway**



### 





## **Database (Banco de Dados)** 	

### **Aurora**

- Forcene poder computacional até 5x mais rápido que m bd mysql tradicional

### **DynamoDB**

- Banco de dados NOSQL

### **ElastiCache**

### **Neptune**

### RDS

- São beneficios Patches e backups automatizados
- São beneficios o redimencionamento da capacidade de acordo com uso





## **Compute (Computação)**	

### **Auto Scaling**

### **AWS Auto Scaling**

https://docs.aws.amazon.com/autoscaling/plans/userguide/what-is-aws-auto-scaling.html

- **Scaling-up** adciona mais recursos a uma instancia e **scaling-out** adciona mais instancias 
- **scaling-up** - vertical scaling
- **scaling-out** - horizontal scaling

### **Batch**

### **EC2(Elastic Compute Cloud)**

- Serviço que vc tem controle total
- **Beneficios da EC2** - Elasticidade, Flexivel, Integração com demais serviços, Confiavél, Seguro, Baixo Custo
- **Tipos de Instancias** - General Purpose, Compute Optimized, Memory Optimized, Accelerated Computing, Storage Optimized

### **Elastic Beanstalk**

### **Lightsail**

### **Elastic Load Balancing**	

- Tipos - Application, Network e Classic 

### **Lambda**

- Serverless

### **App Runner** 

### **ECR Elastic Container Registry** 

### **ECS Elastic Container Service** 

### **EKS Elastic Kubernets Service**

### **Fargate**



## **Computação sem servidor** (Serverless)

### **API Gateway**	





## 





## **Envolvimento Cliente** 	

Connect 

SES Simple Email Services



## **Ferramentas Desenvolvedor** 	

Cloud9

CodeArtifact

CodeBuild

CodeCommit

CodeDeploy

CodePipeline

**CodeStar**

- 



Ferramentas e SDKs da AWS

Interface da Linha de Comando da AWS

X-Ray



## **Gerenciamento Financeiro** 	

### **Budgets**

### **Cost Explorer** 

- Fornece previsões baseadas no uso de custos estimados de faturamento e uso para os proximos meses

### **Saving Plans**

### **Faturamento consolidado**

- Usa bucket s3 direto da conta mestre





## **Management (Governaça)**	

### **CloudFormation**

- Cloudformation Change Sets - pode ser usado para visualizar as alterações nos recursos

### **CloudTrail** 

### **CloudWatch**

### **SDK**

- Kit de desenvolvimento

### **Config**

- Controla as alterações de configuração nos recuros 

### **Console de gerenciamento**

### **Interface de linha de comando (CLI)**

### **License Manager** 

### **Organization** 

### **Service Catalog** 

### **System Manager** 

### **Trusted Advisor**

- Checar os softlimits 

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

### **SQS**

### **Step Functions** 



## **Machine Learning**	

Forecast

Fraud Detector 

SageMaker



## **Migration (Migração)**	

### **Estratégias de Migração (6R´s)**

https://aws.amazon.com/blogs/enterprise-strategy/6-strategies-for-migrating-applications-to-the-cloud/

![image-20211102183406187](./Imagans/image-20211102183406187.png)



- Rehost
- Refactory (Refatorar)
- Replatform





### **Database Migration Service (DMS)**

- Migra bd do local para AWS
- Migra bd da AWS para Local
- Migra bd do EC2 para RDS
- Migra Redshift para DynamoDB

### **DataSync**

- Maneira mais simples e rápida de migrar grandes quantidades de dados entre o local e S3, EFS ou FSx. 

### **Server Migration Service**



## **Networking (Rede)**	

### **Cloud Map**

### **CloudFront**

### **Global Accelerator**

### **Route 53**

### **VPC**

- Uma rede virtual dedicada a sua conta
- Subnets
- route-tables
- vpc-flowlogs - Captura trafego da vpc, subnet e armazena no cloudwatch logs

### **Security Group  (Grupo de Segurança)**

- **Segurança a nivel da instancia**

### **Network ACL - NACL**

- Pode ser configurada adcionalmente a nível de subnet para controlar o tráfego de entrada e saida. 
- **Segurança a nivel da subnet**



## **Security (Segurança)**	

### **IAM(Identity & Access Management)**

- Controle de acesso para recursos
- MFA
- Analise de acesso

### **Shared Responsability  (Modelo de Responsabilidade Compartilhada)**

![image-20211102181239562](./Imagans/image-20211102181239562.png)



### Artifact

- Acesso aos relatorios emitidos pelo auditor da AWS

### **Audit Manager**

### **Certificate Manager**

### **Cognito**

### **Firewall Manager**

### **Inspector**

- Realiza verificações nas instancias EC2 em relação a modelos de segurança

- Analisa vulnerabilidades

  

### **GuardDuty**

### **Key Management Service**	

### **Macie**

### **Network Firewall**

### **Resource Access Manager**

- 

### **Secrets Manager**

### **Shield and Shield Advanced**

### **WAF**

# **Links** 

https://jayendrapatil.com/aws-certified-cloud-practitioner-exam-learning-path/#AWS_Certified_Cloud_Practitioner_Exam_CLF-C01_Learning_Path

https://jayendrapatil.com/aws-certified-cloud-practitioner-exam-learning-path/#AWS_Certified_Cloud_Practitioner_Exam_Contents

https://github.com/brunokktro/auladobruno



