# invagas

#Projeto:
├── settings.py Configurações do projeto: BD, Linguagem, TimeZone, etc..
├── urls.py     Onde ficam as rotas do sistema, Ex.: localhost:8080/admin
└── wsgi.py     Script de inicializacao do sistema //nao interessa muito a principio


#Criar um app:
1 - Vai tools > Run manage.py tasks
2 - Executa startapp <nome_do_app>

#Depois de criado o app:

├── __init__.py  Indica que é um pacote python
├── admin.py     Altera as configurações do site administrativo
├── migrations   Esquema do banco de dados
│   └── __init__.py
├── models.py    Os modelos do banco de dados. Cada classe represeta uma tabela
├── tests.py     Testes do Django
└── views.py     Onde ficam as regras de negocios

#Controle de versao:
1 - Verificar as mudancas: No painel de consoles > Version Control > Show Diff (cmd + D / ctrl + D)
2 - Clica com o direito em cima do arquivo modificado e escolhe a opcao commit changes