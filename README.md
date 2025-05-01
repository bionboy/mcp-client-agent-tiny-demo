# Running the hugging face client demo

> https://github.com/huggingface/huggingface.js/tree/main/packages/mcp-client

1. Install hugging face dependencies and login

```bash
uv install
pnpx @huggingface/cli login
```

2. set the HF_TOKEN environment variable in .env

```bash
export HF_TOKEN=<your_token>
```

3. source the .env file

```bash
source .env
```

4. run the client

```bash
pnpx @huggingface/mcp-client
```
