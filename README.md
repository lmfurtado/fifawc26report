
🏆 Relatório Power BI - Copa do Mundo FIFA 2026
Este repositório contém o arquivo e a documentação de um relatório interativo desenvolvido no Power BI com dados detalhados sobre a Copa do Mundo FIFA 2026, a maior edição da história, sediada conjuntamente por Canadá, Estados Unidos e México.

O objetivo do relatório é fornecer uma análise visual e estatística abrangente sobre as seleções classificadas, suas confederações, as cidades que sediarão os jogos e a estrutura competitiva do torneio.

📊 Funcionalidades e Telas do Relatório
O relatório foi estruturado em diferentes visões estratégicas para facilitar a navegação e a extração de insights:

1. 🌍 Mapa de Países Participantes por Confederação
Descrição: Um mapa-múndi interativo que destaca todos os 48 países classificados para o torneio.

Filtros e Cores: As seleções estão codificadas por cores de acordo com suas respectivas confederações (AFC, CAF, CONCACAF, CONMEBOL, OFC, UEFA).

Insights: Permite visualizar a distribuição geográfica do novo formato expandido da Copa do Mundo e a representatividade de cada continente.

2. 📍 Mapa das Cidades-Sede
Descrição: Detalhamento geográfico dos 16 estádios e cidades-sede distribuídos pelos três países anfitriões.

Recursos: Tooltips (dicas de ferramenta) personalizadas que mostram o nome do estádio, capacidade de público e o país correspondente ao passar o mouse sobre a cidade.

3. 🛡️ Detalhes das Equipes (Team Profiles)
Descrição: Uma visão aprofundada de cada seleção nacional individualmente.

Conteúdo: Inclui informações como a alcunha do time, técnico principal, histórico resumido em copas anteriores e principais jogadores (destaques).

4. 🗂️ Grupos da Copa
Descrição: Matriz visual contendo a divisão oficial das 48 seleções nos 12 grupos do torneio (Grupo A ao Grupo L).

Interatividade: Ao selecionar um grupo, os demais visuais filtram automaticamente para exibir apenas as informações das equipes pertencentes a ele.

5. 📈 Ranking FIFA das Seleções
Descrição: Gráfico de barras e tabela comparativa mostrando a posição oficial de cada país participante no Ranking da FIFA antes do início do torneio.

Métricas: Permite identificar rapidamente quais são os cabeças de chave teóricos, as seleções mais fortes e as possíveis "zebras" da competição com base nos pontos oficiais da FIFA.

🛠️ Tecnologias Utilizadas
Power BI Desktop: Construção do modelo de dados, criação dos visuais e design dos dashboards.

Power Query (M Language): Extração, transformação e limpeza dos dados (ETL), incluindo a consolidação das bases de dados geográficas e esportivas.

DAX (Data Analysis Expressions): Criação de medidas calculadas para contagem de equipes por confederação, médias de ranking e segmentações dinâmicas.

🗃️ Estrutura do Modelo de Dados
O modelo segue boas práticas de modelagem em estrela (Star Schema), garantindo performance e flexibilidade nos filtros cruzados:

Fato_Selecoes: Tabela central com métricas, posições do Ranking FIFA e chaves de relacionamento.

Dim_Geografia / Dim_Cidades: Informações de latitude, longitude, estádios e capacidades.

Dim_Grupos: Mapeamento dos grupos e chaves de cruzamento.

Dim_Confederacoes: Dados auxiliares sobre as federações continentais.

🚀 Como Visualizar o Relatório
Para abrir e interagir com o relatório localmente:

Faça o clone deste repositório ou baixe o arquivo .pbix.

Certifique-se de ter o Power BI Desktop instalado em sua máquina.

Abra o arquivo Copa_Mundo_2026.pbix.

(Opcional) Caso os dados sejam atualizados de fontes externas, clique em Atualizar (Refresh) na guia Página Inicial.

✍️ Autor
Desenvolvido por [Seu Nome / Seu Usuário do GitHub].

Sinta-se à vontade para se conectar, sugerir melhorias ou fazer um fork do projeto!

Dica: Lembre-se de alterar as partes entre colchetes [...] com o nome do seu arquivo real e seus links de contato antes de subir para o GitHub!

faça em ingles

O seu arquivo README.md em inglês foi gerado com sucesso para o seu projeto da Copa do Mundo de 2026.

O arquivo Markdown (MD) está disponível aqui:
Ícone do app MD
 README_en 
MD

Abaixo está o texto formatado para cópia rápida, caso precise:

🏆 Power BI Report - FIFA World Cup 2026
This repository contains the file and documentation for an interactive report developed in Power BI featuring detailed data about the 2026 FIFA World Cup, the largest edition in tournament history, jointly hosted by Canada, Mexico, and the United States.

The objective of this report is to provide a comprehensive visual and statistical analysis of the qualified national teams, their continental confederations, the host cities, and the tournament's competitive structure.

