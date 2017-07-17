## Darwin Algorithmic Trading System (DATS)

The goal of DATS is to provide a fully automatic trading platform for professional investors, and small asset manager to manage, execute and monitor their trading activities.

### Trading Features
1. Integrating various trading APIs and connecting multiple brokage accounts:
    - Chinese Future Market (Through CTP)
    - Cryptocurrency (BTC, and etc)
    - International Future Market (Through Interactive Broker)
2. Advanced strategy backtest, live-simulation and trading features: 
    - including multi-legs strategy, pair/basket-trading, option strategies and etc. 
    - support in-sample/out-of-sample test, walk-forward tests 
    - paramset optimization, sensitivity tests, random entry/exit tests and etc, with AI features
3. Portfolio, Asset Allocation and Risk Management:
    - strategy portfolio backtest and live-trading
    - strategy correlation and position sizing analysis
    - risk management features

### Front-end features
The front-end of DarwinSys is based on HTML5/CSS/Javascript, which provide users easy-access features:
1. Desktop-based trading dashboard and workbench
    - Strategy backtests, simulation and trading
    - Strategy performance analysis and monitoring tools  
2. Mobile-based trading monitor tools

### Infrastructure Features
DATS is designed to deploy in a distributed environment with robustness and transparency as the core requirement. 
1. Individual modules including strategy running, front-end web app, datafeed recording and management, trading API and brokage account management, database system (storing historical data and meta data) are all indepedent module, which can be running in different process or host
2. Through centralized caching system and async messaging system to monitor the status of each module and communicate inbetween. 
With such distributed system design, we woud like to achieve:
- Robust and extendable system. Trader can easily deploy strategies by adding runnng instances/hosts for the strategies, without affecting the performance of other modules
- Safety: Trading enviornment including strategy running process, account information and related trading/order logs can be separated from the front-end web-app. It protects the mot valuable intellectual property of the trader - the strategy

## Contact
If you are interseted in our project, please contact us 


