# 🍔 Análise de Dados: Fast Food nos EUA (2019)

**Disciplina:** Lógica de Programação | **Curso:** Administração  
**Fonte dos dados:** QSR Magazine – QSR50 (2020)  
**Dataset:** `top_50_fast_food_US-1.csv` — Top 50 redes de fast food dos EUA em 2019

---

## 📋 Descrição do Projeto

Este projeto realiza uma análise exploratória do setor de fast food nos Estados Unidos com base no ranking **QSR50 de 2019**, publicado pela QSR Magazine. A partir de dados sobre vendas, número de unidades, modelo de negócio (franquia vs. própria) e categoria de produto, o notebook investiga padrões de mercado, eficiência operacional e dinâmicas de crescimento das 50 maiores redes americanas.

---

## 📁 Estrutura do Notebook

| # | Seção | Descrição |
|---|-------|-----------|
| 1 | **Título e descrição** | Apresentação do projeto, disciplina e fonte dos dados |
| 2 | **Importação das bibliotecas** | `pandas`, `matplotlib`, `seaborn`, `numpy` |
| 3 | **Carregamento dos dados** | Upload do CSV, limpeza de colunas e visualização inicial |
| 4 | **Análise de contexto** | Top 5 em vendas e unidades; gráfico de barras horizontais com Top 10 |
| 5 | **Análise de eficiência** | Vendas por unidade; scatter plot eficiência × tamanho da rede |
| 6 | **Franquias vs. Próprias** | Composição por modelo de negócio; barras empilhadas e boxplot |
| 7 | **Segmentação por categoria** | Burger, Chicken, Sandwich, Global etc.; 3 gráficos comparativos |
| 8 | **Conclusões finais** | Síntese dos 5 principais achados de negócio |

---

## 🔍 Principais Achados

### 1. Concentração de Mercado
McDonald's lidera com **US$ 40,4 bilhões** em vendas — quase o dobro do 2º colocado (Starbucks, US$ 21,5 bi). As 5 maiores redes concentram aproximadamente **54% do faturamento total** do QSR50.

### 2. Eficiência ≠ Escala
**Chick-fil-A** (2.500 unidades) tem a maior venda por loja: **US$ 4.517K/unidade**.  
**Subway**, a maior rede em número de unidades (23.802), registra apenas **US$ 410K/unidade** — 11× menos. Foco e posicionamento superam estratégias de expansão pura.

### 3. Modelo Próprio = Maior Eficiência por Loja
Redes majoritariamente próprias (>80%) faturam em média **US$ 2.891K/unidade** — **2,3× mais** que as majoritariamente franqueadas (US$ 1.248K/unidade). Chipotle e In-N-Out Burger são exemplos de alta eficiência com controle total da operação.

### 4. Burger domina em Volume; Chicken lidera em Eficiência
A categoria **burger** fatura **US$ 81,6 bilhões** (38% do total do ranking), mas **chicken** tem a maior média de vendas por unidade (**US$ 2.001K**), mostrando alto valor por loja.

### 5. Crescimento Seletivo
A categoria **global** (+64,8 unidades/rede em média) liderou a expansão em 2019.  
**Sandwich** (-70,6 unidades/rede) foi a que mais retraiu — fortemente influenciada pela perda de 996 unidades do Subway, sinal de reposicionamento do setor.

---

## 📊 Gráficos Gerados

| Arquivo | Conteúdo |
|---------|----------|
| `grafico_top10_vendas.png` | Top 10 redes por vendas totais (barras horizontais) |
| `grafico_dispersao_eficiencia.png` | Scatter plot: total de unidades × vendas por unidade |
| `grafico_franquia_vs_propria.png` | Barras empilhadas (composição) + boxplot (eficiência por modelo) |
| `grafico_categorias.png` | Painel com 3 gráficos: vendas totais, média/unidade e variação de unidades por categoria |

---

## 🛠️ Tecnologias Utilizadas

```python
pandas       # manipulação e análise de dados
matplotlib   # visualização e formatação de gráficos
seaborn      # gráficos estatísticos
numpy        # cálculos auxiliares
```

---

## ▶️ Como Executar

1. Abra o notebook no [Google Colab](https://colab.research.google.com/)
2. Execute as células na ordem
3. Quando solicitado, faça o upload do arquivo `top_50_fast_food_US-1.csv`
4. Os gráficos serão gerados e salvos automaticamente

> **Requisito:** o arquivo CSV deve estar disponível localmente para upload na célula de carregamento de dados.

---

## 📂 Arquivos do Repositório

```
📦 fast-food-analysis/
 ┣ 📓 Trabalho_Prático___Análise_de_Dados_do_Setor_de_Fast_Food_nos_EUA__2019_.ipynb
 ┣ 📄 top_50_fast_food_US-1.csv
 ┗ 📖 README.md
```

---

## 📚 Fonte

> **QSR Magazine – QSR50 (2020)**  
> Ranking anual das 50 maiores redes de fast food dos Estados Unidos, com dados referentes ao ano fiscal de 2019.  
> Disponível em: [qsrmagazine.com](https://www.qsrmagazine.com/content/qsr50-2020-top-50-chart)
