# Local AI Packaged

A comprehensive solution that integrates multiple AI services and tools into a containerized environment for local deployment. This project combines workflow automation, language models, and various AI capabilities into a unified, self-hosted infrastructure.

## Quick Links

### Memory Bank Documentation
- [Project Brief](memory-bank/projectbrief.md) - Core requirements and goals
- [Product Context](memory-bank/productContext.md) - Why this exists and how it works
- [System Patterns](memory-bank/systemPatterns.md) - Architecture and design patterns
- [Technical Context](memory-bank/techContext.md) - Technologies and setup
- [Active Context](memory-bank/activeContext.md) - Current work and decisions
- [Progress](memory-bank/progress.md) - Status and roadmap

## Features

### Core Services
- **n8n**: Workflow automation and integration platform
- **Flowise**: AI workflow creation and management
- **Ollama**: Local large language model hosting
- **Open WebUI**: Interface for model interaction
- **SearxNG**: Privacy-focused web search
- **Langfuse**: Observability and analytics
- **Supabase**: Database functionality
- **Caddy**: Reverse proxy with automatic HTTPS

### Key Capabilities
- Containerized deployment with Docker
- Automatic HTTPS with Let's Encrypt
- GPU support for language models
- Persistent data storage
- Integrated workflow automation
- Privacy-focused architecture

## Getting Started

### Prerequisites
- Docker Engine
- Docker Compose
- NVIDIA drivers (optional, for GPU support)

### Configuration
1. Clone the repository
2. Copy `.env.example` to `.env`
3. Configure your environment variables
4. Run `docker compose up -d`

### Port Configuration
- External HTTPS: 8443 (forwarded to 9443)
- HTTP: 9080
- HTTPS: 9443
- n8n: 5678
- Flowise: 3001
- Open WebUI: 3011
- Langfuse: 3005
- Ollama: 11435
- SearxNG: 8083

## Documentation

For detailed documentation, explore the memory bank directories:

### Architecture
- Container relationships and dependencies
- Service communication patterns
- Data flow and storage

### Configuration
- Environment variables
- Service-specific settings
- Network configuration

### Development
- Build processes
- Testing procedures
- Deployment guidelines

## Current Status

See [Progress](memory-bank/progress.md) for detailed status information.

### Working Features
- Base infrastructure deployment
- Service containerization
- SSL/TLS configuration
- Volume persistence

### In Progress
- Telegram webhook connectivity
- Container DNS resolution
- Documentation updates

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the terms found in [LICENSE](LICENSE).
