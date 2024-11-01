# Projeto_Tkinter_SQL


## Sistema de Controle de Estoque (CRUD com Python)

Bem-vindo ao projeto **Controle de Estoque**! Este projeto está sendo desenvolvido para gerenciar o estoque de produtos de maneira simples e eficiente, utilizando o Python com integração de uma interface gráfica via **Tkinter** e banco de dados **SQL**.

### Funcionalidades

- **Busca de Insumo**: Permite consultar o banco de dados para verificar a existência de um insumo específico e exibe detalhes como nome, quantidade, lote e data de validade.
- **Adicionar Insumo**: Insere novos insumos no banco de dados ou atualiza a quantidade de um insumo existente.
- **Deletar Insumo**: Remove um insumo do banco de dados.
- **Registrar Uso de Insumo**: Reduz a quantidade de um insumo conforme uso registrado, garantindo que o estoque disponível seja suficiente para o uso solicitado.

### Tecnologias Utilizadas

- **Python** - para o desenvolvimento da aplicação
- **Tkinter** - para a interface gráfica
- **pyodbc** - para a conexao com o banco de dados
- **SQL** - para armazenamento e gestão dos dados do estoque, no caso usei SQL Server

### Instalação

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seuusuario/sistema-controle-estoque.git
   cd sistema-controle-estoque

2. **Instale as dependências**: Caso não tenha o pyodbc instalado, você pode instalá-lo usando:
   ```bash
   pip install pyodbc

3. **Configure a conexão com o banco de dados**: No código Python, ajuste as credenciais de conexão:
   ```bash
   pip install pyodbc

4. **Banco de dados**: Certifique-se de que o banco de dados EstoqueMentoria e a tabela Insumos estejam criados. A estrutura da tabela Insumos deve incluir os seguintes campos:
   ```python
   dados_conexao = ("Driver={SQL Server};"
                    "Server=SEU_SERVIDOR;"
                    "Database=EstoqueMentoria")

### Licença
Este projeto é distribuído sob a licença MIT. Consulte o arquivo LICENSE para mais informações.

### Como Contribuir

Contribuições serão bem-vindas! Para contribuir, faça um fork do projeto, crie uma nova branch, faça suas alterações e envie um pull request.

### Contatos

- **E-mail**: marcio.asriel@gmail.com
- **LinkedIn**: [Marcio Luiz](https://www.linkedin.com/in/marcioluiz-multicloud/)
- **WhatsApp**: +47 99926-1250
