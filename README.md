# BipedalWalker-v3 Hardcore

BipedalWalker-v3 Hardcore 환경을 이용한 강화학습 텀프로젝트입니다.

## 환경 설치 (Mac)

### 1. Conda 환경 생성

```bash
conda create -n walker python=3.10 -y
conda activate walker
```

### 2. Swig 설치

Box2D 빌드에 필요한 swig를 먼저 설치합니다.

```bash
brew install swig
```

### 3. 패키지 설치

```bash
# Gymnasium + Box2D (BipedalWalker 환경)
pip install "gymnasium[box2d]"

# PyTorch
pip install torch

# 기타 유틸리티
pip install matplotlib numpy
```

### 4. 설치 확인

```bash
python -m test_walker
```

BipedalWalker 창이 뜨고 랜덤하게 움직이면 설치 완료입니다.
