光伏Peformance ratio衰减情况分析<br>
=========
根据一个5.1kW小电站多年的运行数据(本数据来自于澳大利亚沙漠太阳能研究中心https://dkasolarcentre.com.au/source/alice-springs/dka-m5-b-phase)<br>
分析组件的实际发电功率并测算组件每年的pr衰减情况。<br>

使用库：<br>
采用光伏系统函数库pvlib(0.6.3)版本，以及rdtools(一个用于光伏系统退化分析的库,1.2.0版本)<br>
本项目中采用了rdtools的年度退化率计算，以此估计光伏pr年与年之间的衰减率<br>
pvlib使用功能如下：<br>
太阳位置计算，辐照度计算：估算全球水平辐照度、直接法向辐照度和散射辐照度。<br>
数据管理：处理和转换光伏系统数据。<br>

数据见：https://dkasolarcentre.com.au/source/alice-springs/dka-m5-b-phase)<br>
或者本仓库的main分支下的 DATA\84-Site_DKA-M5_B-Phase.csv<br>