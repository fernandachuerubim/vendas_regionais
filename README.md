# Regional Sales - Power BI

## Sobre o projeto

Este projeto tem como objetivo a análise de vendas regionais, desenvolvido no Microsoft Power BI no formato **.pbip** (Power BI Project). 

O uso do formato PBIP permite versionar todo o projeto (relatório, modelo semântico e configurações) diretamente com Git, facilitando o acompanhamento de alterações e o trabalho colaborativo.

## Estrutura do projeto

```plaintext
regional_sales/
├── dataset/                    # Base de dados utilizada pelo modelo
├── regional_sales.Report/      # Definição do relatório (páginas, visuais, temas e configurações)
├── regional_sales.SemanticModel/ # Modelo semântico (tabelas, relacionamentos, medidas DAX e colunas calculadas)
├── regional_sales.pbip         # Arquivo principal do projeto Power BI
└── .gitignore
```

## Tecnologias utilizadas

- [Microsoft Power BI Desktop](https://www.microsoft.com/pt-br/power-platform/power-bi/desktop)
- Power Query (M)
- DAX (Data Analysis Expressions)
- Formato [Power BI Project (.pbip)](https://learn.microsoft.com/pt-br/power-bi/developer/projects/projects-overview)

## Como abrir o projeto

1. Instale a versão mais recente do **Power BI Desktop** com suporte a arquivos `.pbip`.
2. Clone este repositório:
   ```bash
   git clone https://github.com/fernandachuerubim/vendas_regionais.git
   ```
3. Abra o arquivo `regional_sales.pbip` diretamente no Power BI Desktop.
4. Caso as fontes de dados estejam em caminhos locais, atualize-as em `Transformar dados > Configurações da fonte de dados`.

## Observações

- Os arquivos dentro de `regional_sales.Report/` e `regional_sales.SemanticModel/` são gerados pelo Power BI Desktop. Não é recomendado editá-los manualmente.
- Caso o diretório `dataset/` esteja vazio ou com arquivos diferentes, verifique as configurações de origem dos dados após abrir o projeto.

## Fonte

Dados públicos do site do Power Bi da Microsoft:
https://learn.microsoft.com/en-us/power-bi/create-reports/sample-regional-sales
