erp-repo
→ APPLICATION SOURCE
→ Laravel backend
→ Dockerfile
→ migrations/controllers/models
→ used to BUILD erp-api image

erp-devops
→ DEPLOYMENT ONLY
→ docker-compose.yml
→ server/deployment configs
→ NO backend source
→ NO real .env

Docker Hub
→ mrityunjaybhagat/erp-api:v4
→ built application

VPS ~/erp
→ clone of erp-devops
→ .env created locally on VPS
→ pulls/runs Docker image
