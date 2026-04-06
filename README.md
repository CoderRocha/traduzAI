## TraduzAI

O TraduzAI é uma sistema web de tradução de textos, onde o usuário seleciona os idiomas de origem e destino, digita um texto e visualiza a tradução do mesmo em tempo real.

## Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Stack](#stack)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Instalação](#instalação)
- [Executando o Projeto](#executando-o-projeto)
- [Configurações](#configurações)
- [Autor](#autor)

## Sobre o Projeto

O **TraduzAI** é um sistema de tradução de textos com UI simples e responsiva. O usuário seleciona o idioma de origem e o idioma de destino a partir de uma lista com mais de 80 línguas, e então, digita o texto e clica em traduzir. A solicitação é processada por uma API externa e a resposta é exibida em tempo real.

## Funcionalidades

- **Tradução de textos**
  - Seleção de idioma de origem e idioma de destino.
  - Lista com mais de 80 idiomas suportados.
  - Troca rápida entre os idiomas selecionados.

- **User Interface**
  - Layout responsivo (feito com Tailwind CSS).

## Stack

- **Frontend**

  - **React**
  - **Vite**
  - **Tailwind CSS**

## Estrutura do Projeto

- **`src/`**
  - **`App.jsx`**
  - **`main.jsx`**
  - **`index.css`**
  - **`languagesData.js`**
  - **`Components/TranslatorStart.jsx`**
  - **`Components/TranslatorApp.jsx`**

## Instalação

Pré-requisitos:

- **Node.js**

1. **Instalar as dependências**

   ```bash
   npm install
   ```

2. **Criar o arquivo `.env` a partir do exemplo**

   ```bash
   cp .env.example .env
   ```

3. **Configurar a variável de ambiente no `.env`**

   - `VITE_MEMORY_API_URL`

## Executando o Projeto

```bash
npm run dev
```

Após rodar o comando, acesse a aplicação em `http://localhost:5173`.

## Configurações

As variáveis de ambiente estão em `.env.example`:

## Autor

**Guilherme Rocha (CoderRocha)**

- GitHub: [CoderRocha](https://github.com/coderrocha)
- LinkedIn: [Guilherme Rocha](https://www.linkedin.com/in/guilherme-rocha-da-silva)

---
