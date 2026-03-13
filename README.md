# Projeto AWS — Sistema Distribuído na Amazon Web Services

📌 Sobre o Projeto
Este projeto foi desenvolvido durante um trabalho e tem como objetivo a implementação de um sistema distribuído na plataforma Amazon Web Services (AWS), integrando serviços de computação, armazenamento, banco de dados, roteamento de tráfego e orquestração de containers. A aplicação é composta por um frontend estático e um backend em Node.js, com infraestrutura totalmente provisionada na nuvem.

☁️ Serviços AWS Utilizados

- EC2: Instâncias de computação para hospedar o frontend e o backend
- S3 (Bucket): Armazenamento de arquivos estáticos e assets da aplicação
- RDS / DynamoDB: Banco de dados relacional e/ou NoSQL para persistência dos dados
- Lambda + API Gateway: Funções serverless e gerenciamento de rotas da API
- ECS: Orquestração e gerenciamento de containers Docker
- Elastic Load Balancer: Direcionamento de usuários e balanceamento de carga entre instâncias
- GitHub Actions / CodeDeploy: Pipeline de CI/CD com auto deploy a partir do repositório GitHub


🛠️ Tecnologias

- Frontend: HTML5, CSS, JavaScript
- Backend: Node.js / JavaScript
- Infraestrutura: Amazon Web Services (AWS)
- Scripts: Shell Script (automação e provisionamento)
- Containers: Docker + Amazon ECS
- CI/CD: GitHub Actions / AWS CodeDeploy
