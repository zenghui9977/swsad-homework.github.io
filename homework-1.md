# Homework 1

## 1. 简答题
* **软件工程的定义**
    
    > Software engineering is “(1) the application of a systematic, disciplined, quantifiable approach to the development, operation, and maintenance of software, that is, the application of engineering to software,” and “(2) the study of approaches as in (1).” –– IEEE Standard 610.12

    软件工程是指：

    1. 利用工程的思想对软件的开发、运行和维护采用一种系统的、有纪律的、可量化的方法，即将工程中的系统性、纪律性、可度量性应用到软件开发中。
    2. 对 1 中方法的研究
* **解释导致 software crisis 本质原因、表现，述说克服软件危机的方法**

    * **software crisis：** ***软件危机*** 是计算机科学早期使用的一个术语，指在规定的时间内编写有用而高效的计算机程序的困难。软件危机是由于计算机能力的迅速提高和无法解决的问题的复杂性造成的。随着软件复杂性的增加，由于现有方法的不足，出现了许多软件问题。
    * **导致软件危机的本质原因：** 计算机的发展。机器的发展导致了软件危机，机器越强大，编程问题也越强
    * **软件危机的表现：** 
        * 经费预算问题 ：软件完成时间不断拖延，经费不断增加，不能按计划进度按时完成。
        * 开发的软件不能满足客户要求：发初期对用户的要求了解不够明确，未能得到明确的表达。开发工作开始后，软件人员和用户又未能及时交换意见，使得一些问题不能及时解决，导致开发的软件不能满足用户的要求，因而导致开发失败，浪费人力物力。
        * 开发的软件可维护性差：开发过程中没有同意的、公认的规范，软件开发人员按各自的风格工作，开发过程无完整、规范的文档，发现问题后进行杂乱无章的修改。程序结构混乱，运行时发现错误也很难修改，导致维护性差。
        * 软件的可靠性差：由于在开发过程中，没有确保软件质量的体系和措施，在软件测试时，又没有严格的、充分的、完全的测试，导致给到用户手中的软件不一定确保有效好用。
    * **克服软件危机的方法：** 构建生产软件的方法与知识体系，合理利用软件规模估算模型，采用有系统化、与时俱进的软件工程方法，来规避 software crisis。 

* **软件生命周期：**
    在时间维度，对软件项目任务进行划分，又成为软件开发过程。常见有瀑布模型、螺旋模型、敏捷的模型等。
