
# Análise de Vendas, Lucro e Unidades Vendidas

Projeto desenvolvido como desafio prático do bootcamp **Analisando Dados com SQL, Analytics e Power BI** da [DIO](https://www.dio.me/).

## 📊 Paginas do Relatório



1. **Página 1 – Relatório de vendas considerando produtos e segmento**
   Vendas totais por produto, preço médio de venda por produto e vendas por produto/ano/segmento.

2. **Página 2 – Relatório de vendas considerando Países e Lucro**
   Lucro por país, total de vendas e máximo de unidades vendidas, evolução do lucro médio por mês e vendas por país.

3. **Página 3 – Relatório Detalhado**
   Árvore de decomposição do COGS (custo das mercadorias vendidas), gráfico cascata de COGS por segmento, treemap de COGS médio por vendas, com filtros por faixa de desconto, mês e país.

4. **Página 4 – Distribuição de Lucros, Vendas e Unidades vendidas por países e segmentos** 
   - Mapa: soma de lucro por país (cor mais escura = maior lucro)
   - Mapa: soma de vendas e unidades vendidas por país (cor mais escura = maior venda; unidades vendidas disponíveis ao passar o mouse)
   - Gráfico de pizza: lucro por segmento

   > Os mapas usam o visual **Shape Map** com um mapa-múndi customizado (ao invés do visual nativo Map/Filled Map), pelo motivo explicado na seção abaixo.

## 🗂️ Fonte dos dados

Os dados utilizados (Financial Sample) foram disponibilizados pela expert no repositório original do curso:
🔗 https://github.com/julianazanelatto/power_bi_analyst

## 🛠️ Ferramentas utilizadas

- Power BI Desktop
- Sample financeira fornecida pelo curso

## ⚠️ Desafio técnico e solução

No meu ambiente, utilizando uma conta pessoal da Microsoft, não consegui utilizar os visuais nativos Map e Filled Map, pois o acesso ao serviço de mapas apresentou limitações relacionadas à autenticação/conta.

**Solução:** utilizei o visual **Shape Map**, carregando um arquivo TopoJSON customizado com as fronteiras dos países do mundo, o que permitiu criar os mapas coroplético (choropleth) por país sem depender de nenhuma autenticação corporativa.

Como também não havia acesso ao Power BI Service para publicação, o relatório foi entregue em formato **PDF**, exportado diretamente do Power BI Desktop.

## 📎 Arquivos neste repositório

| Arquivo | Descrição |
|---|---|
| `relatorio.pbix` | Arquivo original do projeto Power BI |
| `relatorio.pdf` | Exportação em PDF do relatório completo |

## 🖼️ Prévia da página 4
<img width="476" height="407" alt="Captura de tela 2026-08-05 140548" src="https://github.com/user-attachments/assets/4859868a-8e1c-4536-ac08-2661e9bac522" />



---

Projeto feito para fins de estudo e portfólio, como parte do bootcamp da [DIO](https://www.dio.me/).