📊 Features & Dashboard Views
The report is structured into distinct strategic views to simplify navigation and enhance insights discovery:

1. 🌍 Participating Countries Map by Confederation
Description: An interactive world map highlighting all 48 qualified countries for the tournament.

Filters & Visual Coding: National teams are color-coded based on their respective continental confederations (AFC, CAF, CONCACAF, CONMEBOL, OFC, UEFA).

Insights: Allows users to visualize the geographical distribution of the newly expanded World Cup format and continental representation.

2. 📍 Host Cities Map
Description: Geographical mapping of the 16 stadiums and host cities across the three host nations.

Features: Custom tooltips displaying stadium names, matchday capacity, and the respective country when hovering over each city.

3. 🛡️ Team Profiles & Details
Description: A deep dive into each individual national team.

Content: Includes details such as team nicknames, head coaches, historic World Cup performance records, and key players to watch.

4. 🗂️ World Cup Groups
Description: A clean visual matrix showing the official distribution of the 48 teams into the 12 tournament groups (Group A through Group L).

Interactivity: Selecting a group automatically filters cross-report visuals to display only the data relevant to that group's teams.

5. 📈 FIFA World Ranking
Description: Bar charts and comparative tables displaying each participating country's official position in the FIFA World Ranking prior to the tournament.

Metrics: Allows quick identification of seeded teams, top-tier contenders, and potential underdogs based on official FIFA points.

🛠️ Tech Stack
Power BI Desktop: Data modeling, visual creation, and dashboard user experience design.




O Gemini é uma IA e pode cometer erros.

# 🏆 Power BI Report - FIFA World Cup 2026

This repository contains the file and documentation for an interactive report developed in Power BI featuring detailed data about the **2026 FIFA World Cup**, the largest edition in tournament history, jointly hosted by Canada, Mexico, and the United States.

The objective of this report is to provide a comprehensive visual and statistical analysis of the qualified national teams, their continental confederations, the host cities, and the tournament's competitive structure.

---

## 📊 Features & Dashboard Views

The report is structured into distinct strategic views to simplify navigation and enhance insights discovery:

### 1. 🌍 Participating Countries Map by Confederation
* **Description:** An interactive world map highlighting all 48 qualified countries for the tournament.
* **Filters & Visual Coding:** National teams are color-coded based on their respective continental confederations (AFC, CAF, CONCACAF, CONMEBOL, OFC, UEFA).
* **Insights:** Allows users to visualize the geographical distribution of the newly expanded World Cup format and continental representation.

### 2. 📍 Host Cities Map
* **Description:** Geographical mapping of the 16 stadiums and host cities across the three host nations.
* **Features:** Custom tooltips displaying stadium names, matchday capacity, and the respective country when hovering over each city.

### 3. 🛡️ Team Profiles & Details
* **Description:** A deep dive into each individual national team.
* **Content:** Includes details such as team nicknames, head coaches, historic World Cup performance records, and key players to watch.

### 4. 🗂️ World Cup Groups
* **Description:** A clean visual matrix showing the official distribution of the 48 teams into the 12 tournament groups (Group A through Group L).
* **Interactivity:** Selecting a group automatically filters cross-report visuals to display only the data relevant to that group's teams.

### 5. 📈 FIFA World Ranking
* **Description:** Bar charts and comparative tables displaying each participating country's official position in the FIFA World Ranking prior to the tournament.
* **Metrics:** Allows quick identification of seeded teams, top-tier contenders, and potential underdogs based on official FIFA points.

---

## 🛠️ Tech Stack

* **Power BI Desktop:** Data modeling, visual creation, and dashboard user experience design.
* **Power Query (M Language):** Extract, Transform, and Load (ETL) processes, including the consolidation of geographic and sports datasets.
* **DAX (Data Analysis Expressions):** Calculated measures for team counts by confederation, ranking averages, and dynamic cross-filtering behaviors.

---

## 🗃️ Data Model Structure

The model follows a reliable **Star Schema** architectural pattern, ensuring optimized performance and seamless cross-filtering capabilities:

* **Fact_Teams (Fato_Selecoes):** Central table housing core metrics, FIFA ranking positions, and primary relationship keys.
* **Dim_Geography / Dim_Cities:** Geographic data containing latitude, longitude, stadium profiles, and venue capacities.
* **Dim_Groups:** Group mappings and tournament structure bridge keys.
* **Dim_Confederations:** Auxiliary data regarding continental governing bodies.

---

## 🚀 How to View the Report

To open and explore the interactive dashboard locally:

1. Clone this repository or download the `.pbix` file.
2. Ensure you have **Power BI Desktop** installed on your machine.
3. Open the file `World_Cup_2026.pbix`.
4. *(Optional)* If the external data sources require an update, click **Refresh** under the Home ribbon tab.

---

## ✍️ Author

Developed with 🧠 and ⚽ by Lucas Furtado / lmfurtado.  
Feel free to connect, suggest improvements, or fork this project!
README_en.md
Exibindo README_en.md.
