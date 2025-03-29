# Dummy Agent Library

## Setup

1. (Optional) Create Python alias:
```bash
# On Unix/Linux/macOS - add to ~/.bashrc or ~/.zshrc
alias python=python3

# On Windows - create a .bat file in your PATH
echo @python3 %* > C:\Windows\python.bat
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Configure your environment:
- Copy `.env.example` to `.env`
- Replace the HF_TOKEN value with your Hugging Face token
  (Get your token from: https://huggingface.co/settings/tokens)

5. Run the application:
```bash
python app.py
```
