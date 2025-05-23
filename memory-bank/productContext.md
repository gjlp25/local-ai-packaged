# Product Context

## Why This Project Exists

This project addresses several key challenges in AI development and deployment:

1. **Need for Local Control**: 
   - Organizations and developers need control over their AI infrastructure
   - Data privacy concerns with cloud-based solutions
   - Cost considerations of cloud services

2. **Integration Complexity**: 
   - Multiple AI tools and services need to work together
   - Setting up individual services is time-consuming
   - Configuration and networking can be complex

3. **Resource Management**:
   - Need for efficient use of local computing resources
   - Support for both CPU and GPU configurations
   - Data persistence and state management

## Problems It Solves

1. **Infrastructure Setup**:
   - Provides pre-configured Docker environment
   - Handles service dependencies and networking
   - Manages SSL/TLS certificates automatically

2. **Service Integration**:
   - Centralized workflow automation with n8n
   - Local LLM hosting with Ollama
   - AI workflow creation with Flowise
   - Privacy-focused search with SearxNG
   - Observability with Langfuse
   - Database functionality with Supabase

3. **Development Efficiency**:
   - Unified environment for AI development
   - Consistent configuration across services
   - Easy deployment and updates

## How It Should Work

### 1. Deployment
- Simple initialization with docker-compose
- Environment configuration through .env file
- Automatic service discovery and networking
- Volume management for data persistence

### 2. Service Communication
- Internal service discovery via Docker networking
- Reverse proxy handling with Caddy
- Websocket support for real-time features
- Port forwarding for external access

### 3. User Interaction
- Access services through configured domains
- Secure HTTPS connections
- Unified logging and monitoring
- Easy backup and restore

### 4. Development Workflow
- Local development without external dependencies
- Easy integration of new services
- Flexible configuration options
- Support for custom tools and workflows

## User Experience Goals

1. **Simplicity**:
   - One-command deployment
   - Clear configuration options
   - Intuitive service access

2. **Reliability**:
   - Consistent service availability
   - Data persistence
   - Proper error handling

3. **Security**:
   - Automatic HTTPS
   - Container isolation
   - Access control

4. **Flexibility**:
   - Customizable configurations
   - Scalable architecture
   - Multiple deployment options

5. **Performance**:
   - Efficient resource usage
   - Fast service response
   - Optimized networking
