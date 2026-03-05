# 📊 Alura Store: Análise de Vendas e Desempenho das Lojas

<p align="center">
  <em>Projeto de inteligência de dados para suporte à decisão estratégica do Senhor João. 📈✨</em>
</p>

---

## 🎯 Objetivo do Projeto
O objetivo desta análise foi avaliar o desempenho de quatro unidades da rede Alura Store para identificar qual delas apresenta o cenário mais favorável para **desinvestimento (venda)**, garantindo que o Senhor João mantenha os ativos mais rentáveis e com maior potencial de crescimento.

## 🛠️ Tecnologias Utilizadas
- **Python**: Linguagem base. 🐍
- **Pandas**: Processamento e manipulação de dados. 📑
- **Matplotlib & Seaborn**: Visualização de dados e criação de dashboards. 🎨
- **Numpy**: Cálculos matemáticos. 🔢

## ⚙️ Processamento e Transformação
Os dados foram coletados de arquivos CSV individuais para cada loja.
- **Unificação**: Utilizamos o método `concat` do Pandas para criar um banco de dados unificado.
- **Limpeza**: Os dados foram verificados quanto a nulos e duplicatas, apresentando alta integridade ("redondinhos"). 💅
- **Enriquecimento**: Criamos colunas de **Ano** e **Mês** a partir das datas de compra para análise de sazonalidade.

---

## 📉 Resumo da Performance Operacional

| Métrica | Melhor Desempenho | Menor Desempenho |
| :--- | :--- | :--- |
| **Faturamento Total** | Loja 1 (R$ 1,53M) | Loja 4 (R$ 1,38M) |
| **Ticket Médio** | Loja 1 (R$ 650,00) | Loja 4 (R$ 587,17) |
| **Avaliação de Clientes** | Loja 3 (4.05) | Loja 1 (3.98) |
| **Custo Médio do Frete** | **Loja 4 (R$ 31,28)** | Loja 1 (R$ 34,69) |

---

## 💡 Recomendação Estratégica: Por que vender a Loja 4?

Após cruzar os dados de faturamento, vendas por categoria e comportamento temporal, a recomendação é a venda da **Loja 4**. 

### Justificativa Técnica:
1. **Faturamento vs. Esforço**: Embora o volume de vendas seja próximo ao das outras unidades, a Loja 4 gera o menor faturamento absoluto. Isso indica que ela opera com produtos de menor margem ou ticket médio inferior.
2. **Ciclo de Queda**: A análise mensal detectou uma tendência de queda nas vendas desta unidade. É estratégico vender um ativo enquanto ele ainda possui valor de mercado robusto antes de uma desvalorização maior. 
3. **Atratividade para o Comprador**: A Loja 4 possui o **menor custo de frete da rede**. Para um novo dono, este é um diferencial competitivo enorme que facilita a recuperação da margem de lucro se bem trabalhado no marketing. 

### Por que não vender a Loja 1?
A Loja 1 é o nosso motor de receita principal. Vender nossa unidade mais lucrativa causaria um um impacto negativo imediato no fluxo de caixa global. Além disso, a Loja 4 já provou ter potencial, tendo sido líder de vendas no Ano 1, o que a torna um excelente "ativo de recuperação" para terceiros. 

---

##  Autor
** (Lucas Torres)**
