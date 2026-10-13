# IronFlow

Aplicativo mobile para registrar exercícios, acompanhar cargas utilizadas nos treinos e visualizar a evolução do usuário ao longo do tempo.

## Tecnologias utilizadas

- React Native
- Expo
- TypeScript
- Node.js
- npm
- Git e GitHub
- Visual Studio Code

## Requisitos para execução

- Node.js LTS (recomendado >= 20)
- npm
- Expo Go (para testar em dispositivo) ou emulador Android/iOS

## Instalação

```bash
npm install
```

## Execução

```bash
npx expo start
```

## Estrutura resumida

```text
ironflow/
├── assets/
├── src/
│   ├── components/
│   ├── screens/
│   ├── navigation/
│   ├── services/
│   ├── hooks/
│   ├── contexts/
│   ├── utils/
│   ├── types/
│   └── constants/
├── .env.example
├── .gitignore
├── app.json
├── App.tsx
├── package.json
├── package-lock.json
├── README.md
└── tsconfig.json
```

## Padrão de branches

- `main`: versão estável do projeto
- `develop`: integração contínua de desenvolvimento
- `feature/nome-da-funcionalidade`
- `fix/nome-da-correcao`
- `chore/nome-da-tarefa`

## Padrão de commits

Este projeto utiliza **Conventional Commits**.

Exemplos:

- `feat: adiciona tela de registro de carga`
- `fix: corrige validação do formulário de login`
- `docs: atualiza instruções de instalação`
- `chore: configura eslint e prettier`

## Variáveis de ambiente

- Use `.env.example` como referência de variáveis obrigatórias.
- O arquivo `.env` real é local e **não deve** ser versionado.
- Não inclua no repositório: senhas, tokens, chaves privadas, credenciais e certificados.
- Variáveis `EXPO_PUBLIC_` podem ser embutidas no app compilado, então não armazene segredos nelas.
