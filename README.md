# Promptfoo evals with Langchain and Structured Outputs

## Config

Set up `.env` with the following properties (replace with your API values):

```
AZURE_API_HOST=https://example.openai.azure.com
AZURE_DEPLOYMENT_NAME=gpt-4o-deployment-example
AZURE_API_KEY=secret
```

Then run:
```
npx promptfoo eval -c test/promptfoo/page-links/promptfooconfig.yaml --no-cache
```

Afterwards, you can view the results by running `npx promptfoo view test/promptfoo/page-links`
