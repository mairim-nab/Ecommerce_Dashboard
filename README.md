# Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX

## Desafio: Modelagem e Transformação de Dados com DAX no Power BI

### Descrição do Desafio

O objetivo deste projeto foi utilizar a tabela única **Financial Sample** para construir um modelo de dados baseado no esquema estrela (*star schema*), criando tabelas de dimensão e fato. Esse processo envolveu a criação de novas tabelas derivadas da tabela original, selecionando colunas específicas para compor as visões necessárias. A tabela principal (fato) serviu como base para gerar as tabelas de dimensão.

### Estrutura das Tabelas
- **Financials_origem** (modo oculto - backup)
- **F_Vendas** (fato)
- **D_Produtos** (dimensão)
- **D_Produtos_Detalhes** (dimensão)
- **D_Detalhes** (dimensão)
- **D_Calendário** (dimensão)

### Descrição dos Passos Realizados

#### 1. Importação de Dados
Os dados foram importados diretamente da planilha **Financial Sample** para o Power BI Desktop.

#### 2. Duplicação da Tabela
A tabela **Financials** foi duplicada e renomeada como **Financials_origem**, mantendo-a como backup no modo oculto.

#### 3. Criação da Tabela Fato
Na área de modelagem, foi criada a tabela **F_Vendas**, que representa a tabela fato principal do modelo.

#### 4. Criação das Tabelas de Dimensão
As seguintes tabelas de dimensão foram criadas a partir da tabela principal:

- **D_Produtos**
- **D_Produtos_Detalhes**
- **D_Detalhes**
- **D_Descontos**
- **D_Calendário** (construída com base no guia "Os Primeiros Passos com DAX")

#### 5. Transformação e Definição de Colunas
As colunas das tabelas de dimensão foram transformadas e organizadas conforme as necessidades do modelo:

- **D_Produtos**: Contém informações gerais dos produtos.
- **D_Produtos_Detalhes**: Detalhes específicos de cada produto.
- **D_Descontos**: Informações relacionadas a descontos aplicados.
- **D_Detalhes**: Dados adicionais relevantes.

#### 6. Organização e Relacionamentos
As tabelas foram organizadas e os relacionamentos entre elas foram definidos de acordo com o esquema estrela, garantindo uma estrutura otimizada para análise de dados.

### Conclusão
O modelo criado seguiu as boas práticas de modelagem de dados e organização em esquema estrela, utilizando ferramentas do Power BI e fórmulas DAX para proporcionar uma estrutura eficiente e flexível para análise. Esse dashboard pode ser utilizado para gerar insights estratégicos relacionados às vendas e operações do e-commerce.

