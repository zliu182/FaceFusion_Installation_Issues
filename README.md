## Guides to install FaceFusion:
https://www.youtube.com/watch?v=oYlauViR_y4

## Open terminal on mac
Installation link: https://docs.facefusion.io/installation

### 1. GIT:
```bash
brew install git
```

### 2. Conda:
```bash
brew install miniconda
```

### 3. FFmpeg:
```bash
brew install ffmpeg
```

## Environment
```bash
conda init --all
```
```bash
conda create --name facefusion python=3.10
```

Reload your shell cinfiguration to avoid the CondaError:
```bash
source ~/.zshrc
```
Activate your environment:
```bash
conda activate facefusion
```
Deactivate your environment:
```bash
conda deactivate
```


## Download your copy
### 1. Git clone
```bash
git clone https://github.com/facefusion/facefusion
```

### 2. Enter the directory:
```bash
cd facefusion
```

### 3. Run script the avoid the installation error:
```bash
python install.py --onnxruntime default
```

## Refresh your environment
```bash
conda deactivate
```

```bash
conda activate facefusion
```

## Done and run this application in your local
```bash
python facefusion.py run
```





