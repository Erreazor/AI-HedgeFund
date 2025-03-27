# AI Hedge Fund

An AI-powered hedge fund that uses multiple AI analysts to make investment decisions. The system combines insights from various investment strategies and AI models to analyze stocks and make trading decisions.

## Features

- Multiple AI analysts (Ben Graham, Warren Buffett, Charlie Munger, etc.)
- Support for various LLM providers (OpenAI, Groq, Anthropic, etc.)
- Technical and fundamental analysis
- Portfolio management
- Risk management

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Erreazor/AI-HedgeFund.git
cd AI-HedgeFund
```

2. Install dependencies using Poetry:
```bash
poetry install
```

3. Create a `.env` file in the root directory with your API keys:
```
GROQ_API_KEY=your-groq-api-key
FINANCIAL_DATASETS_API_KEY=your-financial-datasets-api-key
OPENAI_API_KEY=your-openai-api-key
```

## Usage

Run the hedge fund with specific stock tickers:

```bash
poetry run python src/main.py --tickers "AAPL,MSFT"
```

Optional arguments:
- `--initial-cash`: Starting cash amount (default: 100000)
- `--margin-requirement`: Margin requirement (default: 0.5)
- `--start-date`: Start date for analysis (default: 1 year ago)
- `--end-date`: End date for analysis (default: today)
- `--show-reasoning`: Show the reasoning behind decisions
- `--show-agent-graph`: Show the agent interaction graph

## Contributing

Feel free to submit issues and enhancement requests!
