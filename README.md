<div align="center">

# PhysLoop

### Harnessing LLMs' Physics Awareness for Self-Improving Video Generation Models

<p>
Yuxuan Chen<sup>1*</sup> · Xiaojie Li<sup>2*</sup> · Hao Chen<sup>1</sup> · Juncheng Ma<sup>1,2</sup> · Kewei Zhang<sup>1</sup><br>
Zhongjing Du<sup>1</sup> · Guoqiang Wei<sup>2</sup> · Fangfang Wang<sup>6</sup> · Zhen Dong<sup>3</sup> · Zhiyang Dou<sup>4</sup><br>
Liming Zhao<sup>2‡</sup> · Yan Zeng<sup>2</sup> · Jianwei Zhang<sup>5§</sup> · Daquan Zhou<sup>1†§</sup>
</p>

<p>
<sup>1</sup> Peking University &nbsp; <sup>2</sup> ByteDance Seed &nbsp; <sup>3</sup> University of California, Santa Barbara<br>
<sup>4</sup> Massachusetts Institute of Technology &nbsp; <sup>5</sup> Universität Hamburg &nbsp; <sup>6</sup> Hangzhou Normal University
</p>

<sup>*</sup> Equal contributions &nbsp; <sup>‡</sup> Industry advisor &nbsp; <sup>†</sup> Project lead &nbsp; <sup>§</sup> Corresponding author

[![Project Page](https://img.shields.io/badge/Project-Page-2ea44f?logo=googlechrome&logoColor=white)](https://chenyx24.github.io/PhysLoop-site/) [![Discord](https://img.shields.io/badge/Join-Discord-5865f2?logo=discord&logoColor=white)](https://discord.gg/uS7vgwG6sU)

[arXiv:2611.16748](https://arxiv.org/abs/2611.16748)

</div>

The code release is pending company policy review.

## Overview

[![PhysLoop overview](https://chenyx24.github.io/PhysLoop-site/media/framework-20261028/fig2-framework-db7714610db0.png)](https://chenyx24.github.io/PhysLoop-site/media/framework-20261028/fig2-framework-abfb003057bd.pdf)

## News

- **2026.10.18**: Project page and community links are available.

## Todo List

- [x] Paper available on [arXiv](https://arxiv.org/abs/2611.16748).
- [ ] Reproduction package.
- [ ] PhysLoop-Gen and PhysLoop-Repair evaluation datasets.
- [ ] PhysLoop-100K training data.

## Project Page

[![PhysLoop Project Page](https://chenyx24.github.io/PhysLoop-site/media/project-video-20261018/poster-c5288b1e1697.jpg)](https://chenyx24.github.io/PhysLoop-site/)

## Getting Started

The following commands and guides are for the code release.

```bash
git clone https://github.com/DAGroup-PKU/PhysLoop.git
cd PhysLoop
```

| Step | Guide |
| :--- | :--- |
| Environment and Unreal Engine setup | Installation (`docs/ENGINEERING.md`) |
| Run and replay cases | Usage (`USAGE.md`) |
| Browse case specifications | Cases (`cases/TREE.md`) |
| Data releases | Datasets (`docs/DATASETS.md`) |

## Repository

```text
harness/   Planning, execution, verification and refinement
scripts/   Case execution and workspace tools
cases/     Case specifications
config/    Runtime settings and variant plans
tests/     Tests
docs/      Setup, usage and release documentation
```

## Community

<table>
  <tr>
    <th align="center">WeChat</th>
    <th align="center">Discord</th>
  </tr>
  <tr>
    <td align="center"><img src="https://chenyx24.github.io/PhysLoop-site/media/community-20261018/wechat.png" width="220" alt="WeChat contact QR code"></td>
    <td align="center"><a href="https://discord.gg/uS7vgwG6sU"><img src="https://chenyx24.github.io/PhysLoop-site/media/community-20261018/discord.png" width="220" alt="Join PhysLoop on Discord"></a></td>
  </tr>
  <tr>
    <td align="center">Add with <strong>PhysLoop</strong> for a group invite.</td>
    <td align="center"><a href="https://discord.gg/uS7vgwG6sU">Join Discord</a></td>
  </tr>
</table>

## Citation

```bibtex
@misc{chen2026physloop,
  title = {{PhysLoop}: Harnessing {LLMs}' Physics Awareness for Self-Improving Video Generation Models},
  author = {Chen, Yuxuan and
            Li, Xiaojie and
            Chen, Hao and
            Ma, Juncheng and
            Zhang, Kewei and
            Du, Zhongjing and
            Wei, Guoqiang and
            Wang, Fangfang and
            Dong, Zhen and
            Dou, Zhiyang and
            Zhao, Liming and
            Zeng, Yan and
            Zhang, Jianwei and
            Zhou, Daquan},
  year = {2026},
  eprint = {2611.16748},
  archivePrefix = {arXiv},
  primaryClass = {cs.CV},
  url = {https://arxiv.org/abs/2611.16748}
}
```

## License

Original project code uses the MIT license. Third-party components retain their upstream licenses.
