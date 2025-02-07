# Literature on SRAM-based Compute-In-Memory
This repository serves as a comprehensive resource for the rapidly advancing field of SRAM-based Compute-In-Memory (CIM), particularly in the context of AI acceleration. It compiles a wide range of materials, including research papers, tools, and surveys, curated by our [team of Maintainers](#maintainers). We welcome and encourage contributions from the community.

The content is systematically categorized to provide a clear and structured overview:
- [Macro Level](#macro-level): Research on CIM macro designs.
- [Architecture Level](#architecture-level): Designs and optimizations of CIM accelerators.
- [Simulation Tools](#simulation-tools): Evaluation tools for CIM.
- [Software Stack](#software-stack): Software integration with CIM hardware.
- [Surveys and Analysis](#surveys-and-analysis): In-depth reviews and meta-studies in CIM research.

This curated collection aims to offer valuable insights into the integration of CIM technologies for AI, showcasing the latest advancements and methodologies in the field.

---
## Macro Level
* [**TVLSI 2025**] Reconfigurable 10T SRAM for Energy-Efficient CAM Operation and In-Memory Computing.  
  >*Zhang Zhang, Zhihao Chen, Jiedong Wang, Guangjun Xie, Gang Liu.* [[Paper]](https://doi.ieeecomputersociety.org/10.1109/TVLSI.2025.3526973)
* [**A-SSCC 2024**] A 65nm 687.5-TOPS/W Drive Strength-based SRAM Compute-In-Memory Macro with Adaptive Dynamic Range for Edge AI applications.  
  >*D.-G. Choi, et al.* [[Paper]](https://doi.org/10.1109/A-SSCC60305.2024.10848920)
* [**DAC 2024**] Digital CIM with Noisy SRAM Bit: A Compact Clustered Annealer for Large-Scale Combinatorial Optimization.
  >*Anni Lu, Junmo Lee, Yuan-Chun Luo, et al.* [[Paper]](https://doi.org/10.1145/3649329.3655673)
* [**DAC 2024**] Addition is Most You Need: Efficient Floating-Point SRAM Compute-in-Memory by Harnessing Mantissa Addition.
  >*Weidong Cao, Jian Gao, Xin Xin, et al.* [[Paper]](https://doi.org/10.1145/3649329.3655930)
* [**DAC 2024**] ModSRAM: Algorithm-Hardware Co-Design for Large Number Modular Multiplication in SRAM.
  >*Jonathan Hao-Cheng Ku, Junyao Zhang, Haoxuan Shan, et al.* [[Paper]](https://doi.org/10.1145/3649329.3656496)
* [**DAC 2024**] Energy-efficient SNN Architecture using 3nm FinFET Multiport SRAM-based CIM with Online Learning.
  >*Lucas Huijbregts, Hsiao-Hsuan Liu, Paul Detterer, et al.* [[Paper]](https://doi.org/10.1145/3649329.3656514)
* [**DAC 2024**] Improving the Efficiency of In-Memory-Computing Macro with a Hybrid Analog-Digital Computing Mode for Lossless Neural Network Inference.
  >*Qilin Zheng, Ziru Li, Jonathan Ku, et al.* [[Paper]](https://doi.org/10.1145/3649329.3658472)
* [**JSSC 2023**] MACC-SRAM: A Multistep Accumulation Capacitor-Coupling In-Memory Computing SRAM Macro for Deep Convolutional Neural Networks.
  >*Bo Zhang, Jyotishman Saikia, Jian Meng, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2023.3332017)
* [**CICC 2023**] A 65 nm 1.4-6.7 TOPS/W Adaptive-SNR Sparsity-Aware CIM Core with Load Balancing Support for DL workloads.
  >*Mustafa Fayez Ali,  Indranil Chakraborty,  Sakshi Choudhary, et al.* [[Paper]](https://doi.org/10.1109/CICC57935.2023.10121243)
* [**CICC 2023**] A Double-Mode Sparse Compute-In-Memory Macro with Reconfigurable Single and Dual Layer Computation.
  >*Yuanzhe Zhao,  Minglei Zhang,  Pengyu He, et al.* [[Paper]](https://doi.org/10.1109/CICC57935.2023.10121308)
* [**CICC 2023**] iMCU: A 102-μJ, 61-ms Digital In-Memory Computing-based Microcontroller Unit for Edge TinyML.
  >*Chuan-Tung Lin,  Paul Xuanyuanliang Huang,  Jonghyun Oh, et al.* [[Paper]](https://doi.org/10.1109/CICC57935.2023.10121221)
* [**ISSCC 7.1 2023**] A 22nm 832Kb Hybrid-Domain Floating-Point SRAM In-Memory-Compute Macro with 16.2-70.2TFLOPS/W for High-Accuracy AI-Edge Devices.
  >*Ping-Chun Wu,  Jian-Wei Su,  Li-Yang Hong, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067527)
* [**ISSCC 7.2 2023**] A 28nm 64-kb 31.6-TFLOPS/W Digital-Domain Floating-Point-Computing-Unit and Double-Bit 6T-SRAM Computing-in-Memory Macro for Floating-Point CNNs.
  >*An Guo,  Xin Si,  Xi Chen, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067260)
* [**ISSCC 7.3 2023**] A 28nm 38-to-102-TOPS/W 8b Multiply-Less Approximate Digital SRAM Compute-In-Memory Macro for Neural-Network Inference.
  >*Yifan He,  Haikang Diao,  Chen Tang, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067305)
* [**ISSCC 7.4 2023**] A 4nm 6163-TOPS/W/b $\mathbf{4790-TOPS/mm^{2}/b}$ SRAM Based Digital-Computing-in-Memory Macro Supporting Bit-Width Flexibility and Simultaneous MAC and Weight Update.
  >*Haruki Mori,  Wei-Chang Zhao,  Cheng-En Lee, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067555)
* [**ISSCC 7.5 2023**] A 28nm Horizontal-Weight-Shift and Vertical-feature-Shift-Based Separate-WL 6T-SRAM Computation-in-Memory Unit-Macro for Edge Depthwise Neural-Networks.
  >*Bo Wang,  Chen Xue,  Zhongyuan Feng, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067526)
* [**ISSCC 7.6 2023**] A 70.85-86.27TOPS/W PVT-Insensitive 8b Word-Wise ACIM with Post-Processing Relaxation.
  >*Sung-En Hsieh,  Chun-Hao Wei,  Cheng-Xin Xue, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067335)
* [**ISSCC 7.7 2023**] CV-CIM: A 28nm XOR-Derived Similarity-Aware Computation-in-Memory for Cost-Volume Construction.
  >*Zhiheng Yue,  Yang Wang,  Huizheng Wang, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067720)
* [**ISSCC 7.8 2023**] A 22nm Delta-Sigma Computing-In-Memory (Δ∑CIM) SRAM Macro with Near-Zero-Mean Outputs and LSB-First ADCs Achieving 21.38TOPS/W for 8b-MAC Edge AI Processing.
  >*Peiyu Chen,  Meng Wu,  Wentao Zhao, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067289)
* [**JSSC 2023**] A Charge Domain SRAM Compute-in-Memory Macro With C-2C Ladder-Based 8-Bit MAC Unit in 22-nm FinFET Process for Edge Inference.
  >*Hechen Wang,  Renzhi Liu, Richard Dorrance, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2022.3232601)
* [**JSSC 2023**] In Situ Storing 8T SRAM-CIM Macro for Full-Array Boolean Logic and Copy Operations.
  >*Zhiting Lin,  Zhongzhen Tong,  Fangming Wang, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2022.3206318)
* [**CICC 2022**] An area-efficient 6T-SRAM based Compute-In-Memory architecture with reconfigurable SAR ADCs for energy-efficient deep neural networks in edge ML applications.
  >*Avishek Biswas,  Hetul Sanghvi,  Mahesh Mehendale, et al.* [[Paper]](https://doi.org/10.1109/CICC53496.2022.9772789)
* [**CICC 2022**] 5GHz SRAM for High-Performance Compute Platform in 5nm CMOS.
  >*R. Mathur,  M. Kumar,  Vivek Asthana, et al.* [[Paper]](https://doi.org/10.1109/CICC53496.2022.9772840)
* [**DAC 2022**] CP-SRAM: Charge-Pulsation SRAM Marco for Ultra-High Energy-Efficiency Computing-in-Memory.
  >*He Zhang,  Linjun Jiang,  Jianxin Wu, et al.* [[Paper]](https://doi.org/10.1145/3489517.3530398)
* [**DAC 2022**] TAIM: ternary activation in-memory computing hardware with 6T SRAM array.
  >*Nameun Kang,  Hyungjun Kim,  Hyunmyung Oh, et al.* [[Paper]](https://doi.org/10.1145/3489517.3530574)
* [**ISSCC 11.6 2022**] A 5-nm 254-TOPS/W 221-TOPS/mm2 Fully-Digital Computing-in-Memory Macro Supporting Wide-Range Dynamic-Voltage-Frequency Scaling and Simultaneous MAC and Write Operations.
  >*Hidehiro Fujiwara,  Haruki Mori,  Wei-Chang Zhao, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42614.2022.9731754)
* [**ISSCC 11.7 2022**] A 1.041-Mb/mm2 27.38-TOPS/W Signed-INT8 Dynamic-Logic-Based ADC-less SRAM Compute-In-Memory Macro in 28nm with Reconfigurable Bitwise Operation for AI and Embedded Applications.
  >*Bonan Yan,  Jeng-Long Hsu,  Pang-Cheng Yu, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42614.2022.9731545)
* [**ISSCC 11.8 2022**] A 28nm 1Mb Time-Domain Computing-in-Memory 6T-SRAM Macro with a 6.6ns Latency, 1241GOPS and 37.01TOPS/W for 8b-MAC Operations for Edge-AI Devices.
  >*Ping-Chun Wu,  Jian-Wei Su,  Yen-Lin Chung, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42614.2022.9731681)
* [**JSSC 2022**] Two-Way Transpose Multibit 6T SRAM Computing-in-Memory Macro for Inference-Training AI Edge Chips.
  >*Jian-Wei Su, Xin Si, Yen-Chi Chou, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2021.3108344)
* [**VLSI 2022**] A 32.2 TOPS/W SRAM Compute-in-Memory Macro Employing a Linear 8-bit C-2C Ladder for Charge Domain Computation in 22nm for Edge Inference.
  >*Hechen Wang,  Renzhi Liu,  Richard Dorrance, et al.* [[Paper]](https://doi.org/10.1109/VLSITechnologyandCir46769.2022.9830322)
* [**VLSI C02-5 2022**] A 12nm 121-TOPS/W 41.6-TOPS/mm2 All Digital Full Precision SRAM-based Compute-in-Memory with Configurable Bit-width For AI Edge Applications.
  >*Chia-Fu Lee,  Cheng-Han Lu,  Cheng-En Lee, et al.* [[Paper]](https://doi.org/10.1109/VLSITechnologyandCir46769.2022.9830438)
* [**VLSI C04-2 2022**] Neuro-CIM: A 310.4 TOPS/W Neuromorphic Computing-in-Memory Processor with Low WL/BL activity and Digital-Analog Mixed-mode Neuron Firing.
  >*Sangyeob Kim,  Sangjin Kim,  Soyeon Um, et al.* [[Paper]](https://doi.org/10.1109/VLSITechnologyandCir46769.2022.9830276)
* [**CICC 2021**] A 128x128 SRAM Macro with Embedded Matrix-Vector Multiplication Exploiting Passive Gain via MOS Capacitor for Machine Learning Application.
  >*Rezwan A. Rasul, Mike Shuo-Wei Chen* [[Paper]](https://doi.org/10.1109/CICC51472.2021.9431485)
* [**CICC 2021**] An In-Memory-Computing Charge-Domain Ternary CNN Classifier.
  >*Xiangxing Yang,  Keren Zhu,  Xiyuan Tang, et al.* [[Paper]](https://doi.org/10.1109/CICC51472.2021.9431398)
* [**DAC 2021**] A Charge-Sharing based 8T SRAM In-Memory Computing for Edge DNN Acceleration.
  >*Kyeongho Lee,  Sungsoo Cheon,  Joongho Jo, et al.* [[Paper]](https://doi.org/10.1109/DAC18074.2021.9586103)
* [**ISSCC 16.3 2021**] A 28nm 384kb 6T-SRAM Computation-in-Memory Macro with 8b of Precision for AI Edge Chips.
  >*Jian-Wei Su,  Yen-Chi Chou,  Ruhui Liu, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42613.2021.9365984)
* [**ISSCC 16.4 2021**] An 89TOPS/W and 16.3TOPS/mm2 All-Digital SRAM-Based Full-Precision Compute-In Memory Macro
in 22nm for Machine-Learning Edge Applications.
  >*Yu-Der Chih,  Po-Hao Lee,  Hidehiro Fujiwara, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42613.2021.9365766)
* [**ISSCC, 16.1 2021**] DIMC: 2219TOPS/W 2569F2/b Digital In-Memory Computing Macro in 28nm Based on Approximate Arithmetic Hardware.
  >*Dewei Wang,  Chuan-Tung Lin,  Gregory K. Chen, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42614.2022.9731659)
* [**JSSC 2021**] Two-Direction In-Memory Computing Based on 10T SRAM With Horizontal and Vertical Decoupled Read Ports.
  >*Zhiting Lin,  Zhiyong Zhu,  Honglan Zhan, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2021.3061260)
* [**JSSC 2021**] A Local Computing Cell and 6T SRAM-Based Computing-in-Memory Macro With 8-b MAC Operation for Edge AI Chips.
  >*Xin Si,  Yung-Ning Tu,  Wei-Hsing Huang, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2021.3073254)
* [**JSSC 2021**] A 7-nm Compute-in-Memory SRAM Macro Supporting Multi-Bit Input, Weight and Output and Achieving 351 TOPS/W and 372.4 GOPS.
  >*Mahmut E. Sinangil,  Burak Erbagci,  Rawan Naous, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2020.3031290)
* [**JSSC 2021**] Colonnade: A Reconfigurable SRAM-Based Digital Bit-Serial Compute-In-Memory Macro for Processing Neural Networks.
  >*Hyunjoon Kim,  Taegeun Yoo,  Tony Tae-Hyoung Kim, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2021.3061508)
* [**JSSC 2021**] Cascade Current Mirror to Improve Linearity and Consistency in SRAM In-Memory Computing.
  >*Zhiting Lin,  Honglan Zhan,  Zhongwei Chen, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2021.3063719)
* [**JSSC 2021**] ±CIM SRAM for Signed In-Memory Broad-Purpose Computing From DSP to Neural Processing.
  >*Saurabh Jain, Longyang Lin, and Massimo Alioto* [[Paper]](https://doi.org/10.1109/JSSC.2021.3092759)
* [**JSSC 2021**] CAP-RAM: A Charge-Domain In-Memory Computing 6T-SRAM for Accurate and Precision-Programmable CNN Inference.
  >*Zhiyu Chen,  Zhanghao Yu,  Qing Jin, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2021.3056447)
* [**VLSI JFS2-5 2021**] HERMES Core – A 14nm CMOS and PCM-based In-Memory Compute Core using an array of 300ps/LSB Linearized CCO-based ADCs and local digital processing.
  >*Riduan Khaddam-Aljameh,  Milos Stanisavljevic,  Jordi Fornt Mas, et al.* [[Paper]](https://doi.org/10.23919/VLSICircuits52068.2021.9492362)
* [**VLSI JFS2-6 2021**] A 20x28 Spins Hybrid In-Memory Annealing Computer Featuring Voltage-Mode Analog Spin Operator for Solving Combinatorial Optimization Problems.
  >*Junjie Mu, Yuqi Su, Bongjin Kim* [[Paper]](https://doi.org/10.23919/VLSICircuits52068.2021.9492453)
* [**CICC 2020**] A 16K Current-Based 8T SRAM Compute-In-Memory Macro with Decoupled Read/Write and 1-5bit Column ADC.
  >*Chengshuo Yu,  Taegeun Yoo,  Tony Tae-Hyoung Kim, et al.* [[Paper]](https://doi.org/10.1109/CICC48029.2020.9075883)
* [**DAC 2020**] Bit Parallel 6T SRAM In-memory Computing with Reconfigurable Bit-Precision.
  >*Kyeongho Lee,  Jinho Jeong,  Sungsoo Cheon, et al.* [[Paper]](https://doi.org/10.1109/DAC18072.2020.9218567)
* [**DAC 2020**] A Two-way SRAM Array based Accelerator for Deep Neural Network On-chip Training.
  >*Hongwu Jiang,  Shanshi Huang,  Xiaochen Peng, et al.* [[Paper]](https://doi.org/10.1109/DAC18072.2020.9218524)
* [**DATE 2020**] Robust and High-Performance 12-T Interlocked SRAM for In-Memory Computing.
  >*Neelam Surana, Mili Lavania, Abhishek Barma and Joycee Mekie* [[Paper]](https://doi.org/10.23919/DATE48585.2020.9116361)
* [**ICCAD 2020**] XOR-CIM: Compute-In-Memory SRAM Architecture with Embedded XOR Encryption.
  >*Shanshi Huang,  Hongwu Jiang,  Xiaochen Peng, et al.* [[Paper]](https://doi.org/10.1145/3400302.3415678)
* [**ICCAD 2020**] Energy-efficient XNOR-free In-Memory BNN Accelerator with Input Distribution Regularization.
  >*Hyungjun Kim, Hyunmyung Oh, Jae-Joon Kim* [[Paper]](https://doi.org/10.1145/3400302.3415641)
* [**ISSCC 15.2 2020**] A 28nm 64Kb Inference-Training Two-Way Transpose Multibit 6T SRAM Compute-in-Memory Macro for AI Edge Chips.
  >*Jian-Wei Su,  Xin Si,  Yen-Chi Chou, et al.* [[Paper]](https://doi.org/10.1109/ISSCC19947.2020.9062949)
* [**ISSCC 15.3 2020**] A 351TOPS/W and 372.4GOPS Compute-in-Memory SRAM Macro in 7nm FinFET CMOS for Machine-Learning
Applications.
  >*Qing Dong,  Mahmut E. Sinangil,  Burak Erbagci, et al.* [[Paper]](https://doi.org/10.1109/ISSCC19947.2020.9062985)
* [**ISSCC 15.5 2020**] A 28nm 64Kb 6T SRAM Computing-in-Memory Macro with 8b MAC Operation for AI Edge Chips.
  >*Xin Si,  Yung-Ning Tu,  Wei-Hsing Huang, et al.* [[Paper]](https://doi.org/10.1109/ISSCC19947.2020.9062995)
* [**ISSCC 31.2 2020**] CIM-Spin: A 0.5-to-1.2V Scalable Annealing Processor Using Digital Compute-In-Memory Spin Operators and Register-Based Spins for Combinatorial Optimization Problems.
  >*Yuqi Su, Hyunjoon Kim, Bongjin Kim* [[Paper]](https://doi.org/10.1109/ISSCC19947.2020.9062938)
* [**JSSC 2020**] A 4-Kb 1-to-8-bit Configurable 6T SRAM-Based Computation-in-Memory Unit-Macro for CNN-Based AI Edge Processors.
  >*Yen-Cheng Chiu,  Zhixiao Zhang,  Jia-Jing Chen, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2020.3005754)
* [**JSSC 2020**] C3SRAM: An In-Memory-Computing SRAM Macro Based on Robust Capacitive Coupling Computing Mechanism.
  >*Zhewei Jiang,  Shihui Yin,  Jae-Sun Seo, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2020.2992886)
* [**JSSC 2020**] A Twin-8T SRAM Computation-in-Memory Unit-Macro for Multibit CNN-Based AI Edge Processors.
  >*Xin Si,  Jia-Jing Chen,  Yung-Ning Tu, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2019.2952773)
* [**JSSC 2020**] A 28-nm Compute SRAM With Bit-Serial Logic/Arithmetic Operations for Programmable In-Memory Vector Computing.
  >*Jingcheng Wang,  Xiaowei Wang,  Charles Eckert, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2019.2939682)
* [**JSSC 2020**] XNOR-SRAM: In-Memory Computing SRAM Macro for Binary/Ternary Deep Neural Networks.
  >*Shihui Yin,  Zhewei Jiang,  Jae-Sun Seo, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2019.2963616)
* [**VLSI 2020**] Z-PIM: An Energy-Efficient Sparsity-Aware Processing-In-Memory Architecture with Fully-Variable Weight Precision.
  >*Ji-Hoon Kim,  Juhyoung Lee,  Jinsu Lee, et al.* [[Paper]](https://doi.org/10.1109/VLSICircuits18222.2020.9163015)
* [**JSSC 2019**] CONV-SRAM: An Energy-Efficient SRAM With In-Memory Dot-Product Computation for Low-Power Convolutional Neural Networks.
  >*Avishek Biswas, and Anantha P. Chandrakasan* [[Paper]](https://doi.org/10.1109/JSSC.2018.2880918)

---
## Architecture Level
* [**TVLSI 2025**] SysCIM: A Heterogeneous Chip Architecture for High-Efficiency CNN Training at Edge.  
  >*Shuai Wang, Ziwei Li, Yuang Ma, Yi Kang.* [[Paper]](https://doi.org/10.1109/TVLSI.2025.3526363)
* [**DAC 2024**] CAP: A General Purpose Computation-in-memory with Content Addressable Processing Paradigm.
  >*Zhiheng Yue, Shaojun Wei, Yang Hu, et al.* [[Paper]](https://doi.org/10.1145/3649329.3655689)
* [**DAC 2024**] Dyn-Bitpool: A Two-sided Sparse CIM Accelerator Featuring a Balanced Workload Scheme and High CIM Macro Utilization.
  >*Xujiang Xiang, Zhiheng Yue, Yuxuan Li, et al.* [[Paper]](https://doi.org/10.1145/3649329.3655690)
* [**DAC 2024**] FDCA: Fine-grained Digital-CIM based CNN Accelerator with Hybrid Quantization and Weight-Stationary Dataflow.
  >*Bo Liu, Qingwen Wei, Yang Zhang, et al.* [[Paper]](https://doi.org/10.1145/3649329.3656253)
* [**DAC 2024**] AIG-CIM: A Scalable Chiplet Module with Tri-Gear Heterogeneous Compute-in-Memory for Diffusion Acceleration.
  >*Yiqi Jing, Meng Wu, Jiaqi Zhou, et al.* [[Paper]](https://doi.org/10.1145/3649329.3657373)
* [**DAC 2024**] Towards Efficient SRAM-PIM Architecture Design by Exploiting Unstructured Bit-Level Sparsity.
  >*Duan, Cenlin, Jianlei Yang, Yiou Wang, et al.* [[Paper]](https://arxiv.org/abs/2404.09497)
* [**DAC 2024**] Hyb-Learn: A Framework for On-Device Self-Supervised Continual Learning with Hybrid RRAM/SRAM Memory.
  >*Fan Zhang, Li Yang, Deliang Fan* [[Paper]](https://doi.org/10.1145/3649329.3657389)
* [**DAC 2024**] Efficient Memory Integration: MRAM-SRAM Hybrid Accelerator for Sparse On-Device Learning.
  >*Fan Zhang, Amitesh Sridharan, Wilman Tsai, et al.* [[Paper]](https://doi.org/10.1145/3649329.3657390)
* [**DAC 2024**] An In-Memory Computing Accelerator with Reconfigurable Dataflow for Multi-Scale Vision Transformer with Hybrid Topology.
  >*Zhiyuan Chen, Yufei Ma, Keyi Li, et al.* [[Paper]](https://doi.org/10.1145/3649329.3658244)
* [**DAC 2024**] HEIRS: Hybrid Three-Dimension RRAM- and SRAM-CIM Architecture for Multi-task Transformer Acceleration.
  >*Liukai Xu, Shuai Yuan, Dengfeng Wang, et al.* [[Paper]](https://doi.org/10.1145/3649329.3657327)
* [**DATE 2024**] CiMComp: An Energy Efficient Compute-in-Memory Based Comparator for Convolutional Neural Networks.
  >*Kavitha S, Binsu J Kailath, B. S. Reniwal* [[Paper]](https://doi.org/10.23919/DATE58400.2024.10546864)
* [**DATE 2024**] H3DFact: Heterogeneous 3D Integrated CIM for Factorization with Holographic Perceptual Representations.
  >*Zishen Wan, Che-Kai Liu, Mohamed Ibrahim, et al.* [[Paper]](https://doi.org/10.23919/DATE58400.2024.10546582)
* [**DATE 2024**] AdaP-CIM: Compute-in-Memory Based Neural Network Accelerator Using Adaptive Posit.
  >*Jingyu He, Fengbin Tu, Kwang-Ting Cheng, et al.* [[Paper]](https://doi.org/10.23919/DATE58400.2024.10546569)
* [**DATE 2024**] DAISM: Digital Approximate In-SRAM Multiplier-Based Accelerator for DNN Training and Inference.
  >*L. Sonnino, S. Shresthamali, Y. He, et al.* [[Paper]](https://doi.org/10.23919/DATE58400.2024.10546578)
* [**TCAS-I 2024**] DCIM-GCN: Digital Computing-in-Memory Accelerator for Graph Convolutional Network.
  >*Ma, Yufei, Yikan Qiu, Wentao Zhao, et al.* [[Paper]](https://ieeexplore.ieee.org/abstract/document/10500021)
* [**DAC 2023**] BP-NTT: Fast and Compact in-SRAM Number Theoretic Transform with Bit-Parallel Modular Multiplication.
  >*Jingyao Zhang, Mohsen Imani, Elaheh Sadredini* [[Paper]](https://doi.org/10.48550/arXiv.2303.00173)
* [**DAC 2023**] Morphable CIM: Improving Operation Intensity and Depthwise Capability for SRAM-CIM Architecture.
  >*Yun-Chen Lo, Ren-Shuo Liu* [[Paper]](https://doi.org/10.1109/DAC56929.2023.10247750)
* [**DATE 2023**] Process Variation Resilient Current-Domain Analog In Memory Computing.
  >*Kailash Prasad,  Sai Shubham,  Aditya Biswas, et al.* [[Paper]](https://doi.org/10.23919/DATE56975.2023.10137088)
* [**DATE 2023**] PIC-RAM: Process-Invariant Capacitive Multiplier Based Analog In Memory Computing in 6T SRAM.
  >*Kailash Prasad,  Aditya Biswas,  Arpita Kabra, et al.* [[Paper]](https://doi.org/10.23919/DATE56975.2023.10137338)
* [**HPCA 2023**] EVE: Ephemeral Vector Engines.
  >*Khalid Al-Hawaj,  Tuan Ta,  Nick Cebry, et al.* [[Paper]](https://doi.org/10.1109/HPCA56546.2023.10071074)
* [**HPCA 2023**] Dalorex: A Data-Local Program Execution and Architecture for Memory-bound Applications.
  >*Marcelo Orenes-Vera,  Esin Tureci,  David Wentzlaff, et al.* [[Paper]](https://doi.org/10.1109/HPCA56546.2023.10071089)
* [**ISSCC 16.1  2023**] MuITCIM: A 28nm $2.24 \mu\mathrm{J}$/Token Attention-Token-Bit Hybrid Sparse Digital CIM-Based Accelerator for Multimodal Transformers.
  >*Fengbin Tu,  Zihan Wu,  Yiqi Wang, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067842)
* [**ISSCC 16.2  2023**] A 28nm 53.8TOPS/W 8b Sparse Transformer Accelerator with In-Memory Butterfly Zero Skipper for Unstructured-Pruned NN and CIM-Based Local-Attention-Reusable Engine.
  >*Shiwei Liu,  Peizhe Li,  Jinshan Zhang, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067360)
* [**ISSCC 16.3  2023**] A 28nm 16.9-300TOPS/W Computing-in-Memory Processor Supporting Floating-Point NN Inference/Training with Intensive-CIM Sparse-Digital Architecture.
  >*Jinshan Yue,  Chaojie He,  Zi Wang, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067779)
* [**ISSCC 16.4  2023**] TensorCIM: A 28nm 3.7nJ/Gather and 8.3TFLOPS/W FP32 Digital-CIM Tensor Processor for MCM-CIM-Based Beyond-NN Acceleration.
  >*Fengbin Tu,  Yiqi Wang,  Zihan Wu, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067285)
* [**ISSCC 16.7 2023**] A 40-310TOPS/W SRAM-Based All-Digital Up to 4b In-Memory Computing Multi-Tiled NN Accelerator in FD-SOI 18nm for Deep-Learning Edge Applications.
  >*Giuseppe Desoli,  Nitin Chawla,  Thomas Boesch, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42615.2023.10067422)
* [**JSSC 2023**] ReDCIM: Reconfigurable Digital Computing- In -Memory Processor With Unified FP/INT Pipeline for Cloud AI Acceleration.
  >*Fengbin Tu,  Yiqi Wang,  Zihan Wu, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2022.3222059)
* [**JSSC 2023**] TT@CIM: A Tensor-Train In-Memory-Computing Processor Using Bit-Level-Sparsity Optimization and Variable Precision Quantization.
  >*Guo,  Ruiqi and Yue,  Zhiheng and Si, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2022.3198413)
* [**JSSC 2023**] PIMCA: A Programmable In-Memory Computing Accelerator for Energy-Efficient DNN Inference.
  >*Bo Zhang,  Shihui Yin,  Minkyu Kim, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2022.3211290)
* [**JSSC 2023**] An In-Memory-Computing Charge-Domain Ternary CNN Classifier.
  >*Xiangxing Yang, Keren Zhu, Xiyuan Tang, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2023.3238725)
* [**JSSC 2023**] TranCIM: Full-Digital Bitline-Transpose CIM-based Sparse Transformer Accelerator With Pipeline/Parallel Reconfigurable Modes.
  >*Fengbin Tu,  Zihan Wu,  Yiqi Wang, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2022.3213542)
* [**JSSC 2023**] IMPACT: A 1-to-4b 813-TOPS/W 22-nm FD-SOI Compute-in-Memory CNN Accelerator Featuring a 4.2-POPS/W 146-TOPS/mm2 CIM-SRAM With Multi-Bit Analog Batch-Normalization.
  >*Adrian Kneip,  Martin Lefebvre,  Julien Verecken, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2023.3269098)
* [**MICRO 2023**] MVC: Enabling Fully Coherent Multi-Data-Views through the
Memory Hierarchy with Processing in Memory.
  >*Daichi Fujiki* [[Paper]](https://doi.org/10.1145/3613424.3623784)
* [**MICRO 2023**] MAICC : A Lightweight Many-core Architecture with In-Cache Computing for Multi-DNN Parallel Inference.
  >*Renhao Fan,  Yikai Cui,  Qilin Chen, et al.* [[Paper]](https://doi.org/10.1145/3613424.3614268)
* [**TC 2023**] Eidetic: An In-Memory Matrix Multiplication Accelerator for Neural Networks.
  >*Charles Eckert,  Arun Subramaniyan,  Xiaowei Wang, et al.* [[Paper]](https://doi.org/10.1109/TC.2022.3214151)
* [**TC 2023**] An Area-Efficient In-Memory Implementation Method of Arbitrary Boolean Function Based on SRAM Array.
  >*Sunrui Zhang,  Xiaole Cui,  Feng Wei, et al.* [[Paper]](https://doi.org/10.1109/TC.2023.3301156)
* [**TCAD 2023**] SDP: Co-Designing Algorithm, Dataflow, and Architecture for in-SRAM Sparse NN Acceleration.
  >*Fengbin Tu,  Yiqi Wang,  Ling Liang, et al.* [[Paper]](https://doi.org/10.1109/TCAD.2022.3172600)
* [**TCAD 2023**] Dedicated Instruction Set for Pattern-Based Data Transfers: An Experimental Validation on Systems Containing In-Memory Computing Units.
  >*Kevin Mambu, Henri-Pierre Charles, and Maha Kooli* [[Paper]](https://doi.org/10.1109/TCAD.2023.3258346)
* [**TCAS-I 2023**] SPCIM: Sparsity-Balanced Practical CIM Accelerator With Optimized Spatial-Temporal Multi-Macro Utilization.
  >*Yiqi Wang,  Fengbin Tu,  Leibo Liu, et al.* [[Paper]](https://doi.org/10.1109/TCSI.2022.3216735)
* [**TCAS-I 2023**] ARBiS: A Hardware-Efficient SRAM CIM CNN Accelerator With Cyclic-Shift Weight Duplication
and Parasitic-Capacitance Charge Sharing for AI Edge Application.
  >*Chenyang Zhao,  Jinbei Fang,  Jingwen Jiang, et al.* [[Paper]](https://doi.org/10.1109/TCSI.2022.3215535)
* [**TCAS-I 2023**] MC-CIM: Compute-in-Memory With Monte-Carlo Dropouts for Bayesian Edge Intelligence.
  >*Priyesh Shukla, Shamma Nasrin,  Nastaran Darabi, et al.* [[Paper]](https://doi.org/10.1109/TCSI.2022.3224703)
* [**TCAS-I 2023**] An 82-nW 0.53-pJ/SOP Clock-Free Spiking Neural Network With 40-µs Latency for AIoT Wake-Up Functions Using a Multilevel-Event-Driven Bionic Architecture and Computing-in-Memory Technique.
  >*Ying Liu,  Yufei Ma,  Wei He, et al.* [[Paper]](https://doi.org/10.1109/TCSI.2023.3275387)
* [**TCAS-I 2023**] TDPRO: Time-Domain-Based Computing-in Memory Engine for Ultra-Low Power ECG Processor.
  >*Liang Chang,  Siqi Yang,  Zhiyuan Chang, et al.* [[Paper]](https://doi.org/10.1109/TCSI.2023.3294181)
* [**TCAS-I 2023**] WDVR-RAM: A 0.25–1.2 V, 2.6–76 POPS/W Charge-Domain In-Memory-Computing Binarized
CNN Accelerator for Dynamic AIoT Workloads.
  >*Hongtu Zhang,  Yuhao Shu,  Qi Deng, et al.* [[Paper]](https://doi.org/10.1109/TCSI.2023.3294296)
* [**CICC 2022**] T-PIM: A 2.21-to-161.08TOPS/W Processing-In-Memory Accelerator for End-to-End On-Device Training.
  >*Jaehoon Heo,  Junsoo Kim,  Wontak Han, et al.* [[Paper]](https://doi.org/10.1109/CICC53496.2022.9772808)
* [**DAC 2022**] CREAM: Computing in ReRAM-assisted Energy and Area efficient SRAM for Neural Network Acceleration.
  >*Liukai Xu,  Songyuan Liu,  Zhi Li, et al.* [[Paper]](https://doi.org/10.1145/3489517.3530399)
* [**DAC 2022**] Processing-in-SRAM Acceleration for Ultra-Low Power Visual 3D Perception.
  >*Yuquan He,  Songyun Qu,  Gangliang Lin, et al.* [[Paper]](https://doi.org/10.1145/3489517.3530446)
* [**DAC 2022**] MC-CIM: A Reconfigurable Computation-In-Memory For Efficient Stereo Matching Cost Computation.
  >*Zhiheng Yue,  Yabing Wang,  Leibo Liu, et al.* [[Paper]](https://doi.org/10.1145/3489517.3530477)
* [**DATE 2022**] HyperX: A Hybrid RRAM-SRAM partitioned system for error recovery in memristive Xbars.
  >*Adarsh Kosta,  Efstathia Soufleri,  Indranil Chakraborty, et al.* [[Paper]](https://doi.org/10.23919/DATE54114.2022.9774549)
* [**DATE 2022**] AID: Accuracy Improvement of Analog Discharge-Based in-SRAM Multiplication Accelerator.
  >*Saeed Seyedfaraji, Baset Mesgari, Semeen Rehman * [[Paper]](https://doi.org/10.23919/DATE54114.2022.9774748)
* [**ISCA 2022**] Gearbox: a case for supporting accumulation dispatching and hybrid partitioning in PIM-based accelerators.
  >*Marzieh Lenjani,  Alif Ahmed,  Mircea Stan, et al.* [[Paper]](https://doi.org/10.1145/3470496.3527402)
* [**ISSCC 15.4  2022**] A 40nm 60.64TOPS/W ECC-Capable Compute-in-Memory/Digital 2.25MB/768KB RRAM/SRAM System with Embedded Cortex M3 Microprocessor for Edge Recommendation Systems.
  >*Muya Chang,  Samuel D. Spetalnick,  Brian Crafton, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42614.2022.9731679)
* [**ISSCC 15.3 2022**] COMB-MCM: Computing-on-Memory-Boundary NN Processor with Bipolar Bitwise Sparsity Optimization for Scalable Multi-Chiplet-Module Edge Machine Learning.
  >*Haozhe Zhu,  Bo Jiao,  Jinshan Zhang, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42614.2022.9731657)
* [**ISSCC 15.5 2022**] A 28nm 29.2TFLOPS/W BF16 and 36.5TOPS/W INT8 Reconfigurable Digital CIM Processor with Unified FP/INT Pipeline and Bitwise In-Memory Booth Multiplication for Cloud Deep Learning Acceleration.
  >*Fengbin Tu,  Yiqi Wang,  Zihan Wu, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42614.2022.9731762)
* [**ISSCC 29.3 2022**] A 28nm 15.59μJ/Token Full-Digital Bitline-Transpose CIM-Based Sparse Transformer Accelerator with
Pipeline/Parallel Reconfigurable Modes.
  >*Fengbin Tu,  Zihan Wu,  Yiqi Wang, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42614.2022.9731645)
* [**ISSCC 2022**] DIANA: An End-to-End Energy-Efficient Digital and ANAlog Hybrid Neural Network SoC.
  >*Kodai Ueyoshi, Ioannis A. Papistas, Pouya Houshmand, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42614.2022.9731716)
* [**JETC 2022**] Towards a Truly Integrated Vector Processing Unit for Memory-bound Applications Based on a Cost-competitive Computational SRAM Design Solution.
  >*Maha Kooli,  Antoine Heraud,  Henri-Pierre Charles, et al.* [[Paper]](https://doi.org/10.1145/3485823)
* [**JSSC 2022**] Scalable and Programmable Neural Network Inference Accelerator Based on In-Memory Computing.
  >*Hongyang Jia,  Murat Ozatay,  Yinqi Tang, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2021.3119018)
* [**TCAD 2022**] MARS: Multimacro Architecture SRAM CIM-Based Accelerator With Co-Designed Compressed Neural Networks.
  >*Syuan-Hao Sie,  Jye-Luen Lee,  Yi-Ren Chen, et al.* [[Paper]](https://doi.org/10.1109/TCAD.2021.3082107)
* [**TCAS-I 2022**] BR-CIM: An Efficient Binary Representation Computation-In-Memory Design.
  >*Zhiheng Yue,  Yabing Wang,  Yubin Qin, et al.* [[Paper]](https://doi.org/10.1109/TCSI.2022.3185135)
* [**DATE 2021**] Compute-in-Memory Upside Down: A Learning Operator Co-Design Perspective for Scalability.
  >*Shamma Nasrin,  Priyesh Shukla,  Shruthi Jaisimha, et al.* [[Paper]](https://doi.org/10.23919/DATE51398.2021.9474119)
* [**DATE 2021**] Running Efficiently CNNs on the Edge Thanks to Hybrid SRAM-RRAM In-Memory Computing.
  >*Marco Rios,  Flavio Ponzina,  Giovanni Ansaloni, et al.* [[Paper]](https://doi.org/10.23919/DATE51398.2021.9474233)
* [**ISSCC 15.1 2021**] A Programmable Neural-Network Inference Accelerator Based on Scalable In-Memory Computing.
  >*Hongyang Jia,  Murat Ozatay,  Yinqi Tang, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42613.2021.9365788)
* [**ISSCC 15.2 2021**] A 2.75-to-75.9TOPS/W Computing-in-Memory NN Processor Supporting Set-Associate Block-Wise Zero Skipping and Ping-Pong CIM with Simultaneous Computation and Weight Updating.
  >*Jinshan Yue,  Xiaoyu Feng,  Yifan He, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42613.2021.9365958)
* [**ISSCC 15.4 2021**] A 5.99-to-691.1TOPS/W Tensor-Train In-Memory-Computing Processor Using Bit-Level-SparsityBased Optimization and Variable-Precision Quantization.
  >*Ruiqi Guo,  Zhiheng Yue,  Xin Si, et al.* [[Paper]](https://doi.org/10.1109/ISSCC42613.2021.9365989)
* [**JSSC 2021**] A 0.44-μJ/dec, 39.9-μs/dec, Recurrent Attention In-Memory Processor for Keyword Spotting.
  >*Hassan Dbouk,  Sujan K. Gonugondla,  Charbel Sakr, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2020.3029586)
* [**JSSC 2021**] Z-PIM: A Sparsity-Aware Processing-in-Memory Architecture With Fully Variable Weight Bit-Precision for Energy-Efficient Deep Neural Networks.
  >*Ji-Hoon Kim,  Juhyoung Lee,  Jinsu Lee, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2020.3039206)
* [**VLSI JFS2-3 2021**] A 6.54-to-26.03 TOPS/W Computing-In-Memory RNN Processor using Input Similarity Optimization and Attention-based Context-breaking with Output Speculation.
  >*Ruiqi Guo,  Hao Li,  Ruhui Liu, et al.* [[Paper]](https://doi.org/10.23919/VLSICircuits52068.2021.9492492)
* [**CICC 2020**] KeyRAM: A 0.34 uJ/decision 18 k decisions/s Recurrent Attention In-memory Processor for Keyword Spotting.
  >*Hassan Dbouk,  Sujan K. Gonugondla,  Charbel Sakr, et al.* [[Paper]](https://doi.org/10.1109/CICC48029.2020.9075923)
* [**DAC 2020**] Q-PIM: A Genetic Algorithm based Flexible DNN Quantization Method and Application to Processing-In-Memory Platform.
  >*Yun Long,  Edward Lee,  Daehyun Kim, et al.* [[Paper]](https://doi.org/10.1109/DAC18072.2020.9218737)
* [**DATE 2020**] A Fast and Energy Efficient Computing-in-Memory Architecture for Few-Shot Learning Applications.
  >*Dayane Reis,  Ann Franchesca Laguna,  Michael Niemier, et al.* [[Paper]](https://doi.org/10.23919/DATE48585.2020.9116292)
* [**ISSCC 14.3 2020**] A 65nm Computing-in-Memory-Based CNN Processor with 2.9-to-35.8TOPS/W System Energy Efficiency Using Dynamic-Sparsity Performance-Scaling Architecture and Energy-Efficient Inter/Intra-Macro Data Reuse.
  >*Jinshan Yue,  Zhe Yuan,  Xiaoyu Feng, et al.* [[Paper]](https://doi.org/10.1109/ISSCC19947.2020.9062958)
* [**JSSC 2020**] A Programmable Heterogeneous Microprocessor Based on Bit-Scalable In-Memory Computing.
  >*Hongyang Jia,  Hossein Valavi,  Yinqi Tang, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2020.2987714)
* [**JSSC 2020**] A 2× 30k-Spin Multi-Chip Scalable CMOS Annealing Processor Based on a Processing-in-Memory Approach for Solving Large-Scale Combinatorial Optimization Problems.
  >*Takashi Takemoto,  Member,  IEEE, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2019.2949230)
* [**JSSC 2020**] A 28-nm Compute SRAM With Bit-Serial Logic/Arithmetic Operations forProgrammable In-Memory Vector Computing.
  >*Jingcheng Wang,  Xiaowei Wang,  Charles Eckert, et al.* [[Paper]](https://doi.org/10.1109/JSSC.2019.2939682)
* [**MICRO 2020**] CATCAM: Constant-time Alteration Ternary CAM with Scalable In-Memory Architecture.
  >*Dibei Chen,  Zhaoshi Li,  Tianzhu Xiong, et al.* [[Paper]](https://doi.org/10.1109/MICRO50266.2020.00038)
* [**TC 2020**] CIMAT: A Compute-In-Memory Architecture for On-chip Training Based on Transpose SRAM Arrays.
  >*Hongwu Jiang,  Xiaochen Peng,  Shanshi Huang, et al.* [[Paper]](https://doi.org/10.1109/TC.2020.2980533)
* [**DAC 2018**] SNrram: an efficient sparse neural network computation architecture based on resistive random-access memory.
  >*Peiqi Wang,  Yu Ji,  Chi Hong, et al.* [[Paper]](https://doi.org/10.1145/3195970.3196116)

---
## Simulation Tools
* [**DATE 2024**] X-PIM: Fast Modeling and Validation Framework for Mixed-Signal Processing-in-Memory Using Compressed Equivalent Model in System Verilog.
  >*I. Jeong, J. -E. Park* [[Paper]](https://doi.org/10.23919/DATE58400.2024.10546655)
* [**TCAS-I 2024**] NeuroSim V1. 4: Extending Technology Support for Digital Compute-in-Memory Toward 1nm Node.
  >*Lee, Junmo, Anni Lu, Wantong Li, et al.* [[Paper]](https://www.x-mol.com/paper/1761279482257969152)
* [**TCAD 2023**] MNSIM 2.0: A Behavior-Level Modeling Tool for Processing-In-Memory Architectures.
  >*Zhenhua Zhu,  Hanbo Sun,  Tongxin Xie, et al.* [[Paper]](https://doi.org/10.1109/TCAD.2023.3251696) [[GitHub]](https://github.com/thu-nics/MNSIM-2.0)
* [**ASPDAC 2021**] DP-Sim: A Full-stack Simulation Infrastructure for Digital Processing In-Memory Architectures.
  >*Minxuan Zhou, Mohsen Imani, Yeseong Kim* [[Paper]](https://doi.org/10.1145/3394885.3431525)
* [**FAI 2021**] NeuroSim Simulator for Compute-in-Memory Hardware Accelerator: Validation and Benchmark.
  >*Anni Lu,  Xiaochen Peng,  Wantong Li, et al.* [[Paper]](https://doi.org/10.3389/frai.2021.659060) [[GitHub]](https://github.com/neurosim)
* [**TCAD 2021**] DNN+NeuroSim V2.0: An End-to-End Benchmarking Framework for Compute-in-Memory Accelerators for On-Chip Training.
  >*Xiaochen Peng,  Shanshi Huang,  Hongwu Jiang, et al.* [[Paper]](https://doi.org/10.1109/TCAD.2020.3043731) [[GitHub]](https://github.com/neurosim/DNN_NeuroSim_V2.1)
* [**TCAD 2020**] Eva-CiM: A System-Level Performance and Energy Evaluation Framework for Computing-in-Memory Architectures.
  >*Di Gao,  Dayane Reis,  Xiaobo Sharon Hu, et al.* [[Paper]](https://doi.org/10.1109/TCAD.2020.2966484) [[GitHub]](https://github.com/skycrapers/Eva-CiM)

---
## Software Stack
* [**TCSI 2025**] A Design Framework of Heterogeneous Approximate DCIM-Based Accelerator for Energy-Efficient NN Processing.  
  >*Kyeongho Lee, Hyeyeong Lee, Jongsun Park.* [[Paper]](https://doi.org/10.1109/TCSI.2025.3530637)
* [**DAC 2024**] EasyACIM: An End-to-End Automated Analog CIM with Synthesizable Architecture and Agile Design Space Exploration.
  >*Haoyi Zhang, Jiahao Song, Xiaohan Gao, et al.* [[Paper]](https://doi.org/10.1145/3649329.3656229)
* [**DATE 2024**] A Novel March Test Algorithm for Testing 8T SRAM-Based IMC Architectures.
  >*L. Ammoura, M. -L. Flottes, P. Girard, et al.* [[Paper]](https://doi.org/10.23919/DATE58400.2024.10546583)
* [**DATE 2024**] PIMLC: Logic Compiler for Bit-Serial Based PIM.
  >*C. Tang, C. Nie, W. Qian, et al.* [[Paper]](https://doi.org/10.23919/DATE58400.2024.10546754)
* [**ASPLOS 2024**] CIM-MLC: A Multi-level Compilation Stack for Computing-In-Memory Accelerators.
  >*Songyun Qu, Shixin Zhao, Bing Li, et al.* [[Paper]](https://ar5iv.org/abs/2401.12428)
* [**ASPLOS 2023**] Infinity Stream: Portable and Programmer-Friendly In-/Near-Memory Fusion.
  >*Zhengrong Wang,  Christopher Liu,  Aman Arora, et al.* [[Paper]](https://polyarch.cs.ucla.edu/papers/asplos2023-infinity-stream.pdf)
* [**DAC 2023**] AutoDCIM: An Automated Digital CIM Compiler.
  >*Jia Chen,  Fengbin Tu,  Kunming Shao, et al.* [[Paper]](https://doi.org/10.1109/DAC56929.2023.10247976)
* [**DAC 2023**] PIM-HLS: An Automatic Hardware Generation Tool for Heterogeneous
Processing-In-Memory-based Neural Network Accelerators.
  >*Yu Zhu,  Zhenhua Zhu,  Guohao Dai, et al.* [[Paper]](https://doi.org/10.1109/DAC56929.2023.10247755)
* [**ASPDAC 2022**] Optimal Data Allocation for Graph Processing in Processing-in-Memory Systems.
  >*Zerun Li, Xiaoming Chen, Yinhe Han* [[Paper]](https://doi.org/10.1109/ASP-DAC52403.2022.9712587)
* [**MICRO 2022**] Multi-Layer In-Memory Processing.
  >*Daichi Fujiki,  Alireza Khadem,  S. Mahlke, et al.* [[Paper]](https://doi.org/10.1109/MICRO56248.2022.00068)
* [**TCAS-I 2022**] Neural Network Training on In-Memory-Computing Hardware With Radix-4 Gradients.
  >*Christopher Grimm, and Naveen Verma* [[Paper]](https://doi.org/10.1109/TCSI.2022.3185556)
* [**ASPDAC 2021**] Providing Plug N’ Play for Processing-in-Memory Accelerators.
  >*Paulo C. Santos, Bruno E. Forlin, Luigi Carro* [[Paper]](https://doi.org/10.1145/3394885.3431527)
* [**DAC 2021**] Leveraging Noise and Aggressive Quantization of In-Memory Computing for Robust DNN Hardware Against Adversarial Input and Weight Attacks.
  >*Sai Kiran Cherupally,  Adnan Siraj Rakin,  Shihui Yin, et al.* [[Paper]](https://doi.org/10.1109/DAC18074.2021.9586233)
* [**DAC 2021**] Invited: Accelerating Fully Homomorphic Encryption with Processing in Memory.
  >*Saransh Gupta, Tajana Simunic Rosing* [[Paper]](https://doi.org/10.1109/DAC18074.2021.9586285)

---
## Surveys and Analysis
* [**DAC 2023**] Unified Agile Accuracy Assessment in Computing-in-Memory Neural Accelerators by Layerwise Dynamical Isometry.
  >*Xuan-Jun Chen, Cynthia Kuan, Chia-Lin Yang* [[Paper]](https://doi.org/10.1109/DAC56929.2023.10247782)
* [**DAC 2023**] Advances and Trends on On-Chip Compute-in-Memory Macros and Accelerators.
  >*Jae-sun Seo* [[Paper]](https://doi.org/10.1109/DAC56929.2023.10248014)
* [**TCAS-I 2022**] A Practical Design-Space Analysis of Compute-in-Memory With SRAM.
  >*Samuel Spetalnick, and Arijit Raychowdhury* [[Paper]](https://doi.org/10.1109/TCSI.2021.3138057)
* [**DATE 2021**] Perspectives on Emerging Computation-in-Memory Paradigms.
  >*Shubham Rai,  Mengyun Liu,  Anteneh Gebregiorgis, et al.* [[Paper]](https://doi.org/10.23919/DATE51398.2021.9473976)
* [**DATE 2021**] Modeling and Optimization of SRAM-based In-Memory Computing Hardware Design.
  >*Jyotishman Saikia,  Shihui Yin,  Sai Kiran Cherupally, et al.* [[Paper]](https://doi.org/10.23919/DATE51398.2021.9473973)
* [**TCAS-I 2021**] Challenges and Trends of SRAM-Based Computing-In-Memory for AI Edge Devices.
  >*Chuan-Jia Jhang,  Cheng-Xin Xue,  Je-Min Hung, et al.* [[Paper]](https://doi.org/10.1109/TCSI.2021.3064189)
* [**TCAS-I 2021**] Impact of Analog Non-Idealities on the Design Space of 6T-SRAM Current-Domain Dot-Product Operators for In-Memory Computing.
  >*Adrian Kneip, and David Bol* [[Paper]](https://doi.org/10.1109/TCSI.2021.3058510)
* [**TCAS-I 2021**] Analysis and Optimization Strategies Toward Reliable and High-Speed 6T Compute SRAM.
  >*Jian Chen,  Wenfeng Zhao,  Yuqi Wang, et al.* [[Paper]](https://doi.org/10.1109/TCSI.2021.3054972)
* [**ICCAD 2020**] Fundamental Limits on the Precision of In-memory Architectures.
  >*Sujan K. Gonugondla,  Charbel Sakr,  Hassan Dbouk, et al.* [[Paper]](https://doi.org/10.1145/3400302.3416344)

---
## Maintainers
- Yingjie Qi, Beihang University. [[GitHub]](https://github.com/Kevin7Qi)
- Cenlin Duan, Beihang University. [[GitHub]](https://github.com/AuroraSky111)
- Xiaolin He, Beihang University. [[GitHub]](https://github.com/iboxl)
