# Análise de Dados Hospitalares

### Visão Geral

Este projeto é uma análise de dados exploratória (EDA) sobre informações de pacientes de um hospital. O objetivo foi extrair, tratar e visualizar dados para obter insights valiosos sobre custos de tratamento, demografia de pacientes e eficiência operacional.

O projeto foi dividido em duas etapas principais:
1.  **Pré-processamento e extração de dados com Python:** Utilização da biblioteca Pandas para carregar, inspecionar e limpar o dataset original (`hospital.csv`).
2.  **Visualização e criação de dashboard com Power BI:** Construção de um painel interativo para visualizar métricas chave de forma clara e intuitiva.

### Ferramentas e Tecnologias

* **Python:** Para manipulação e pré-processamento de dados.
* **Pandas:** Biblioteca fundamental de Python para análise e limpeza de dados.
* **Power BI:** Para visualização de dados e criação do dashboard.

### Estrutura do Projeto

* `hospital.csv`: O dataset original contendo as informações dos pacientes.
* `hospital_limpo.csv`: O dataset limpo e preparado após o pré-processamento em Python.
* `dashboard_hospitalar.pbix` (ou imagens do dashboard): O arquivo do projeto no Power BI, mostrando as visualizações criadas.

### Principais Análises e Visualizações

O dashboard interativo no Power BI permite explorar as seguintes métricas:

* **Custo Médio de Tratamento por Departamento:** Identifica os setores com maior custo médio.
* **Distribuição de Pacientes por Idade e Gênero:** Revela o perfil demográfico da base de pacientes.
* **Total de Pacientes com e sem Seguro:** Analisa a cobertura de seguro dos pacientes.
* **Evolução do Custo Total ao Longo do Tempo:** Permite identificar tendências e sazonalidade nos gastos.
* **Duração Média da Estadia por Diagnóstico:** Oferece insights sobre a eficiência e complexidade dos tratamentos.

### Como Executar o Projeto

1.  **Clonar o repositório:**
    `git clone <URL_DO_SEU_REPOSITÓRIO>`
2.  **Executar o script Python:**
    `python analise_hospital.py`
    Este passo irá gerar o arquivo `hospital_limpo.csv`.
3.  **Abrir o dashboard no Power BI:**
    Abra o arquivo `.pbix` (se disponível) ou importe o `hospital_limpo.csv` no Power BI Desktop para replicar as visualizações.

