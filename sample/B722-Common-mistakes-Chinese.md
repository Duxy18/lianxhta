
# 研究中的常见错误及建议解决方案

## A. 设计与数据收集

### 1. 假设-分析一致性
- **常见错误**: 假设没有恰当地反映被测量的构念，或者不能直接测试，或与所使用的实证方法不匹配。  
- **建议解决方案**:  
  - 确保理论构念与实证构念之间的一致性。  
  - 清晰地说明对照处理（实验）的预期方向性。  
  - 明确说明是否研究了效应或关联，并在单一假设中避免使用多个解释变量和多个因变量。  

### 2. 实验设计
- **2.1 实验操作混淆**  
  - 精心设计并进行实证前测试，确保每次仅操作一个变量（以便隔离处理效应）。  

- **2.2 使用需求驱动的启动研究**  
  - 进行前测，确保实验处理不会触发不对称的需求效应。  
  - 使用非启动技术来操控目标构念。  

- **2.3 操控检查放置在操控变量与因变量之间**  
  - 如果需要操控检查，应该在样本外进行。  
  - 如果操控检查放在因变量之前，进行附加的“减少形式”实验可以测试是否研究结果受到操控检查的偏倚影响。  

- **2.4 操控检查与注意力检查或合规检查混淆**  
  - 清晰区分设计、术语和解释中不同类型的检查。  

- **2.5 通过操控检查并假设效应仅通过假设的渠道发生**  
  - 补充操控检查，通过判别性操控检查，证明处理不会影响其他可能的渠道。  

### 3. 测量
- **3.1 使用双重问题的量表项目**  
  - 清晰说明数据省略或排除的情况，并提供详细信息。  

- **3.2 测量量表的修改未加以说明**  
  - 报告所有量表修改，包括修改过和未修改的项目。  

- **3.3 使用 Cronbach’s alpha（克朗巴赫 α 系数）**  
  - 考虑使用 Cronbach’s alpha 的替代方法，如 McDonald’s Omega 或 Raykov’s rho。  

### 4. 质性研究方法
- **4.1 编码方法模糊不清**  
  - 报告具有可重复性的分析（例如，通过主题建模）。  

- **4.2 使用目的性抽样但没有对照组**  
  - 选择代表性样本或随机对照组。  

- **4.3 数据省略和排除未妥善报告**  
  - 清晰说明数据省略或排除的理由，并提供详细解释。  

- **4.4 访谈问题有偏或存在其他偏见**  
  - 避免使用引导性问题，采用中性语言，并清楚报告所有在研究中使用的措施。  

### 5. 开放科学
- **5.1 开放科学程序和实践没有充分遵循**  
  - 如果可能，预注册定量和定性研究，允许对原计划做少量偏差。  
  - 透明地报告研究过程，分享已发表的文章中的数据。  
  - 清晰区分确认性和探索性分析。  
  - 提供从已发表文章中提取的代码和分析文件，简化重复性研究。  
  - 共享实验材料或数据收集/挖掘的详细信息。  

### 6. 文献综述
- **6.1 文献综述中使用模糊或无法重复的程序**  
  - 确保文献综述的可重复性。  
  - 清楚描述文献搜索和筛选的程序，以简化复制过程。  
  - 遵循 PRISMA（系统评价与元分析报告标准）指南。  

## B. 数据分析

### 7. 数据预处理与转换
- **7.1 缺失数据未进行适当的解释或删除**  
  - 清晰记录缺失数据，合理解释缺失数据的删除，并使用合适的估算方法处理缺失数据。  

- **7.2 不当或不必要地进行数据中心化（例如，均值或尺度中心化）**  
  - 仅在合适的情况下进行均值中心化，提供清晰的理由说明数据中心化的必要性。  

- **7.3 使用不必要的指标和复合指标（包括分层复合指标）**  
  - 避免使用不必要的指标和复合指标，模型中应合理地做出分层决策。  

- **7.4 不当使用非线性（如对数）转换**  
  - 所有的非线性转换都应有理论依据，并提供关于变量之间关系的功能形式的清晰解释。  

