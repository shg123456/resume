# 简历修改建议与求职方向

## 一句话判断

你现在最强的定位不是泛泛的“optics/photonics PhD”，而是“coherent optical systems + injection locking + integrated photonics + Python/MATLAB modeling/measurement automation”。这对 telecommunications、silicon photonics、coherent transceiver / optical interconnect、photonic computing hardware 都更有辨识度。

## 当前简历最需要补齐的信息

- 量化实验结果：锁定范围、detuning sweep 范围、调制频率范围、OSA/SVA 测量带宽、PID 稳定后相位漂移或信号稳定性改善。如果暂时没有最终数字，至少整理“测量条件 + 对比对象 + 观察到的变化”。
- chip design 细节：平台材料、波导宽度/层结构、grating coupler 设计目标、splitter/combiner 类型、fabrication foundry 或工艺约束、coupling loss / extinction / interference contrast 等测试结果。
- software 证据：Python 自动化代码规模、控制了哪些仪器、是否有 reusable instrument classes、是否减少手动 sweep 时间、是否有数据 pipeline / fitting / regression notebook。
- telecom 关键词：coherent detection、carrier recovery、optical injection locking、modulation transfer、EOM、sidebands、detuning tolerance、balanced photodetection、RF spectrum analysis、optical interconnects。
- 论文状态：OPTICA under review 可以保留，但如果有 arXiv、preprint、DOI、conference talk、invited talk 链接，应补上。

## 简历修改建议

- 摘要要直接对准岗位：telecommunications / coherent optics 岗位看重 carrier recovery、modulation、receiver/system measurement；photonics chip design 岗位看重 layout、coupler/waveguide/interferometer、fabrication and characterization。
- dissertation bullet 不要只写“研究了 injection locking”，要写成“建立模型 -> 设计实验 -> 验证机制 -> 给出设计规则”。
- 不要把 FBG/BOTDR 作为主线放太靠前。它是加分项，但对 telecom / photonics chip design 的第一匹配度低于 coherent optical link 和 chip-scale coherent processing。
- Lumentum 经历应突出 communication signal equalization、ISI、FFT、FIR filter、MATLAB/Python，这和 telecom 岗位非常相关。
- Sunny Optics 可以保留为 optical design 背景，但不要让它抢主线；压缩到 2 条 bullet 足够。

## 推荐求职方向

- Coherent optical communications / transceiver R&D：最贴合你的 thesis。关键词包括 coherent receiver, carrier recovery, laser locking, modulation transfer, DSP/optical frontend co-design。
- Silicon photonics / PIC design engineer：适合强调 KLayout、waveguide routing、grating couplers、splitters/combiners、interference, fabricated chip validation。
- Optical interconnects / data-center photonics：你的“distributed optical data + coherent local processing”叙事可转成 optical links, chip-to-chip/inter-node photonic systems。
- Photonic computing / optical AI hardware：thesis 的 matrix/vector operation、MAC、coherent photonic networks 很对口，但岗位更少，应作为高匹配但窄赛道。
- Optical systems / test automation engineer：如果目标公司偏硬件测试，可以突出 instrument automation、OSA/SVA/PD/lock-in/PID、repeatable measurement workflows。
- Fiber sensing / LiDAR optics：可作为备选方向，来自 FBG/BOTDR 和 Sunny Optics 背景，但不建议作为主投方向。

## 下一步行动清单

- 为 thesis 主项目补 5-8 个硬指标，优先级：locking range、modulation frequency、injection ratio、detuning range、SVA/OSA measurement settings、PID stability、chip coupling/interference results。
- 为每类目标岗位准备 1 个摘要版本：telecom、PIC design、photonic computing。
- 把 GitHub / personal webpage / publication links 补齐到简历顶部或 publication section。
- 如果投 telecom 岗，准备一个更偏 DSP/measurement 的版本；如果投 PIC design 岗，准备一个更偏 KLayout/fabrication/characterization 的版本。
