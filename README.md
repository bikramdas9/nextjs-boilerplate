# Salesforce SSE Proxy

This is a minimal Node.js server to proxy Salesforce MIAW SSE messages to your frontend app.

## How to Run

```bash
npm install
node server.js
```

## Environment

- Port: defaults to 3001

## Deploy to GitHub

1. Clone your GitHub repo:
   ```bash
   git clone https://github.com/bikramdas9/nextjs-boilerplate
   ```

2. Copy the contents of this project into the repo folder:
   ```bash
   cp -r salesforce-sse-proxy/* nextjs-boilerplate/
   cd nextjs-boilerplate
   ```

3. Commit and push:
   ```bash
   git add .
   git commit -m "Add Salesforce SSE proxy server"
   git push origin main
   ```

## Deploy to Heroku

```bash
heroku create your-app-name
git push heroku main
```
