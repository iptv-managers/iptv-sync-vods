# 📦 Channels Sync for XUI.one

Este é um projeto simples feito em Node.js. Ele pode ser usado para sincronizar canais dentro do XUI.one, tanto novos canais como sincronizar a base inteira.

---

## ✅ Requisitos

Antes de começar, você precisa ter instalado no seu computador:

- [Node.js](https://nodejs.org/) (recomendado: versão 19 ou superior)
- Um editor de texto (como o [Visual Studio Code](https://code.visualstudio.com/)) ou qualquer um de sua preferencia
- Conexão com a internet (para instalar os pacotes)

---

## 🚀 Como usar o projeto

Siga os passos abaixo com atenção:

### 1. Faça o download do projeto

Você pode fazer isso de duas formas:

- **Opção 1:** Baixe o ZIP do projeto e extraia em uma pasta.
- **Opção 2:** Se souber usar o Git, rode:
  ```bash
  git clone https://github.com/seu-usuario/seu-projeto.git
  ```

### 2. Renomeie o arquivo .env.example
Este projeto usa um arquivo chamado .env para guardar configurações (como tokens, URLs e senhas).

Encontre o arquivo chamado .env.example para .env

### 3. Abra o arquivo .env.example, renomeie para .env, e preencha as informações com os seus dados. Exemplo:
```
# Configurações da API Xtream Codes para VODS
XTREAM_URL_VODS="http://fontedecanais.com:80"
XTREAM_USER_VODS="seu_usuario_da_fonte"
XTREAM_PASS_VODS="sua_senha_da_fonte"

# Configurações da API Xtream Codes para canais
XTREAM_URL_CHANNELS="http://fontedecanais.shop"
XTREAM_USER_CHANNELS="seu_usuario_da_fonte"
XTREAM_PASS_CHANNELS="sua_senha_da_fonte"


M3U8_PATH="./lista.m3u"
SYNC_CATEGORIES=true
USE_IPTV_ORGANIZER=false

# Configurações do Banco de Dados MySQL
DB_HOST="localhost"
DB_USER="seu_usuario_db"
DB_PASSWORD="sua_senha_db"
DB_NAME="seu_banco_de_dados"

# Apenas se for usar o IPTV Organizer
TMDB_API_KEY=""
TMDB_LANGUAGE="pt-BR"
```


### 4. Abra o terminal ou prompt de comando dentro da pasta do projeto e execute:
`npm install`

Este comando instala todas as bibliotecas que o projeto precisa para funcionar.

### 5. Rode o projeto
Ainda no terminal, execute: `node index.js`

### 6. Licença
Este projeto é livre para uso pessoal e aprendizado.
