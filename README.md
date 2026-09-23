### Step-by-step instructions


## How to generate an NVIDIA API Key

- ​Go to build.nvidia.com and sign in.
- Open any model card (for example, Nemotron 3 Nano 30B).
- Scroll down and click Self-hosted Deployment.
- Click Get API Key.
- Select Generate Key.
- Copy and save your API key on your laptop (it typically begins with nvapi-).

## ​How to generate a Tavily API Key

- ​Go to https://app.tavily.com/home.
- Sign in or create an account.
- From the dashboard, click the + button next to API Keys.
- Enter a name for your key and click Create.
- ​Copy and save the generated API key on your laptop.

## ​[Optional] How to generate a LangSmith API Key

- ​Go to https://smith.langchain.com.
- Sign in or create an account.
- On smith.langchain.com go to Tracing on the left.
- ​Click + Project on the top, enter Project name and click Create Project.
- Go to that project and Click “Generate API Key” on the right (Configure environment section). 

​Toggle to .env and copy the lines (will look similar to this) and store safely.

```
​LANGSMITH_TRACING=true
​LANGSMITH_ENDPOINT=https://api.smith.langchain.com
​LANGSMITH_API_KEY=<your-api-key>
​LANGSMITH_PROJECT="test-langsmith"
```