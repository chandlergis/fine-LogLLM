# fine-LogLLM

## Installation

```bash
# Install dependencies
pip install git+https://github.com/yanqiangmiffy/huggingface-dl.git

# Install required packages
pip install torch==2.4.0 torchvision==0.19.0 torchaudio==2.4.0 --index-url https://download.pytorch.org/whl/cu121
pip install transformers datasets peft accelerate bitsandbytes safetensors
pip install scikit-learn
pip install tqdm
```
### Download BERT Model
```bash
cd model
hfdl dl https://huggingface.co/meta-llama/Meta-Llama-3-8B/tree/main
```

### Download LLaMA Model
```bash
hfdl dl https://huggingface.co/google-bert/bert-base-uncased
```