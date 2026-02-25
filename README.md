# 🛒 Análise de Dados de Preços e Descontos em Supermercado do Chile

Este projeto faz parte do Módulo 13 – Fundamentos da Descoberta de Dados, no qual realizo uma investigação estatística e exploratória sobre uma base de produtos de um supermercado no Chile.

O objetivo é aplicar técnicas de estatística descritiva, visualização de dados, boxplots, gráficos de barras e treemap interativo, identificando padrões relevantes sobre preços, categorias e descontos.

# 📊 Objetivos do Projeto

Explorar a distribuição dos preços por categoria.

Comparar Média vs. Mediana em cada categoria.

Identificar categorias com maior variabilidade (desvio padrão).

Detectar outliers em categorias críticas.

Visualizar descontos por categoria e por marca.

Criar um treemap interativo com Plotly.

# 📁 Sobre os Dados

A base contém as seguintes variáveis:

Title: Nome do produto

Marca: Marca do produto

Categoria: Categoria (em espanhol)

Preco_Normal: Preço sem desconto

Preco_Desconto: Preço após desconto

Preco_Anterior: Preço antes do desconto atual

Desconto: Valor do desconto aplicado

As colunas com 0 indicam produtos sem desconto.

# 🧠 Principais Perguntas Respondidas
## 1️⃣ Média e Mediana por Categoria

Foi calculada a média e a mediana da coluna Preço_Normal para cada categoria.

### Insight:
Em praticamente todas as categorias, a média ficou acima da mediana, indicando a presença de valores altos puxando a média (assimetria positiva).

## 2️⃣ Desvio Padrão por Categoria

Calculei média, mediana e desvio padrão para cada categoria.

Categoria com maior desvio padrão:
### 👉 lacteos

O que isso significa?

A média dos preços é muito maior que a mediana.

Há forte presença de valores extremos.

Alto grau de variabilidade dentro da categoria.

## 3️⃣ Boxplot da Categoria com Maior Desvio

A categoria lacteos apresenta:

Distribuição assimétrica

Muitos outliers, confirmando a grande variabilidade

Preços que variam bastante dentro de uma mesma categoria

(Aqui você pode inserir uma imagem do boxplot quando postar no GitHub)

## 4️⃣ Desconto Médio por Categoria (Bar Plot)

Foi criado um gráfico de barras mostrando a média dos descontos aplicados.

### Insight:

Podemos identificar quais categorias mais recebem promoções, auxiliando campanhas de marketing e gestão de estoque.

## 5️⃣ Treemap Interativo (Categoria → Marca → Desconto)

Utilizando Plotly, foi criado um treemap que mostra:

Categorias

Subdivisão por marcas

Média de descontos encontrados

Essa visualização facilita descobrir:

Quais marcas oferecem mais descontos

Quais categorias são mais competitivas

Relações hierárquicas entre marca e categoria

# 🛠️ Tecnologias Utilizadas

Python 3.10+

Pandas

Matplotlib

Plotly Express

Google Colab

# 📦 Como Reproduzir o Projeto
# Clone o repositório
git clone https://github.com/RonaldoFerreiraMacedo/NOME_DO_REPOSITORIO.git

# Instale dependências
pip install pandas matplotlib plotly

Ou execute diretamente no Google Colab.

# 📈 Principais Conclusões

A categoria lacteos possui a maior variabilidade de preços, sugerindo produtos muito heterogêneos.

A diferença entre média e mediana em várias categorias indica possíveis outliers persistentes.

O treemap mostra marcas que consistentemente oferecem descontos acima da média.

A análise pode ajudar departamentos de precificação e marketing a entender onde aplicar promoções.

# 📌 Próximos Passos / Melhorias Futuras

Criar dashboards em Power BI ou Streamlit.

Aplicar clustering para segmentar categorias por comportamento.

Identificar sazonalidade de descontos.

Criar relatório final em PDF com insights.

# 🧑‍💻 Autor

Ronaldo Ferreira Macedo
Cientista de Dados em formação
📎 GitHub: https://github.com/RonaldoFerreiraMacedo

📎 LinkedIn: [https://www.linkedin.com/in/macedoronaldo/]
