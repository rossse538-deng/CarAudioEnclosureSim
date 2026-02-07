# Logic V27 - 车载中音逆向分析系统 (Midrange Enclosure Calculator)

## 项目简介 (Introduction)
这是一个基于声学物理模型开发的Web端计算工具，专为汽车音响改装设计。
很多倒模施工往往忽略了等效容积(Vas)对中音单元的影响，导致Qtc失控。本软件利用AI辅助编程，实现了对3D打印箱体、A柱倒模的声学逆向分析。

This tool calculates the optimal volume for 3D printed speaker enclosures in car audio applications.

## 核心功能 (Key Features)
1.  **Qtc 智能计算**：输入净容积与T/S参数，自动计算系统总品质因数。
2.  **填充系数仿真**：支持空箱、波浪棉、标准填充、高密填充四种模式的声学模拟。
3.  **材料刚性评估**：根据打印材料（PLA/ABS/ASA/碳纤维）评估箱体在大动态下的谐振风险。
4.  **DSP 策略建议**：基于物理谐振频率(Fc)给出安全的分频点建议。

## 解决的痛点
*   解决A柱倒模容积过小导致的声音发干、发紧。
*   解决低频轰头、下潜不足的物理匹配问题。
*   为3D打印音箱提供科学的壁厚与工艺指导。

## 在线使用
https://rossse538-deng.github.io/CarAudioEnclosureSim/
