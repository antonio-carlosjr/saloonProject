Aqui está um **README.md** adequado para o seu projeto de **Sistema de Gestão para Salão de Beleza**, baseado nos arquivos analisados e na estrutura do código. Ele fornece informações essenciais para o repositório do GitHub. 

---

### **Sistema de Gestão para Salão de Beleza**

**Versão:** 1.0  
**Autor:** [Antônio Carlos](https://github.com/antonio-carlosjr)   
**Licença:** GPL  

---

## **Descrição**

O **SaloonProject** é um sistema desktop desenvolvido em **Java** para gerenciamento de salões de beleza e adaptável para barbearias. Ele automatiza processos administrativos, como controle de clientes, prestadores de serviço, cálculo de comissões e geração de relatórios.  

A interface gráfica foi construída utilizando **Swing**, com um banco de dados **MySQL** para armazenamento das informações.  

---

## 🚀 **Funcionalidades**

✅ **Gerenciamento de Usuários:** Cadastro, edição e remoção de funcionários e clientes.  
✅ **Cadastro de Serviços:** Registra serviços disponíveis, com valores e percentuais de comissão.  
✅ **Registro de Serviços Realizados:** Associa um serviço a um cliente e prestador, com cálculo automático de comissão.  
✅ **Relatórios Financeiros:** Geração de relatórios detalhados por período e prestador, exportáveis em **PDF** ou **Excel**.  
✅ **Controle de Acesso:** Diferencia permissões entre administradores e usuários comuns.  

---

## 🛠 **Tecnologias Utilizadas**

- **Linguagem:** Java 21 (Swing para UI)  
- **Banco de Dados:** MySQL  
- **Gerenciamento de Dependências:** Maven  
- **Relatórios:** JasperReports/iReport  
- **Bibliotecas Auxiliares:**  
  - `mysql-connector-j` → Conexão com MySQL  
  - `commons-dbutils` → Manipulação de banco de dados  
  - `rs2xml` → Exibição de tabelas no frontend  

---

## 📦 **Instalação**

1️⃣ **Clone o repositório:**  
```bash
git clone https://github.com/antonio-carlosjr/saloonProject
```

2️⃣ **Configure o banco de dados:**  
- Crie um banco de dados chamado `dbsalaom`.  
- Configure as credenciais no arquivo `ModuloConexao.java`.  

3️⃣ **Compile e execute o projeto:**  
```bash
mvn clean install
java -jar target/SaloonProject-1.0-SNAPSHOT.jar
```

---

## 🎮 **Capturas de Tela**
📷 *Adicione imagens do sistema aqui*  

---

## 📌 **Estrutura do Projeto**
```
📂 src/main/java/br/com/saloonproject
 ┣ 📂 dal                # Módulo de conexão com MySQL
 ┣ 📂 telas              # Interface gráfica e telas do sistema
 ┃ ┣ 📜 TelaLogin.java       # Tela de login
 ┃ ┣ 📜 TelaPrincipal.java   # Tela principal do sistema
 ┃ ┣ 📜 TelaCliente.java     # Gerenciamento de clientes
 ┃ ┣ 📜 TelaUsuario.java     # Controle de usuários
 ┃ ┣ 📜 TelaNovoServico.java # Cadastro de serviços
 ┃ ┣ 📜 TelaServicoRealizado.java  # Registro de serviços realizados
 ┃ ┣ 📜 TelaRelatorio.java   # Relatórios e exportação
 ┃ ┣ 📜 TelaSobre.java       # Informações sobre o sistema
``` 

---

## 📄 **Licença**
Este projeto é licenciado sob a **GPL (General Public License)**, permitindo que qualquer pessoa use e modifique o código livremente.  

---

## 📬 **Contato**
Caso tenha dúvidas ou sugestões, entre em contato:  
📧 **Email:** profissional.contatocarlos@gmail.com
📌 **GitHub:** [Antônio Carlos](https://github.com/antonio-carlosjr)  

