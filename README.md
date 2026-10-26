# DevSpot – App com Expo + React Native

## Integrantes

- Pedro Luis de Freitas Nascimento
- Fabiana Mieko da Silva

## Descrição

Aplicativo mobile desenvolvido com **Expo** e **React Native** que reproduz duas telas de um portfólio:

- **Home**: logo, imagem de perfil, apresentação, botões "Sobre mim" (navega para a segunda tela) e "Entre em contato!" (Alert), seção de redes sociais (GitHub, LinkedIn, Instagram e Twitch, com links reais) e um Switch que exibe um Alert "Switch pressionado".
- **Sobre mim**: título, texto de biografia e rodapé com créditos.

Tecnologias: Expo, React Native, React Navigation (native stack), StyleSheet e @expo/vector-icons.

## Estrutura

```
App.js
index.js
src/
  assets/       # imagens
  components/   # Header, ProfileImage, PrimaryButton, SocialButton, Footer
  screens/      # HomeScreen, AboutScreen
  theme/        # colors.js
```

## Prints das telas

![Home](src/assets/home.png)
![Sobre mim](src/assets/about_me.png)

## Como rodar

```bash
npm install
npx expo start
```

Depois escaneie o QR code com o app **Expo Go** (Android/iOS) ou pressione `a` (emulador Android), `i` (simulador iOS) ou `w` (web).
