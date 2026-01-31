 Multi-Agent Generative AI Stock Market Simulation
 
Overview
This project is a multi-agent stock market simulation powered by Generative AI, designed to study emergent market behavior arising from heterogeneous, autonomous trading agents.
The simulation models a virtual stock market with:
Two tradable stocks (Stock A and Stock B)
50 AI-powered trader agents, each with distinct personalities and risk profiles
A full 264 trading-day cycle (1 trading year)
Agents make independent buy/sell/hold decisions based on personality, market conditions, capital constraints, news events, and learned behavior—resulting in realistic price dynamics, volatility, and market shocks.

Key Features
Virtual Market Environment
Two stocks with dynamically evolving prices
Supply–demand driven price formation
Market reacts to agent behavior and external news

AI Trading Agents (50 Total)
Each agent is uniquely parameterized with:
Risk appetite (conservative → aggressive)
Trading strategy (momentum, contrarian, random, news-driven, long-term)
Capital constraints
Decision-making powered by Generative AI reasoning

Trading Timeline
264 trading days
Daily market opening, trading, and closing cycles
Long-term trends and short-term volatility emerge naturally
Advanced Market Mechanics

News & Events System
Random and scheduled news events
Positive/negative sentiment impacts on Stock A and/or B
Agents interpret news differently based on personality
Loans & Interest
Agents can borrow capital when liquidity is low
Interest accumulates daily
Over-leveraged agents face higher bankruptcy risk

Bankruptcy & Exit
Agents unable to service debt or maintain minimum capital go bankrupt
Bankrupt agents exit the market
Market liquidity and volatility adjust dynamically
Simulation Outputs

The system tracks and logs:
Daily stock prices (A & B)
Trading volume
Agent portfolio values
Loan balances and interest
Bankruptcy events
Market-wide statistics

These outputs can be used for:
Market behavior analysis
Strategy comparison
Emergence studies
Visualization and research experiments

Use Cases

Financial market simulations
Multi-agent reinforcement & generative AI research
Behavioral finance experiments
Stress testing market dynamics


