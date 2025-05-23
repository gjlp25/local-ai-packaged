# Project Brief: Local AI Packaged

## Overview
Local AI Packaged is a comprehensive solution that integrates multiple AI services and tools into a containerized environment for local deployment. The project aims to provide a seamless, self-hosted AI infrastructure that combines workflow automation, language models, and various AI capabilities.

## Core Requirements

### 1. Service Integration
- n8n for workflow automation
- Flowise for AI workflow creation
- Ollama for local language model hosting
- Open WebUI for model interaction
- SearxNG for privacy-focused web search
- Langfuse for observability
- Supabase for database functionality
- Caddy for reverse proxy and HTTPS

### 2. Containerization
- Docker-based deployment
- Docker Compose orchestration
- Efficient resource management
- Volume persistence for data

### 3. Networking
- Secure internal communication
- Reverse proxy with Caddy
- Websocket support
- Port management

### 4. Security
- HTTPS support via Caddy
- Proper container isolation
- Environment variable configuration
- Access control

## Project Goals
1. Provide a unified local AI development environment
2. Enable easy deployment and management of AI services
3. Ensure secure and reliable service communication
4. Support both CPU and GPU configurations
5. Maintain data privacy through local hosting

## Success Criteria
- All services start and communicate properly
- Websocket connections work for real-time features
- Data persists between container restarts
- Services are accessible through configured domains
- System resources are managed efficiently

## Current Challenges
- Telegram webhook configuration in n8n
- Service resolution between containers
- Port forwarding configuration
