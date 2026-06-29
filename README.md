# ArbitrageFX

Automated forex arbitrage system built in C++ for MetaTrader 4/5.

Monitors price discrepancies across multiple currency pairs simultaneously and executes
arbitrage trades with real-time risk management and position sizing.

## Features

- Multi-symbol monitoring in real time
- Configurable spread threshold and slippage tolerance
- Integrated risk management: lot sizing, max drawdown, daily loss limit
- Compatible with MetaTrader 4 and MetaTrader 5

## Requirements

- MetaTrader 4 or MetaTrader 5
- Windows (MT4/MT5 environment)
- MQL4 or MQL5 compiler (included in the platform)

## Usage

1. Copy the `.ex4` / `.ex5` file to your MetaTrader `Experts` folder
2. Restart MetaTrader or refresh the Navigator
3. Drag the EA onto any chart
4. Configure the input parameters (spread threshold, lot size, risk %)
5. Enable Algo Trading in MetaTrader

## Parameters

| Parameter | Description | Default |
|-----------|-------------|---------|
| SpreadThreshold | Minimum spread difference to trigger trade (pips) | 2.0 |
| LotSize | Base lot size | 0.01 |
| MaxDrawdown | Maximum allowed drawdown (%) | 5.0 |
| MagicNumber | Unique identifier for EA orders | 12345 |

## Author

Rodrigo Maia Escorsim — Senior C++/MQL Developer
[GitHub](https://github.com/rodrigoescorsim) · [CacheSnap](https://cachesnap.com)
