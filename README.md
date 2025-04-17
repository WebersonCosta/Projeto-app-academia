# Gym App - Documentação Base

## 🏷️ Nome do Projeto

*(Escolha do nome ainda em aberto. Sugestões: GymTrack, FitControl, TreinoPlus...)*

---

## 🎯 Objetivo do App

Desenvolver um aplicativo mobile multiplataforma (Android e iOS) com foco em auxiliar o usuário na organização e execução de treinos de academia, permitindo o cadastro de usuários, montagem dinâmica de fichas de treino e recursos para acompanhamento dos exercícios.

---

## 👤 Funcionalidades

### 🔐 Autenticação
- Tela de login
- Tela de cadastro
- Validação de dados
- Integração com Firebase Authentication

### 🏋️ Gestão de Fichas de Treino
- Criar, editar e excluir treinos personalizados
- Cada treino contém:
  - Nome do exercício
  - Número de séries
  - Tipo de série (drop set, progressão, etc.)
  - Peso por série
  - Repetições por série
  - Observações
- Organização dos treinos por dia da semana (ex: Peito/Segunda, Costas/Terça)

### ⏱️ Execução de Treino
- Visualização dos treinos do dia
- Marcar exercícios como concluídos
- Cronômetro/temporizador de descanso entre séries
- Botão para "Finalizar treino"

### 📦 Armazenamento de Dados
- Firebase Firestore (dados dos treinos)
- Firebase Authentication (usuários)
- Futuro: Firebase Storage (para imagens, caso necessário)

### 🎨 Interface e UX
- Visual minimalista
- Suporte a tema claro e escuro

---

## 🧭 Navegação

Utilização do `react-navigation` com navegação stack e tab:

### Telas principais:
- Login
- Cadastro
- Home (Tabs: Treinos | Histórico | Perfil)
- Criar/Editar Treino
- Execução de Treino

---

## 🔧 Tecnologias Utilizadas

- [x] React Native (Expo)
- [x] TypeScript
- [x] Firebase (Auth + Firestore)
- [ ] React Navigation
- [ ] AsyncStorage (opcional para cache local)
- [ ] Zustand ou Context API para gerenciamento de estado global

---

## 📌 Próximos Passos
- [ ] Definir o nome oficial do app
- [ ] Criar as telas de login e cadastro
- [ ] Configurar Firebase Auth
- [ ] Estruturar navegação
- [ ] Criar modelos de dados dos treinos
- [ ] Implementar funcionalidade de criação de treino


