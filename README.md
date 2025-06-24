# 📄 Automação de Contratos

Este projeto automatiza a geração de contratos em formato Word e PDF a partir de uma planilha Excel com dados de fornecedores.

## 🚀 Como funciona

1. O script lê os dados dos fornecedores do arquivo `fornecedores.xlsx`.
2. Para cada fornecedor, gera um contrato personalizado em formato `.docx` (Word).
3. Converte o contrato gerado para o formato `.pdf`.

## 🛠️ Tecnologias utilizadas

- [Python](https://www.python.org/)
- [openpyxl](https://openpyxl.readthedocs.io/) para leitura do Excel
- [python-docx](https://python-docx.readthedocs.io/) para manipulação de arquivos Word
- [fpdf](https://pyfpdf.github.io/fpdf2/) para geração de PDFs

## 📦 Como usar

1. Instale as dependências:
   ```
   pip install openpyxl python-docx fpdf
   ```
2. Certifique-se de ter o arquivo `fornecedores.xlsx` na mesma pasta do script.
3. Execute o script:
   ```
   python appp.py
   ```
4. Os contratos serão gerados nas versões `.docx` e `.pdf` para cada fornecedor.

## 📁 Estrutura esperada da planilha

A planilha `fornecedores.xlsx` deve conter as seguintes colunas (na ordem):

- Nome da Empresa
- Endereço
- Cidade
- Estado
- CEP
- Telefone
- E-mail
- Setor

## ✨ Observações

- Os arquivos gerados terão o nome `contratos_NOMEEMPRESA.docx` e `contratos_NOMEEMPRESA.pdf`.
- Certifique-se de que os nomes das empresas não contenham caracteres inválidos para nomes de arquivos.

---

Feito com 💻 por Lucas Christo <3.
