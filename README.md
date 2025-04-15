# Ponzibank - The Green Pyramid Bank 🟢

**ENGLISH | [PORTUGUÊS](#ponzi-bank---o-banco-da-pirâmide-verde-)**

## About the Project
Ponzibank is a satirical clone of Nubank, designed to humorously mimic a Ponzi scheme. Built with **Flutter**, **Laravel**, and **MySQL**, it offers a fun and interactive way to showcase modern app development skills.

## Features
- **User Authentication:** Secure login and registration.
- **Dashboard:** View your "magically growing" balance.
- **Transactions:** Simulate transfers between users.
- **Transaction History:** Track your "investments" in the pyramid.
- **Ponzi Levels:** Climb the pyramid with each "investment."
- **Green Theme:** A fresh, satirical take on the Nubank design.

## Technologies
- **Frontend:** Flutter
- **Backend:** Laravel
- **Database:** MySQL
- **DevOps:** Docker for deployment

## Installation

### Prerequisites
- Flutter installed ([Flutter installation guide](https://docs.flutter.dev/get-started/install))
- PHP and Composer installed ([Composer installation guide](https://getcomposer.org/))
- MySQL installed
- Docker (optional, for deployment)

### Steps
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/jesseld/ponzi-bank.git
   cd ponzi-bank
   ```

2. **Backend Setup (Laravel):**
   - Navigate to the `ponzi-backend` folder:
     ```bash
     cd ponzi-backend
     ```
   - Install dependencies:
     ```bash
     composer install
     ```
   - Configure the `.env` file:
     ```bash
     cp .env.example .env
     ```
     Update the database credentials in the `.env` file.
   - Run migrations:
     ```bash
     php artisan migrate
     ```
   - Start the Laravel server:
     ```bash
     php artisan serve
     ```

3. **Frontend Setup (Flutter):**
   - Navigate to the `ponzi-app` folder:
     ```bash
     cd ../ponzi-app
     ```
   - Install dependencies:
     ```bash
     flutter pub get
     ```
   - Run the app:
     ```bash
     flutter run
     ```

4. **Optional: Docker Deployment**
   - Use the provided `docker-compose.yml` file to deploy the app:
     ```bash
     docker-compose up --build
     ```

## Screenshots
*(Add screenshots of the app here)*

## License
This project is for educational and entertainment purposes only. It is not intended for real financial use.

---

# Ponzibank - O Banco da Pirâmide Verde 🟢

## Sobre o Projeto
Ponzibank é um clone satírico do Nubank, projetado para imitar humoristicamente um esquema Ponzi. Construído com **Flutter**, **Laravel** e **MySQL**, ele oferece uma maneira divertida e interativa de demonstrar habilidades modernas de desenvolvimento de aplicativos.

## Funcionalidades
- **Autenticação de Usuário:** Login e registro seguros.
- **Dashboard:** Veja seu saldo "crescendo magicamente."
- **Transações:** Simule transferências entre usuários.
- **Histórico de Transações:** Acompanhe seus "investimentos" na pirâmide.
- **Níveis Ponzi:** Suba na pirâmide a cada "investimento."
- **Tema Verde:** Uma abordagem satírica ao design do Nubank.

## Tecnologias
- **Frontend:** Flutter
- **Backend:** Laravel
- **Banco de Dados:** MySQL
- **DevOps:** Docker para deploy

## Instalação

### Pré-requisitos
- Flutter instalado ([Guia de instalação do Flutter](https://docs.flutter.dev/get-started/install))
- PHP e Composer instalados ([Guia de instalação do Composer](https://getcomposer.org/))
- MySQL instalado
- Docker (opcional, para deploy)

### Passos
1. **Clone o Repositório:**
   ```bash
   git clone https://github.com/jesseld/ponzi-bank.git
   cd ponzi-bank
   ```

2. **Configuração do Backend (Laravel):**
   - Navegue até a pasta `ponzi-backend`:
     ```bash
     cd ponzi-backend
     ```
   - Instale as dependências:
     ```bash
     composer install
     ```
   - Configure o arquivo `.env`:
     ```bash
     cp .env.example .env
     ```
     Atualize as credenciais do banco de dados no arquivo `.env`.
   - Execute as migrações:
     ```bash
     php artisan migrate
     ```
   - Inicie o servidor Laravel:
     ```bash
     php artisan serve
     ```

3. **Configuração do Frontend (Flutter):**
   - Navegue até a pasta `ponzi-app`:
     ```bash
     cd ../ponzi-app
     ```
   - Instale as dependências:
     ```bash
     flutter pub get
     ```
   - Execute o app:
     ```bash
     flutter run
     ```

4. **Opcional: Deploy com Docker**
   - Use o arquivo `docker-compose.yml` para fazer o deploy do app:
     ```bash
     docker-compose up --build
     ```

## Capturas de Tela
*(Adicione capturas de tela do app aqui)*

## Licença
Este projeto é apenas para fins educacionais e de entretenimento. Não é destinado para uso financeiro real.
