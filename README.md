# GovChain-AI-Powered-Transparent-Public-Fund-System
# Transparency Dashboard

A blockchain-powered transparency platform for government project management, featuring AI-driven fraud detection and real-time monitoring.

## 🚀 Features

- **Blockchain Integration**: Immutable transaction ledger using custom blockchain implementation
- **AI Fraud Detection**: Machine learning-powered anomaly detection for financial transactions
- **Multi-Role Access**: Separate dashboards for Government, Contractors, and Public users
- **Real-Time Updates**: WebSocket-powered live notifications and updates
- **Project Management**: Complete lifecycle management from funding to completion
- **Work Tracking**: Milestone-based progress tracking with visual verification
- **Rating System**: Contractor performance evaluation and feedback
- **Funding Requests**: Top-up request system with approval workflows

## 🛠️ Technologies Used

- **Backend**: Python Flask with Flask-SocketIO
- **Blockchain**: Custom Python implementation
- **AI/ML**: Scikit-learn for fraud detection
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Database**: In-memory storage (hackathon-friendly)
- **Async**: Eventlet for WebSocket support

## 📋 Prerequisites

- Python 3.8+
- Virtual environment (recommended)

## 🔧 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/transparency-dashboard.git
   cd transparency-dashboard
   ```

2. **Create and activate virtual environment**
   ```bash
   python -m venv .venv
   # On Windows:
   .venv\Scripts\activate
   # On macOS/Linux:
   source .venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

1. **Start the application**
   ```bash
   python SSS--main/app.py
   ```

2. **Access the dashboard**
   Open your browser and navigate to: `http://localhost:8000`

3. **Login Credentials**
   - **Government**: username: `gov`, password: `gov123`
   - **Contractor**: username: `contractor`, password: `contract123`
   - **Public**: username: `public`, password: `public123`

## 📁 Project Structure

```
SSS--main/
├── app.py                 # Main Flask application
├── blockchain.py          # Blockchain implementation
├── ai_governance.py       # AI fraud detection logic
├── image.py              # Image processing utilities
├── requirements.txt       # Python dependencies
├── README.md             # This file
└── uploads/              # Directory for file uploads (created automatically)
```

## 🔍 Key Components

### Blockchain System
- Custom block and blockchain classes
- Transaction immutability
- Chain validation

### AI Fraud Detection
- Isolation Forest algorithm for anomaly detection
- Transaction pattern analysis
- Risk scoring system

### Dashboard Features
- Project overview and statistics
- Transaction ledger with blockchain verification
- Funding request management
- Work log and rating system

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⚠️ Disclaimer

This is a demonstration project for educational purposes. In production, consider:
- Proper database implementation
- Security hardening
- Comprehensive testing
- Professional deployment practices

## 📞 Support

For questions or issues, please open an issue on GitHub.

---

**Built with ❤️ for transparent governance**
