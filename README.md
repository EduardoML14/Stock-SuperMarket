# 🛒 Stock-SuperMarket

Sistema de gerenciamento de estoque para supermercados via terminal

![Python](https://img.shields.io/badge/Python-3.x-3572A5?style=flat-square&logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Concluído-success?style=flat-square)

---

## 📋 Sobre o projeto

Sistema CLI desenvolvido em Python para controle de estoque de supermercado. Permite cadastrar, consultar, atualizar e remover produtos, além de gerar alertas de estoque baixo e exportar os dados para planilha Excel.

---

## 🧰 Tecnologias utilizadas

| Tecnologia | Uso |
|---|---|
| `Python 3.x` | Linguagem principal |
| `SQLite3` | Banco de dados local |
| `Pandas` | Exportação para Excel |
| `openpyxl` | Geração do arquivo `.xlsx` |

---

## ⚙️ Funcionalidades

- ✅ Cadastro de produtos com código único
- 🔍 Consulta por nome, código ou categoria
- ✏️ Atualização de quantidade em estoque
- 🗑️ Remoção de produtos com confirmação
- ⚠️ Alerta de estoque baixo (quantidade < 10)
- 📊 Exportação do estoque para planilha `.xlsx`

---

## 🚀 Como executar

### Pré-requisitos

```bash
pip install pandas openpyxl
```

### Rodando o projeto

```bash
# Clone o repositório
git clone https://github.com/Dudxszzz/stock-supermarket

# Acesse a pasta
cd stock-supermarket

# Execute o programa
python main.py
```

---

## 🗂️ Estrutura do projeto

```
stock-supermarket/
├── main.py        # Código principal
├── estoque.db     # Banco de dados SQLite (gerado automaticamente)
└── estoque.xlsx   # Planilha exportada (gerada pela opção 6)
```

---

## 📌 Menu principal

```
============================================================
          Modelagem de estoque supermarket
============================================================

1. Cadastrar Produto
2. Gerenciar Produto
3. Consulta de produtos
4. Produtos
5. Estoque baixo
6. Criar Planilha
7. Sair
```

---

## 🗃️ Estrutura do banco de dados

Tabela: `estoque`

| Campo | Tipo | Descrição |
|---|---|---|
| `id` | INTEGER | Chave primária, auto incremento |
| `nome` | TEXT | Nome do produto |
| `codigo` | INTEGER | Código único do produto |
| `preco` | REAL | Preço unitário |
| `quantidade` | INTEGER | Quantidade em estoque |
| `categoria` | TEXT | Categoria do produto |

---

## 🧑‍💻 Autor

Feito por **Eduardo Lima**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eduardomoreiralima/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:limaedu.contato@gmail.com)
