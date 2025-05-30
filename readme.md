# InvestFake: Geração de Dados Sintéticos de Investidores Brasileiros 🇧🇷📊

## 💡 Descrição

O **InvestFake** é um projeto de geração de dados sintéticos realistas focado em perfis de investidores brasileiros. Utilizando a biblioteca `Faker` para dados demográficos e o `SDV (Synthetic Data Vault)` para modelagem probabilística avançada, criamos uma base robusta que simula comportamentos, preferências e características de investidores — de forma segura, anonimizada e realista.

---

## 🎯 Objetivo

Este projeto tem como propósito:

- Gerar uma base sintética de investidores brasileiros com características demográficas e comportamentais;
- Permitir análises de dados e testes de modelos sem violar privacidade;
- Utilizar modelos como `CTGAN` ou `GaussianCopula` da SDV para simular padrões complexos;
- Servir como base para projetos de análise de investimentos, BI, modelagem preditiva e visualizações.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.10+
- [Faker](https://faker.readthedocs.io/en/master/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [SDV](https://docs.sdv.dev/)
- [Jupyter Notebook](https://jupyter.org/)

---

## 📁 Estrutura do Projeto
```
📦 InvestFake
├── 📄 InvestFake_synthetic_data.ipynb  # Notebook principal com geração e modelagem dos dados
├── 📄 README.md                        # Documentação do projeto
├── 📁 data/
│ ├── base_investfake.csv               # Base inicial gerada com Faker
```

---

## 🔍 Atributos Simulados

### 🎫 Dados Demográficos
- Idade
- Gênero
- Estado Civil
- Região (do Brasil)
- Renda Mensal
- Nível Educacional

### 💸 Dados de Investimento
- Perfil do Investidor
- Tempo de Experiência no Mercado
- Valor Total Investido
- Objetivo Principal
- Setores Preferenciais
- Frequência de Operações
- Conhecimento de Mercado
- Uso de Análise Técnica
- Uso de Análise Fundamentalista

---

## 🚀 Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/investfake.git
   cd investfake
