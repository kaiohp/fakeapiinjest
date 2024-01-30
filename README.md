# FakerAPI Injest
This project is designed to generate a fictitious database and populate a relational database hosted on Google Cloud. The data will be generated using the Faker and Random libraries, and the ORM will utilize SQLAlchemy. The API will follow REST standards and be implemented using Flask, containerized with Docker.

## Instalação e Configuração

1. Clone o repositório:
```bash
git clone https://github.com/kaiohp/fakeapiinjest.git
cd fakeapiinjest
```
2. Configure a versão correta do Python com o pyenv:
```bash
pyenv install 3.12.1
```
3. Instale as dependências do projeto:
```bash
# O gerenciador de dependências do projeto é o Poetry
poetry env use 3.12.1
# Ative o ambiente virtual
poetry shell
# Instale as dependências
poetry install
```