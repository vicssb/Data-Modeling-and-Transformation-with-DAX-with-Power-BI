<img src="./img/gif v1.gif" min-width="400px" max-width="400px" width="400px" align="right" alt="Computador iuriCode">
<p>
<div align="right"> 
<a href="./readme.md"> <img src="./img/LogoUK.png" alt="Logo UK" width="30"/></a><a href="./leiame.md"> <img src="./img/logoBrazil.png" alt="Logo Brasil" width="30"/> </a>
</div>
  <H1><b> Victor Sérgio Silva Barros </b> </H1>
</p> 

<div align="top" style="display: flex; justify-content: space-between;">
  <img src="./img/LogoSQL.jpeg" alt="Logo SQL" width="80"/>
  <img src="./img/logoBI.jpeg" alt="Logo Power BI" width="80"/>
</div>

# Criando um Star Schema para Cenários de Vendas com Power BI

Este projeto faz parte do laboratório [Criando um Star Schema para Cenários de Vendas com Power BI](https://web.dio.me/lab/criando-um-star-schema-para-cenarios-de-vendas-com-power-bi/learning/cc70d8ef-2b44-4f53-a05b-643de8e5086b?back=/track/formacao-power-bi-analyst), oferecido pela DIO.

## Objetivo

O objetivo deste projeto é demonstrar como criar um Star Schema para cenários de vendas utilizando Power BI, com foco em otimizar a modelagem de dados e melhorar a performance de relatórios.

## Processo de Modelagem

Utilizaremos a tabela única **Financial Sample** para criar as tabelas dimensão e fato do nosso modelo baseado em Star Schema. O processo consiste na criação das tabelas com base na tabela original. A partir da cópia, serão selecionadas as colunas que irão compor a visão da nova tabela.

### Tabelas Criadas

1. **Financials_origem** (modo oculto – backup da tabela original).

2. **D_Produtos**:
   - Colunas: `ID_produto`, `Produto`, `Média de Unidades Vendidas`, `Médias do Valor de Vendas`, `Mediana do Valor de Vendas`, `Valor Máximo de Venda`, `Valor Mínimo de Venda`.

3. **D_Produtos_Detalhes**:
   - Colunas: `ID_produtos`, `Discount Band`, `Sale Price`, `Units Sold`, `Manufactoring Price`.

4. **D_Descontos**:
   - Colunas: `ID_produto`, `Discount`, `Discount Band`.

5. **D_Detalhes**:
   - Colunas: (*detalhes adicionais a serem definidos*).

6. **D_Calendário**:
   - Criada por DAX com a função `CALENDAR()`.

7. **F_Vendas**:
   - Colunas: `SK_ID`, `ID_Produto`, `Produto`, `Units Sold`, `Sales Price`, `Discount Band`, `Segment`, `Country`, `Salers`, `Profit`, `Date`.

## Ferramentas Utilizadas

- **Power BI**: Para processamento, modelagem e visualização de dados.

## Resultados Esperados

- Estruturação eficiente de dados em um Star Schema.
- Criação de relatórios e dashboards interativos.
- Melhoria na performance de consultas e análises.

## Referência

Para mais detalhes, acesse o laboratório original: [Criando um Star Schema para Cenários de Vendas com Power BI](https://web.dio.me/lab/criando-um-star-schema-para-cenarios-de-vendas-com-power-bi/learning/cc70d8ef-2b44-4f53-a05b-643de8e5086b?back=/track/formacao-power-bi-analyst).

## Autor

**Victor Sérgio Silva Barros**

<p align="left">
  <a href="mailto:vicssb@gmail.com" alt="Gmail" target="_blank">
  <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=mailto:vicssb@gmail.com" /></a>

  <a href="https://www.linkedin.com/in/victor-sergio-silva-barros/" alt="Linkedin" target="_blank">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/victor-sergio-silva-barros/" /></a>

  <a href="https://wa.me/+5512981328278" alt="WhatsApp" target="_blank">
  <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white&link=https://wa.me/+5512987085327"/></a>
</p>

<p>Por favor, siga o GitHub e junte-se a nós! Obrigado pela visita e boa codificação!</p>