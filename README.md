# DeepLearning.AI Agentic AI Reference

## Environment Setup

Create a local `.env` file from the sample file before running the notebooks:

```bash
cp .env_sample .env
```

On Windows PowerShell:

```powershell
Copy-Item .env_sample .env
```

Then open `.env` and add your API keys:

```env
OPENAI_API_KEY="your_openai_api_key_here"
ANTHROPIC_API_KEY="your_anthropic_api_key_here"
```

`OPENAI_API_KEY` is required for the default notebook model settings. `ANTHROPIC_API_KEY` is needed for notebooks or examples that use Claude for reflection/evaluation.

The notebooks call `load_dotenv()`, so keeping `.env` in the repository root is enough when you launch Jupyter from this project directory.
