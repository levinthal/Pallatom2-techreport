# README 上传说明

1. 将同目录的 `README.md` 和整个 `assets/` 文件夹一起放到 `levinthal/Pallatom2-techreport` 仓库根目录。保留文件夹名称和图片文件名，README 中的六张图使用相对路径引用。
2. 最终稿确定后，建议以 `Pallatom2_Technical_Report.pdf` 为固定文件名上传到仓库根目录。
3. 将 README 的 `Technical report` 状态行替换为下面这一行。相同文字也已放在 README 的隐藏注释中，方便操作。

```markdown
**Technical report:** [Read the full report](./Pallatom2_Technical_Report.pdf).
```

若最终文档采用其他名称或存放位置，修改链接中的相对路径即可。论文取得正式 DOI 或发表信息后，再更新 Citation。

内容依据：2026 年 11 月 6 日提供的 `Pallatom-Binder-Technical-Report-EN(2).pdf`。该版本标题含 “Navigating the De Novo Protein Universe”，对称组装总长上限为 2,000 个残基。

仓库当前文件列表未能通过本次网络访问核实；README 因而不依赖假定的现有目录，也未填写未经确认的文档下载链接、DOI、软件许可证或代码和权重发布入口。

## 配图来源

六组配图均来自本次提供的 `Pallatom-Binder-Technical-Report-EN(2).pdf`：

- `assets/all_atom_generation.png`：第 5 页 Fig. 1。
- `assets/symmetric_assemblies.png`：第 13 页 Fig. 7，包含 9 个案例。
- `assets/computational_benchmark.png`：第 16 页 Fig. 9a，计算筛选 benchmark。
- `assets/kd_distribution.png`：第 19 页 Fig. 12a，逐靶点 KD 采样点图和中位数。
- `assets/lowest_kd_comparison.png`：第 19 页 Fig. 12b，逐靶点最低 KD 与已发表方法的比较。
- `assets/experimental_binding.png`：第 19 页 Fig. 12c，保留完整十靶点结构与 BLI 面板。

图像从稿件直接提取或裁切，未重画分子结构与数据曲线。
