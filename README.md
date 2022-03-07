1. swap eth for weth
2. Deposit some ETH (wETH) into AAVE
3. Borrow some asset with ETH collateral
    1. (OPT) Sell that borrowed asset (short selling)
4. Repay everything back

Testing: 
Integration test: kovan
Unit tests: Mainnet-fork (As we are not using oracles and don't need mocks otherwise we'd use a development network)