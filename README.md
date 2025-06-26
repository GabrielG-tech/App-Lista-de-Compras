# 🛒 App Lista de Compras
![React Native](https://img.shields.io/badge/React_Native-2025-blue?logo=react)
![Plataforma](https://img.shields.io/badge/Android-Suportado-brightgreen?logo=android)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![Licença](https://img.shields.io/badge/Licen%C3%A7a-MIT-blue)

> Aplicativo desenvolvido em **React Native CLI** com o objetivo de demonstrar habilidades em desenvolvimento mobile, incluindo integração com recursos nativos como **voz**, **câmera**, **armazenamento local**, **tema escuro/claro**, **navegação personalizada** e **geração de APK**.

## 📱 Demonstrações (GIFs ou imagens)
> ⚠️ *(Adicione aqui futuramente prints ou GIFs mostrando as principais telas do app em funcionamento, como login, lista, botão de voz, etc.)*

## ✅ Funcionalidades do Projeto
| Funcionalidade              | Recurso Utilizado                                                     | Status             |
|----------------------------|------------------------------------------------------------------------|--------------------|
| Login/Cadastro             | `Firebase Auth` ou `AsyncStorage` com validação de e-mail             | ✅ Implementado     |
| Lista de Compras (CRUD)    | `FlatList`, `TextInput`, `AsyncStorage`                               | ✅ Implementado     |
| Inserção por Voz           | `react-native-voice`                                                  | ⏳ Em desenvolvimento |
| Uso da Câmera              | `react-native-camera` ou `image-picker`                               | ⏳ Em desenvolvimento |
| Tema Claro/Escuro          | `react-native-paper` ou `styled-components`                           | ✅ Implementado     |
| Navegação + Menu Hamburguer| `react-navigation` com `Drawer Navigator`                             | ✅ Implementado     |
| Geração de APK             | `./gradlew assembleRelease` via Android CLI                           | ✅ Testado          |

## 🚀 Como rodar o projeto
1. Clone o repositório:
```bash
git clone https://github.com/GabrielG-tech/App-Lista-de-Compras.git
cd App-Lista-de-Compras
```
2. Instale as dependências:
```bash
npm install
# ou
yarn install
```
3. Execute no Android (emulador ou dispositivo físico com USB debugging):
```bash
npx react-native run-android
```

## 📦 Como gerar o APK (versão de produção)
```bash
cd android
./gradlew assembleRelease
```
📁 O APK será gerado em:
```
android/app/build/outputs/apk/release/app-release.apk
```

## 📂 Estrutura planejada do projeto
```css
ListaDeComprasApp/
├── android/
├── ios/
├── src/
│   ├── components/
│   ├── screens/
│   ├── services/
│   ├── context/
│   └── assets/
├── App.tsx
└── README.md
```

## 📚 Recursos utilizados
- [React Native CLI](https://reactnative.dev)
- [React Navigation](https://reactnavigation.org/)
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/)
- [React Native Voice](https://github.com/react-native-voice/voice)
- [React Native Paper](https://callstack.github.io/react-native-paper/)
- [Firebase Authentication](https://firebase.google.com/docs/auth)

## ✨ Autor
**Gabriel Gomes**  
👨‍💻  [GitHub](https://github.com/GabrielG-tech)

## 📄 Licença
Este projeto está sob a licença MIT — sinta-se à vontade para usar, modificar e contribuir!
