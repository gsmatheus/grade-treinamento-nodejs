# Instalação do Node.js e VS Code

Este guia irá te ajudar a instalar o Node.js e o Visual Studio Code (VS Code) em diferentes sistemas operacionais. Mesmo que você seja novo em programação, siga as instruções passo a passo para uma instalação bem-sucedida.

## Índice

1. Instalação do Node.js
   - Linux
   - Windows
   - Mac
2. Instalação do VS Code
   - Linux
   - Windows
   - Mac

## 1. Instalação do Node.js

### Linux

1. **Usando o gerenciador de pacotes**:

   ```bash
   sudo apt update
   sudo apt install nodejs npm
   ```

2. **Verifique a instalação**:
   ```bash
   node -v
   npm -v
   ```

### Windows

1. **Baixe o instalador**:

   - Acesse o [site oficial do Node.js](https://nodejs.org/) e baixe o instalador para Windows.

2. **Execute o instalador**:

   - Siga as instruções na tela. Ele também instalará o `npm`.

3. **Verifique a instalação**:
   - Abra o prompt de comando e digite:
     ```
     node -v
     npm -v
     ```

### Mac

1. **Usando Homebrew** (recomendado se você já tiver o Homebrew instalado):

   ```bash
   brew install node
   ```

2. **Baixe o instalador**:

   - Se você não tem o Homebrew, acesse o [site oficial do Node.js](https://nodejs.org/) e baixe o instalador para Mac.

3. **Verifique a instalação**:
   ```bash
   node -v
   npm -v
   ```

## 2. Instalação do VS Code

### Linux

1. **Baixe o pacote .deb ou .rpm**:

   - Acesse o [site oficial do VS Code](https://code.visualstudio.com/) e baixe o pacote apropriado para sua distribuição.

2. **Instale o pacote**:
   - Para distribuições baseadas em Debian/Ubuntu:
     ```bash
     sudo dpkg -i <nome_do_arquivo>.deb
     sudo apt-get install -f # para corrigir dependências, se necessário
     ```
   - Para distribuições baseadas em Red Hat/Fedora:
     ```bash
     sudo rpm -i <nome_do_arquivo>.rpm
     ```

### Windows

1. **Baixe o instalador**:

   - Acesse o [site oficial do VS Code](https://code.visualstudio.com/) e baixe o instalador para Windows.

2. **Execute o instalador**:
   - Siga as instruções na tela.

### Mac

1. **Baixe o arquivo .zip**:

   - Acesse o [site oficial do VS Code](https://code.visualstudio.com/) e baixe o arquivo .zip para Mac.

2. **Descompacte o arquivo**:
   - Mova o aplicativo `Visual Studio Code` para a pasta `Aplicativos`.
