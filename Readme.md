# ME.AI Desktop Operator

A powerful desktop application for handling multi-channel customer support with integrated Web3 capabilities, AI-powered responses, and system control features.

## 🌟 Features

### Multi-Channel Support
- **Chat Support**: Real-time messaging with AI-powered responses
- **Voice Calls**: Integrated VAPI for voice communication
- **Digital Channels**: Handle various digital communication channels

### Web3 Integration
- Secure wallet connection through MetaMask
- Polygon network support
- Real-time balance tracking
- Seamless session management with wallet authentication

### Intelligent Routing
- Domain-specific agent assignment (Hardware, Software, Network, Security)
- Multi-level expertise handling (L1, L2, L3)
- Dynamic load balancing
- Automatic issue categorization

### System Control
- Real-time system diagnostics
- Hardware issue detection
- Software problem resolution
- Performance monitoring
- Audio and display troubleshooting

### Advanced AI Integration
- Multiple AI provider support (OpenAI, Deepseek, Qwen)
- Automatic failover between providers
- Context-aware responses
- Streaming response support

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- PyQt5
- Web3.py
- Flask
- MetaMask wallet

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/meai-desktop-operator.git
cd meai-desktop-operator
```

2. Install dependencies:
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
- Built with PyQt5 for robust desktop integration
- Web3 integration for blockchain connectivity
- VAPI integration for voice call handling
- Modern dark theme UI with responsive design
- Real-time system monitoring capabilities

### Server (app123.py)
- Flask-based backend server
- Advanced agent orchestration system
- Multi-provider AI integration
- Session management with persistence
- Event-driven architecture with SSE support

## 💡 Usage

1. **Connect Wallet**
   - Click "Connect Wallet" to authenticate with MetaMask
   - Ensure you're connected to Polygon network
   - View your MATIC balance

2. **Start Session**
   - Enter customer phone number
   - Initialize support session
   - Access multi-channel support options

3. **Handle Support**
   - Use chat interface for text communication
   - Initiate voice calls through VAPI integration
   - Monitor system diagnostics
   - View real-time action logs

## 🔧 Configuration

### AI Providers
```python
# Configure in app123.py
OPENAI_API_KEY="your-openai-key"
DEEPSEEK_API_KEY="your-deepseek-key"
QWEN_API_KEY="your-qwen-key"
```

### Web3 Settings
```python
# Configure in meaichain.py
INFURA_URL="your-infura-url"
NETWORK_ID=137  # Polygon Mainnet
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Anthropic Claude](https://www.anthropic.com/claude) for AI capabilities
- [VAPI](https://vapi.ai) for voice integration
- [Web3.py](https://web3py.readthedocs.io/) for blockchain connectivity
- [PyQt5](https://www.riverbankcomputing.com/software/pyqt/) for desktop interface

## 📞 Support

For support, email support@meai.com or join our [Discord community](https://discord.gg/meai).

---
Built with ❤️ by ME.AI Team