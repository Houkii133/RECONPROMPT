# Main README
cat > README.md << 'EOL'
# RECONPROMPT

RECONPROMPT is an interactive database system for organizing, searching, and utilizing 27,665+ AI prompts across multiple domains and AI models.

## Features

- Multi-dimensional prompt organization by intent, domain, content type, and more
- Advanced search with intelligent filtering and recommendations
- Personal collections and public libraries of curated prompts
- Template system for customizing prompts to specific needs
- Analytics to track prompt effectiveness across different AI models
- Integration capabilities with popular AI platforms (OpenAI, Anthropic, etc.)

## Repository Structure

- `docs/` - Documentation
- `server/` - Backend Node.js/Express application
- `client/` - Frontend React application
- `database/` - Database schema and scripts
- `.github/` - GitHub workflow configurations

## Getting Started

See [INSTALLATION.md](docs/INSTALLATION.md) for setup instructions.

## License

This project is licensed under the MIT License.
EOL

# Docs README
cat > docs/README.md << 'EOL'
# Documentation

This directory contains all documentation for the RECONPROMPT project.

## Contents

- System architecture
- API specifications
- Database schema
- UI/UX guidelines
- Setup instructions
EOL

# Server README
cat > server/README.md << 'EOL'
# RECONPROMPT Server

Backend implementation for the RECONPROMPT application.

## Technology Stack

- Node.js
- Express
- PostgreSQL
- JWT Authentication

## Directory Structure

- `src/controllers/` - API route handlers
- `src/models/` - Database models
- `src/services/` - Business logic
- `src/middleware/` - Auth and other middleware
- `src/utils/` - Helper functions
- `src/routes/` - API route definitions
- `config/` - Configuration files
- `scripts/` - Import/migration scripts
EOL

# Client README
cat > client/README.md << 'EOL'
# RECONPROMPT Client

Frontend implementation for the RECONPROMPT application.

## Technology Stack

- React
- TypeScript
- Tailwind CSS
- React Router

## Directory Structure

- `src/components/` - React components
- `src/pages/` - Page layouts
- `src/hooks/` - Custom React hooks
- `src/services/` - API clients
- `src/utils/` - Helper functions
- `src/context/` - React context providers
- `public/` - Static assets
EOL

# Database README
cat > database/README.md << 'EOL'
# RECONPROMPT Database

Database schema and scripts for the RECONPROMPT application.

## Structure

- `schema/` - Schema definition files
- `migrations/` - Database migrations
- `seeds/` - Seed data scripts

## Setup

See the main README for database setup instructions.
EOL