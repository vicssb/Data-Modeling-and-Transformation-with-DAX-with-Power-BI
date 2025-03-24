<img src="./img/gif v1.gif" min-width="400px" max-width="400px" width="400px" align="right" alt="Computer iuriCode">
<p>
<div align="right"> 
<a href="./readme.md"> <img src="./img/LogoUK.png" alt="Logo UK" width="30"/></a><a href="./leiame.md"> <img src="./img/logoBrazil.png" alt="Logo Brazil" width="30"/> </a>
</div>
  <H1><b> Victor Sérgio Silva Barros </b> </H1>
</p> 

<div align="top" style="display: flex; justify-content: space-between;">
  <img src="./img/LogoSQL.jpeg" alt="SQL Logo" width="80"/>
  <img src="./img/logoBI.jpeg" alt="Power BI Logo" width="80"/>
</div>

# Creating a Star Schema for Sales Scenarios with Power BI

This project is part of the lab [Creating a Star Schema for Sales Scenarios with Power BI](https://web.dio.me/lab/criando-um-star-schema-para-cenarios-de-vendas-com-power-bi/learning/cc70d8ef-2b44-4f53-a05b-643de8e5086b?back=/track/formacao-power-bi-analyst), offered by DIO.

## Objective

The objective of this project is to demonstrate how to create a Star Schema for sales scenarios using Power BI, focusing on optimizing data modeling and improving report performance.

## Modeling Process

We will use the single **Financial Sample** table to create the dimension and fact tables of our Star Schema-based model. The process consists of creating tables based on the original table. From the copy, the columns that will compose the view of the new table will be selected.

### Created Tables

1. **Financials_origem** (hidden mode – backup of the original table).

2. **D_Produtos**:
   - Columns: `ID_produto`, `Produto`, `Average Units Sold`, `Average Sales Value`, `Median Sales Value`, `Maximum Sales Value`, `Minimum Sales Value`.

3. **D_Produtos_Detalhes**:
   - Columns: `ID_produtos`, `Discount Band`, `Sale Price`, `Units Sold`, `Manufacturing Price`.

4. **D_Descontos**:
   - Columns: `ID_produto`, `Discount`, `Discount Band`.

5. **D_Detalhes**:
   - Columns: (*additional details to be defined*).

6. **D_Calendário**:
   - Created using DAX with the `CALENDAR()` function.

7. **F_Vendas**:
   - Columns: `SK_ID`, `ID_Produto`, `Produto`, `Units Sold`, `Sales Price`, `Discount Band`, `Segment`, `Country`, `Salers`, `Profit`, `Date`.

## Tools Used

- **Power BI**: For data processing, modeling, and visualization.

## Expected Results

- Efficient data structuring in a Star Schema.
- Creation of interactive reports and dashboards.
- Improved query and analysis performance.

## Reference

For more details, access the original lab: [Creating a Star Schema for Sales Scenarios with Power BI](https://web.dio.me/lab/criando-um-star-schema-para-cenarios-de-vendas-com-power-bi/learning/cc70d8ef-2b44-4f53-a05b-643de8e5086b?back=/track/formacao-power-bi-analyst).

## Author

**Victor Sérgio Silva Barros**

<p align="left">
  <a href="mailto:vicssb@gmail.com" alt="Gmail" target="_blank">
  <img src="https://img.shields.io/badge/-Gmail-FF0000?style=flat-square&labelColor=FF0000&logo=gmail&logoColor=white&link=mailto:vicssb@gmail.com" /></a>

  <a href="https://www.linkedin.com/in/victor-sergio-silva-barros/" alt="Linkedin" target="_blank">
  <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/victor-sergio-silva-barros/" /></a>

  <a href="https://wa.me/+5512981328278" alt="WhatsApp" target="_blank">
  <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white&link=https://wa.me/+5512987085327"/></a>
</p>

<p>Please follow GitHub and join us! Thank you for visiting and happy coding!</p>