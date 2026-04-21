## Nextflow Installation (Mac)

### 1. Install Java 21
```bash
brew install openjdk@21
echo 'export PATH="/opt/homebrew/opt/openjdk@21/bin:$PATH"' >> ~/.zshrc
echo 'export JAVA_HOME="/opt/homebrew/opt/openjdk@21"' >> ~/.zshrc
source ~/.zshrc
java -version  
```

### 2. Install Nextflow
```bash
curl -s https://get.nextflow.io | bash
mv nextflow /usr/local/bin/
nextflow -version
```

## nf-core Installation

### Recommended: pip (fast)
```bash
pip install nf-core
nf-core --version
```

### Not recommended: conda (very slow, gets stuck)
```bash
# This takes very long and may get stuck:
conda install nf-core   ← avoid this
```

### Verify installation
```bash
nf-core --version
nf-core list    # see all available pipelines
```
