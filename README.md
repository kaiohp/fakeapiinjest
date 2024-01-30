# FakerAPI Injest
This project is designed to generate a fictitious database and populate a relational database hosted on Google Cloud. The data will be generated using the Faker and Random libraries, and the ORM will utilize SQLAlchemy. The API will follow REST standards and be implemented using Flask, containerized with Docker.

## Instalação e Configuração

1. Clone the repository:
```bash
git clone https://github.com/kaiohp/fakeapiinjest.git
cd fakeapiinjest
```
2. Set up the correct Python version using pyenv:
```bash
pyenv install 3.12.1
```
3. Install project dependencies:
```bash
# The project's dependency manager is Poetry
poetry env use 3.12.1
# Activate the virtual environment
poetry shell
# Install dependencies
poetry install
```