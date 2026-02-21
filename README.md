# Exploratory Data Analysis - Mobilidade Urbana (Avanti Bootcamp)

## O Desafio Prático
Este projeto foi desenvolvido como entregável principal para o Bootcamp de Data Science da Avanti (Equipe 1 & Entrega 1). O objetivo central foi sair da teoria e resolver um problema real de dados: importar um dataset bruto de corridas de bicicleta, aplicar técnicas de limpeza, tratar inconsistências e construir uma narrativa visual para entender o comportamento dos usuários.

## Tecnologias e Ferramentas
* **Linguagem:** Python
* **Manipulação e Limpeza:** Pandas, NumPy
* **Visualização de Dados:** Matplotlib, Seaborn
* **Ambiente de Desenvolvimento:** Jupyter Notebook

## Minha Atuação (Desenvolvimento End-to-End)
Neste projeto colaborativo, atuei como o desenvolvedor principal do notebook, conduzindo a análise de ponta a ponta, desde a ingestão dos dados até a síntese dos resultados. Minhas responsabilidades diretas incluíram:
* **Data Cleaning & Tratamento:** Identificação e tratamento de valores nulos (como em `user_residence` e `user_gender`), conversão de tipos de dados e tratamento de *outliers* extremos no tempo de viagem.
* **Análise Exploratória (EDA):** Estruturação das lógicas de agrupamento e filtragem para investigar os padrões de uso entre diferentes estações e demografias.
* **Data Visualization:** Desenvolvimento de gráficos analíticos (dispersão, barras, contingência) para traduzir o volume de dados em informações visíveis e claras.
* **Conclusão e Storytelling:** Elaboração da síntese final do projeto, conectando as descobertas técnicas com o comportamento real dos usuários e formulando hipóteses de negócio.

## Principais Insights e Descobertas de Negócio

* **Perfil Predominante e Casos de Uso:** A base é composta majoritariamente por jovens (20 a 30 anos) do sexo masculino (74%). A maior concentração de viagens ocorre na estação "Instituto de Artes" com trajetos curtos (média de 30 min), evidenciando um forte uso por estudantes universitários. Em contrapartida, estações em áreas hoteleiras (ex: Brasil 21) apresentam viagens de maior duração, sugerindo uso focado no turismo.
* **Comportamento de Retenção e Anomalias:** A política de uso tem limite de 60 minutos, e a grande maioria das devoluções ocorre no prazo. No entanto, a detecção de anomalias revelou *outliers* extremos (viagens registradas com até 999 minutos), levantando hipóteses sobre bugs no sistema de registro ou retenção indevida das bicicletas.
* **Correlação Demográfica nos Atrasos:** A análise bivariada cruzando idade, gênero e tempo de uso identificou que a proporção de atrasos cresce significativamente em faixas etárias mais avançadas. Notou-se uma variação maior na duração de viagens de mulheres aos 50 e 80 anos. Esse insight indica padrões de uso distintos ou possíveis necessidades de acessibilidade motora que o serviço poderia abordar.

---
*Projeto desenvolvido para fins acadêmicos e construção de portfólio prático.*
