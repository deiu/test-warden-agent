# Test Agent

A helpful AI agent named Test Agent

## Setup

Install dependencies:

```bash
npm install
```


## Development

Build and run the agent:

```bash
npm run build
npm run agent
```

The agent will be available at `http://localhost:3000`.

## Docker

Build and run with Docker:

```bash
docker build -t Test Agent .
docker run -p 3000:3000 -e AGENT_URL=http://your-public-url:3000 Test Agent
```

Set `AGENT_URL` to the public URL where the agent will be reachable. This is used in the agent card for discovery by other agents and clients.
