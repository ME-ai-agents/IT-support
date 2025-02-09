
# ME.ai: at Your Service
# Revolutionizing Service Industry
# AI Service Hub
# # ME.ai-Agents @ https://meagents.nl/

An advanced IT support system featuring multi-channel communication, intelligent agent orchestration, and blockchain integration. Built to provide enterprise-grade support with AI capabilities and secure Web3 authentication.

🔗 [Live Demo](#) | [Documentation](#) | [Report Issues](https://github.com/ME-ai-agents/IT-support/issues)

## 🌟 Core Features

### Multi-Channel Support
- **Chat Integration**: Real-time messaging with AI-assisted responses
- **Voice Support**: VAPI-powered voice communication
- **Digital Channels**: Handle various digital communication methods
- **Web3 Authentication**: Secure wallet-based authentication via MetaMask
- **Session Persistence**: Neo4j-based session management

### Intelligent Agent Orchestration
- **Support Levels**:
  - L1: General IT support and basic troubleshooting
  - L2: Advanced technical support
  - L3: Expert-level problem resolution
- **Domain Expertise**:
  - Hardware troubleshooting
  - Software support
  - Network infrastructure
  - Security management
- **Dynamic Load Balancing**: Smart distribution of support requests
- **Real-time Monitoring**: Live agent status and performance tracking

### AI-Powered Resolution
- Multiple AI provider support (OpenAI, Deepseek, Qwen)
- Automatic failover between providers
- Context-aware responses
- System diagnostics integration
- Real-time performance monitoring

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- Neo4j 4.4 or higher
- MetaMask wallet
- Node.js and npm

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ME-ai-agents/IT-support.git
cd IT-support
```

2. Install Python dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
```bash
cp .env.example .env
# Edit .env with your configuration
```

4. Start the server:
```bash
python app123.py
```

5. Launch the desktop application:
```bash
python meaichain.py
```

## 🏗️ Architecture

### Desktop Client (meaichain.py)
- PyQt5-based desktop application
- Web3 integration for blockchain connectivity
- VAPI integration for voice calls
- Modern dark theme UI
- Real-time system monitoring

### Server (app123.py)
- Flask-based backend
- Multi-agent orchestration
- AI provider integration
- Session management
- Event-driven architecture

### Database Layer
- Neo4j graph database for session management
- Relationship tracking between:
  - Users and agents
  - Support tickets and resolutions
  - Channel interactions
  - Session history

## 💡 Usage

### Connect Your Wallet
```python
# Initialize Web3 connection
web3_handler = Web3Handler()
web3_handler.connect_wallet()
```

### Start Support Session
```python
# Create new session
session = Session(session_id)
session.add_channel('chat')
orchestrator.assign_agent(session)
```

### Handle Multi-Channel Support
```python
# Initialize channels
vapi = VapiIntegration(
    on_call_start=handle_call_start,
    on_call_end=handle_call_end
)
```

## 🔧 Configuration

### AI Providers
```python
# Configure in app123.py
OPENAI_API_KEY="your-openai-key"
DEEPSEEK_API_KEY="your-deepseek-key"
QWEN_API_KEY="your-qwen-key"
```

### Neo4j Settings
```python
# Database configuration
NEO4J_URI="bolt://localhost:7687"
NEO4J_USER="neo4j"
NEO4J_PASSWORD="your-password"
```

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Anthropic Claude](https://www.anthropic.com/claude) for AI capabilities
- [VAPI](https://vapi.ai) for voice integration
- [Web3.py](https://web3py.readthedocs.io/) for blockchain connectivity
- [Neo4j](https://neo4j.com/) for graph database
- [PyQt5](https://www.riverbankcomputing.com/software/pyqt/) for desktop interface

## 📞 Support

For support:
- Open an [issue](https://github.com/ME-ai-agents/IT-support/issues)
- Email: support@meai.com
- Join our [Discord](#)

---
Built by ME.AI Agents Team
