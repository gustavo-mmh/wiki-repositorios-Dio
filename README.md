# 📚 GitHub Wiki Explorer

Este projeto é uma aplicação web desenvolvida em React que permite aos usuários buscar e visualizar repositórios do GitHub, organizando-os em uma lista interativa. É uma ferramenta útil para quem deseja acompanhar projetos específicos ou criar uma "wiki" pessoal de repositórios.

## ✨ Funcionalidades

  * **Busca de Repositórios:** 🔎 Permite buscar repositórios do GitHub por nome de usuário/organização e nome do repositório.
  * **Listagem Dinâmica:** Exibe os repositórios encontrados em uma lista, incluindo informações relevantes como nome, descrição e link.
  * **Remoção de Repositórios:** Possibilidade de remover repositórios da lista exibida.
  * **Componentes Reutilizáveis:** Construído com uma arquitetura de componentes reutilizáveis para entrada de dados (Input), botões (Button) e exibição de itens de repositório (ItemRepo).
  * **Integração com API GitHub:** Utiliza a API do GitHub para buscar dados de repositórios.
  * **Estilização com Styled-components:** Design modular e responsivo com uso de CSS-in-JS.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído com as seguintes tecnologias principais:

  * **React:** Biblioteca JavaScript para construir interfaces de usuário.
  * **Styled-components:** Para estilização de componentes com CSS-in-JS.
  * **Axios:** Cliente HTTP baseado em promessas para fazer requisições à API do GitHub.
  * **HTML & CSS:** Estrutura e estilização básica.
  * **JavaScript (ES6+):** Lógica da aplicação.

## 📂 Estrutura do Projeto

A seguir, a estrutura principal do projeto:

```
├── public/                     # Arquivos públicos (HTML, ícones, manifest) 🌐
│   ├── favicon.ico
│   ├── index.html              # Arquivo HTML principal da aplicação
│   ├── logo192.png             # Ícone do aplicativo
│   ├── logo512.png             # Ícone do aplicativo
│   └── manifest.json           # Manifest da Progressive Web App (PWA)
├── src/                        # Código-fonte da aplicação 💻
│   ├── assets/                 # Imagens (ex: logo do GitHub) 🖼️
│   ├── components/             # Componentes reutilizáveis (Button, Input, ItemRepo) 🧩
│   │   ├── Button/
│   │   ├── Input/
│   │   └── ItemRepo/
│   ├── pages/                  # Páginas da aplicação (ex: App principal) 📄
│   ├── services/               # Configurações de API (ex: axios para GitHub) ⚙️
│   └── styles/                 # Estilos globais da aplicação 🎨
├── package.json                # Gerenciamento de dependências e scripts 📦
├── yarn.lock                   # Bloqueio de versões de dependências 🔒
└── README.md                   # Documentação do projeto 📖
```

## 🚀 Como Começar

Siga estas instruções para obter uma cópia do projeto em execução em sua máquina local.

### 📋 Pré-requisitos

Certifique-se de ter o Node.js e o Yarn (ou npm) instalados em sua máquina.

### ⬇️ Instalação

1.  **Clone o repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    cd desafio0-github-wiki-dio
    ```
2.  **Instale as dependências:**
    Usando Yarn:
    ```bash
    yarn install
    ```
    Ou usando npm:
    ```bash
    npm install
    ```

### ▶️ Executando a Aplicação

Para iniciar o servidor de desenvolvimento:

```bash
yarn start
# ou
npm start
```

Isso abrirá o aplicativo em seu navegador padrão em `http://localhost:3000`. A página será automaticamente recarregada conforme você fizer alterações no código.

## 📜 Scripts Disponíveis

No diretório do projeto, você pode executar:

  * **`npm start`**: Inicia o aplicativo em modo de desenvolvimento.
  * **`npm test`**: Inicia o executor de testes em modo de observação interativo.
  * **`npm run build`**: Compila o aplicativo para produção na pasta `build`.
  * **`npm run eject`**: Remove a única dependência de build do seu projeto. **Use com cautela, é uma operação irreversível\!**

## 🤝 Contribuição

Contribuições são bem-vindas\! Sinta-se à vontade para abrir issues ou pull requests para melhorias.

## 📝 Licença

Este projeto é de código aberto e está disponível sob a licença padrão da plataforma.
