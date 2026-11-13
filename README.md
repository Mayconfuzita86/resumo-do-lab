### ☁️ Resumo do Lab: Computação em Nuvem com Microsoft Azure

Este repositório contém o resumo dos conceitos fundamentais e dos principais serviços disponibilizados pelo Microsoft Azure, desenvolvido como parte do desafio de laboratório prático na DIO (Digital Innovation One).

### 💡 A Importância da Computação em Nuvem para o Programador Moderno

Hoje em dia, para se destacar e ser um excelente programador, não basta apenas escrever um código limpo e funcional localmente: é indispensável dominar a computação em nuvem. Compreender a arquitetura e os serviços de provedores como o Microsoft Azure permite que o desenvolvedor projete aplicações verdadeiramente resilientes, escaláveis e preparadas para lidar com alta volumetria de tráfego. Entender como o software é implantado, monitorado e escalado na nuvem conecta a escrita do código diretamente com a eficiência de custos, segurança e estabilidade em produção.

### 🌐 O que é o Microsoft Azure?

O Azure é a plataforma de computação em nuvem pública da Microsoft. Ele oferece uma infraestrutura global distribuída em dezenas de regiões e um conjunto abrangente de serviços que permitem criar, testar, implantar e gerenciar aplicações através de datacenters gerenciados pela Microsoft.

A plataforma opera sob o modelo Pay-as-you-go (Pague pelo que usar), permitindo que empresas e desenvolvedores escalem recursos computacionais sob demanda, eliminando a necessidade de altos investimentos iniciais em infraestrutura física (on-premises).

### 🛠️ Overview dos Principais Serviços do Azure

## 1. Computação (Compute)

Serviços responsáveis por fornecer poder de processamento e ambientes de execução para aplicações:

Azure Virtual Machines (VMs): Máquinas virtuais Windows ou Linux sob o modelo IaaS (Infrastructure as a Service), oferecendo controle total sobre o sistema operacional.

Azure App Service: Plataforma PaaS (Platform as a Service) totalmente gerenciada para hospedar aplicações web, APIs REST e back-ends sem precisar gerenciar servidores subjacentes.

Azure Kubernetes Service (AKS): Serviço gerenciado para orquestração de containers com Kubernetes, ideal para arquiteturas baseadas em microsserviços.

Azure Functions: Computação Serverless orientada a eventos, onde o código é executado sob demanda e a cobrança ocorre apenas pelo tempo real de execução.

## 2. Armazenamento (Storage)

Soluções seguras, redundantes e altamente escaláveis para persistência de arquivos e dados:

Azure Blob Storage: Armazenamento de objetos otimizado para grandes volumes de dados não estruturados (logs, imagens, vídeos e backups).

Azure Files: Compartilhamentos de arquivos totalmente gerenciados na nuvem, acessíveis via protocolos padrão como SMB.

Azure Disk Storage: Discos de armazenamento em bloco de alta performance acoplados às Máquinas Virtuais.

## 3. Bancos de Dados (Databases)

Opções gerenciadas de bancos de dados relacionais e NoSQL com backups automatizados e alta disponibilidade:

Azure SQL Database: Banco de dados relacional gerenciado baseado no motor do Microsoft SQL Server.

Azure Database for PostgreSQL / MySQL: Serviços gerenciados para bancos de dados open-source amplamente utilizados no mercado.

Azure Cosmos DB: Banco de dados NoSQL multimodelo distribuído globalmente, projetado para baixíssima latência e alta escalabilidade horizontal.

Azure Cache for Redis: Serviço de cache em memória de alta velocidade baseado no Redis para acelerar o desempenho de aplicações críticas.

## 4. Redes (Networking)

Serviços voltados para conectividade, isolamento, balanceamento de carga e segurança de tráfego:

Azure Virtual Network (VNet): Rede privada na nuvem que permite a comunicação segura entre recursos do Azure, a internet e redes corporativas locais.

Azure Load Balancer & Application Gateway: Balanceadores de carga que distribuem o tráfego de entrada entre múltiplas instâncias para garantir resiliência e disponibilidade.

Azure VPN Gateway: Estabelece conexões criptografadas entre redes locais (on-premises) e a rede virtual do Azure.

## 5. Inteligência Artificial e Machine Learning (AI & ML)

Ferramentas para incorporar inteligência cognitiva e modelos generativos às aplicações:

Azure OpenAI Service: Acesso corporativo aos modelos de linguagem avançados da OpenAI (como GPT) com segurança e governança de dados do Azure.

Azure AI Services: APIs prontas para visão computacional, processamento de linguagem natural, tradução e reconhecimento de fala.

Azure Machine Learning: Plataforma completa para treinar, implantar e gerenciar modelos de aprendizado de máquina em escala.

## 6. Identidade e Segurança (Identity & Security)

Serviços essenciais para controle de acesso, proteção de segredos e governança:

Microsoft Entra ID (antigo Azure AD): Gerenciamento de identidades e acessos na nuvem, suportando Single Sign-On (SSO) e autenticação multifator (MFA).

Azure Key Vault: Cofre centralizado e seguro para armazenar chaves de criptografia, senhas, connection strings e certificados digitais.

Microsoft Defender for Cloud: Monitoramento contínuo da postura de segurança e proteção contra ameaças em cargas de trabalho na nuvem.

### 🚀 Conclusão

A exploração do ecossistema Microsoft Azure reforça como os modelos de serviço em nuvem (IaaS, PaaS e Serverless) aceleram o ciclo de desenvolvimento de software, permitindo que desenvolvedores foquem na regra de negócio enquanto a infraestrutura escala com segurança e previsibilidade.
