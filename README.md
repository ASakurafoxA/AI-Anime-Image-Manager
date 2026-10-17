# AI Anime Image Manager（本地版 · 已冻结）

> **一句话**：本地动漫图库管理器：自动打 Danbooru 标签、标签中文化、以图搜图、回收站；全部本地运行、不上传图片。
>
> 基于上游 [Uyoung666/ai-image-manager](https://github.com/Uyoung666/ai-image-manager) v2.2.3（MIT，© 2025 Luan Roger）的**个人自用修改版**。
>
> ⚠️ **本版已冻结**（2026-10-18 最后一次更新）。后续维护在 **WD** 与 **NEXT** 两个仓库。

## 三个版本怎么选

| 版本 | 打标模型 | 局域网/手机 | 状态 |
|---|---|---|---|
| **本地版**（本仓库） | WD14（在安装包里） | 无 | **已冻结** |
| WD（`AI-Anime-Image-Manager-WD`） | WD14（在安装包里） | **有** | 持续维护 |
| NEXT（`AI-Anime-Image-Manager-NEXT`） | PixAI Tagger v1.0（和 NEXT 安装包放同一处） | **有** | 持续维护 |

> 三个版本**语义搜索**都是中文 CLIP（在安装包里），**角色识别**都用 CCIP（外置模型，三版共用一份）。
>
> ⚠️ **文档里的速度/倍率都是本机实测**（RTX 4070 Ti SUPER，图库约 7.7 万张），**不代表所有电脑**，仅供参考。

## 怎么装（2 步）

1. **装本体**：双击 `AI Anime Image Manager-2.2.3-20261018.msi`（713 MB，WD14 模型已在包内），按向导走；
2. **打开**：开始菜单里的「AI Anime Image Manager」，先选一个图库文件夹。

> 角色识别想用的话，再放一次 CCIP 模型：见 [CCIP模型安装说明.md](CCIP模型安装说明.md)。

## 下载

| 内容 | 地址 |
|---|---|
| **安装包**（三个版本） | <https://pan.baidu.com/s/1jDBvv4tL9v5_BgYhRDJcGQ?pwd=6666> 提取码 `6666` |
| **CCIP 角色识别模型**（三版共用，339 MB，单独一份） | 见 [CCIP模型安装说明.md](CCIP模型安装说明.md) |

- 历史版本在 [Releases](https://github.com/ASakurafoxA/AI-Anime-Image-Manager/releases)（一版一个 tag，旧版不会被覆盖）。

## 更新了什么

见 [CHANGELOG.md](CHANGELOG.md)。功能细节见 [功能说明.md](功能说明.md)。

## 许可

本项目代码 **MIT**（见 [LICENSE](LICENSE)）；第三方模型许可见 [MODELS.md](MODELS.md)。
