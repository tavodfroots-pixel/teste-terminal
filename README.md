# Polymarket Market Maker Bot (v2.0)

Bot autônomo para **market making de arbitragem de conjunto completo** na Polymarket, focado nos mercados de 5 e 15 minutos de criptomoedas (BTC, ETH, SOL, XRP).

## 🎯 Estratégia

- **Arbitragem matemática**: compra simultânea de YES+NO por menos de $1.00 e merge para USDC.
- **Gestão de capital com Kelly Criterion fracionado dinâmico**.
- **Spread alvo ajustado por volatilidade** (via Binance).
- **Fechamento unilateral inteligente** com take-profit, stop-loss e timeout.
- **Monitor de saúde e alertas via Telegram**.

## ⚙️ Instalação

```bash
git clone <seu-repo>
cd polymarket-mm-bot
cp .env.example .env   # Edite com sua chave privada e configurações
npm install
