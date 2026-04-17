## Nextflow Installation (Mac)

### 1. Install Java 21
```bash
brew install openjdk@21
echo 'export PATH="/opt/homebrew/opt/openjdk@21/bin:$PATH"' >> ~/.zshrc
echo 'export JAVA_HOME="/opt/homebrew/opt/openjdk@21"' >> ~/.zshrc
source ~/.zshrc
java -version  # should show openjdk 21
```

### 2. Install Nextflow
```bash
curl -s https://get.nextflow.io | bash
mv nextflow /usr/local/bin/
nextflow -version
```
