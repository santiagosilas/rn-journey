# Preparar o ambiente

Verifique Node.js e npm:

```bash
node -v
npm -v
```

Crie um projeto Expo com TypeScript:

```bash
npx create-expo-app@latest MeuApp --template blank-typescript

cd MeuApp
```

Inicie:

```bash
npx expo start
```

Baixar o apk em https://expo.dev/go

---

# Executar no Expo Go

1. Instale o **Expo Go** no celular (Instalar o Expo Go direto de expo.dev/go?)
2. Execute:

```bash
npx expo start
```

3. Escaneie o QR Code.
4. Mantenha celular e computador acessíveis na mesma rede quando necessário.

Para Android:

```bash
npx expo start --android
```

Para Web:

```bash
npx expo start --web
```

Se o suporte web não estiver instalado:

```bash
npx expo install react-dom react-native-web @expo/metro-runtime
```

---

Se precisar limpar o cache:

```bash
npx expo start --clear
```
