Portfólio Flask
Este projeto é uma aplicação web simples feita com Flask que exibe uma página de portfólio. O portfólio apresenta informações pessoais, formação acadêmica, habilidades e projetos.

Estrutura do Projeto
cpp
Copiar
Editar
flask-portfolio
├── app
│   ├── static
│   │   └── style.css
│   ├── templates
│   │   └── index.html
│   └── app.py
├── requirements.txt
└── README.md
Instruções de Configuração
Clone o repositório:

bash
Copiar
Editar
git clone <url-do-repositório>
cd flask-portfolio
Crie um ambiente virtual:

nginx
Copiar
Editar
python -m venv venv
Ative o ambiente virtual:

No Windows:

Copiar
Editar
venv\Scripts\activate
No macOS/Linux:

bash
Copiar
Editar
source venv/bin/activate
Instale os pacotes necessários:

nginx
Copiar
Editar
pip install -r requirements.txt
Executando a Aplicação
Para executar a aplicação Flask, rode o seguinte comando no terminal:

bash
Copiar
Editar
python app/app.py
A aplicação estará acessível em http://127.0.0.1:5000/.

Uso
Com a aplicação em execução, acesse a página inicial para visualizar o portfólio. A página inclui seções com informações pessoais, formação, habilidades e projetos.
