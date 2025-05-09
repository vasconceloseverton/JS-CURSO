# 🧾 Formulário de Cadastro de Produtos com Azure e Streamlit

Este é um projeto desenvolvido como parte do curso da [DIO (Digital Innovation One)](https://www.dio.me/), com o objetivo de praticar a integração de aplicações Python com serviços da Microsoft Azure. A aplicação é um formulário simples, feito com Streamlit, que permite cadastrar e visualizar produtos. Os dados são armazenados no **Azure SQL Database** e os arquivos são manipulados usando um **container de Blob Storage**.

## 🚀 Tecnologias Utilizadas

- **Python**
- **Streamlit**
- **Azure SQL Database**
- **Azure Blob Storage**
- **pymssql** (para conexão com o banco de dados)
- **azure-storage-blob** (para interação com o Blob Storage)

## 📦 Funcionalidades

- ✅ Página de **cadastro de produtos**
- ✅ Página para **listar os produtos cadastrados**
- ✅ Armazenamento dos dados no **Azure SQL**
- ✅ Upload e manipulação de arquivos no **Azure Blob Storage**

## 📷 Demonstração

https://github.com/user-attachments/assets/7458570e-a805-4a50-a91f-c0a0663cbd31

## 🛠️ Como Executar Localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/vasconceloseverton/JS-CURSO.git
   cd nome-do-repositorio
   ```

2. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

4. Configure as variáveis de ambiente com as credenciais do Azure (ex: `BLOB_CONNECTION_STRING`, `SQL_SERVER `).

5. Execute o app:
   ```bash
   streamlit run main.py
   ```

## 🧠 Aprendizados

Este projeto me permitiu:

- Praticar a criação de interfaces com o **Streamlit**
- Compreender como conectar e interagir com **bancos de dados na nuvem**
- Utilizar o **Azure Blob Storage** para armazenar arquivos
- Ter uma visão prática da **integração entre Python e serviços em nuvem**

## 📂 Estrutura do Projeto

```
📁 projeto/
├── .env
├── requirements.txt
├── info.txt
├── main.py
└── README.md
```

## 📌 Requisitos

- Python 3.8+
- Conta no Azure com:
  - Azure SQL Database criado
  - Container de Blob Storage ativo

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se livre para abrir issues ou enviar pull requests.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito com 💙 por Everton Vasconcelos
