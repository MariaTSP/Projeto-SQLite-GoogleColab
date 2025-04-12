# 🌸 **Projeto: Sistema de Doações com SQLite** 🌸

**Um projeto acadêmico com o objetivo de:**

* Praticar o uso de banco de dados SQLite.
* Utilizar o Google Colab como ambiente de desenvolvimento.
* Promover a prática do uso do GitHub para versionamento e compartilhamento.

Este projeto simula um sistema de doações, permitindo o registro de:

* **Usuários:** Doadores e Beneficiários.
* **Categorias de Itens:** Para organizar os donativos.
* **Itens:** Os produtos ou serviços sendo doados.
* **Solicitações:** Pedidos de ajuda feitos pelos usuários.

O sistema foi implementado utilizando **SQLite** e executado no ambiente **Google Colab**.

---

### 🛠️ **Tecnologias Utilizadas:**

* 🐍 **Python**
* 💾 **SQLite**
* ☁️ **Google Colab**
* <0xF0><0x9F><0x93><0x84> **GitHub**

---

### 📚 **Bibliotecas Python Utilizadas:**

* **sqlite3:** Para interação com o banco de dados SQLite.
* **pandas:** Para análise e manipulação de dados (dataframes).
* **matplotlib:** Para criação de gráficos e visualizações.
* **seaborn:** Para visualizações estatísticas mais avançadas (baseado em Matplotlib).

---

### ✨ **O Que o Projeto Faz?** ✨

* Cria um banco de dados relacional diretamente **na memória**.
* Define a estrutura das tabelas, incluindo **chaves primárias** e **estrangeiras** para garantir a integridade dos dados.
* Insere **dados de exemplo** para facilitar os testes e a compreensão do sistema.
* Permite a **inserção** de novos dados e a **consulta** de informações utilizando comandos SQL como `SELECT`, `JOIN` e `GROUP BY`.
* Simula o fluxo de **solicitações de ajuda** por beneficiários e o registro de **itens doados** por doadores.

---

### 🎨 **Modelo Conceitual do Banco de Dados**:

![DER projeto-bd-colab](https://github.com/user-attachments/assets/cc3acf5f-a729-4821-9b92-cb510aa860e6)


---

### 🚀 **Como Abrir o Notebook?** 🚀

1.  Acesse o repositório do projeto no **GitHub**.
2.  Localize e clique no arquivo: `Projeto_BD_SQLite.ipynb`.
3.  Clique no botão **"Open in Colab"** (geralmente localizado no topo do arquivo).

**Ou, alternativamente:**

1.  Copie a URL do repositório:
    ```
    [https://github.com/MariaTSP/Projeto-SQLite-GoogleColab.git](https://github.com/MariaTSP/Projeto-SQLite-GoogleColab.git)
    ```
2.  Abra o **Google Colab** no seu navegador:
    ```
    [https://colab.research.google.com](https://colab.research.google.com)
    ```
3.  No Colab, clique em **"Arquivo"** (File) no menu superior.
4.  Selecione a opção **"Abrir notebook..."** (Open notebook...).
5.  Vá para a aba **"GitHub"**.
6.  Cole a URL do repositório no campo fornecido e clique em **"Pesquisar"** (Search).
7.  Selecione e abra o arquivo **"Projeto_BD_SQLite.ipynb"**.

---

### ⚙️ **Como Reproduzir no Seu Próprio Colab?** ⚙️

1.  Abra o notebook `Projeto_BD_SQLite.ipynb` no **Google Colab**.
2.  Certifique-se de **executar todas as células em ordem**, começando pela primeira e seguindo até a última (você pode usar `Ctrl+F9` para executar todas as células).
3.  O banco de dados SQLite será criado **na memória** através do comando:
    ```python
    sqlite3.connect(':memory:')
    ```
4.  Os **dados de exemplo** serão inseridos automaticamente ao executar as células correspondentes, deixando o banco de dados pronto para suas consultas.
5.  Utilize as **células de código dedicadas às consultas SQL** para visualizar e interagir com os dados do sistema.

---

### ✅ **Requisitos:**

* 🌐 Um navegador com acesso à internet.
* 🔑 Uma conta **Google** para utilizar o Google Colab.

---

