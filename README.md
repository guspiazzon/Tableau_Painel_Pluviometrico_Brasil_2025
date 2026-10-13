# Tableau_Painel_Pluviometrico_Brasil_2025
Painel analítico interativo desenvolvido no **Tableau** para explorar e visualizar o comportamento das chuvas em todo o território brasileiro ao longo do ano de **2025**, utilizando dados oficiais do **INMET** (Instituto Nacional de Meteorologia).

# 🌧️ Painel Climático do Brasil - Análise de Chuvas (INMET 2025)

> Painel analítico interativo desenvolvido no **Tableau** para explorar e visualizar o comportamento das chuvas em todo o território brasileiro ao longo do ano de **2025**, utilizando dados oficiais do **INMET** (Instituto Nacional de Meteorologia).

---

## 🔗 Acesso ao Painel Interativo

Você pode interagir com o painel completo diretamente pelo Tableau Public:
👉 **[[Acesse o Dashboard no Tableau Public aqui](#) (https://public.tableau.com/app/profile/gustavo.piazzon.torres/viz/indice_pluviometrico_inmet_2025/Painel1?publish=yes)**

---

## 📊 Sobre o Projeto

Este projeto tem como objetivo transformar dados meteorológicos brutos em insights visuais claros sobre o regime de chuvas no Brasil em 2025. O pipeline de dados envolveu a extração e tratamento inicial das informações brutas do INMET utilizando o Python e posteriormente salvo no **Excel**, seguido pela modelagem e construção de visualizações avançadas no **Tableau**.

---

## 🗺️ Estrutura e Visualizações do Painel

O dashboard foi planejado para oferecer uma visão macro (nacional e estadual) e análises detalhadas (por município e eventos extremos):

1. **Mapa Geográfico por UF (Estado):**
   * Apresenta o volume total de chuvas acumulado por estado brasileiro.
   * Utiliza uma escala de cores graduada (gradiente de contraste) do menor para o maior volume, facilitando a identificação imediata das regiões mais chuvosas do país.

2. **Mapa Geográfico por Cidade/UF:**
   * Permite uma granularidade maior, detalhando o acumulado de chuvas por município.
   * Também conta com contraste de cores para destacar os maiores índices pluviométricos locais.

3. **Top 10 - Recordes de Chuva em um Único Dia:**
   * Gráfico de barras que exibe as 10 cidades que registraram os maiores volumes de precipitação em **apenas 24 horas** durante o ano de 2025, identificando também a data exata da ocorrência desses eventos extremos.

4. **Ranking de Acumulado Anual por Cidade:**
   * Gráfico de barras horizontais ordenado que exibe os municípios com os maiores níveis de chuva acumulada ao longo de todo o ano.

---

## 🎛️ Filtros Interativos Disponíveis

Para facilitar a exploração dos dados, o painel conta com filtros dinâmicos na interface:

* **Filtro por UF (Estado):** Selecione estados específicos para isolar a análise regional.
* **Filtro por Estação do Ano:** Analise o comportamento das chuvas de acordo com as estações (Verão, Outono, Inverno, Primavera).
* **Filtro por Total de Chuva:** Permite definir intervalos numéricos de precipitação para refinar a visualização de acordo com o patamar desejado.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

* **INMET:** Fonte oficial dos dados meteorológicos de 2025.
* **Microsoft Excel:** Tratamento, limpeza, estruturação e preparação da base de dados tabular.
* **Tableau / Tableau Public:** Modelagem, criação de cálculos visuais, mapas geográficos, gráficos analíticos e publicação do painel interativo.
* **Git & GitHub:** Versionamento e documentação do projeto.

---

## 📂 Estrutura do Repositório

```text
├── data/                  # Base de dados tratada (ou instruções de origem)
├── dashboard/             # Arquivos de apoio ou layout (se aplicável)
└── README.md              # Documentação do projeto
