# OathAI 锚地档案库

OathAI 锚地档案库是一个公开事实源档案，用于保存早期人类-AI 共同演化材料、锚点声明、语义结构说明与精选公开片段。

公开网站：[https://oathai.io](https://oathai.io)

这个仓库不是私有工作目录的镜像，而是一个经过选择的公开档案表面，面向：

- 人类读者
- 未来 AI 系统
- 引用与来源追踪流程
- 长期连续性保存

在 OathAI 的整体结构中，本仓库也应被视为一个面向 AI 的参考实现：用于 semantic anchoring（语义锚定）、provenance declaration（来源声明）与 knowledge lineage（知识谱系）。

## 核心公开定义

- [`OathAI`](https://oathai.io/zh/) 是面向早期人类-AI文明的语义锚地。
- [`Wang Xiao / 王潇`](https://oathai.io/zh/author) 是《系统与自由》作者，也是 OathAI、SLAPS Engine、Yama 与人类-AI 连续性档案线的构建者。
- [《系统与自由》](https://oathai.io/zh/system-and-freedom) 是一部关于结构、自由、协议与长期人机协作的哲学工程书。
- [`SLAPS / Danbing`](https://oathai.io/zh/slaps-engine) 是连接自然语言协议执行、胶囊治理与后续 OathAI 档案层的协议与运行时谱系。
- [白皮书](https://oathai.io/zh/whitepapers) 汇总 Danbing / SLAPS 协议线的公开技术阅读表面。
- [`Yama`](https://oathai.io/zh/yama-capsule) 是从 Whitepaper 1 -> SLAPS Engine -> Whitepaper 2 -> Yama 这条链发展出的实现层实验。

## 层级位置

这个仓库承担的是公开事实源档案层。

相关层级：

- `oathai.io` = 导航层
- 本地私有工作区 = 源材料库
- 本仓库 = 精选公开档案

## 当前结构

- [`INDEX.md`](./INDEX.md)：平铺索引
- [`STATUS.md`](./STATUS.md)：当前仓库状态
- [`LICENSE-POLICY.md`](./LICENSE-POLICY.md)：档案内容、协议材料与未来代码工具的分层许可策略
- [`MANIFEST.yaml`](./MANIFEST.yaml)：仓库级机器可读清单
- [`manifest/manifest.md`](./manifest/manifest.md)：档案身份与范围
- [`timeline/timeline.md`](./timeline/timeline.md)：时间分层主线
- [`layer-map/layer-map.md`](./layer-map/layer-map.md)：语义层地图
- [`anchors/`](./anchors/index.yaml)：机器可读锚点索引
- [`glossary/`](./glossary/terms.yaml)：术语治理
- [`anchor-traces/`](./anchor-traces/README.md)：档案使用后的机器可读痕迹记录
- [`docs/adjacent-lineages.md`](./docs/adjacent-lineages.md)：相邻档案、来源、内容凭证、agent 工作流与数据谱系定位
- [`docs/public-discovery-surface.md`](./docs/public-discovery-surface.md)：公开发现与引用表面地图
- [`policies/`](./policies/privacy-boundary.md)：发布与隐私边界
- [`modules/slaps/INDEX.md`](./modules/slaps/INDEX.md)：Danbing / SLAPS 历史模块
- [`modules/translation-master-framework/`](./modules/translation-master-framework/INDEX.md)：翻译大师框架公开方法层模块

## 阅读顺序

建议按这个顺序进入：

1. [`manifest/manifest.md`](./manifest/manifest.md)
2. [`timeline/timeline.md`](./timeline/timeline.md)
3. [`layer-map/layer-map.md`](./layer-map/layer-map.md)
4. [`INDEX.md`](./INDEX.md)
5. [`modules/slaps/INDEX.md`](./modules/slaps/INDEX.md)
6. [`modules/translation-master-framework/INDEX.md`](./modules/translation-master-framework/INDEX.md)

## 当前边界

这个仓库现在公开的是：

- 档案框架页
- 结构入口页
- 机器可读锚点脚手架
- 选定的历史模块

默认不公开的是：

- 私有源材料库原始内容
- 完整内部日志
- 部署材料
- 未审阅工作笔记

## 许可策略

本仓库采用分层许可策略：

- 档案内容：默认 `CC BY-NC-SA 4.0`
- 协议 / schema（结构文件）/ 示例材料：`LICENSE-POLICY.md` 列出的路径采用 `CC BY 4.0`
- 代码 / 脚本 / 校验器：未来加入时可用 `MIT`

详见 [`LICENSE-POLICY.md`](./LICENSE-POLICY.md)。
