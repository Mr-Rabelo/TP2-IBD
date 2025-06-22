# TP2-IBD
## 📚 Educação e Oportunidades de Emprego no Brasil (2023)

Este repositório contém os códigos e scripts desenvolvidos para o trabalho prático da disciplina de Introdução a Banco de Dados (IBD) da Universidade Federal de Minas Gerais (UFMG). O objetivo do projeto é investigar a correlação entre a infraestrutura e os resultados educacionais (básicos e superiores) e os indicadores de emprego e renda nos estados brasileiros em 2023.

---

### 🚀 Sobre o Projeto

A Lei de Acesso à Informação (LAI) tem promovido a transparência e o acesso a dados governamentais. Neste contexto, a integração de dados de educação e trabalho oferece um panorama valioso sobre o desenvolvimento social e econômico do país. Este estudo busca responder a questões como: "Unidades Federativas com melhores indicadores de infraestrutura escolar e maior qualificação docente na educação superior apresentam, de fato, melhores oportunidades de emprego e maiores níveis de renda para sua população?".

Para isso, utilizamos dados de três fontes públicas importantes do Brasil:

1.  **Censo Escolar da Educação Básica (INEP)**: Dados sobre infraestrutura, matrículas, turmas e docentes de todas as escolas de educação básica do país.
2.  **Censo da Educação Superior (INEP)**: Informações sobre Instituições de Educação Superior (IES), cursos de graduação e docentes.
3.  **Pesquisa Nacional por Amostra de Domicílios Contínua (PNAD Contínua - IBGE)**: Principal pesquisa sobre força de trabalho no país, investigando trimestralmente características de emprego, desemprego, renda e outras características sociais.

---

### 📁 Conteúdo do Repositório

Este repositório está organizado para facilitar a compreensão e reprodução do trabalho:

* **`notebooks/`**: Notebooks Jupyter (ou scripts Python) utilizados para:
    * **Limpeza e Pré-processamento de Dados**: Scripts para leitura dos arquivos `.txt` da PNAD Contínua, seleção de variáveis, tratamento de dados nulos/descontinuados, renomeação de colunas e conversão para `.csv`.
    * **Carga de Dados**: Scripts para importação dos dados para o SGBD PostgreSQL.
* **`sql/`**: Arquivos SQL contendo as consultas utilizadas para:
    * **Criação do Esquema do Banco de Dados**: Definição das tabelas `escolas`, `ies` e `pnad_2023` no PostgreSQL.
    * **Consultas de Análise Descritiva**: Para extrair estatísticas básicas das principais variáveis de educação e emprego.
    * **Consultas de Agregação**: Para calcular indicadores estaduais (ex: % de escolas com internet de banda larga, % de docentes com doutorado, taxa de desocupação, rendimento médio mensal).
    * **Consultas de Análise de Correlação e Integração**: Para investigar as relações entre os indicadores educacionais e de emprego/renda.

---

### 🛠️ Ferramentas Utilizadas

* **SGBD**: PostgreSQL 
* **Linguagem de Análise**: Python 
    * **Bibliotecas**: Pandas, NumPy, OS (para manipulação de dados) 
    * **Visualização**: Matplotlib, Seaborn (para gráficos e visualizações) 
* **Linguagem de Consulta**: SQL 

---

### 💡 Próximos Passos e Conclusão

As conclusões do projeto e possíveis desdobramentos podem ser encontrados no relatório final, que será disponibilizado.

---

### 🎓 Autores

* Arthur Ferreira Rabelo
* Felipe Almeida Pereira
* Felipe Silva Fraga Damasceno
* Raiza Wunsch Pinto

---
**Disciplina:** Introdução a Banco de Dados (IBD)
**Semestre:** 1º Semestre de 2025
**Universidade:** Universidade Federal de Minas Gerais (UFMG)
**Data de Geração do Relatório:** 22 de junho de 2025
