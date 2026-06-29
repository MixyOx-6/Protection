# 🛡️ Zx Protect

**Zx Protect** is a powerful and lightweight CLI tool to protect and obfuscate your Client-Side code (HTML, CSS, JavaScript). It uses Advanced Compression and Base64 Encoding to hide your source code from being easily copied or viewed using "View Page Source".

### ✨ Features
- 🚀 **Fast & Secure:** Encodes your code instantly.
- 📱 **Mobile Friendly:** Perfectly formatted for Termux and narrow terminal screens.
- 🔄 **Auto-Decoding:** The browser dynamically decodes and renders the page without affecting user experience.
- 🎨 **Beautiful UI:** Developed using Python's `rich` library for an elegant CLI experience.

### 🛠️ Prerequisites
Make sure you have Python installed on your system or Termux.

### 📥 Installation & Usage

Clone the repository and install the required modules:

```bash
# 1. Clone the repository
git clone https://github.com/MixyOx-6/zx-protect.git

# 2. Go into the directory
cd zx-protect

# 3. Install requirements
pip install -r requirements.txt

# 4. Put your target .html files in the same folder

# 5. Run the tool
python zx_protect.py
