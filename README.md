# Embodied Model Architecture Atlas

An interactive, source-linked map for reading embodied-AI model architectures.

**Live demo**  [English](https://moquansha.github.io/embodied-model-architecture-atlas/index-en.html) · [中文](https://moquansha.github.io/embodied-model-architecture-atlas/) · [Hugging Face Space](https://huggingface.co/spaces/shamoquan/embodied-model-architecture-atlas)

The atlas currently covers **38 representative models and methods across 26 architecture tags**. Each entry connects a simplified data flow to the original paper figure, interface explanation, training/deployment order, reported results, limitations, and implementation or project links.

This is an orientation atlas and a community-maintained starting point, not an exhaustive literature review or a cross-paper performance leaderboard. Please use the linked original papers for complete equations, datasets, ablations, and evidence boundaries. Figure copyright remains with the original authors; the categorization and explanatory notes are provided for educational use.

## Quick tour

- Browse the [English interactive atlas](https://moquansha.github.io/embodied-model-architecture-atlas/index-en.html).
- Choose a family such as [VLM-Backboned VLA](https://moquansha.github.io/embodied-model-architecture-atlas/index-en.html#/category/backbone), [Predict-then-Act WAM](https://moquansha.github.io/embodied-model-architecture-atlas/index-en.html#/category/predict), or [Diffusion / Flow Action Policy](https://moquansha.github.io/embodied-model-architecture-atlas/index-en.html#/category/diffusion).
- Open a model detail page, follow the figure reading guide, and compare up to three entries.
- Use the linked paper and project sources to continue the full reading.

## Why this exists

Embodied models are often described through overlapping labels such as VLA, WAM, hierarchical, asynchronous, diffusion, and world model. This atlas separates those labels into explicit design dimensions so that readers can ask what enters the model, what intermediate state is passed between modules, what is trained, and what actually runs in the robot control loop.

## Contributing

Missing a well-known work, a source figure, or an important boundary? Please open an issue using the relevant template, or start a discussion. Small corrections are welcome, especially when they include a paper section, figure number, or official implementation link. See [CONTRIBUTING.md](CONTRIBUTING.md).

## Citation

If the atlas is useful in a paper, report, lecture, or project, please cite the repository and include the version or commit you used. See [CITATION.cff](CITATION.cff).

## Local use

The site is a single-file static HTML application with hash routing, search, category browsing, model comparison, and figure zoom. Download `index-en.html` or `index.html` and open it in a modern browser. Embedded family figures work offline; original paper figures and external links require an internet connection.

## 中文简介

具身模型结构图谱是一个面向具身智能论文阅读的交互式索引，目前覆盖 38 个模型与方法、26 个结构标签。页面提供分类导航、搜索、结构与接口拆解、训练和部署顺序、论文原图、来源链接及横向对比。

中文入口：[在线阅读](https://moquansha.github.io/embodied-model-architecture-atlas/)。图谱用于抛砖引玉，不替代原论文，也不构成跨论文性能排名。
