<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/zF4ke/nlw-ai/master/assets/nlw-logo.webp" width="100" />
<br>Next Level Week AI
</h1>
<h3>◦ Projeto da NLW AI da Rocketseat, editado por mim.</h3>

<p align="center">
<img src="https://img.shields.io/badge/SVG-FFB13B.svg?style&logo=SVG&logoColor=black" alt="SVG" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style&logo=JavaScript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style&logo=HTML5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/PostCSS-DD3A0A.svg?style&logo=PostCSS&logoColor=white" alt="PostCSS" />
<img src="https://img.shields.io/badge/Autoprefixer-DD3735.svg?style&logo=Autoprefixer&logoColor=white" alt="Autoprefixer" />
<img src="https://img.shields.io/badge/Vite-646CFF.svg?style&logo=Vite&logoColor=white" alt="Vite" />
<img src="https://img.shields.io/badge/React-61DAFB.svg?style&logo=React&logoColor=black" alt="React" />

<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style&logo=Axios&logoColor=white" alt="Axios" />
<img src="https://img.shields.io/badge/ESLint-4B32C3.svg?style&logo=ESLint&logoColor=white" alt="ESLint" />
<img src="https://img.shields.io/badge/OpenAI-412991.svg?style&logo=OpenAI&logoColor=white" alt="OpenAI" />
<img src="https://img.shields.io/badge/TypeScript-3178C6.svg?style&logo=TypeScript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Prisma-2D3748.svg?style&logo=Prisma&logoColor=white" alt="Prisma" />
<img src="https://img.shields.io/badge/Fastify-000000.svg?style&logo=Fastify&logoColor=white" alt="Fastify" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style&logo=JSON&logoColor=white" alt="JSON" />
</p>
<img src="https://img.shields.io/github/languages/top/zF4ke/nlw-ai?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/zF4ke/nlw-ai?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/zF4ke/nlw-ai?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/license/zF4ke/nlw-ai?style&color=5D6D7E" alt="GitHub license" />

</div>


---

