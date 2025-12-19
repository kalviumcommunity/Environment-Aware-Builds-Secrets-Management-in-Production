## Environment-Aware Builds & Secrets Management

This project supports multiple environments:
- Development
- Staging
- Production

Each environment uses its own configuration through environment variables.

### Environment Files
- `.env.development` – local development
- `.env.staging` – testing / preview
- `.env.production` – production

Only `.env.example` is committed to the repository.  
All real secrets are ignored using `.gitignore`.

### Build Commands
```bash
npm run build:dev
npm run build:staging
npm run build:production
