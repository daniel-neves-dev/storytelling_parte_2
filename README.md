<h1>Data Analytics com Power BI</h1> 

<h2>Desafio 5 - Parte 2: Criando Relatório de Vendas
<p></p>
Objetivo:</h2>

<p>Este projeto foi desenvolvido como parte do Bootcamp NTT DATA Engenharia de Dados com Python, oferecido pela Digital Innovation One (DIO). O foco deste desafio é criar um relatório de vendas utilizando os conceitos de data analystics, modelagem star schema,
navegação entre páginas com botões, gráficos de dispersão, limpeza e transformação de dados, experiência do usuário, formulas DAX, mesclagem de tabelas, e todos os conhecimentos adquiridos durante o bootcamp.</p>


<h3> Primeiro passo: limpeza e transformação de dados. </h3>

<h4> Tabelas:</h4>

-------------------------------------------------------
<p>d-produtos</p>

![d-produtos](https://github.com/user-attachments/assets/6e1ec09c-2524-4b80-8714-a327fedc423b)
-------------------------------------------------------

-------------------------------------------------------
<p>d-vendas</p>

![d-vendas](https://github.com/user-attachments/assets/d19a3242-9291-4a99-9490-09acbe01081a)
-------------------------------------------------------

-------------------------------------------------------
<p>d-país</p>

![d-paises](https://github.com/user-attachments/assets/413cbeb4-38e1-4a74-8ffb-de2acaa4e49e)
-------------------------------------------------------

-------------------------------------------------------
<p>f-vendas</p>

![f-vendas](https://github.com/user-attachments/assets/5079ce67-ba8c-480d-bbe0-6c526814d4a1)
-------------------------------------------------------

<h3> Segundo passo: relacionamento star schema. </h3>

-------------------------------------------------------
![star-schema](https://github.com/user-attachments/assets/45acf282-fbb5-4760-b457-e9b7383f29f9)
-------------------------------------------------------

<h3>Terceiro passo: relatórios</h3>

<h4>Página 1: Relatório de Vendas</h4>

<p>Esta página apresenta uma visão geral das vendas brutas, líquidas, descontos, lucro e COGS (Custo das Mercadorias Vendidas). Inclui um gráfico de vendas por período, distribuição das vendas por segmento e uma visão de vendas brutas por país, destacando os principais mercados, como Estados Unidos, Canadá e França.</p>

-------------------------------------------------------
![pagina1](https://github.com/user-attachments/assets/be400db4-b3f4-46c9-aa44-033921d247d2)
-------------------------------------------------------

<h4>Página 2: Vendas por Produto e Período</h4>

<p>Focando nas unidades vendidas e vendas brutas, esta página exibe gráficos de dispersão que mostram a relação entre a quantidade vendida e o lucro, tanto por produto quanto por mês. Isso permite uma análise detalhada do desempenho de cada produto ao longo do tempo.</p>

-------------------------------------------------------
![pagina2](https://github.com/user-attachments/assets/0cc749ca-85e3-4766-89a6-10bf0496aab7)
-------------------------------------------------------

<h4>Página 3: Detalhes de Vendas</h4>

<p>Nesta página, temos uma visão detalhada das vendas por semestre e ano, além de histogramas que mostram a quantidade de unidades vendidas e a distribuição das vendas por produto. Também há uma tabela que detalha as vendas por trimestre.</p>

-------------------------------------------------------
![pagina3](https://github.com/user-attachments/assets/b2b02bd1-96b6-4796-b428-fa5d7cd96aa8)
-------------------------------------------------------

<h4>Página 4: Top 3 Produtos</h4>

<p>Esta página foca nos três produtos mais vendidos em cada país, apresentando gráficos de barras que comparam a venda bruta e os principais produtos em cada mercado. Também há gráficos circulares que mostram o lucro e as vendas por mês, oferecendo uma visão clara do desempenho mensal.</p>

-------------------------------------------------------
![pagina4](https://github.com/user-attachments/assets/edd81bda-88fe-48d9-a4ad-14e6c08bf472)
-------------------------------------------------------

<h4>Página 5: Top 3 Países</h4>

<p>Por fim, esta página destaca os três países com as maiores vendas. Os gráficos de barras mostram a venda máxima e os três principais produtos em cada país. Um gráfico circular ilustra a participação percentual dos países em relação às vendas máximas.</p>

-------------------------------------------------------
![pagina5](https://github.com/user-attachments/assets/75b9bba9-05aa-437b-b33e-25ba008ba1c3)
-------------------------------------------------------

## Tecnologia usada.

- **Power BI** - Ferramenta de visualização de dados utilizada para criar os relatórios interativos.
-----------------------------------------------------------
### Como Executar:

1 - Faça o download do arquivo .pbix (storytellying_2).

2 - Abra o arquivo no Power BI Desktop.

3 - Navegue pelas páginas de vendas, produtos e países, utilizando os filtros interativos para explorar os dados de diferentes ângulos e obter insights.
