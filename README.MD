# n8n on Render (Free Tier)

This repo lets you deploy n8n on Render for free using Docker.

## Deployment Steps

1. Create a new repo on GitHub
2. Upload these files:
   - Dockerfile
   - docker-compose.yml
   - README.md
3. Go to Render → Web Service → Connect Repo
4. Set environment variables:
   - N8N_ENCRYPTION_KEY
   - N8N_BASIC_AUTH_USER
   - N8N_BASIC_AUTH_PASSWORD
5. Deploy

n8n will be available at:

https://<your-service>.onrender.com
