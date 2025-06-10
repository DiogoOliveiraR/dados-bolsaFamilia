# 📊 Análise de Dados do Programa Bolsa Família

Este projeto tem como objetivo explorar e analisar dados do programa Bolsa Família, com foco em identificar padrões de distribuição dos recursos, desigualdades regionais e insights que possam orientar políticas públicas mais eficazes para o combate à pobreza.

---

## 📌 Objetivo

- Analisar a distribuição dos pagamentos do Bolsa Família por estado e município.
- Investigar desigualdades regionais nos valores recebidos.
- Refletir sobre a relação entre desenvolvimento social e dependência do programa.
- Propor sugestões com base nos dados analisados.

---

## 🧰 Tecnologias utilizadas

- Python 3
- Google Colab
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 📁 Fonte dos dados

Os dados utilizados são públicos e foram obtidos no [Portal da Transparência do Governo Federal](https://aplicacoes.cidadania.gov.br/vis/).

---

## 🧭 Passo a passo do projeto

### 1. Coleta e leitura dos dados
- Importação do arquivo `.csv` para o ambiente do Google Colab.
- Leitura com `pandas.read_csv()` usando o separador `;` e codificação `latin1`.

### 2. Exploração inicial
- Visualização de amostras (`df.head()`).
- Entendimento das colunas: UF, Município, CPF (oculto), NIS, Nome, Valor da parcela etc.

### 3. Limpeza e padronização
- Renomeação de colunas para facilitar o manuseio.
- Tratamento de dados nulos e tipos de dados.

### 4. Análises principais
- Total de beneficiários únicos por estado.
- Valores totais e médios pagos por UF.
- Cálculo da proporção entre valor médio e valor total.
- Visualizações com gráficos de barras para facilitar a interpretação.

### 5. Perguntas analisadas
- Quais estados apresentam maior desigualdade entre valores médios e totais?
- Existe sazonalidade nos pagamentos?
- Quais municípios têm o maior número de beneficiários?
- Como o valor das parcelas se distribui entre os beneficiários?

---

## 💡 Conclusão

A análise revelou que os estados mais pobres, com menos acesso a emprego e educação, concentram o maior número de beneficiários e recebem os maiores volumes de repasse. Já os estados mais desenvolvidos economicamente apresentam menor participação no programa.

Essa distribuição reflete o papel do Bolsa Família como uma rede de proteção social, mas também evidencia a necessidade de políticas públicas complementares que promovam:
- Geração de emprego e renda;
- Melhoria na qualidade da educação;
- Desenvolvimento regional sustentável.

---

## 📝 Licença

Este projeto é livre para uso educacional e pessoal. Dados públicos.

---

