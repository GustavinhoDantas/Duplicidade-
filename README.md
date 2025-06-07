# 🔍 Verificação de Duplicidade em Bases de Apólices

Este projeto em **Python**, desenvolvido no **Google Colab**, tem como objetivo identificar **duplicidades de renovação** entre duas bases de dados de apólices de seguro. Ele é útil para evitar que apólices renovadas sejam cadastradas mais de uma vez no sistema, garantindo integridade e consistência nas informações.

## 🧠 Objetivo

Verificar se uma apólice já foi renovada por outra, identificando entradas duplicadas ou inconsistentes entre duas bases distintas.

## 🛠 Tecnologias Utilizadas

- Python 3
- Google Colab
- Pandas

## 📂 Estrutura do Projeto
 📂 Projeto_Duplicidade_Apolices/
 
├── Verificacao_Duplicidade.ipynb

├── README.md

└── 📄 dados_exemplo_base1.csv

└── 📄 dados_exemplo_base2.csv

## 🧪 Como Funciona

1. **Leitura das bases**: Duas bases de dados (por exemplo, CSVs) são carregadas.
2. **Tratamento e normalização**: Os dados são padronizados para garantir a consistência.
3. **Lógica de verificação**: São comparados campos como `numero_apolice`, `renovada_por`, `cpf_cnpj`, `inicio_vigencia`, etc.
4. **Relatório de duplicidades**: Gera-se uma tabela indicando quais apólices foram identificadas como potenciais duplicatas.


## 📈 Melhorias Futuras

 - Implementar visualizações com gráficos.
 - Adicionar interface via formulário no Colab.
 - Gerar um log detalhado de inconsistências.
