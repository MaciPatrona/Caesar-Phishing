# Caesar Phishing Framework 👑

A modern, interactive phishing campaign management framework built with Flask. Features a sleek dark theme interface and real-time monitoring capabilities.

![Caesar Phishing](https://img.shields.io/badge/Caesar-Phishing-purple)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Flask](https://img.shields.io/badge/Flask-2.0+-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 🌟 Features

- 🎯 Multiple phishing templates:
  - Social Media (Facebook, Instagram, Twitter, LinkedIn)
  - Email Services (Gmail, Outlook)
  - Business (PayPal, Credit Card)
- 🔄 Real-time campaign monitoring
- 📊 Live statistics and capture tracking
- 🌐 Automatic Ngrok tunnel integration
- 🎨 Modern dark theme interface
- 📱 Responsive design
- 🔒 Admin-only access control
- 📥 Export captured data to CSV
- ⚡ Interactive particle effects
- 🔔 Real-time notifications

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/caesar-phishing.git
cd caesar-phishing
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

4. Configure Ngrok:
- Sign up at [ngrok.com](https://ngrok.com)
- Get your auth token
- Update the token in `data/config.json`

## 🛠️ Configuration

The configuration file (`data/config.json`) contains:
```json
{
    "ngrok_token": "your_token_here",
    "server": {
        "host": "0.0.0.0",
        "port": 5000,
        "debug": true
    },
    "security": {
        "secret_key": "your_secret_key_here"
    }
}
```

## 🎮 Usage

1. Start the server:
```bash
python app.py
```

2. Access the admin panel:
- Open `http://localhost:5000` in your browser
- Only accessible from localhost for security

3. Create a campaign:
- Click "New Campaign"
- Select a template
- Copy the generated Ngrok URL

4. Monitor campaigns:
- View active campaigns
- Track captures in real-time
- Export data to CSV

## 🔒 Security Features

- Admin-only access control
- Localhost restriction
- Ngrok URL filtering
- Secure data storage
- Session protection

## 📊 Data Management

Captured data is stored in:
- `data/captured_data.json`
- `data/active_pages.json`

Export options:
- CSV export with timestamps
- Comprehensive data fields
- Secure data handling

## 🎨 UI Features

- Interactive particle effects
- Real-time statistics
- Smooth animations
- Copy-to-clipboard functionality
- Toast notifications
- Responsive grid layouts
- Modern glassmorphism design

## ⚠️ Disclaimer

This tool is for educational purposes only. The authors are not responsible for any misuse or damage caused by this program. Use responsibly.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a pull request

## 📧 Contact

For questions and support, please open an issue in the GitHub repository. 