## 📒 Índice
- [📍 Visão Geral](#-visão-geral)
- [⚙️ Funcionalidades](#%EF%B8%8F-funcionalidades)
- [📂 Estrutura do Projeto](#-estrutura-do-projeto)
- [🧩 Módulos](#-módulos)
- [🚀 Começando](#-começando)
- [🤝 Contribuir](#-contribuir)
- [📄 Licença](#-licença)
- [👏 Agradecimentos](#-agradecimentos)

---


## 📍 Visão Geral

O projeto permite aos utilizadores carregar vídeos, transcreve-los para texto e gerar conclusões com as IAs da OpenAI, baseados em prompts pre-definidos. A proposta de valor do projeto consiste em tirar partido da IA para gerar conclusões eficientes e de alta qualidade para vários fins, como a criação de títulos e descrições apelativos para vídeos do YouTube. Em geral, oferece uma interface de fácil utilização para os utilizadores interagirem com sistemas de conclusão alimentados por IA.

Ele foi criado durante a NLW AI da Rocketseat porém possuí algumas diferenças minimas de visual e comportamento adicionadas por mim.

Destaque para: OpenAI API (Whisper e GPT-3.5 turbo 16k), FFmpeg WASM.


<br>
<img src="https://github.com/zF4ke/nlw-ai/blob/master/assets/home-completion.png" alt="Preview" />

---

## ⚙️ Funcionalidades

| Feature                | Description                           |
| ---------------------- | ------------------------------------- |
| **⚙️ Arquitetura**     | base de código segue uma arquitetura servidor-cliente com uma API de backend construída em Fastify e um frontend construído em React. O backend usa Prisma como ORM para interagir com uma base de dados SQLite.   |
| **📖 Documentação**   | [🧩 Clique aqui. ](#-módulos)    |
| **🔗 Dependências**    | O sistema depende de bibliotecas externas como Fastify, React, Prisma, Tailwind CSS, OpenAI e axios. Estas bibliotecas fornecem funcionalidades essenciais para servir a API, construir o frontend, operações ORM, gerir estilos, processamento de PNL e efetuar chamadas à API.    |
| **🧩 Modularidade**      | A base de código está organizada em vários componentes, rotas e bibliotecas. Cada componente tem uma responsabilidade específica e pode ser trocado ou reutilizado facilmente. No entanto, é possível melhorar a separação de preocupações e reduzir as dependências entre componentes.    |
| **✔️ Testes**          | O código não tem uma estratégia de teste abrangente como Jest ou Cypress. Possui no entanto algumas rotas HTTP no backend para uma verificação manual do comportamento do servidor.   |
| **⚡️ Performance**      | A performance varia dependendo do tamanho do vídeo. A IA pode ser otimizada.    |
| **🔐 Segurança**        | Indisponível no momento.    |
| **🔀 Controlo de versões** | Este repositório.   |
| **🔌 Integrações**    | A API do sistema interage com OpenAI para serviços de processamento de linguagem natural, Prisma para operações de bases de dados e FFmpeg com Web Assembly para processamento de vídeo e áudio.    |
| **📶 Escalabilidade**     | Indisponível no momento.  |

---


## 📂 Estrutura do Projeto

- `web/` : Frontend.
- `api/` : Backend.


---

## 🧩 Módulos

| File                                                                                                                                    | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ---                                                                                                                                     | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| [routes.http](https://github.com/zF4ke/nlw-ai/blob/master/api/routes.http)                                                                | Um arquivo com as possível rotas da aplicação.                                                                                                                                                                            |
| [App.tsx](https://github.com/zF4ke/nlw-ai/blob/master/web/src/App.tsx)                                                                    | UI da aplicação onde o usuário irá carregar o vídeo e selecionar o prompt desejado. |                                                                                                                                                                                                                                                                                           |
| [create-transcription.ts](https://github.com/zF4ke/nlw-ai/blob/master/api/src/routes/create-transcription.ts)                             |  Rota POST para gerar a transcrição de um determinado vídeo. Ele valida os parâmetros e o corpo do pedido, busca os detalhes do vídeo, processa o arquivo de áudio, envia-o para a API de transcrição da OpenAI, armazena o resultado no banco de dados e retorna o texto da transcrição como resposta.                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| [generate-ai-completion.ts](https://github.com/zF4ke/nlw-ai/blob/master/api/src/routes/generate-ai-completion.ts)                         |  Rota POST que lida com a geração de IA para um determinado vídeo. Valida a entrada, obtém os dados do vídeo, gera uma mensagem de aviso e utiliza o modelo GPT da OpenAI para gerar uma conclusão. A conclusão gerada é então transmitida de volta como uma stream para ser lida pelo front-end, token a token.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| [get-all-prompts.ts](https://github.com/zF4ke/nlw-ai/blob/master/api/src/routes/get-all-prompts.ts)                                       |  Rota GET que, quando um pedido é feito, ele recupera todos os prompts do banco de dados usando o Prisma.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| [upload-video.ts](https://github.com/zF4ke/nlw-ai/blob/master/api/src/routes/upload-video.ts)                                             | Rota POST para carregar vídeos MP3 usando o Fastify. Ele valida o tipo de arquivo, salva-o em um local temporário e armazena as informações do vídeo em um banco de dados usando o Prisma.                                                                                                                                        

---

## 🚀 Começando

### 📦 Instalação

1. Clonar o repositório:
```sh
git clone https://github.com/zF4ke/nlw-ai
```

2. Mudar para o diretório `web/` do projeto:
```sh
cd nlw-ai/web
```

3. Instalar dependências:
```sh
npm install
```

4. Mudar para o diretório `api/` do projeto:
```sh
cd ../api
```

5. Instalar dependências:
```sh
npm install
```



### 🎮 Usando NLW-AI

Em `web/`:

```sh
npm run dev
```

Em `api/`:

```sh
npm run dev
```

### 🧪 Testes
```sh
Indisponível.
```

---

## 🤝 Contribuir

As contribuições são sempre bem-vindas! Por favor, siga os seguintes passos:
1. Bifurcar o repositório do projeto. Isto cria uma cópia do projeto na sua conta que pode modificar sem afetar o projeto original.
2. Clone o repositório bifurcado para a sua máquina local usando um cliente Git como o Git ou o GitHub Desktop.
3. Crie um novo branch com um nome descritivo (por exemplo, `new-feature-branch` ou `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Faça alterações na base de código do projeto.
5. Faça o commit das suas alterações no seu branch local com uma mensagem de commit clara que explique as alterações que você fez.
```sh
git commit -m 'Implementou nova funcionalidade.'
```
6. Envie suas alterações para o repositório bifurcado no GitHub usando o seguinte comando
```sh
git push origin new-feature-branch
```
7. Crie uma nova pull request para o repositório original do projeto. No pull request, descreva as alterações que você fez e por que elas são necessárias.
Os mantenedores do projeto revisarão suas alterações e fornecerão feedback ou as mesclarão no branch principal.

---

## 📄 Licença

Este projeto está licenciado sob a licença `MIT`. Veja o arquivo [LICENSE](https://github.com/zF4ke/nlw-ai/blob/master/LICENSE) para informações adicionais.

---

## 👏 Agradecimentos

> - `ℹ️  Rocketseat - rocketseat.com.br`

---
