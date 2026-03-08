# LangGraph Workflows

A collection of LangGraph workflow implementations demonstrating various graph-based AI applications.

## 📁 Project Structure

### Sequence Workflows
- **BMI Calculator** - Basic sequential workflow
- **LLM Q&A** - Question answering system
- **Prompt Chaining** - Multi-step prompt processing
- **Essay Generator** - Automated essay writing

### Parallel Workflows
- **Essay Parallel** - Parallel processing for essay generation

### Conditional Workflows
- **Quadratic Equation Solver** - Conditional logic for equation solving
- **Review Handling** - Sentiment analysis with conditional routing
  - Analyzes customer reviews
  - Routes to positive/negative response handlers
  - Includes diagnosis for negative feedback

### Iterative Workflows
- **Multiple Evaluation LLM Response** - Iterative response improvement
  - Generates initial response
  - Evaluates quality
  - Optimizes based on feedback
  - Repeats until approved or max iterations reached

### Chatbot
- **Basic Chatbot** - Simple conversational AI using LangGraph
  - Message state management
  - LLM integration with Groq/Ollama
  - Stateful conversation flow

## 🚀 Setup

1. Clone the repository
```bash
git clone https://github.com/Vinay21rout/LangGraph-Workflows.git
cd LangGraph-Workflows
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Configure environment variables
```bash
cp .env.example .env
# Add your API keys to .env
```

## 🔑 Environment Variables

Create a `.env` file with:
- `GROQ_API_KEY` - For Groq LLM access
- Other API keys as needed

## 📊 Workflows

Each workflow demonstrates different LangGraph capabilities:
- State management
- Conditional edges
- Parallel execution
- Node composition
- Iterative loops
- Message handling

## 🛠️ Technologies

- LangGraph
- LangChain
- Groq/Ollama LLMs
- Python 3.x

## 📝 License

MIT
