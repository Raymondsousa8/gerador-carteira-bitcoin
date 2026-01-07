# Gerador de Carteiras Bitcoin ₿

Projeto desenvolvido para o desafio da **Formação Blockchain Especialista** da [DIO](https://www.dio.me/).

## 📝 Descrição
O objetivo deste projeto é criar um gerador de carteiras de Bitcoin utilizando Node.js. O script gera uma frase mnemônica (Seed), chaves privadas e endereços para a rede de testes (Testnet).

## 🚀 Tecnologias Utilizadas
- **Node.js**: Ambiente de execução.
- **bitcoinjs-lib**: Biblioteca para manipulação de endereços e transações.
- **bip39**: Para geração da frase mnemônica.
- **bip32**: Para a criação de carteiras hierárquicas determinísticas.

## ⚙️ Como executar
1. Clone este repositório.
2. No terminal, execute `npm install` para baixar as dependências.
3. Execute o projeto com o comando:
   ```bash
   node createWallet.js