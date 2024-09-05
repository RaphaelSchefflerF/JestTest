# JestTest

Este repositório contém testes unitários para um projeto de API de usuários utilizando Jest e TypeScript. Siga as instruções abaixo para configurar e rodar o ambiente de teste.

## Pré-requisitos

Antes de começar, verifique se você tem as seguintes ferramentas instaladas:

- [Node.js](https://nodejs.org/) (versão 14.x ou superior)
- [npm](https://www.npmjs.com/) (gerenciador de pacotes do Node.js)
- [Docker](https://www.docker.com/) (opcional, para executar o ambiente em containers)

## Configuração do Ambiente

### 1. Instalar Node.js e npm

Se você ainda não tem o Node.js e o npm instalados, siga estas etapas:

#### No Linux (Ubuntu)

```bash
# Atualize o repositório de pacotes
sudo apt update

# Instale Node.js e npm
sudo apt install -y nodejs npm

# Verifique a instalação
node -v
npm -v
```

#### No Windows

1. Faça o download do instalador do Node.js em [nodejs.org](https://nodejs.org/).
2. Execute o instalador e siga as instruções para instalar o Node.js e o npm.

### 2. Instalar Dependências do Projeto

Clone o repositório e instale as dependências:

```bash
# Clone o repositório
git clone https://github.com/RaphaelSchefflerF/JestTest.git

# Navegue até o diretório do projeto
cd JestTest

# Instale as dependências
npm install
```

### 3. Configuração do Docker (Opcional)

Se você deseja usar Docker para rodar o ambiente de teste, siga estas etapas:

#### 3.1. Instalar Docker

Siga as instruções de instalação para o [Docker](https://docs.docker.com/get-docker/).

#### 3.2. Rodar o Docker Container

```bash
# Construa a imagem do Docker e inicie o container
docker-compose up -d --build
```

Se você estiver usando Docker, os testes serão executados automaticamente ao iniciar o container.

### 4. Executar os Testes Localmente

Se você preferir rodar os testes localmente, use o comando:

```bash
npm test
```

## Contribuições

Se você deseja contribuir para este projeto, siga as etapas padrão de fork, branch, commit e pull request.
