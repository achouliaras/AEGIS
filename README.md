# AEGIS: Adversarial Exploration for Generalized Improved State representations

Official implementation of **AEGIS**, a novel pretraining algorithm for self-supervised RL that improves representation learning through adversarial exploration. 

---

## 🚀 Quick Start

### Prerequisites
- Python 3.8+
- [PyTorch 2.6.0+](https://pytorch.org/get-started/locally/) (with CUDA if GPU available)
- [Gymansium 1.0.0+](https://gymnasium.farama.org/)
- [MiniGrid 3.0.0+](https://minigrid.farama.org/index.html) (for environments)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/..../AEGIS.git
   cd AEGIS
   
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
(Optional: Use a virtual environment: python -m venv aegis_env && source aegis_env/bin/activate)

## 🎯 Usage

Use the provided bash scripts to replicate the experiemnts found in the paper. For example:
   ```bash
   ./test_aegis_reward.sh
