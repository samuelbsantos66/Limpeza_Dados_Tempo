# ☀️🌧️ Limpeza e Tratamento de Dados Climáticos (`tempo.csv`)

Este repositório contém a **solução desenvolvida por mim para o exercício "FAÇA VOCÊ MESMO 2"** da **Formação Cientista de Dados: O Curso Completo - 2025**, ministrado pelo professor **Fernando Amaral**.

---

## 🧠 Objetivo

Aplicar conceitos de **exploração**, **limpeza** e **tratamento de dados** ao arquivo `tempo.csv`, providenciado pelo curso, com foco na preparação dos dados para futuras análises e modelos preditivos.

---

## 📁 Conteúdo

- `tempo.csv`: Arquivo original com os dados brutos, fornecido pelo curso.
- `tempo_tratado.xls`: Arquivo resultante após limpeza e padronização.
- `limpeza_tempo.ipynb`: Notebook Jupyter com a implementação passo a passo da solução.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Jupyter Notebook
- Pandas
- Seaborn
- Statistics

---

## 🔍 Etapas da Solução

O notebook realiza as seguintes etapas:

1. **Exploração Inicial dos Dados**
   - Visualização geral do dataset
   - Verificação de tipos de dados
   - Análise de frequência e estatísticas

2. **Tratamento de Valores Nulos**
   - Preenchimento com moda e mediana conforme o tipo da variável

3. **Validação de Domínios**
   - Correção de valores fora do domínio esperado nas colunas:
     - `Aparencia`: `sol`, `chuva`, `nublado`
     - `Temperatura`: -130 a 130 ºF
     - `Umidade`: 0 a 100
     - `Vento`: `FALSO`, `VERDADEIRO`
     - `Jogar`: `sim`, `nao`

4. **Tratamento de Outliers**
   - Identificação e remoção/correção de valores inconsistentes

5. **Exportação do Conjunto de Dados Tratado**

---

## ✅ Resultado

O resultado final é um dataset limpo, com dados padronizados, consistente com os domínios definidos no enunciado do exercício, pronto para uso em análises ou modelos preditivos simples.

---

## 📚 Créditos

- Curso: **Formação Cientista de Dados: O Curso Completo - 2025**
- Instrutor: **Fernando Amaral**
- Exercício: **FAÇA VOCÊ MESMO 2**
- Arquivo original: `tempo.csv` (fornecido no material do curso)

---

## 📄 Licença

Este projeto segue fins educacionais, com base no material disponibilizado no curso. Todos os direitos do conteúdo original pertencem ao autor do curso.

