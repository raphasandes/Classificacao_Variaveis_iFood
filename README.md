# 🧑‍🏫 Classificação de Variáveis em Análise de Dados com Pandas (Base iFood)

Este projeto didático visa demonstrar o processo fundamental de **classificação de variáveis** (em Numéricas e Categóricas, e seus subtipos) utilizando a biblioteca **Pandas** em Python.
A análise é realizada sobre um conjunto de dados real de restaurantes do iFood.

---

## 🎓 Contexto do Projeto

Este exercício foi desenvolvido como parte da **Formação em Ciência de Dados** da **Escola DNC**, na disciplina de **Estatística com Python**.
O objetivo é aplicar conceitos estatísticos e de programação em um cenário de dados reais.

---

## 🎯 Objetivo

O principal objetivo deste guia é:

* **Distinguir** entre variáveis numéricas (Discretas e Contínuas) e categóricas (Nominais e Ordinais).
* **Aplicar** comandos essenciais do Pandas para inspecionar tipos de dados e valores únicos.
* **Preparar** a base para análises estatísticas mais aprofundadas, garantindo o tratamento adequado para cada tipo de variável.

---

## 📊 Entendendo o Conjunto de Dados

O DataFrame (`df`) contém informações de restaurantes do iFood. As colunas principais são:

| Coluna | Descrição | Tipo no Pandas (`dtype`) |
| :--- | :--- | :--- |
| `avatar` | URL da imagem do avatar do restaurante. | `object` |
| `category` | Tipo de comida oferecido (ex: Lanches, Pizza). | `object` |
| `delivery_fee` | Taxa de entrega do restaurante. | `float64` |
| `delivery_time` | Tempo estimado de entrega (em minutos). | `int64` |
| `distance` | Distância do restaurante (em km). | `float64` |
| `name` | Nome do restaurante. | `object` |
| `price_range` | Classificação do preço (CHEAPEST, CHEAP, etc.). | `object` |
| `rating` | Avaliação do restaurante pelos usuários. | `float64` |
| `url` | Link para a página do restaurante no iFood. | `object` |
| `lat`, `long` | Coordenadas geográficas. | `float64` |

---

## 💻 Passos da Análise

O processo de carregamento, inspeção e classificação dos dados está detalhado no notebook `classificando_variaveis.ipynb`.

### 1. Identificação dos Tipos de Dados

Utilizamos `df.dtypes` e `df.info()` para um *overview* dos tipos de dados detectados pelo Pandas.

```python
df.dtypes

---

## 🎓 Observação importante

O dataset foi intencionalmente diminunído para que pudesse ser utilizado na plataforma Git. O arquivo original continham mais que 350.000 registro e 113,6 MB.

---
