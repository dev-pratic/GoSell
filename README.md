# GoSell

## Passo a passo

### Requisitos

Antes de iniciar, certifique-se de ter instalado:

- Node.js (Versão recomendada: v23.8.0)
- npm (Versão: v10.9.2, incluído no Node.js)
- Expo CLI
- Git

### Instalação

#### Instalar o Node.js e npm
Baixe e instale o Node.js v23.8.0 a partir do site oficial: [Node.js](https://nodejs.org/)

Verifique a instalação executando:

```sh
node -v
npm -v
```

Caso haja problemas com `npx expo start`, reinstale o Node.js usando:

```sh
nvm install node --reinstall-packages-from=node
```

#### Instalar o Expo CLI
Com o npm instalado, execute o seguinte comando para instalar o Expo CLI globalmente:

```sh
npm install -g expo-cli
```

Para verificar se a instalação foi bem-sucedida:

```sh
expo --version
```

### Configuração do Expo SDK
O projeto GoSell utiliza a versão 50 do Expo SDK. Certifique-se de estar usando a versão correta:

```sh
expo install expo@50
```

