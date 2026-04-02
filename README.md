# 📊 Análise dos Sorteios da Mega-Sena

Este projeto realiza uma análise exploratória dos sorteios da Mega-Sena, utilizando **Python** e a biblioteca **Pandas**. O objetivo é identificar padrões, estatísticas e curiosidades nos números sorteados ao longo do tempo.

O conjunto de dados utilizado contém **2.988 concursos**, com informações sobre os números sorteados, vencedores e valores de prêmios.

---

## 🔍 Funcionalidades

O projeto inclui as seguintes análises:

* **Números mais frequentes:** identifica quais números saíram mais vezes
  *Exemplo:* 10, 53, 37, 5, 34, 33

* **Números menos frequentes:** mostra os números que menos apareceram
  *Exemplo:* 26, 21, 55, 22, 15, 31, 48, 3, 12, 7

* **Distribuição pares x ímpares:** contabiliza a quantidade de números pares e ímpares sorteados
  *Exemplo:* Pares: 9003 | Ímpares: 8925

* **Espaçamento entre números consecutivos:** calcula a diferença entre números dentro de cada sorteio

* **Padrões de espaçamento repetidos:** identifica padrões que se repetem ao longo dos concursos

* **Número mais frequente por posição:** analisa qual número aparece mais em cada posição (Bola1 a Bola6)

* **Números que nunca foram sorteados:**
  ✔ Resultado: todos os números de 1 a 60 já foram sorteados pelo menos uma vez

* **Média dos números sorteados:** calcula a média por concurso e a média geral
  ✔ Resultado: média geral = **30,53**

---

## 🛠️ Tecnologias utilizadas

* Python 3
* Pandas (análise de dados)
* Excel (fonte dos dados)

---

## 📁 Estrutura do projeto

```
Analise-Mega-Sena/
│
├── data/
│   └── Mega-Sena.xlsx
│
├── notebooks/
│   └── Mega_Sena.ipynb
│
├── README.md
```

---

## 📈 Conclusão

Este projeto oferece uma visão estatística dos resultados da Mega-Sena, permitindo identificar:

* Tendências nos sorteios
* Números mais e menos frequentes
* Padrões de distribuição e espaçamento

Essas análises são úteis tanto para estudo de dados quanto para curiosidade sobre padrões em loterias.

---

## ⚠️ Observação

Este projeto tem fins **educacionais e exploratórios**.
Não é possível prever resultados futuros com base em dados passados de sorteios.

---
