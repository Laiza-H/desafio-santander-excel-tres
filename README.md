# desafio-santander-excel-tres
Repositório para o terceiro desafio do bootcamp santander excel com inteligência artificial - Criando um Dashboard de Vendas do Xbox com Excel

# 🎮 Dashboard de Assinaturas: Xbox Game Pass Sales

Este projeto apresenta uma solução completa de **Business Intelligence (BI)** desenvolvida em Excel para monitorar e analisar o desempenho de vendas das assinaturas do Xbox Game Pass durante o ano de 2024.

## 📝 O Desafio

O objetivo principal foi transformar uma base de dados bruta com informações de milhares de assinantes em um painel interativo que responda a perguntas críticas de negócio, como faturamento por plano, impacto de cupons de desconto e evolução mensal das vendas.

### Principais Indicadores (KPIs) Monitorados:
* **Faturamento Bruto vs. Líquido:** Análise do impacto de descontos no faturamento total.
* **Distribuição de Planos:** Comparação entre os planos *Core*, *Standard* e *Ultimate*.
* **Venda de Season Passes:** Monitoramento específico de pacotes extras (EA Play e Minecraft).
* **Taxa de Renovação:** Análise de assinaturas com renovação automática ativa.

---

## 🚀 Estrutura de Inteligência do Arquivo

O projeto foi construído seguindo as melhores práticas de organização de dados (método ETL simplificado):

1.  **Bases (Extração):** Armazenamento dos dados brutos de IDs de assinantes, tipos de plano e datas de início.
2.  **Cálculos (Transformação):** Aba técnica onde os dados são processados via fórmulas complexas e Tabelas Dinâmicas para responder às "Perguntas de Negócio".
3.  **Assets (Design):** Repositório de paleta de cores, ícones e logotipos para garantir uma identidade visual profissional e consistente.
4.  **Dashboard (Visualização):** Interface final interativa com gráficos dinâmicos para análise executiva.

---

## 🔒 Segurança e Experiência do Usuário

Para simular a entrega de um projeto real de Business Intelligence, o arquivo foi configurado com foco na integridade dos dados e na experiência de navegação:

* **Dashboard Protegido:** A aba principal está bloqueada para edição. Isso evita a alteração acidental de fórmulas e gráficos, garantindo que o painel funcione conforme o esperado durante a interação.
* **Camadas de Dados Ocultas:** As planilhas de **Bases** e **Cálculos** estão ocultadas por padrão. O objetivo é oferecer uma interface limpa, onde o usuário visualiza apenas o que é essencial para a tomada de decisão.
* **Liberdade de Exploração:** Caso deseje analisar a estrutura técnica, o usuário possui total liberdade para desbloquear o dashboard e reexibir as abas ocultas (clicando com o botão direito nas abas inferiores e selecionando "Reexibir").

---

## 🛠️ Tecnologias e Técnicas Aplicadas

* **Tabelas Dinâmicas Avançadas:** Para sumarização de grandes volumes de dados de vendas.
* **Segmentação de Dados (Slicers):** Filtros interativos por Período de Cálculo e Tipos de Assinatura.
* **Lógica de Negócio:** Cálculos de percentual de desconto, valor médio de cupons e faturamento por renovação.
* **Design UI/UX:** Layout otimizado para visualização clara de métricas, utilizando paleta de cores específica para o setor de games.

---

## 📈 Como Utilizar a Ferramenta

1.  Abra o arquivo `desafio3.1.xlsx`.
2.  Vá para a aba **D̳ashboard** ou **D̳ashboard_product**.
3.  Utilize os filtros laterais para ajustar o período de análise (Jan-Dez 2024).
4.  Observe os gráficos se atualizarem automaticamente para refletir a performance daquele segmento.

---
⭐ *Projeto focado em demonstrar competências de Data Analytics e estruturação lógica de Dashboards.*
