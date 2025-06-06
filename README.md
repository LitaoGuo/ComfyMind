<h1 align="center">
ComfyMind: Toward General-Purpose Generation 

via Tree-Based Planning and Reactive Feedback
</h1>
<p align="center">
    <a href="https://litaoguo.github.io/ComfyMind.github.io/"> <img alt="Project Page" src="https://img.shields.io/badge/Project-Page-green"> </a>
    <a href="https://arxiv.org/abs/2505.17908"> <img alt="arXiv Paper" src="https://img.shields.io/badge/arXiv-Paper-red"> </a>
    <a href="https://envision-research.hkust-gz.edu.cn/ComfyMind/"> <img alt="Demo" src="https://img.shields.io/badge/Demo-Live-orange"> </a>
</p>

## 💫 Introduction

![Teaser](assets/teaser.png)

We present ComfyMind, a collaborative AI system designed to enable robust and scalable general-purpose generation, built on the ComfyUI platform. We evaluate ComfyMind on three public benchmarks: ComfyBench, GenEval, and Reason-Edit, which span generation, editing, and reasoning tasks. Results show that ComfyMind consistently outperforms existing open-source baselines and achieves performance comparable to GPT-Image-1. ComfyMind paves a promising path for the development of open-source general-purpose generative AI systems.


## 📰 News

- **[2025/05/30]** Our online demo has been released. [https://envision-research.hkust-gz.edu.cn/ComfyMind/](https://envision-research.hkust-gz.edu.cn/ComfyMind/)
- **[2025/05/24]** Our paper is submitted to arXiv.

## ️⚙️ Installation

### Step-by-step Installation

1. Clone the repository, create and activate conda environment:
```bash
git clone https://github.com/LitaoGuo/ComfyMind.git
cd ComfyMind

conda create -n comfymind python=3.12
conda activate comfymind
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

⚠️ 3. Before using ComfyMind, please prepare your ComfyUI with necessary models and extensions.

- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) Installation
- [ComfyUI-Manager](https://github.com/Comfy-Org/ComfyUI-Manager) offers custom nodes management and installation.
- [Hugging Face](https://huggingface.co/) offers Models Installation 


## Configuration

⚠️ Modify `config.yaml` to set your APIs:


## 🚀 Usage

### Execute the main script
```bash
python main.py \
    --instruction "The generation instruction" \
    --resource1 "<optional>path/to/the/reference1" \
    --resource2 "<optional>path/to/the/reference2"
    --save_path "path/to/save/result"
```

### Gradio Demo
```bash
python main_gradio.py
```

## 📜 Citation

If you find our work helpful, please consider citing our paper:

```bibtex
@misc{guo2025comfymindgeneralpurposegenerationtreebased,
      title={ComfyMind: Toward General-Purpose Generation via Tree-Based Planning and Reactive Feedback}, 
      author={Litao Guo and Xinli Xu and Luozhou Wang and Jiantao Lin and Jinsong Zhou and Zixin Zhang and Bolan Su and Ying-Cong Chen},
      year={2025},
      eprint={2505.17908},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2505.17908}, 
}
```

## ❤️ Acknowledgments
We would like to thank the authors of the following projects for their excellent works.

- [ComfyBench](https://github.com/xxyQwQ/ComfyBench)
- [GPT-ImgEval](https://github.com/PicoTrex/GPT-ImgEval)

## 📄 License

This code is released under the MIT License.

## 📞 Contact

If you have any questions, please raise an issue or contact us at guolitauo@gmail.com.
