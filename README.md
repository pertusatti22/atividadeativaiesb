# AtividadeAtivaIESB

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

## Descrição
O **AtividadeAtivaIESB** é um sistema de enquetes desenvolvido como trabalho acadêmico, baseado no tutorial do Django. Ele permite aos usuários:
- Criar e gerenciar **enquetes**
- Registrar **perguntas e opções de resposta**
- Votar em enquetes existentes
- Exibir resultados das votações em tempo real

## Tecnologias Utilizadas
- **Linguagem**: Python 3.10+
- **Framework**: Django 4+
- **Banco de Dados**: SQLite (padrão) ou PostgreSQL
- **Autenticação**: Django Auth
- **Front-end**: HTML + Bootstrap (templates Django)

## Como Rodar o Projeto
```bash
git clone https://github.com/seu-usuario/atividadeativaiesb.git
cd atividadeativaiesb
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

Acesse em `http://127.0.0.1:8000/polls/`.

