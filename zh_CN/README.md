# NotebookMLX

[English](../README.md) | [简体中文](./zh_CN/README.md)

> [meta-llama/NotebookLlama](https://github.com/meta-llama/llama-recipes/tree/main/recipes/quickstart/NotebookLlama)

我用 [MLX](https://github.com/ml-explore/mlx)
移植了 [NotebookLlama](https://github.com/meta-llama/llama-recipes/tree/main/recipes/quickstart/NotebookLlama) 🔥

其使用了 [mlx-community/Qwen2.5-3B-Instruct-4bit](https://huggingface.co/mlx-community/Qwen2.5-3B-Instruct-4bit) 对
PDF
进行预处理, [mlx-community/Qwen2.5-14B-Instruct-4bit](https://huggingface.co/mlx-community/Qwen2.5-14B-Instruct-4bit)
撰写讲稿, [mlx-community/Qwen2.5-7B-Instruct-4bit](https://huggingface.co/mlx-community/Qwen2.5-7B-Instruct-4bit) 润色讲稿,
最后用 [lucasnewman/f5-tts-mlx](https://huggingface.co/lucasnewman/f5-tts-mlx) 生成播客音频 ⚡

> 这里引用了 NotebookLlama 流程图.
> ![Outline.jpg](resources/Outline.jpg)


[步骤 1](Step-1-PDF预处理.ipynb): 预处理
PDF：使用 [mlx-community/Qwen2.5-1.5B-Instruct-bf16](https://huggingface.co/mlx-community/Qwen2.5-1.5B-Instruct-4bit)
预处理PDF并将其保存为`.txt`文件。

[步骤 2](Step-2-撰写讲稿.ipynb):
撰写讲稿：使用 [mlx-community/Qwen2.5-14B-Instruct-4bit](https://huggingface.co/mlx-community/Qwen2.5-14B-Instruct-4bit)
写一个播客讲稿。

[步骤 3](Step-3-润色讲稿.ipynb):
润色讲稿：使用[mlx-community/Qwen2.5-7B-Instruct-4bit](https://huggingface.co/mlx-community/Qwen2.5-7B-Instruct-4bit)
对讲稿进行润色。

[步骤 4](Step-4-生成播客.ipynb): 生成播客：使用[lucasnewman/f5-tts-mlx](https://huggingface.co/lucasnewman/f5-tts-mlx)
生成播客音频。

## 这个是生成效果

https://github.com/user-attachments/assets/63252d4f-1dfc-4134-b7a9-31a95994337e

## Star History

<a href="https://star-history.com/#maiqingqiang/NotebookMLX&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=maiqingqiang/NotebookMLX&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=maiqingqiang/NotebookMLX&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=maiqingqiang/NotebookMLX&type=Date" />
 </picture>
</a>