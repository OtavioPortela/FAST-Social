# Projeto Maratona FastAPI & React: Rede Social

Este é o projeto desenvolvido durante a maratona de estudos para a criação de uma rede social completa, utilizando **FastAPI** (backend), **React** (frontend), **Docker**, **Alembic** e implantação na **AWS**.

O objetivo é construir uma aplicação funcional que permita o cadastro de usuários, login, upload de fotos e visualização de perfis, com foco em uma arquitetura robusta e boas práticas de desenvolvimento.

---

## 🚀 Progresso da Maratona

Acompanhe o andamento do projeto marcando as etapas concluídas.

### Backend (FastAPI, Alembic, Docker)

#### **Sessão 1: Fundamentos e Estrutura**

- [ ] Instalação do Python e Poetry.
- [ ] Criação do projeto e inicialização do Poetry (`poetry init`).
- [ ] Adição das dependências necessárias (FastAPI, Uvicorn, SQLAlchemy, etc.).
- [ ] Criação da estrutura de pastas do backend.
- [ ] Criação do arquivo `.gitignore`.

#### **Sessão 2: Primeiros Passos com FastAPI e Autenticação**

- [ ] Estruturação das rotas de API para registro e login.
- [ ] Implementação de um modelo Pydantic para os dados de entrada (`schemas`).
- [ ] Criação da função para gerar e verificar senhas.

#### **Sessão 3: Banco de Dados e SQLAlchemy**

- [ ] Configuração da conexão com o banco de dados PostgreSQL.
- [ ] Definição dos modelos de dados (`User` e `Photo`) com SQLAlchemy.
- [ ] Estabelecimento do relacionamento entre `User` e `Photo`.

#### **Sessão 4: Gerenciamento de Migrações com Alembic**

- [ ] Instalação e configuração do Alembic.
- [ ] Geração da primeira migração para criar as tabelas `users` e `photos`.
- [ ] Execução da migração para aplicar as alterações no banco de dados.

#### **Sessão 5: Dockerizando o Backend e o Banco de Dados**

- [ ] Criação do `Dockerfile` para a aplicação FastAPI.
- [ ] Criação do `docker-compose.yml` para orquestrar o backend e o banco de dados.
- [ ] Ajuste da conexão do backend para usar o serviço de banco de dados do Docker Compose.

#### **Sessão 6: Upload de Arquivos e Armazenamento**

- [ ] Implementação do endpoint de upload de fotos no FastAPI.
- [ ] Lógica para salvar os arquivos em uma pasta local.
- [ ] Configuração de rotas estáticas para servir as imagens.

---

### Implantação (AWS)

#### **Sessão 7: Publicando na AWS - Parte 1 (Ambiente)**

- [ ] Criação da conta na AWS.
- [ ] Criação de uma VPC e um Security Group.
- [ ] Configuração das regras de entrada e saída no Security Group.

#### **Sessão 8: Publicando na AWS - Parte 2 (Instância EC2)**

- [ ] Provisionamento de uma instância EC2.
- [ ] Conexão via SSH com a instância.
- [ ] Instalação do Docker e Docker Compose na instância.

#### **Sessão 9: Publicando na AWS - Parte 3 (Implantação)**

- [ ] Geração da imagem Docker e push para o Docker Hub.
- [ ] Pull da imagem na instância EC2.
- [ ] Execução do contêiner da aplicação em produção.

---

### Frontend (React)

#### **Sessão 10: Estrutura do Frontend com React**

- [ ] Criação do projeto React (`create-react-app` ou `Vite`).
- [ ] Instalação de bibliotecas de roteamento e estilização (React Router, etc.).
- [ ] Criação dos componentes iniciais (Login, Registro, Home, Perfil).

#### **Sessão 11: Integração e Funcionalidades**

- [ ] Implementação da lógica de autenticação no frontend (registro e login).
- [ ] Conexão do React com a API do FastAPI para consumir os dados.
- [ ] Exibição das fotos e informações dos perfis.
- [ ] Implementação do formulário de upload de fotos.

---

## 🧑‍💻 Como Rodar o Projeto

*Instruções futuras sobre como clonar, instalar dependências e rodar a aplicação localmente.*