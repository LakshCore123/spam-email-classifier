📧 AI-Powered Spam Classifier

## 🌐 Live Demo
Try it yourself: **[Click here to test the Spam Classifier](https://lakshcore123.github.io/spam-email-classifier/spam_classifier.html)**

A machine learning-based spam detection system that classifies SMS messages as spam or ham with **98.7% accuracy**.

## ✨ Features

- **98.7% accuracy** on real SMS data
- **Interactive web interface** - no installation needed
- **Real-time classification** with confidence scores
- **Spam indicators** showing why a message was flagged
- **Works offline** - runs entirely in your browser

## 🚀 Quick Start

1. **Run in Google Colab** (Recommended):
   - Open the notebook
   - Run all cells
   - The classifier will open automatically

2. **Or use the HTML file directly**:
   - Download `spam_classifier.html`
   - Double-click to open in any browser
   - Start classifying!

## 📊 How It Works

The model uses:
- **TF-IDF vectorization** with n-grams
- **Logistic Regression** algorithm
- **5,574 SMS messages** for training
- **Spam pattern detection** for accuracy

## 📱 Try These Examples

**Spam Example:
Congratulations! You've won $1000! Click here to claim your prize now!**
✅ Result: **SPAM** (85-95% confidence)

**Ham Example:
Hey, are we still meeting for coffee at 3pm tomorrow?**
✅ Result: **NOT SPAM** (80-90% confidence)

## 🛠️ Tech Stack

- Python + scikit-learn (ML model)
- HTML/CSS/JavaScript (Web interface)
- Pandas, NumPy (Data processing)

## 📈 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | 98.7% |
| Precision | 96.2% |
| Recall | 94.8% |

## 🤝 Contributing
Contributions are welcome! Feel free to:

Report bugs

Suggest features

Submit pull requests

📄 License
MIT License - feel free to use and modify!

Made with ❤️ using Python & Machine Learning
## 💻 Installation (Optional)

```bash
# Clone the repo
git clone https://github.com/yourusername/spam-classifier.git
cd spam-classifier

# Install dependencies
pip install pandas scikit-learn numpy

# Run the script
python spam_classifier.py
spam-classifier/
├── spam_classifier.py      # ML training script
├── spam_classifier.html    # Web interface
├── README.md               # This file
└── requirements.txt        # Dependencies ```
