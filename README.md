# Marcação de Consultas Médicas

Este projeto é uma aplicação mobile desenvolvida em **React Native** com **Expo**, que tem como objetivo facilitar o agendamento de consultas médicas de forma prática, rápida e intuitiva.

## 📄 Owner

 - Eduardo Akira Murata - RM98713

## 📱 Funcionalidades

- **Tela inicial** com listagem de especialidades médicas disponíveis.
- **Tela de agendamento**, onde o usuário pode selecionar:
  - Especialidade médica
  - Médico desejado
  - Data e horário disponíveis
- **Tela de confirmação** da consulta marcada.
- Navegação entre telas utilizando **React Navigation**.
- Interface moderna e responsiva com uso de componentes customizados.
- Utilização de imagens ilustrativas para melhorar a experiência do usuário.

## 🛠️ Refatorações Realizadas

- Refatoração da estrutura de pastas para separar melhor os componentes, assets e telas.
- Conversão dos arquivos para **TypeScript** visando maior segurança de tipos.
- Padronização de nomenclaturas e organização de código para melhorar a legibilidade.
- Otimização do carregamento de imagens e recursos estáticos.
- Melhoria da navegação entre telas e fluxo de marcação da consulta.

## 🚀 Tecnologias Utilizadas

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [React Navigation](https://reactnavigation.org/)

## 📦 Estrutura do Projeto

```
📁 marcacaoDeConsultasMedicas
├── 📁 assets           # Imagens e recursos estáticos
├── 📁 src
│   ├── 📁 screens       # Telas da aplicação
│   ├── 📁 components    # Componentes reutilizáveis
│   └── 📁 navigation    # Configuração das rotas
├── App.tsx             # Arquivo principal do app
├── package.json        # Dependências e scripts
├── tsconfig.json       # Configurações do TypeScript
```

## ▶️ Como Executar o Projeto

Certifique-se de ter o [Node.js](https://nodejs.org/) e o [Expo CLI](https://docs.expo.dev/get-started/installation/) instalados:

```bash
# Clone o repositório
git clone https://github.com/akiramrt/marcacaoDeConsultasMedicas.git

# Acesse o diretório
cd marcacaoDeConsultasMedicas

# Instale as dependências
npm install

# Inicie o projeto
npx expo start
```
