# 磁矩调控钠离子电池层状正极晶格氧氧化还原
### Spin Magnetic Moment Regulation of Lattice Oxygen Redox in Sodium-Ion Layered Oxide Cathodes

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Online%20Review-0f5c73?style=flat-square&logo=github)](https://zhr2271854800.github.io/time/)
[![Field](https://img.shields.io/badge/Field-Solid%20State%20Chemistry%20%7C%20Battery%20Science-b4552d?style=flat-square)]()
[![Papers](https://img.shields.io/badge/Reviews-2%20Interactive%20Editions-8b1e3f?style=flat-square)]()

---

## 📖 在线阅读与两篇综述直达入口

本仓库包含**两篇针对钠电正极磁矩与晶格氧氧化还原的深度前沿综述**（均已部署在线交互版，顶部附带一键无缝切换导航条）：

| 综述报告 | 特色与重点 | 🌐 在线交互阅读链接 (GitHub Pages) | 📄 本地 HTML 链接 |
|---|---|---|---|
| **篇一：《磁矩调控在钠离子电池层状氧化物正极氧（阴离子）氧化还原中的研究进展——调研综述》** | 全彩自适应版式、内嵌高清 SVG 矢量晶体场与轨道能级图、双栏交互目录 | 👉 **[在线阅读（篇一·矢量图版）](https://zhr2271854800.github.io/time/index.html)** | [`磁矩调控钠电正极层氧综述.html`](./磁矩调控钠电正极层氧综述.html) |
| **篇二：《磁矩调控钠离子电池层状正极晶格氧氧化还原：机理、策略与展望》** | 侧重电子结构物理本质、Goodenough 规则、超交换与铁电/磁电界面协同 | 👉 **[在线阅读（篇二·理论深度版）](https://zhr2271854800.github.io/time/outlook.html)** | [`磁矩调控钠电正极层氧调研综述.html`](./磁矩调控钠电正极层氧调研综述.html) |

> 📝 **纯文本源稿**：[`磁矩调控钠电正极层氧调研综述.md`](./磁矩调控钠电正极层氧调研综述.md)（含完整参考文献列表）

---

## 🔬 核心科学背景与立论依据

在钠离子电池（SIB）层状过渡金属氧化物（$\mathrm{Na}_x\mathrm{TMO}_2$）中，依赖过渡金属（$3d$）阳离子氧化还原的容量正逼近理论瓶颈。激活**晶格氧氧化还原（Lattice Oxygen Redox, LOR）**是实现能量密度跨越的关键，但往往伴随氧空穴过度局域化、$\mathrm{O}-\mathrm{O}$ 二聚化、氧气不可逆析出以及过渡金属迁移导致的严重电压滞后与结构坍塌。

**本课题的核心突破口在于引入“局域磁矩与自旋态”作为调控层氧活性与稳定性的电子结构抓手：**

```
                 八面体配位场 (Oh)
             TM 3d 电子构型 (HS / LS)
                        │
                        ▼
            TM 3d 与 O 2p 轨道杂化程度
                        │
                        ▼
      局域磁矩 μ ◄──────────────► 氧配体空穴 (Ligand Hole L)
(SQUID / EPR / Compton)           (mRIXS / XAS)
                        │
                        ▼
       超交换作用抑制不可逆 O-O 二聚与结构相变
```

### 1. 物理图像：把“磁”作为氧空穴的定量探针
孤立 $\mathrm{O}^{2-}$ 离子为闭壳层 $2p^6$，磁矩为零。当晶格氧失电子参与电荷补偿时形成配体空穴（$\underline{L}$），产生未配对自旋和局域磁矩。磁 Compton 散射与中子衍射已证实充电态下氧位存在约 $0.2\,\mu_\mathrm{B}/\mathrm{O}$ 的感生磁矩，这表明**层氧氧化还原在自旋空间留下明确的磁指纹**。

### 2. 过渡金属自旋态对氧骨架的锚定机制
八面体晶体场中 $t_{2g}$ 与 $e_g$ 轨道的占据方式决定了过渡金属的自旋态（高自旋 HS / 低自旋 LS / 中自旋 IS）：
* **$\mathrm{Fe}^{3+}/\mathrm{Fe}^{4+}$ 介导**：$\mathrm{Fe}^{4+}$（$t_{2g}^3 e_g^1$）具有强 Jahn-Teller 效应并与 $\mathrm{O}\;2p$ 强烈杂化，充当“电子缓冲带”，显著抑制不可逆氧释放；
* **$\mathrm{Mn}^{3+}/\mathrm{Mn}^{4+}$ 骨架**：利用反铁磁超交换作用（Superexchange）钉扎氧空穴，调控层间滑移势垒；
* **高自旋态 vs 低自旋态工程**：通过诱导自旋态跃迁调节 TM–O 共价键比例，平滑相变动力学。

---

## 📁 仓库目录结构

```text
C:\Users\Administrator\time\
├── index.html                     # 网页展示主入口（默认呈现篇一·矢量图版）
├── review.html                    # 篇一英文直达别名
├── 磁矩调控钠电正极层氧综述.html     # 篇一独立交互单文件 (68 KB，含矢量图)
├── outlook.html                   # 篇二英文直达别名
├── 磁矩调控钠电正极层氧调研综述.html # 篇二独立交互单文件 (51 KB，理论深度版)
├── 磁矩调控钠电正极层氧调研综述.md   # 综述 Markdown 纯文本规范源稿
├── README.md                      # 本学术项目索引与理论框架说明
├── .nojekyll                      # 保证 GitHub Pages 静态直出
└── .gitignore                     # Git 忽略配置
```

---

## 🛠️ 本地运行与浏览

1. **直接双击浏览器打开**：
   在 Windows 资源管理器中双击打开任意 `.html` 文件即可立即离线精读。
2. **在线直接阅读**：
   访问部署好的站点：👉 **[https://zhr2271854800.github.io/time/](https://zhr2271854800.github.io/time/)**
