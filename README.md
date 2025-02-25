# To-Do List

## Introdução

Este projeto é uma aplicação de lista de tarefas (To-Do List), onde você pode adicionar, remover e visualizar tarefas de forma simples e eficiente. Desenvolvido com base nas aulas da TreinaWeb, foi uma experiência enriquecedora aprender e construir este projeto.

## Tecnologias Utilizadas

- Python

- Django

- HTML/CSS

- SQLite (banco de dados padrão do Django)

## Como Rodar o Projeto

## 1. Clonar o Repositório

Para obter o código-fonte do projeto na sua máquina local, utilize o comando:

```bash
git clone https://github.com/EliezerMigu3l00/To-Do-List.git
```

## 2. Criar um Ambiente Virtual

Para isolar as dependências do projeto, crie um ambiente virtual com o comando:

```bash
python -m venv .venv
```

## 3. Ativar o Ambiente Virtual

Dependendo do seu sistema operacional, ative o ambiente virtual com:

- **Windows:**
- ```bash
  .venv\Scripts\activate
  ```
- **Linux / macOS:**
- ```bash
  source .venv/bin/activate
  ```
## 4. Instalar as Dependências

Todas as dependências do projeto estão listadas no arquivo requirements.txt. Para instalá-las, execute:

```bash
pip install -r requirements.txt
```

## 5. Executar as Migrações do Banco de Dados

Antes de rodar a aplicação, é necessário configurar o banco de dados executando as migrações:

```bash
python manage.py migrate
```

## 6. Iniciar o Servidor

Agora, você pode iniciar o servidor do Django com o comando:

```bash
python manage.py runserver
```

## 7. Acessar a Aplicação

Abra o navegador e acesse a aplicação através da URL exibida no terminal (por padrão, http://127.0.0.1:8000/).

## Contribuição

Fique à vontade para contribuir com melhorias! Caso encontre bugs ou tenha sugestões, sinta-se livre para abrir uma issue ou enviar um pull request.

## Licença

Este projeto é de código aberto e está licenciado sob a MIT License.

