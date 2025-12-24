

<div align="center">
<h1> UR-Bench: A Benchmark for Multi-Hop Reasoning over Ultra–High-Resolution Images </h1>


</div>

<div align="center">
<p align="center">
💜 <a href="https://knowledgexlab.github.io/UR-Bench/"><b>HomePage</b></a>&nbsp&nbsp | &nbsp&nbsp🤗 <a href="https://huggingface.co/datasets/GDIBench">Hugging Face</a>&nbsp&nbsp | &nbsp&nbsp📑 <a href="https://arxiv.org/pdf/2505.00063">Paper</a>&nbsp&nbsp
</p>


</div>


## 📰 News

Recent multimodal large language models (MLLMs) show strong capabilities in visual-language reasoning, yet their performance on ultra–high-resolution imagery remains largely unexplored. Existing visual question answering (VQA) benchmarks typically rely on medium-resolution data, offering limited visual complexity. To bridge this gap, we introduce Ultra-high-resolution Reasoning Benchmark (UR-Bench), a benchmark designed to evaluate the reasoning capabilities of MLLMs under extreme visual information. UR-Bench comprises two major categories Humanistic Scenes and Natural Scenes —covering four subsets of ultra–high-resolution images with distinct spatial structures and data sources. Each subset contains images ranging from hundreds of megapixels to gigapixels, accompanied by questions organized into three levels, enabling evaluation of models’ reasoning capabilities in ultra–high-resolution scenarios. We further propose an agent-based framework in which a language model performs reasoning by invoking external visual tools. In addition, we introduce Semantic Abstraction and Retrieval tools that enable more efficient processing of ultra–high-resolution images. We evaluate state-of-the-art models using both an end-to-end MLLMs and our agent-based framework, demonstrating the effectiveness of our framework.


## 🎯 UR-Bench

We introduce UR-Bench, a benchmark for ultra–high-resolution multi-hop reasoning, where individual image files range from several megabytes to over 1 GB and exhibit high information density. The benchmark incorporates three levels of reasoning complexity, enabling fine-grained evaluation under extreme visual conditions.

![image-1-1](https://github.com/KnowledgeXLab/UR-Bench/blob/main/image/1-1.jpg)

We propose an automated data engine for generating multi-hop reasoning questions over ultra–high-resolution images, capable of automatically producing questions with varying levels of reasoning difficulty.

![image-2-1](https://github.com/KnowledgeXLab/UR-Bench/blob/main/image/2-1.jpg)

We propose an agent-based framework that enables LLMs to autonomously plan and coordinate tool-based operations. The framework emphasizes semantic decomposition of ultra-large-scale visual information through the Semantic Abstraction and Retrieval Tool, enabling efficient perception and reasoning over ultra–high-resolution images.

![image-3-1](https://github.com/KnowledgeXLab/UR-Bench/blob/main/image/3-1.jpg)

## Case Study

![image-4-1](https://github.com/KnowledgeXLab/UR-Bench/blob/main/image/4-1.jpg)

## Citation

If you find the provided dataset or model useful for your research, consider citing them as:

```
@article{gdibench,
  title={UR-Bench: A Benchmark for Multi-Hop Reasoning over Ultra–High-Resolution Images},
  author={Li, Siqi and Cai, Xinyu and Mei, Jianbiao and Deng, Nianchen and Cai, Pinlong and Wen, Licheng and Shen, Yufan and Yang, Xuemeng and Shi, Botian and Liu, Yong and Qiao, Yu},
  journal={arXiv preprint arXiv:2505.00063},
  year={2025}
}
```


