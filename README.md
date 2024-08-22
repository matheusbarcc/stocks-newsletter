# Stock Newsletter Generator with Agents

Web application that generates a newsletter based on a stock ticket (e.g "AAPL")

## How it works
- 3 AI agents powered by GPT-3.5
  - **Stock Price Analyst**: Utilizes yahoo-finance API as a tool to check the history of the ticket over a period of one year.
  - **Stock News Analyst**: Utilizes duckduckgo to search news about the ticket company.
  - **Stock Analyst Writer**: Delegates the other 2 agents and generate a newsletterr based on the infos that they provide (stock price history and news)
- The process starts with the Stock Price Analyst, then follows to the News Analyst and the Analyst Writer finishes it with the newsletter output
