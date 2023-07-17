
## requirements

pytorch
numpy
matplotlib

## install

torch 설치
```bash
pip install torch torchvision torchaudio
pip install numpy matplotlib pandas jupyter
pip install yfinance scikit-learn

```

만약 GPU를 사용한다면 CUDA를 먼저 설치하고 버전에 맞게 torch를 설치해야합니다. conda 를 사용한다면 더 편하게 설치할 수 있습니다.
    
```bash
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
```
