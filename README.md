# DevOps Platform Monorepo

This repository contains the source code for the Zarish Healthcare DevOps Platform, including multiple apps, services, and shared packages.

## Structure

- **apps/**: Frontend applications (clinical-dashboard, mobile-app)

- **packages/**: Shared TypeScript types and utilities

- **services/**: Backend microservices (zarish-access, zarish-care, zarish-labs, zarish-ops, zarish-sync, zarish-analytics)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/DevOps-Ariful-Islam/DevOps.git
   cd DevOps
   ```

2. Install dependencies for each app/service/package:

   ```bash
   cd apps/clinical-dashboard && npm install
   cd apps/mobile-app && npm install
   cd packages/shared-types && npm install
   # Repeat for each service in services/
   ```

3. Set up environment variables:

   - Copy `.env.example` to `.env` and update values as needed for each app/service.

## Development

- Use feature branches and pull requests for changes.

- Run linting and tests before pushing:

   ```bash
   npm run lint
   npm test
   ```

## CI/CD

- GitHub Actions are used for automated linting and testing.

## Contributing

- Please read the contribution guidelines in each app/service/package README.

## License

MIT
