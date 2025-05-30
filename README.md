IOS:     <img src="https://github.com/user-attachments/assets/6a9dde0d-c9cf-4cba-9a33-e0fd8e79f974" alt="Logo" width="S00" height="400">

ANDROID: <img src="https://github.com/user-attachments/assets/da1c05c9-5600-48fa-8694-58e22846cd48" alt="Logo" width="S00" height="400">










Gerador de Senhas Seguro 

[![Build Status](https://github.com/anakferraro/16-04/actions/workflows/build.yml/badge.svg)](https://github.com/anakferraro/16-04/actions/workflows/build.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm version](https://img.shields.io/npm/v/seu-pacote.svg)](https://www.npmjs.com/package/seu-pacote)
[![Issues](https://img.shields.io/github/issues/anakferraro/16-04.svg)](https://github.com/anakferraro/16-04/issues)

Este é um aplicativo **React Native** desenvolvido com **Expo**, que permite gerar, copiar e armazenar senhas de maneira segura no próprio dispositivo, utilizando `expo-secure-store` para persistência de dados.

---

 Funcionalidades

✅ Geração de senhas seguras e aleatórias com tamanho customizável.
✅ Cópia da senha para a área de transferência.
✅ Salvamento seguro de senhas localmente, com `expo-secure-store`.
✅ Visualização de senhas salvas.
✅ Interface estilizada com `expo-linear-gradient`.

---

## 📱 Tecnologias Utilizadas

* [Expo](https://expo.dev/)
* [React Native](https://reactnative.dev/)
* [expo-secure-store](https://docs.expo.dev/versions/latest/sdk/securestore/)
* [expo-clipboard](https://docs.expo.dev/versions/latest/sdk/clipboard/)
* [expo-linear-gradient](https://docs.expo.dev/versions/latest/sdk/linear-gradient/)

---

 Como usar

1. Instale as dependências

```bash
npm install
```

2. Execute o projeto

```bash
npx expo start
```

Você poderá abrir o aplicativo em:

* Um emulador Android ou iOS.
* Dispositivo físico usando o aplicativo [Expo Go](https://expo.dev/go).
* Navegador, usando a versão web do Expo.

---

 Como funciona

1. Digite um nome descritivo para a senha (ex.: "Email", "Banco").
2. Escolha o comprimento da senha.
3. Toque em "Gerar Senha" para criar uma senha aleatória.
4. Opções disponíveis após a geração:

   * **Copiar Senha**: envia a senha para a área de transferência.
   * **Salvar Senha**: armazena a senha de forma segura no dispositivo.
5. Visualize as senhas salvas na lista abaixo.

---

 Estrutura de arquivos

* `App.js`: Tela principal e lógica de geração, cópia e salvamento de senhas.
* `package.json`: Dependências e scripts.
* `app.json`: Configurações do Expo.
* `eslint.config.js`: Configuração de linting.
* `tsconfig.json`: Configurações do TypeScript.
* `.gitignore`: Arquivos e pastas ignoradas pelo Git.

---

 Scripts disponíveis

* `npm start`: Inicia o Expo.
* `npm run android`: Executa no emulador Android.
* `npm run ios`: Executa no simulador iOS.
* `npm run web`: Executa no navegador.
* `npm run lint`: Executa o linter.
* `npm run reset-project`: Reseta o projeto para o estado inicial.

---

 Pré-requisitos

* Node.js e npm instalados.
* Expo CLI (`npm install -g expo-cli`).

---

Segurança

As senhas são armazenadas de forma **local e segura** utilizando `expo-secure-store`, garantindo que somente o aplicativo possa acessar as informações salvas.

---

