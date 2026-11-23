# 汉火大典 (Hanhuo Dadian)

中华古典文字、碑帖书法与古籍智能工具集。

## 子仓库（Submodules）

- **[`shizi`](https://github.com/hanhuo-org/shizi)**（`shizi/`）— **汉火识字（Hanfire Shizi Clean V10）**：覆盖甲骨文、西周金文、战国楚简、石鼓文/秦汉简帛、汉代玺印及历代碑帖书法的浏览器端离线古文字识别与完整训练工程（21.70 万多原型 INT8 向量库 + Rust-WASM + CenterNet 多字框选切字）。
- **[`niyin`](https://github.com/hanhuo-org/niyin)**（`niyin/`）— **汉火拟音（Hanfire Niyin v1.0）**：覆盖上古、中古（切韵）、近古（中原音韵）三代历史汉语拟音 TTS（ZipVoice + QAT INT8 + WebGPU/WASM 离线工作台）与唐调《诗经》/古文/辞赋男女双声部 44.1kHz 唱吟引擎。

## 克隆方式

```bash
# 方式一：仅克隆单个独立子仓库（推荐）
git clone https://github.com/hanhuo-org/shizi.git
git clone https://github.com/hanhuo-org/niyin.git

# 方式二：连同所有子仓库一起克隆
git clone --recursive https://github.com/hanhuo-org/hanhuo-dadian.git
```
