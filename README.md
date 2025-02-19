# Crypto EVM Wallet Lavos

## Objetivo
Criar uma plataforma web (SPA Angular) para facilitar a visualização de ativos e seus saldos ao conectar uma carteira EVM, exibindo os valores em dólar (USD) em uma interface amigável.

---

## Funcionalidades Principais

1. **Conexão de Carteira EVM:**
   - Suporte para MetaMask inicialmente.
   - Integração com bibliotecas como **ethers.js** ou **web3.js**.

2. **Visualização de Ativos:**
   - Listar tokens ERC-20.
   - Exibir saldos de tokens.
   - Mostrar o valor total em USD.

3. **Conversão de Saldos para USD:**
   - Integração com APIs de preços (CoinGecko e/ou CoinMarketCap).
   - Atualização em tempo real dos valores.

4. **Interface Amigável:**
   - Design inspirado no Debank (https://debank.com).
   - Utilização de Angular Material para componentes UI.
   - Gráficos ou visualizações simples.

5. **Gerenciamento de Redes EVM:**
   - Suporte para múltiplas redes EVM (Ethereum, Binance Smart Chain, Polygon, etc.).
   - Alternância entre redes na interface.

6. **Segurança:**
   - Proteção contra XSS e CSRF.
   - Gerenciamento seguro de dependências.

7. **Funcionalidades Futuras (opcionais):**
   - Suporte para NFTs (ERC-721/ERC-1155).
   - Integração com protocolos DeFi (ex: Aave, Uniswap).
   - Notificações de alterações de saldo.

---

## Tecnologias e Ferramentas

- **Frontend:**
  - Angular (TypeScript, HTML, SCSS).
  - Bibliotecas para blockchain: **ethers.js** ou **web3.js**.
  - UI Components: Angular Material.

- **APIs Externas:**
  - APIs de preços: CoinGecko e/ou CoinMarketCap.
  - APIs de blockchain: Alchemy, Infura, ou Moralis.

- **Ferramentas de Desenvolvimento:**
  - Versionamento: Git (GitHub, GitLab, ou Bitbucket).
  - Gerenciamento de pacotes: npm ou yarn.
  - Testes: Jest para testes unitários e Cypress para testes E2E.

---

## Escopo do Projeto

### Fase 1: Configuração Inicial
- Configurar o projeto Angular.
- Configurar conexão com MetaMask.
- Exibir endereço da carteira conectada.

### Fase 2: Visualização de Ativos
- Listar tokens ERC-20.
- Exibir saldos de tokens.
- Integrar API de preços para conversão em USD.

### Fase 3: Melhorias de Interface
- Criar um design responsivo e amigável inspirado no Debank.
- Adicionar gráficos ou visualizações de saldos.

### Fase 4: Funcionalidades Avançadas
- Suporte para múltiplas redes EVM.
- Integração com protocolos DeFi (opcional).

---

## Perguntas e Respostas

1. **Design e UI/UX:**
   - *Resposta: Design inspirado no Debank (https://debank.com).*

2. **Carteiras EVM:**
   - *Resposta: Suporte inicial para MetaMask, com suporte para múltiplas redes EVM.*

3. **APIs de Preços:**
   - *Resposta: Utilização de CoinGecko e/ou CoinMarketCap, com atualizações em tempo real.*

4. **Funcionalidades Adicionais:**
   - *Resposta: Iniciar com tokens ERC-20, NFTs como funcionalidade futura.*

5. **Segurança:**
   - *Resposta: Proteção contra XSS, CSRF e gerenciamento seguro de dependências.*

6. **Testes:**
   - *Resposta: Incluir testes unitários com Jest e testes E2E com Cypress.*

7. **Deploy:**
   - *Resposta: A definir (sugestão: Vercel ou Netlify para facilidade de deploy).*

---

## Próximos Passos
1. Configurar o projeto Angular e integrar MetaMask.
2. Implementar a listagem de tokens ERC-20 e exibição de saldos.
3. Integrar APIs de preços para conversão em USD.
4. Desenvolver a interface inspirada no Debank utilizando Angular Material.
5. Adicionar suporte para múltiplas redes EVM.

---

## Como Contribuir
1. Clone o repositório.
2. Instale as dependências: `npm install`.
3. Execute o projeto: `ng serve`.
4. Siga as boas práticas de desenvolvimento e envie suas contribuições via pull requests.

---

## Licença
Este projeto está sob a licença [MIT](LICENSE).
