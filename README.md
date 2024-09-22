# Calculadora de IMC (Índice de Massa Corporal)
  Este projeto é um aplicativo móvel feito com React Native (Expo) que pode calcular o Índice de Massa Corporal (IMC). O cálculo é feito usando uma API JavaScript, que também classifica o Índice de Massa Corporal do usuário em uma das categorias: muito magro, saudável peso, muito pesado ou obeso.

# Funcionalidades
  * Inserção de peso e altura pelo usuário
  * Cálculo do IMC com base nos dados inseridos
  * Exibir o resultado do IMC

# Tecnologias utilizadas 
  * Frontend: React Native com Expo
  * Backend: Node.js com Express
  * Comunicação HTTP: Requisições HTTP entre o frontend e o backend para obter o cálculo do IMC

# Estrutura do projeto
  Dentro da pasta backend, você encontrará o arquivo index.js, que é o ponto de entrada para a API, e o arquivo package.json, que contém as dependências do projeto. Já dentro da pasta frontend, o arquivo App.js é o ponto de entrada da aplicação React Native, e também há um package.json para as dependências do frontend
  
# Instalação do projeto Backend (Node.js)
  **Clonar o repositório**
  git clone https://github.com/EduardoTaz/20240909API-WEB-IMC-NODEJS.git
  cd 20240909-API-IMC-NODEJS-2.0.1

  **Instalar as dependências**
  * npm install

  **Rodar a api**
  * node index.js
  
# Instalação do projeto Frontend (React Native com Expo) 
  **Clonar o repositório**
  * git clone https://github.com/EduardoTaz/20240909API-APP-IMC-EXPO.git
  * cd 20240909-API-APP-IMC-EXPO-2.0.1

  **Instalar as dependências**
  * npm install expo

  **Rodar o projeto**
  * npm run android

# Como utilizar
  Depois da instalação, precisa rodar a api no endereço ip da sua máquina e mudar tanto no index.js e no swagger.js. Depois de conseguir rodar sua api em seu endereço ip da sua máquina, precisa trocar o endereço da api na aplicação, colocando o seu ip na url. Logo após, no seu ambiente de desenvolvimento android virtual já estará rodando o cálculo de área de quadrado e retângulo.