- **7.5 对因变量进行对数转换**  
  - 考虑使用广义线性模型（GLM）并使用准最大似然估计（QMLE）进行估计。  

- **7.6 在统计模型中使用比率**  
  - 通常避免在统计模型中使用比率；而应使用分子并对分母进行控制。  

- **7.7 使用未经证实的差异分数作为因变量或解释变量**  
  - 避免使用差异分数。如果必须使用差异分数，请进行相关检验。  

- **7.8 连续变量被任意分类（例如，按中位数分割）**  
  - 始终将连续变量视为连续变量。如果理论上有分类需求，可以考虑使用有限混合模型。  

### 8. 质性文本分析方法
- **8.1 数据清理阶段没有记录或记录不当**  
  - 清晰地记录和解释质性文本分析中的数据清理过程。  

### 9. OLS 适用于有界的因变量
- **9.1 使用具有非线性链接的 GLM，却没有考虑使用 OLS**  
  - 如果研究的兴趣在于估计边际效应（而不是预测），可以使用 OLS 作为默认选项。  

### 10. 回归排名技术
- **10.1 使用相对权重分析来排名模型中预测变量的强度**  
  - 仅解释未标准化的部分回归系数（通过因果模型获得）来推测因果效应。  

### 11. 实验数据分析
- **11.1 忽略了平衡检验，导致随机化治疗可能存在问题**  
  - 使用平衡检验以提供关于随机化是否成功的检验。  

- **11.2 回归结果的系数被误解，尤其是在分析 2x2 实验时**  
  - 报告相关的回归规范和结果。  
  - 避免错误解读，确保使用正确的规范。  

- **11.3 删除未通过后处理操控检查的参与者**  
  - 清楚地解释并记录与操控检查相关的数据删除过程。  

## C. 诊断、推断与报告

### 18. 诊断
- **18.1 使用 Harman 的单因子检验来检测共同方法偏差（CMV）**  
  - 在研究设计中减少 CMV 的风险（例如，通过不同来源收集依赖变量和独立变量），或者在分析阶段使用工具变量估计。  

- **18.2 异常值未被透明且适当识别**  
  - 清晰记录异常值识别的程序，确保结果的可复制性。  
  - 通常报告有异常值和没有异常值的结果，并考虑使用鲁棒回归方法。  

### 19. 统计推断
- **19.1 测试多个结果而没有适当修正**  
  - 通过 Bonferroni 校正或相关程序来缓解该问题。  

- **19.2 结果被解释为“边际显著”**  
  - 避免将结果标记为“边际显著”。应关注显著的结果，并基于事先设定的显著性水平进行解释。  

- **19.3 统计不显著被解释为“没有效应”**  
  - 统计不显著的结果只是意味着“没有得出结论”。若要测试“无效应”，可使用其他分析（例如，等效检验、贝叶斯因子）。  

- **19.4 不合理使用正常标准误差**  
  - 根据数据的特性，使用异方差稳健标准误差。  
  - 在多级模型中，也可能需要使用聚类稳健标准误差。  

### 20. 报告
- **20.1 图表和表格中缺乏足够的细节，无法确保结果的可复制性**  
  - 在回归表中，报告（至少在附录中）所有高阶项、交互作用和控制变量。  
  - 清晰且一致地标记图表中的变量，避免误导性的图表轴标。  

- **20.2 不一致地报告 p 值和其他统计量**  
  - 在提交之前仔细检查 p 值和其他统计量。  

- **20.3 未在表格和图表中报告估计的不确定性**  
  - 报告完整的结果，说明报告效应的大小，并给出估计不确定性的度量。  

- **20.4 错误使用单尾检验（尤其是当估计量功效不足时）**  
  - 通常报告双尾检验。  

- **20.5 将拟合的预测值外推到数据范围之外**  
  - 检查所有预测值是否都在分析数据的范围内，并仅在图表中展示这一范围。  

- **20.6 报告标准化回归系数**  
  - 报告未标准化的回归系数，或者在标准化之前校正 y 中的测量误差。  

- **20.7 只报告 ANOVA 表**  
  - 报告完整的回归表，它提供比 ANOVA 表更清晰和更详细的信息。  
