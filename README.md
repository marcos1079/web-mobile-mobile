# Project Mobile

## Descrição

Este projeto mobile faz parte de um sistema de gerenciamento tarefas, permitindo que usuários registrem, editem e removam atividaes do dia a dia, bem como acompanhem suas atividades. O aplicativo foi desenvolvido utilizando React Native e Expo para suportar tanto Android quanto iOS.

## Índice

- [Descrição](#descrição)
- [Recursos](#recursos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## Recursos

- Adicionar novas tarefas
- Editar informações ou descrição das tarefas
- Remover atrefas
- Visualizar lista de tarefas

## Instalação

### Pré-requisitos

- Node.js (versão 14 ou superior)
- npm (gerenciador de pacotes do Node.js)
- Expo CLI

### Passos para Instalar

1. Clone o repositório:
    ```bash
    git clone https://github.com/<USERNAME>/project-mobile.git
    cd project-mobile
    ```

2. Instale as dependências:
    ```bash
    npm install
    ```

3. Instale as dependências específicas para web:
    ```bash
    npx expo install react-native-web react-dom @expo/metro-runtime
    ```

4. Inicialize o projeto com Expo:
    ```bash
    npx expo start
    ```

## Uso

Para rodar o aplicativo no seu dispositivo ou emulador:

1. Certifique-se de que o servidor Expo está rodando:
    ```bash
    npx expo start
    ```

2. Escaneie o QR code com o aplicativo Expo Go no seu dispositivo móvel, ou escolha rodar no emulador Android/iOS conforme disponível.

## Estrutura do Projeto

```plaintext
project-mobile/
├── assets/                 # Recursos de mídia como imagens
├── components/             # Componentes reutilizáveis
├── screens/                # Telas do aplicativo
├── App.js                  # Arquivo principal do aplicativo
├── app.json                # Configuração do projeto Expo
├── package.json            # Dependências e scripts do npm
└── README.md               # Documentação do projeto
