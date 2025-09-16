# Changelog

All notable changes to this project will be documented in this file.

## [0.1.3] - 2025-01-27

### 🔒 Security Features
- **NEW**: Added login authentication functionality to enhance system security
- Implemented user authentication and authorization mechanisms
- Added session management and access control
- Fixed XSS attack vulnerabilities in frontend components

### 📚 Documentation Updates
- Added security notices in all README files (English, Chinese, Japanese)
- Updated deployment recommendations emphasizing internal/private network deployment
- Enhanced security guidelines to prevent information leakage risks
- Fixed documentation spelling issues

### 🛡️ Security Improvements
- Hide API keys in UI for security purposes
- Enhanced input sanitization and XSS protection
- Added comprehensive security utilities

### 🐛 Bug Fixes
- Fixed OCR AVX support issues
- Improved frontend health check dependencies
- Enhanced Docker binary downloads for target architecture
- Fixed COS file service initialization parameters and URL processing logic

### 🚀 Features & Enhancements
- Improved application and docreader log output
- Enhanced frontend routing and authentication flow
- Added comprehensive user management system
- Improved initialization configuration handling

### 🛡️ Security Recommendations
- Deploy WeKnora services in internal/private network environments
- Avoid direct exposure to public internet
- Configure proper firewall rules and access controls
- Regular updates for security patches and improvements

## [0.1.2] - 2025-01-27

- Fixed health check implementation for docreader service
- Improved query handling for empty queries
- Enhanced knowledge base column value update methods
- Optimized logging throughout the application
- Added process parsing documentation for markdown files
- Fixed OCR model pre-fetching in Docker containers
- Resolved image parser concurrency errors
- Added support for modifying listening port configuration

## [0.1.0] - 2025-09-08

- Initial public release of WeKnora.
- Web UI for knowledge upload, chat, configuration, and settings.
- RAG pipeline with chunking, embedding, retrieval, reranking, and generation.
- Initialization wizard for configuring models (LLM, embedding, rerank, retriever).
- Support for local Ollama and remote API models.
- Vector backends: PostgreSQL (pgvector), Elasticsearch; GraphRAG support.
- End-to-end evaluation utilities and metrics.
- Docker Compose for quick startup and service orchestration.
- MCP server support for integrating with MCP-compatible clients.

[0.1.3]: https://github.com/Tencent/WeKnora/tree/v0.1.3
[0.1.2]: https://github.com/Tencent/WeKnora/tree/v0.1.2
[0.1.0]: https://github.com/Tencent/WeKnora/tree/v0.1.0
