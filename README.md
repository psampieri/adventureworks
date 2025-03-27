# Dashboard comercial em Power BI
Este é um modelo de dashboard criado em Power BI, voltado para análises e decisões comerciais. Foram utilizados dados de uma empresa fictícia para se demonstrar o passo a passo de toda a criação, passando pelo carregamento e limpeza dos dados, realização de todos os cálculos e o desenvolvimento dos painéis.

[Link para o vídeo de apresentação:](https://drive.google.com/file/d/1liPKb94QkcsJqdqHL6_HfzNu6P_MeN09/view?usp=drive_link)

### 1. Carregamento e Transformação dos dados no Power BI
O primeiro passo foi carregar todos os arquivos .csv e realizar sua transformação através do Power Query. Para a normalização dos arquivos, foram necessários ajustes, que incluem:  
. Alteração nos nomes dos arquivos e algumas colunas  
. Adequação do **tipo de dado** nas colunas, especialmente números, strings e calendário  
. Transformação de algumas colunas retirando-se dados específicos  
. Junção das 3 tabelas de vendas (anuais) em uma única  
. Criação dos parâmetros de datas  
![image](https://github.com/user-attachments/assets/09217bdd-b011-4167-bb27-cfeb98adff5c)

### 2. Criação das *relações* entre as tabelas e finalizando o modelo de dados
Foi utilizado o esquema *Snowflake* para que as relações fiquem bem intuitivas. Todas as tabelas possuíam uma relação 1:* (one to many) para com a tabela das vendas.
![image](https://github.com/user-attachments/assets/0ee50408-4f3e-464d-bf7b-964cce58f6a6)

### 3. Criação de *Medidas* com a linguagem DAX
A fim de realizar a agragação dos principais dados usados no painel, tais como totais, contagens e outros indicadores, foram utilizadas a criação de *medidas*. Dentre elas, incluem-se: total de pedidos; total de devoluções; médias de faturamento; metas de lucro; etc. Todas as medidas eram conferidas através de suas inserções em matrizes. Alguns campos calculados também foram inseridos.
![image](https://github.com/user-attachments/assets/b1eec28f-5a4b-45e7-a6b6-fcc4b0127d8b)

### 4. Montagem do Dashboard
Após todas as transformações e cálculos, foram originados 4 paines, que interagem entre si, com os seguintes propósitos, mas não a eles limitados:  
#### 👨‍💼 Dashboard Executivo
Voltado para executivos ou alta gestão.  
**Principais características:** Números curtos e poucos termos; apenas os principais KPIs utilizados: faturamento, lucro, pedidos, produtos; Simples e direto ao ponto.
#### 🌎 Dashboard Mapa
Aliado ao dashboard executivo, mostra a localização geográfica dos dados.
#### 🛒 Dashboard Produtos
Voltado para equipes comerciais e de produção.  
**Principais características:** Demonstra uma análise mais aprofundada de cada produto, especialmente sobre seu faturamento, metas e quantidade de devoluções.
##### 🚴‍♀️ Dashboard Clientes
Voltado para equipes comerciais e de marketing.  
**Principais características:** Visão aprofundada de todos os clientes e seus perfis; Utilização maior de palavras do que métricas; Aprofundamento de características pessoais

### 5. Dashboard Finalizado
#### Screenshots

![image](https://github.com/user-attachments/assets/c35666cb-488d-439d-8606-0d1806045c35)
![image](https://github.com/user-attachments/assets/0bb83554-7c7a-4a2c-b310-fcb8174f0498)
![image](https://github.com/user-attachments/assets/707b0005-a160-48fb-9188-8ef5cbfb7ef0)
![image](https://github.com/user-attachments/assets/7d6b52ef-999c-4334-86f3-d4fb858c54f6)











