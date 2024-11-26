# aris-repo-2

## 현재 최종 

xArm-Python-SDK를 다운받고 venv로 가상환경 만들어주세요.

아나콘다 가상환경은 안되더라구요

그리고 아래 pip를 수행해주세요

pip install 전에 portaudio 설치를 위해 아래 명령어를 수행해야함

sudo apt update

sudo apt install portaudio19-dev

### torch install 먼저 하기 

pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121

pip install --upgrade huggingface_hub==0.25.2

> pip install -r requirements.txt


### uvicorn 실행

> uvicorn app.main:app --reload