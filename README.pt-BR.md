# Análise Comercial da Performance de Vendas

## 1- Visão Geral
Este projeto apresenta um dashboard de análise comercial desenvolvido no Microsoft Power BI, com foco na avaliação da performance de vendas por segmento, fabricante, categoria, pontos de venda e vendedores. O objetivo é gerar insights acionáveis para apoiar decisões estratégicas e operacionais.

---

## 2- Contexto de Negócio
O cliente solicitou uma visão consolidada do desempenho de vendas por segmento, fabricante e categoria de produtos, além de uma análise detalhada do desempenho dos pontos de venda e representantes comerciais. Também foi incluído o visual de *Principais Influenciadores*, permitindo identificar fatores que impulsionam ou reduzem o valor de vendas.

---

## 3- Dataset
* Registros: 457 linhas
* Formato: CSV
* Qualidade dos dados: Sem valores nulos ou em branco

---

### 4- Features
* ID do Produto
* Produto
* Categoria
* Segmento
* Fabricante
* Loja
* Cidade
* Estado
* Vendedor
* ID do Vendedor
* Comissão (%)
* Data da Venda
* Valor da Venda
* Custo

---

## 4- Tratamento de Dados
O dataset apresentou estrutura bem alinhada ao negócio. Os principais ajustes realizados foram a padronização das colunas de *Estado* e *Cidade*, garantindo consistência para análises geográficas e agregações corretas.

---

## 5- Estrutura do Dashboard
* **Narrativa Inteligente**: Resumo automático dos principais padrões e variações de vendas.
* **Vendas por Segmento**: Participação de cada segmento no faturamento total.
* **Vendas por Fabricante e Categoria**: Identificação de marcas e linhas de produtos mais relevantes.
<img width="1288" height="721" alt="Print - narrativa inteligente" src="https://github.com/user-attachments/assets/54a81ffa-f903-4301-85ed-80dcc3b3a41f" />

* **Faixas de Vendas por Categoria e PDV**: Comparação da distribuição de vendas entre lojas.
<img width="1290" height="723" alt="Print - Faixa de vendas x categoria e pdv" src="https://github.com/user-attachments/assets/31f31f36-396a-4179-a065-42ed62930b37" />

* **Principais Influenciadores**: Fatores que aumentam ou reduzem o valor das vendas.
<img width="1285" height="720" alt="Print - principais influenciadores" src="https://github.com/user-attachments/assets/9263cce4-bcb0-4a74-a7a1-9984894c37a5" />

* **Performance por Região e Vendedor**: Análise geográfica e individual utilizando mapas.
<img width="1287" height="716" alt="Print - Vendas x região e vendedor" src="https://github.com/user-attachments/assets/7cc8dc2c-6c2f-4957-b07b-e15a7b84b5be" />

---

## 6- Principais Conclusões
* O **segmento Corporativo** apresenta maior valor médio de vendas em comparação aos segmentos Doméstico e Industrial.
* A categoria **Eletrodomésticos** concentra a maior parte do faturamento, seguida por **Celulares**.
* Poucos fabricantes concentram grande parcela das vendas, indicando possível risco de dependência.
* Há diferenças relevantes de performance entre regiões e vendedores, sugerindo oportunidades para ações direcionadas de incentivo e capacitação.
* O visual de *Principais Influenciadores* evidencia que segmento e categoria são os fatores mais determinantes para o valor de venda.

---

## 7- Ferramentas Utilizadas
* Microsoft Power BI
* DAX para medidas calculadas
* Fonte de dados em CSV

---

## 8- Contato
Para projetos, parcerias ou oportunidades profissionais, entre em contato:

**Leandro Álax**
Email: [leandroalax@hotmail.com](mailto:leandroalax@hotmail.com)
