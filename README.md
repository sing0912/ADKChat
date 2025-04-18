# Google Agent Tool Kit
 - Google Adk Chat Sample

### setup 과정

### 1. python 3.10 이상 버전 설치 
```bash
brew install python3
echo 'export PATH="/opt/homebrew/bin:$PATH"' >> ~/.zshrc
python3 --version
alias python=python3
source ~/.zshrc
```

### 2. python 가상 환경 활성화
```bash 
python3 -m venv .venv
source .venv/bin/activate
```

### 3. google-adk 인스톨 
```bash
pip install google-adk
```

### 4. 현재설정 백업 
```bash
pip freeze > requirements.txt
```
