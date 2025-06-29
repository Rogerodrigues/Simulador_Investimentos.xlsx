# 📊 Simulador de Investimentos em Excel

Este projeto é uma ferramenta simples e funcional criada em Excel com o objetivo de ajudar usuários a simular seus investimentos mensais ao longo do tempo, considerando rendimento composto e dividendos mensais.

---

## 🎯 Objetivo

Ajudar o investidor a responder perguntas importantes:

- 💰 Quanto investir por mês?
- ⏳ Por quantos anos investir?
- 📈 Qual será a taxa de rendimento mensal?
- 📊 Qual será o patrimônio acumulado?
- 💸 Qual a projeção dos dividendos mensais?

---

## 🧮 Fórmulas Utilizadas

- **Patrimônio acumulado**:
  
  \[
  FV = PMT \times \frac{(1 + i)^n - 1}{i}
  \]
  Onde:
  - `FV` = valor futuro
  - `PMT` = valor investido por mês
  - `i` = taxa de rendimento mensal
  - `n` = número de meses (anos × 12)

- **Dividendos mensais**:

  \[
  Dividendos = Patrimônio \times TaxaDeDividendos
  \]

---

## 📁 Estrutura da Planilha

| Área             | Descrição                                      |
|------------------|-----------------------------------------------|
| Entradas         | Valor mensal, taxa, tempo e taxa de dividendos |
| Cálculos         | Total de meses, patrimônio, dividendos         |
| Fórmulas         | Implementadas diretamente nas células          |

---

## 📌 Como Usar

1. Faça o download da planilha:
   - [📥 Simulador_Investimentos.xlsx](./Simulador_Investimentos.xlsx)
2. Abra com Excel ou Google Sheets.
3. Preencha as células de entrada com seus próprios valores.
4. Os resultados são atualizados automaticamente.

---

## 📈 Possibilidades Futuras

- Simulação mês a mês do crescimento do patrimônio
- Gráfico de evolução dos investimentos
- Controle de diferentes ativos (ações, renda fixa, fundos)
- Versão online com Streamlit ou Google Colab

---

## 🧠 Autor

Desenvolvido por **Roger Rodrigues** como parte do seu processo de aprendizado em ciência de dados e finanças pessoais.  
Sinta-se à vontade para usar, modificar e compartilhar! 🚀

---

## 📜 Licença

Este projeto está licenciado sob a licença MIT.
