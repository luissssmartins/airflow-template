# Projeto Airflow

Este repositório contém a configuração e os DAGs (Directed Acyclic Graphs) para o Apache Airflow. O Airflow é uma plataforma para programar, monitorar e gerenciar workflows. Popurlamente conhecido como "orquestrador de tarefas".

## Estrutura de pastas

A estrutura de pastas deste projeto segue as melhores práticas recomendadas para projetos Airflow.

```plaintext
.
├── dags
│   └── dag_<name>
│     └── function_name.py
├── data
│   └── dag_<name>
│     └── dataset.<extension>
├── functions
│   └── dag_<name>
│    └── function_name.py
│
├── requirements.txt
└── README.md

```

### Preparando o ambiente

Após clonar este repositório, certifique-se que seu projeto possua um ambiente virtual criado.

Caso não possua basta, realizar a criação do ambiente virtual utilizando o comando abaixo:

```bash
$ python -m venv venv
```

Após a criação do ambiente, basta estar realizando a instalação das dependências padrões:

```bash
$ source venv/bin/activate
$ pip install -r requirements.txt
```

##### Definindo as dependências do projeto

Com seu terminal aberto, execute o seguinte comando na pasta raíz do projeto:

```bash

$ pip freeze > requirements.txt

```

Certifique-se que está utilizando um ambiente de variavéis virtuais (virtual environments)