* **SWEBoK 的 15 个知识域（An Overview of the SWEBOK Guide 请中文翻译其名称与简短说明）**

    1. Software Requirements：软件需求。软件需求涉及到引出、协商、分析、规范和验证，表达了对软件产品的需求和约束。
    2. Software Design：软件设计。设计被定义位系统或组件的体系结构、组件、接口和其他特征的过程，以及改过程的结果。软件设计包括设计过程和最终产品。
    3. Software Construction：软件构建。软件构建是知通过详细设计、编码、单元测试、集成测试、调试和验证相结合，对工作软件进行详细创建。
    4. Software Testing：软件测试。测试是对产品质量进行评估并通过识别缺陷来改进产品质量的活动。软件测试涉及到在一组有限的测试用例上根据预期行为动态地验证程序的行为。这些测试用例是从(通常非常大的)执行域中选择的。
    5. Software Maintenance：软件维护。软件维护包括增强现有的功能，使软件适应新的和修改的操作环境，以及纠正缺陷。这些类别被称为完善的、自适应的和纠正的软件维护。
    6. Software Configuration Management：软件配置管理。软件配置管理是在不同的时间点识别系统配置的规程，以便系统地控制配置的更改，并在整个软件生命周期中维护配置的完整性和可追溯性。
    7. Software Engineering Management：软件工程管理。软件工程管理包括计划、协调、测量、报告和控制一个项目或程序，以确保软件的开发和维护是系统的、有纪律的和量化的。
    8. Software Engineering Process：软件工程过程。所涵盖的主题包括过程实现和变更(过程基础结构、过程实现和变更的模型以及软件过程管理);过程定义(软件生命周期模型和过程，过程定义、过程适应和过程自动化的符号);过程评估模型和方法;测量(过程测量、产品测量、测量技术、测量结果质量);以及软件过程工具。
    9. Software Engineering Models and Methods：软件工程模型和方法。软件工程模型和方法包括建模(软件工程模型的原理和属性;语法、语义、不变量;(前置条件、后置条件和不变量);模型的类型(信息、结构和行为模型);分析(对正确性、完整性、一致性、质量和交互进行分析;可追溯性;和权衡分析);以及软件开发方法(启发式方法、正式方法、原型方法和敏捷方法)。
    10. Software Quality：软件质量。软件质量是一个普遍存在的软件生命周期问题，包括软件质量的基础(软件工程文化、软件质量特征、软件质量的价值和成本、软件质量改进);软件质量管理过程(软件质量保证、验证和验证、评审和审计);以及实际的考虑(缺陷特性、软件质量度量和软件质量工具)。
    11. Software Engineering Professional Practice：软件工程专业实践。软件工程专业实践是指软件工程师必须具备的知识、技能和态度，以一种专业、负责和道德的方式来实践软件工程。它涵盖专业(专业行为、专业协会、软件工程标准、雇佣合同、法律问题)、伦理准则、团队动态(在团队中工作，认知问题的复杂性，与利益相关者的互动，处理不确定性和模糊性，处理多元文化环境)和沟通能力。
    12. Software Engineering Economics：软件工程经济学。软件工程经济学关注于在业务上下文中做出决策，以使技术决策与组织的业务目标保持一致。所涵盖的主题包括软件工程经济学的基本原理(建议、现金流量、金钱的时间价值、规划期限、通货膨胀、折旧、重置和退休决定);非营利性决策(成本效益分析、优化分析);评估、经济风险和不确定性(评估技术、风险和不确定性下的决策);以及多属性决策(值和度量尺度、补偿和非补偿技术)。
    13. Computing Foundations：计算基础。计算基础涵盖了为软件工程实践提供必要的计算背景的基本主题。主题包括问题解决技术、抽象、算法和复杂性、编程基础、并行和分布式计算的基础、计算机组织、操作系统和网络通信。
    14. Mathematical Foundations：数学基础。数学基础涵盖了为软件工程实践提供必要数学背景的基本主题。主题包括集合、关系和函数;基本命题逻辑和谓词逻辑;证明技术;图表和树木;离散型概率;语法和有限状态机;和数论。
    15. Engineering Foundations：工程基础。工程基础涵盖了为软件工程实践提供必要的工程背景的基本主题。所涵盖的主题包括实证方法和实验技术;统计分析;测量和度量;工程设计;仿真和建模;以及根本原因分析。
* **简单解释 CMMI 的五个级别。例如：Level 1 - Initial：无序，自发生产模式。**

    1. **Level 1 - Initial**：无序，自发生产模式。
    2. **Level 2 - Managed**：建立了基本的项目管理过程来跟踪费用、进度和功能特性。制定了必要的过程纪律，能重复早先类似应用项目取得的成功经验。分别包括：
          * **CM** - Configuration Management
          * **MA** - Measurement and Analysis
          * **PPQA** - Process and Quality Assurance
          * **REQM** - Requirements Management
          * **SAM** - Supplier Agreement Management
          * **SD** - Service Delivery
          * **WMC** - Work Monitoring and Control
          * **WP** - Work Planning
    3. **Level 3 - Defined**：已将软件管理和工程两方面的过程文档化、标准化，并综合成该组织的标准软件过程。所有项目均使用经批准、剪裁的标准软件过程来开发和维护软件，软件产品的生产在整个软件过程是可见的。包括有：
          * **CAM** - Capacity and Availability Management
          * **DAR** - Decision Analysis and Resolution
          * **IRP** - Incident Resolution and Prevention
          * **IWM** - Integrated Work Managements
          * **OPD** - Organizational Process Definition
          * **OPF** - Organizational Process Focus...
          * **OT** - Organizational Training
          * **RSKM** - Risk Management
          * **SCON** - Service Continuity
          * **SSD** - Service System Development
          * **SST** - Service System Transition
          * **STSM** - Strategic Service Management
    4. **Level 4 - Quantitatively Managed**：分析对软件过程和产品质量的详细度量数据，对软件过程和产品都有定量的理解与控制。管理有一个作出结论的客观依据，管理能够在定量的范围内预测性能。包括：
          * **OPP** - Organizational Process Performance
          * **QWM** - Quantitative Work Management
    5. **Level 5 - Optimizing**：过程的量化反馈和先进的新思想、新技术促使过程持续不断改进。包括：
          * **CAR** - Causal Analysis and Resolution.
          * **OPM** - Organizational Performance Management.
* **用自己语言简述 SWEBok 或 CMMI （约200字）**
    * **SWEBoK** ：软件工程知识体系，是为了克服软件危机由IEEE构建的软件生产的最佳实践与相关知识的框架，主要用于指导学科的人才培养与学科的发展建设。在知识体系中，包括有软件工程实践和基础教育两个部分，总共包括15个部分，软件需求和软件设计是其中的重要的两部分。在实践的过程中，过程模型为软件的开发提供了一个极其有效的行动指南，通过对内容以及开发的分析与设计，为软件的开发制定一条时间轴，指导软件按时有序科学的进行，充分规避软件危机的风险
