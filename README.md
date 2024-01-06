
> **Step 0** - Install Python 3.11 or later. [See here](https://www.tutorialsteacher.com/python/install-python) for a step-by-step guide.

<br />

> **Step 1** - Download the project

```bash
git clone https://github.com/assafelovic/gpt-researcher.git
cd gpt-researcher
```

<br />

> **Step 2** - Install dependencies
```bash
pip install -r requirements.txt
```
<br />

> **Step 3** - Create .env file with your OpenAI Key and Tavily API key or simply export it

```bash
export OPENAI_API_KEY={Your OpenAI API Key here}
```
```bash
export TAVILY_API_KEY=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
```


> **Step 4** - Run the agent with FastAPI

```bash
uvicorn main:app --reload
```
<br />

> **Step 5** - Go to http://localhost:8000 on any browser and enjoy researching!

To learn how to get started with Docker or to learn more about the features and services check out the [documentation](https://docs.tavily.com) page.
