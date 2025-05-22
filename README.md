# GerandoPlanilhaEstoque

## Sobre o Projeto

Este projeto em Python simplifica o controle de estoque para revendedoras de cosméticos. Ele automatiza a geração de uma planilha Excel (`.xlsx`) com informações de produtos (estoque, preços, lucro). A extração dos dados brutos de catálogos ou pedidos em PDF é concebida para ser realizada com o auxílio do **Gemini**, eliminando a necessidade de entrada manual.

## Funcionalidades Principais

* Cálculo e acompanhamento de estoque atual e seu valor.
* Análise de lucro por produto e geral.
* Agregação de dados de produtos e operações.
* Exportação para planilha Excel pronta para uso.

## Tecnologias Utilizadas

* **Python**
* **Pandas**: Para manipulação e análise de dados.
* **NumPy**: Para operações numéricas.
* **Jupyter Notebook**: Ambiente de desenvolvimento.
* **Gemini**: Para a extração e estruturação inicial dos dados de arquivos PDF.

## Como Usar

1.  **Instale as dependências:**
    ```bash
    pip install pandas numpy
    ```
2.  **Extração de Dados com Gemini:**
    * Utilize o Gemini para extrair e estruturar os dados relevantes (e.g., nome do produto, preços, quantidades) dos seus arquivos PDF de catálogos ou pedidos.
    * Certifique-se de que a saída do Gemini esteja em um formato que possa ser facilmente incorporado ou lido pelo notebook (e.g., JSON, CSV, ou um dicionário Python).
3.  **Prepare os dados no Notebook:** Insira os dados estruturados obtidos do Gemini no arquivo `ControleEstoque.ipynb` (substituindo o exemplo existente `json_data`).
4.  **Execute o Notebook:** Abra `ControleEstoque.ipynb` no Jupyter e rode todas as células.
5.  **Resultado:** A planilha `planilha_controle_de_estoque.xlsx` será gerada no diretório do projeto.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para sugerir melhorias ou novas funcionalidades.

---

**Autor:** HelissonFabiano da Silva
**Data:** 15/05/2025
