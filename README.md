# GEN-AI

Example notebooks exploring self-attention, transformer architectures (BERT / DistilBERT via `bertviz`), and vector representations of phrases.

## Contents

- `Self_Attention/` — notebooks visualizing attention heads, model views, and Q/K/V vectors using `bertviz` and Hugging Face `transformers`.
- `Vectors/` — notebook demonstrating converting phrases to vectors.

## Setup

### 1. Create a virtual environment

**Windows (PowerShell):**

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**Windows (Git Bash):**

```bash
python -m venv .venv
source .venv/Scripts/activate
```

**macOS / Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 2. Install dependencies

With the virtual environment activated:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 3. Select the kernel

In VS Code, open one of the notebooks and select the `.venv` interpreter as the Jupyter kernel (Command Palette → **Notebook: Select Notebook Kernel**).

### 4. Run the notebooks

Open any notebook under `Self_Attention/` or `Vectors/` and run the cells top to bottom. The first run will download pre-trained model weights (e.g. `bert-base-uncased`, `distilbert-base-uncased`) from Hugging Face, so an internet connection is required.
