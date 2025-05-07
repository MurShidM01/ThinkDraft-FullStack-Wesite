# 🚀 ThinkDraft - AI-Powered Essay Generator & Reviewer

<div align="center">

![ThinkDraft Logo](https://img.shields.io/badge/ThinkDraft-AI%20Essay%20Generator-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Flask](https://img.shields.io/badge/Flask-2.0%2B-lightgrey)
![License](https://img.shields.io/badge/License-MIT-green)

*Transform your writing experience with AI-powered essay generation and review*

[Features](#features) • [Demo](#demo) • [Installation](#installation) • [Usage](#usage) • [Tech Stack](#tech-stack) • [Contributing](#contributing)

</div>

## ✨ Features

<div align="center">

| 🎯 Feature | 📝 Description |
|------------|---------------|
| 🤖 AI-Powered Generation | Generate well-structured essays on any topic using advanced AI technology |
| 📊 Smart Review System | Get detailed feedback and scores for your essays |
| 🎨 Customizable Options | Choose word count, writing style, and additional instructions |
| 📱 Modern UI | Beautiful, responsive interface with dark mode support |
| 🔒 User Authentication | Secure login and registration system |
| 📈 Progress Tracking | Monitor your writing improvement over time |

</div>

## 🎥 Demo

<div align="center">

![Dashboard Preview](https://via.placeholder.com/800x400?text=ThinkDraft+Dashboard)
![Essay Generation](https://via.placeholder.com/800x400?text=Essay+Generation)
![Review System](https://via.placeholder.com/800x400?text=Review+System)

*Replace placeholder images with actual screenshots of your application*

</div>

## 🛠️ Installation

### Prerequisites

- Python 3.8 or higher
- Google Gemini API key
- Git

### Step-by-Step Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ThinkDraft.git
   cd ThinkDraft
   ```

2. **Set up virtual environment**
   ```bash
   # Create virtual environment
   python -m venv venv

   # Activate virtual environment
   # On Windows:
   venv\Scripts\activate
   # On macOS/Linux:
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure environment variables**
   Create a `.env` file in the project root:
   ```env
   SECRET_KEY=your-secret-key-here
   OPENROUTER_API_KEY=openrouter-api-key-here
   ```

5. **Initialize database**
   ```bash
   flask db init
   flask db migrate
   flask db upgrade
   ```

6. **Run the application**
   ```bash
   python app.py
   ```

7. **Access the application**
   Open your browser and navigate to `http://localhost:5000`

## 📱 Usage

1. **Create an Account**
   - Register with your email
   - Verify your account
   - Log in to access features

2. **Generate Essays**
   - Navigate to the dashboard
   - Click "Generate New Essay"
   - Set your parameters
   - Get AI-generated content

3. **Get Reviews**
   - Submit your essay for review
   - Receive detailed feedback
   - Track your progress

4. **Manage Content**
   - View all your essays
   - Download in multiple formats
   - Track improvement over time

## 🛠️ Tech Stack

<div align="center">

| Category | Technologies |
|----------|--------------|
| Backend | Python, Flask, SQLAlchemy |
| Frontend | HTML5, CSS3, JavaScript, Bootstrap 5 |
| AI/ML | Google Gemini AI |
| Database | SQLite |
| Authentication | Flask-Login |
| Icons | Font Awesome |

</div>

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines

- Follow PEP 8 style guide
- Write clear commit messages
- Add tests for new features
- Update documentation

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Google Gemini AI for powering our essay generation
- Bootstrap team for the amazing UI framework
- All our contributors and users

---

<div align="center">

Made with ❤️ by [Ali Khan Jalbani]

[Report Bug](https://github.com/yourusername/ThinkDraft/issues) • [Request Feature](https://github.com/yourusername/ThinkDraft/issues)

</div> 
