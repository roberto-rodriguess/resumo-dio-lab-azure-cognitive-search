# resumo-dio-lab-azure-cognitive-search

Este módulo apresenta a mineração de conhecimento através do Azure Cognitive Search para organizar documentos e realizar pesquisas rápidas em dados não estruturados. O instrutor demonstra como configurar um serviço de busca para analisar avaliações de clientes de uma rede nacional de cafeterias.

### Contexto e Objetivo

O cenário apresentado envolve uma rede nacional de cafeterias que precisa analisar feedback de clientes em diversas unidades pelo Brasil. O Azure Cognitive Search ajuda a extrair informações relevantes e realizar análises de sentimento das avaliações, permitindo identificar rapidamente problemas específicos por localização.

### Recursos do Azure Necessários

- **Azure Cognitive Search**: Configurado com o nível de preço Basic
- **Azure AI Services**: Configurado com o nível Standard S0
- **Storage Account**: Configurado com performance Standard e armazenamento local redundante (LRS)

### Processo de Implementação

- Criar os três recursos no Azure (Search, AI Services, Storage)
- Configurar o Storage Account para permitir acesso anônimo de blob
- Criar um container chamado "coffeereviews" no Storage Account
- Fazer upload dos documentos de avaliações dos clientes
- Importar os dados no Azure Cognitive Search
- Configurar a conexão entre os serviços para processamento dos documentos
- Realizar consultas por localização e sentimento dos clientes

### Demonstração de Consultas

O instrutor demonstrou como filtrar avaliações por localização (Chicago) e identificar sentimentos negativos, permitindo encontrar rapidamente clientes insatisfeitos e os motivos específicos de suas reclamações, como tempo de espera.

### Observações sobre Certificação

O instrutor destacou que a prova de certificação AI-900 não exige conhecimento prático da implementação, mas foca em entender:

- Para que serve cada serviço
- Qual serviço utilizar para resolver determinados problemas
- Quais situações cada serviço atende
