# 🌟  AYSON-CLİ 🌟
ayson-cli is a Python-based solution designed to resolve shortened links from various services, including ay.live, aylink.co, cpmlink.pro, ouo.io, and ouo.press. This project aims to navigate through the redirection chain and extract the final URL, bypassing intermediate pages and CAPTCHA challenges. The core functionality involves sending HTTP requests to the link shortening services, parsing the responses, and following redirections until the final URL is obtained.

## 🚀 Key Features
- Resolves shortened links from multiple services
- Handles CAPTCHA detection and error handling
- Utilizes Python's standard library for HTTP requests and HTML parsing
- Designed to run within the Termux environment on Android
- Provides a command-line interface for user input and link resolution

## 🛠️ Tech Stack
- Python 3.x
- Python Standard Library (argparse, gzip, html, http.cookiejar, json, os, re, shutil, ssl, sys, time, urllib.error, urllib.parse, urllib.request)
- Dataclasses and Typing for structured data and type hints
- Zlib for compression and decompression tasks
- Termux environment for Android integration

## 📦 Getting Started / Setup Instructions
### Prerequisites
- Python 3.x installed on your system
- Termux environment set up on your Android device

### Installation
1. Clone the repository using `git clone https://github.com/BlackCorpDev/ayson-cli/`
2. Navigate to the project directory using `cd ayson-cli`
3. Install the required dependencies using `pip install -r requirements.txt`

### Running Locally
1. Run the script using `python ayson_v1_1.py --install`
2. You can now use it as ayson '<URL>'
3. Follow the command-line interface prompts to input URLs and resolve links
4. To see all commands, use ayson --help 

## 📂 Project Structure
```markdown
ayson-cii/
│
├── ayson_v1_1.py
├── requirements.txt
├── README.md
└── ...
```

## 📸 Screenshots

## 🤝 Contributing
Contributions are welcome! If you'd like to contribute to the project, please fork the repository and submit a pull request with your changes.

## 📝 License
This project is licensed under the MIT License. See the LICENSE file for details.

## 📬 Contact
For questions or concerns, please contact us at [karapinarahmet33@gmail.com](mailto:your-email@example.com).

## 💖 Thanks Message
A huge thank you to all the contributors and users of this project! Your support and feedback are greatly appreciated.
