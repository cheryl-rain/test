# 第二页修订、ee校准及三候选比较：文献与思路核查

日期：2026-10-28。依据用户上传第二页布局修改，完整PPT为4页：方法图、选择原则、ee方案、候选比较。后两页用于保留较大字号，均明确标注拟议实验。

## 1. 初筛与复筛是否合理

| 原思路 | 核查判断 | 修订说明 |
|---|---|---|
| 两阶段筛选 | 合理 | 文献初筛评估平台、反应与检测可行性；实验复筛验证产物、信号、校准及真实样品。候选是研究对象，不等于已有成熟CD方法。 |
| 非手性衍生化不会消旋 | 需修正 | 非手性试剂只表示不另引固定手性中心，不保证水解、加热或酸碱反应不会导致消旋。构型保持必须验证；[17]的胶原研究明确讨论了酸水解引起的异构化/消旋。 |
| 有UV发色团即可用于CD | 需修正 | UV吸收不等于足够CD强度。必须确定目标衍生物、波长、净CD信号、空白和稳定性；[25–26]只证明PTH/NBD体系，不直接证明AQC/OPA/PTC。 |
| HPLC–CD只能非手性衍生化 | 需补充 | [27]证明未衍生化Trp＋手性柱＋在线CD；[28]证明未衍生化Phe＋非手性HSS T3＋在线CD，并用于胰岛素水解液。衍生化不是平台普遍必要条件。 |
| ee直接用CD信号计算 | 需有校准与条件 | 在同一目标D/L共洗脱、UV响应等效、衍生效率无偏且无干扰时，CD/UV经验比可建立ee校准。必须用独立混合比例与浓度挑战验证；不能混同原始峰面积比与无量纲g。 |
| 实际样品验证 | 需扩充 | 除UV/CD、稳定性和线性/准确度/精密度外，增加峰身份与产物纯度、反应完成度、基质回收、Lys多位点反应、水解/衍生构型保持。 |

## 2. ee校准拟议方案

- 适用范围：非手性LC中同一氨基酸的D/L共洗脱，而不同氨基酸或其他产物已被分开。若用手性柱拆分，则分别校准D/L峰，不照搬共洗脱净响应比。
- eeD=(cD−cL)/(cD+cL)×100%；D为正只是计算约定，不代表CD一定为正。cD/cL使用同一目标氨基酸的物质的量浓度。
- 用纯度与盐型校正后的D/L标液保持CT=cD+cL恒定。9个拟议摩尔比：100:0、90:10、75:25、60:40、50:50、40:60、25:75、10:90、0:100；对应eeD=+100、+80、+50、+20、0、−20、−50、−80、−100%。浓度由预实验信噪与线性范围选定，不预先给出未经验证的浓度。
- 先混D/L后统一衍生，以检测真实反应竞争和效率差；仅混合事先衍生物不能完整验证样品衍生化偏倚。每个水平建议至少3份独立制备，而不仅重复进样。
- 目标UV/CD峰同步积分并校正空白、基线和串联检测器时延。SCD必须保留正负号；R=SCD/SUV为仪器经验比，不直接等于g。波长、增益、光程和积分条件固定。
- 逐个氨基酸、衍生试剂和目标产物检验R=a·eeD+b。先检查D/L镜像、外消旋抵消和反应效率/构型保持，再检查残差、失拟与回算误差；不以高R²代替适用性验证。eeD回算=(R−b)/a。
- 独立配制±40%、±70%等QC，不复用校准配液；在固定ee下改变总浓度，检查浓度依赖。接受标准在实验前按用途确定，不能在无数据时宣称已达某回收或精密度。
- 高ee端针对预计反对映体水平加密并做正交手性LC确认；净CD与总UV相减/比值不自动具备痕量反对映体定量能力。低UV或CD信噪不满足时，不报告可靠ee。
- 设置空白、经/不经水解的D/L对照、已知构型肽和基质加标。游离氨基酸水解对照不能完全替代真实肽残基的释放和消旋；Lys先确认单/双衍生物与定量峰。
- 证据层级：[25]证明PTH镜像CD和肽/水解液应用；[26]证明NBD-F的UV/CD-g因子与%D分析。本页9点、QC、重复数与R拟合形式为本项目提出的可检验方案，不是照录原文SOP，也不承诺三候选均满足模型。

## 3. 三条候选的相对差异

| 候选 | 直接文献依据 | 本项目可取之处 | 限制 |
|---|---|---|---|
| PITC/PTC | 蛋白水解物LC–UV组成分析，覆盖伯胺与仲胺[29]。 | 现有方法易衔接，可作为前处理、保留与回收的基线。 | PTC不等于PTH[25]；PTC在线CD需实测；不能将某个1h/萃取方案称为PITC固有地慢。 |
| AQC | 快速一步反应形成稳定非对称脲，可直接进样，pH/试剂过量影响收率[30]。 | 适合作稳定标记和等待进样/批量分析参照。 | 稳定不等于CD强；先测最终pH及反应完成度，再评价CD背景、信噪比；[11]是手性LC，不是CD。 |
| OPA＋非手性硫醇 | 快速柱前反应、易自动化，有组织/食品蛋白组成分析依据[31]。 | 适合作快速流程与自动进样计时的候选。 | 稳定性依硫醇、氨基酸和条件而异；[32]证明特定产物柱上稳定，不宜一概“OPA产物不稳定”；CD仍需验证。 |

## 4. PPT每一处对应哪些资料

| PPT位置 | 文献 | 对应内容 |
|---|---|---|
| 第1页 HPLC–CD分支 | [25–28] | 非手性衍生化、手性柱在线CD及未衍生化直接分析均保留，不能仅列第一类。 |
| 第2页 文献初筛：方法 | [25–28] | CD/UV互补、不拆分比例只在适配非手性路线成立；特定氨基酸可直接测定。 |
| 第2页 文献初筛：试剂 | [17,25–26,29–32] | 非手性不等于不消旋；发色团不保证CD，兼顾效率/稳定性。 |
| 第2页 PITC候选 | [29]；[25]仅用于界定PTC/PTH | 衔接已有LC–UV方法；PTC的CD待验证。 |
| 第2页 AQC候选 | [30] | 稳定非对称脲、直接进样与反应pH条件。 |
| 第2页 OPA候选 | [31–32] | 快反应、可自动化；稳定性按实际体系验证。 |
| 第2页 实验复筛 | 拟议方案；参考[17,25–26] | 产物/峰身份、UV/CD、稳定性、回收、精密度与构型保持；D/L配比校准。 |
| 第3页 ee校准 | [25–26]＋本项目拟议设计 | 不同于原文照录；固定总浓度、带符号R、独立QC、浓度挑战与高ee端正交确认。 |
| 第4页 三候选差异 | [11,25,29–33] | 不是CD性能排名；[33]中的OPA–FMOC组合和特定基质不能代表OPA单独方案的普遍性能。 |

## 5. 完整参考文献（35篇）

编号1–28保持不变；新增三候选文献为29–33；原删除项的两个限制性来源移为34–35。未获取全文的条目标为“公开摘要与书目”，不声称全文已读。

### [01] Chiral nano-liquid chromatography-mass spectrometry applied to amino acids analysis for orange juice profiling.
D'Orazio G, Cifuentes A, Fanali S. Food chemistry. 2008.
- DOI：[ 10.1016/j.foodchem.2007.11.062 ](https://doi.org/10.1016/j.foodchem.2007.11.062)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/26065779/)；核查层级：公开摘要与书目。
- 证据位置：摘要：FITC、vancomycin-modified silica-diol、orange juice段
- 支持内容：HPLC：FITC标记后在万古霉素手性固定相上进行nano-LC–MS分析。
- 样品边界：真实样品：橙汁；非水解液。

### [02] Chirality determination of unusual amino acids using precolumn derivatization and liquid chromatography-electrospray ionization mass spectrometry.
Hess S, Gustafson KR, Milanowski DJ, Alvira E, Lipton MA, Pannell LK. Journal of chromatography. A. 2004.
- DOI：[ 10.1016/j.chroma.2004.02.068 ](https://doi.org/10.1016/j.chroma.2004.02.068)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/15124814/)；核查层级：公开摘要与书目。
- 证据位置：摘要首句四种试剂及RP-HPLC/UV/MS段
- 支持内容：HPLC：直接比较FDAA、GITC、S-NIFE及OPA–IBLC；经反相HPLC–UV/ESI-MS分析非常见氨基酸立体异构体。
- 样品边界：非常见氨基酸及海洋肽应用方向；摘要不足以核实全部具体水解步骤。

### [03] LC-MS/MS-Based Separation and Quantification of Marfey's Reagent Derivatized Proteinogenic Amino Acid DL-Stereoisomers.
Ayon NJ, Sharma AD, Gutheil WG. Journal of the American Society for Mass Spectrometry. 2019.
- DOI：[ 10.1007/s13361-018-2093-9 ](https://doi.org/10.1007/s13361-018-2093-9)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/30421361/)；核查层级：公开摘要与书目。
- 证据位置：摘要：Marfey derivatization、19 pairs、MRSA extracts段
- 支持内容：HPLC：FDAA/Marfey衍生化结合反相LC–MS/MS，实现19对常见手性氨基酸的分离定量。
- 样品边界：标准品与MRSA提取物；非蛋白水解液验证。

### [04] Reliable and sensitive analysis of amino acids in the peptidoglycan of actinomycetes using the advanced Marfey's method.
Nozawa Y, Sakai N, Arai K, Kawasaki Y, Harada K. Journal of microbiological methods. 2007.
- DOI：[ 10.1016/j.mimet.2007.05.003 ](https://doi.org/10.1016/j.mimet.2007.05.003)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/17544532/)；核查层级：公开摘要与书目。
- 证据位置：摘要：L-FDLA/D-FDLA、acid hydrolysis、cell wall段
- 支持内容：HPLC：L-/D-FDLA advanced Marfey法，结合LC/MS确定细胞壁氨基酸构型。
- 样品边界：真实酸水解样品：放线菌细胞壁肽聚糖；肽聚糖不等同于普通蛋白质。

### [05] Simultaneous determination of hydrophilic amino acid enantiomers in mammalian tissues and physiological fluids applying a fully automated micro-two-dimensional high-performance liquid chromatographic concept.
Hamase K, Miyoshi Y, Ueno K, Han H, Hirano J, Morikawa A, Mita M, Kaneko T, Lindner W, Zaitsu K. Journal of chromatography. A. 2010.
- DOI：[ 10.1016/j.chroma.2009.09.002 ](https://doi.org/10.1016/j.chroma.2009.09.002)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/19767006/)；核查层级：公开摘要与书目。
- 证据位置：摘要：NBD-F、Pirkle type enantioselective column、rat plasma/urine段
- 支持内容：HPLC：NBD-F标记后，反相一维分离组分，Pirkle型手性二维拆分对映体。
- 样品边界：真实样品：大鼠血浆、尿液等；非水解液。

### [06] High-performance liquid chromatography evaluation of the enantiomeric purity of amino acids by means of automated precolumn derivatization with ortho-phthalaldehyde and chiral thiols.
Kühnreich R, Holzgrabe U. Chirality. 2016.
- DOI：[ 10.1002/chir.22660 ](https://doi.org/10.1002/chir.22660)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/27897327/)；核查层级：公开摘要与书目。
- 证据位置：摘要：N-acetyl-L-cysteine、N-isobutyryl-L-cysteine、PFP column段
- 支持内容：HPLC：OPA＋NAC或IBLC自动柱前衍生化，普通PFP柱分离非对映衍生物并评价对映体杂质。
- 样品边界：氨基酸原料/标准品对映体纯度；非水解液。

### [07] Dimethylcysteine (DiCys)/o-Phthalaldehyde Derivatization for Chiral Metabolite Analyses: Cross-Comparison of Six Chiral Thiols.
Lkhagva A, Tai HC. Molecules (Basel, Switzerland). 2021.
- DOI：[ 10.3390/molecules26247416 ](https://doi.org/10.3390/molecules26247416)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/34946495/)；核查层级：公开摘要与书目。
- 证据位置：摘要：DiCys/OPA、six chiral thiols、rice extracts段
- 支持内容：HPLC：OPA＋DiCys与其他五种手性硫醇比较；LC-MS分析氨基酸对映体。
- 样品边界：真实样品：大米水提取物；非蛋白水解液。

### [08] Enantioseparation of dansyl amino acids by HPLC on a monolithic column dynamically coated with a vancomycin derivative.
Pittler E, Schmid MG. Biomedical chromatography : BMC. 2010.
- DOI：[ 10.1002/bmc.1430 ](https://doi.org/10.1002/bmc.1430)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/20954213/)；核查层级：公开摘要与书目。
- 证据位置：摘要：Dansyl amino acids、All investigated compounds were separated段
- 支持内容：HPLC：Dansyl氨基酸在万古霉素衍生物动态涂覆的整体柱上实现对映体分离。
- 样品边界：模型氨基酸衍生物；不声称水解液验证。

### [09] Simultaneous analysis of D- and L-serine in cerebrospinal fluid by use of HPLC.
Sethuraman R, Krishnamoorthy MG, Lee TL, Liu EH, Chiang S, Nishimura W, Sakai M, Minami T, Tachibana S. Clinical chemistry. 2007.
- DOI：[ 10.1373/clinchem.2007.086702 ](https://doi.org/10.1373/clinchem.2007.086702)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/17586591/)；核查层级：公开摘要与书目。
- 证据位置：摘要Methods、Results及Conclusion
- 支持内容：HPLC：Dabsyl-serine经预分离、脱盐，再在Sumichiral柱上拆分D/L并以UV–Vis检测。
- 样品边界：真实样品：脑脊液；非水解液。

### [10] Imaging Peptide and Protein Chirality via Amino Acid Analysis by Chiral × Chiral Two-Dimensional Correlation Liquid Chromatography.
Woiwode U, Reischl RJ, Buckenmaier S, Lindner W, Lämmerhofer M. Analytical chemistry. 2018.
- DOI：[ 10.1021/acs.analchem.8b00676 ](https://doi.org/10.1021/acs.analchem.8b00676)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/29871488/)；核查层级：公开摘要与书目。
- 证据位置：摘要：FMOC-derivatized…peptide hydrolysates；gramicidin and bacitracin段
- 支持内容：HPLC：FMOC氨基酸经奎宁/奎尼丁两维手性色谱分析，给出肽水解物组成与构型图。
- 样品边界：真实肽水解物：gramicidin、bacitracin。

### [11] Comprehensive Online Reversed-Phase × Chiral Two-Dimensional Liquid Chromatography-Mass Spectrometry with Data-Independent Sequential Window Acquisition of All Theoretical Fragment-Ion Spectra-Acquisition for Untargeted Enantioselective Amino Acid Analysis.
Karongo R, Horak J, Lämmerhofer M. Analytical chemistry. 2022.
- DOI：[ 10.1021/acs.analchem.2c03042 ](https://doi.org/10.1021/acs.analchem.2c03042)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/36442145/)；核查层级：公开摘要与书目。
- 证据位置：摘要：AQC、chiral tandem column、two peptide hydrolysate samples及oxytocin段
- 支持内容：HPLC：AQC标记结合反相×手性二维LC–MS/MS，用于治疗肽水解液的组成和构型指认。
- 样品边界：真实肽水解液：包括oxytocin等治疗肽；这是手性LC证据，不是CD证据。

### [12] Gas chromatography-mass spectrometry analysis of amino acid enantiomers as methyl chloroformate derivatives: application to space analysis.
Zampolli MG, Basaglia G, Dondi F, Sternberg R, Szopa C, Pietrogrande MC. Journal of chromatography. A. 2007.
- DOI：[ 10.1016/j.chroma.2006.12.033 ](https://doi.org/10.1016/j.chroma.2006.12.033)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/17222857/)；核查层级：公开摘要与书目。
- 证据位置：摘要：methyl/alkyl chloroformate、Chirasil-L-Val、16 pairs段
- 支持内容：GC：氯甲酸甲酯/醇/吡啶衍生化，结合Chirasil-L-Val及SIM-MS，实现多对氨基酸对映体分析。
- 样品边界：标准品与空间分析方法开发；非蛋白水解液应用。

### [13] Gas chromatographic analysis of amino acid enantiomers in Carbetocin peptide hydrolysates after fast derivatization with pentafluoropropyl chloroformate.
Zahradnícková H, Hartvich P, Simek P, Husek P. Amino acids. 2008.
- DOI：[ 10.1007/s00726-007-0577-1 ](https://doi.org/10.1007/s00726-007-0577-1)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/17721675/)；核查层级：公开摘要与书目。
- 证据位置：题名；摘要：traditional acid hydrolysis、GC/FID、Carbetocin段
- 支持内容：GC：五氟丙基氯甲酸酯快速衍生化，结合手性柱GC/FID分析肽水解液。
- 样品边界：真实肽酸水解液：Carbetocin（卡贝缩宫素）。

### [14] GC separation of amino acid enantiomers via derivatization with heptafluorobutyl chloroformate and Chirasil-L-Val column.
Zahradnícková H, Husek P, Simek P. Journal of separation science. 2009.
- DOI：[ 10.1002/jssc.200900400 ](https://doi.org/10.1002/jssc.200900400)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/19842122/)；核查层级：公开摘要与书目。
- 证据位置：摘要：HFBCF、19 AA enantiomers、except proline/arginine/cystine段
- 支持内容：GC：七氟丁基氯甲酸酯（HFBCF）衍生化后，在Chirasil-Val柱评价氨基酸对映体分离。
- 样品边界：标准品；非全部氨基酸都达到有效分离。

### [15] Enantioseparation of chiral amino acids as the N(O,S)-ethoxycarbonylated diastereomeric esters by achiral dual-capillary column gas chromatography.
Lee J, Kim KR, Won S, Kim JH, Goto J. The Analyst. 2001.
- DOI：[ 10.1039/b106610m ](https://doi.org/10.1039/b106610m)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/11814190/)；核查层级：公开摘要与书目。
- 证据位置：摘要：ethyl chloroformate、chiral alcohol、achiral columns及Yakult段
- 支持内容：GC：氯甲酸乙酯引入EOC保护，再用(S)-(+)-3-甲基-2-丁醇等手性醇酯化；在非手性DB-5/DB-17柱拆分非对映异构体。
- 样品边界：真实样品：发酵乳Yakult；非水解液。

### [16] Analysis of amino acid enantiomers derived from antitumor antibiotics using chiral capillary electrophoresis.
Liu J, Dabrah TT, Matson JA, Klohr SE, Volk KJ, Kerns EH, Lee MS. Journal of pharmaceutical and biomedical analysis. 1997.
- DOI：[ 10.1016/s0731-7085(97)00020-4 ](https://doi.org/10.1016/s0731-7085(97)00020-4)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/9408835/)；核查层级：公开摘要与书目。
- 证据位置：摘要中hydrolysate、dansyl chloride、fluorescein isothiocyanate及应用段
- 支持内容：CE：FITC和Dansyl-Cl。文中分别用于LIF及UV检测，结合金属螯合CE和环糊精MEKC分析抗肿瘤缩肽完全水解液。
- 样品边界：肽完全水解液：BMY-45012及类似物；不是普通游离氨基酸标记的推测。

### [17] Cyclodextrin-Modified Capillary Zone Electrophoresis for the Chiral Analysis of Proline and Hydroxyproline Stereoisomers in Chicken Collagen Hydrolysates.
Vodova M, Babini E, Soglia F, Bordini M, Lioi M, Tengattini S, Temporini C, Gotti R. International journal of molecular sciences. 2025.
- DOI：[ 10.3390/ijms26125832 ](https://doi.org/10.3390/ijms26125832)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/40565295/)；核查层级：全文＋摘要。
- 证据位置：已读全文：2.1、2.2、2.3；3.1、3.3、3.4；Figures 2、5、6
- 支持内容：CZE：(R)-NCS为手性异硫氰酸酯；结合β-CD/DM-β-CD分离Pro及羟脯氨酸异构体。OPA/ME在本法中是预封闭伯胺步骤，不是目标仲胺的主标记试剂。
- 样品边界：真实蛋白水解液：鸡III型胶原；全文明确酸水解和实样应用。

### [18] Chiral separation and determination of excitatory amino acids in brain samples by CE-LIF using dual cyclodextrin system.
Wagner Z, Tábi T, Jakó T, Zachar G, Csillag A, Szökő E. Analytical and bioanalytical chemistry. 2012.
- DOI：[ 10.1007/s00216-012-6384-x ](https://doi.org/10.1007/s00216-012-6384-x)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/22960871/)；核查层级：公开摘要与书目。
- 证据位置：摘要：fluorescent derivatization with 4-fluoro-7-nitro…及brain samples段
- 支持内容：CE：NBD-F标记Asp/Glu；双环糊精CE-LIF分离并测定脑样品中的对映体。
- 样品边界：真实样品：雏鸡脑内游离氨基酸；未声称蛋白质水解液验证。

### [19] CE-LIF chiral separation of aspartic acid and glutamic acid enantiomers using human serum albumin and sodium cholate as dual selectors.
Wang S, Fan L, Cui S. Journal of separation science. 2009.
- DOI：[ 10.1002/jssc.200900341 ](https://doi.org/10.1002/jssc.200900341)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/19697316/)；核查层级：公开摘要与书目。
- 证据位置：摘要：DTAF全名、HSA and SC、compound amino acids injection段
- 支持内容：CE：DTAF标记Asp/Glu，HSA/胆酸钠双选择剂辅助对映体分离。DTAF属于芳香亲核取代标记，不是异硫氰酸酯。
- 样品边界：真实样品：复方氨基酸注射液；非水解液。

### [20] Method for on-line derivatization and separation of aspartic acid enantiomer in pharmaceuticals application by the coupling of flow injection with micellar electrokinetic chromatography.
Cheng Y, Fan L, Chen H, Chen X, Hu Z. Journal of chromatography. A. 2005.
- DOI：[ 10.1016/j.chroma.2005.03.019 ](https://doi.org/10.1016/j.chroma.2005.03.019)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/15887496/)；核查层级：公开摘要与书目。
- 证据位置：摘要：derivatization reagents、chiral selector、micellar chemical及real sample段
- 支持内容：MEKC：OPA＋2-巯基乙醇（ME）标记，β-CD提供手性识别，SDS提供胶束体系。
- 样品边界：真实样品：复方氨基酸注射液；非水解液。

### [21] Separation and enantiomer determination ofOPA-derivatised amino acids by using capillary zone electrophoresis.
Kang L, Buck RH. Amino acids. 1992.
- DOI：[ 10.1007/bf00806080 ](https://doi.org/10.1007/bf00806080)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/24194277/)；核查层级：公开摘要与书目。
- 证据位置：摘要首句及MECC/free solution段
- 支持内容：CE：OPA＋手性硫醇生成非对映异构体；文中研究自由溶液CE和SDS-MECC。
- 样品边界：氨基酸衍生物分离研究；摘要未给真实水解液应用。

### [22] 3-[(3-Dehydroabietamidopropyl)dimethylammonio]-1-propane-sulfonate as a new type of chiral surfactant for enantiomer separation in micellar electrokinetic chromatography.
Zhao S, Wang H, Pan Y, He M, Zhao Z. Journal of chromatography. A. 2007.
- DOI：[ 10.1016/j.chroma.2007.01.139 ](https://doi.org/10.1016/j.chroma.2007.01.139)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/17307190/)；核查层级：公开摘要与书目。
- 证据位置：摘要：NDA-D/L-amino acids、chiral surfactant及6 pairs段
- 支持内容：MEKC：NDA标记氨基酸，DHAMAP手性表面活性剂提供手性分离。
- 样品边界：六对所测衍生物的分离研究；不外推至所有氨基酸或水解液。

### [23] Chiral capillary electrophoresis with UV-excited fluorescence detection for the enantioselective analysis of 9-fluorenylmethoxycarbonyl-derivatized amino acids.
Prior A, Coliva G, de Jong GJ, Somsen GW. Analytical and bioanalytical chemistry. 2018.
- DOI：[ 10.1007/s00216-018-1148-x ](https://doi.org/10.1007/s00216-018-1148-x)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/29808298/)；核查层级：全文＋摘要。
- 证据位置：已读全文：Introduction、Chemicals、AA derivatization、Results and discussion/CSF application
- 支持内容：CE：FMOC-Cl；β-CD辅助手性分离，并用UV激发荧光检测，应用于脑脊液。
- 样品边界：真实样品：脑脊液游离氨基酸；非水解液。

### [24] Enantiomeric separation of amino acids using micellar electrokinetic chromatography after pre-column derivatization with the chiral reagent 1-(9-fluorenyl)-ethyl chloroformate.
Chan KC, Muschik GM, Issaq HJ. Electrophoresis. 1995.
- DOI：[ 10.1002/elps.1150160183 ](https://doi.org/10.1002/elps.1150160183)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/7588518/)；核查层级：公开摘要与书目。
- 证据位置：摘要：(+)-/(-)-FLEC、SDS、diastereomers及FMOC比较段
- 支持内容：MEKC：手性FLEC衍生化后用SDS体系分离非对映异构体；同时比较FMOC＋环糊精的直接分离路线。
- 样品边界：标准品/方法研究；非水解液验证。

### [25] Determination of sequence and absolute configuration of peptide amino acids by HPLC-MS/CD-based detection of liberated N-terminus phenylthiohydantoin amino acids.
Hahn D, Wang W, Choi H, Kang H. Scientific reports. 2022.
- DOI：[ 10.1038/s41598-022-14205-x ](https://doi.org/10.1038/s41598-022-14205-x)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/35717509/)；核查层级：全文＋摘要。
- 证据位置：已读全文：Introduction、Results and discussion、Methods；摘要末句acid hydrolysates
- 支持内容：HPLC–MS/CD：PITC经Edman路线生成PTH-AA，建立对照并用于合成肽和天然缩肽；另分析合成肽酸水解液。
- 样品边界：真实肽及肽酸水解液；不可把PTH证据移植到常规PTC衍生物。

### [26] High-throughput comprehensive analysis of D- and L-amino acids using ultra-high performance liquid chromatography with a circular dichroism (CD) detector and its application to food samples.
Eto S, Yamaguchi M, Bounoshita M, Mizukoshi T, Miyano H. Journal of chromatography. B, Analytical technologies in the biomedical and life sciences. 2011.
- DOI：[ 10.1016/j.jchromb.2011.07.025 ](https://doi.org/10.1016/j.jchromb.2011.07.025)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/21903489/)；核查层级：公开摘要与书目。
- 证据位置：摘要：NBD-F was selected；does not require separation；food samples段
- 支持内容：UHPLC–CD：筛选后选择NBD-F，利用g-factor计算%D，无需在柱上拆分同种氨基酸D/L。
- 样品边界：真实食品样品：黑醋、发酵乳、酸奶；摘要未证明完整蛋白水解流程。

### [27] Tryptophanase-catalyzed L-tryptophan synthesis from D-serine in the presence of diammonium hydrogen phosphate.
Shimada A, Ozaki H, Saito T, Noriko F. International journal of molecular sciences. 2009.
- DOI：[ 10.3390/ijms10062578 ](https://doi.org/10.3390/ijms10062578)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/19582219/)；核查层级：全文＋摘要。
- 证据位置：全文：Results/Determination of optical isomeric form by circular dichroism；Figure 4；Experimental/Tryptophan analyses by use of HPLC。
- 支持内容：CROWNPAK CR(+)先分离D/L-Trp，在线CD-1595于233 nm检测相反椭圆度峰；UV于280 nm检测；无需衍生化。
- 样品边界：标准D/L-Trp及色氨酸酶合成反应液；不是蛋白质水解液。

### [28] A novel potential primary method for quantification of enantiomers by high performance liquid chromatography-circular dichroism.
Luo Y, Wu L, Yang B, Jin Y, Zheng K, He Z. Scientific reports. 2018.
- DOI：[ 10.1038/s41598-018-25682-4 ](https://doi.org/10.1038/s41598-018-25682-4)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/29743524/)；核查层级：全文＋摘要。
- 证据位置：全文：Instruments and reagents；Optimization of the HPLC separation conditions；Figure 3（独立手性纯度检查）；Figures 4F、5D（实际在线CD）；pINS应用。
- 支持内容：未衍生化Phe经非手性HSS T3分离后在线CD检测，定量猪胰岛素水解液Phe。CROWNPAK柱是另一独立的D-Phe光学纯度检查，并不是该在线CD定量路线。
- 样品边界：纯Phe、氨基酸混合物及猪胰岛素水解液。

### [29] Rapid analysis of amino acids using pre-column derivatization.
Bidlingmeyer BA, Cohen SA, Tarvin TL. Journal of chromatography. 1984.
- DOI：[ 10.1016/s0378-4347(00)85133-6 ](https://doi.org/10.1016/s0378-4347(00)85133-6)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/6396315/)；核查层级：公开摘要与书目。
- 证据位置：公开摘要：phenylthiocarbamyl derivative、primary and secondary amino acids、protein hydrolyzates、UV detection。
- 支持内容：PITC形成PTC衍生物，用于蛋白水解物伯胺与仲胺氨基酸的LC–UV分析；支持已有组成分析基线，不证明PTC的CD响应。
- 样品边界：蛋白质水解物及常见氨基酸。

### [30] Synthesis of a fluorescent derivatizing reagent, 6-aminoquinolyl-N-hydroxysuccinimidyl carbamate, and its application for the analysis of hydrolysate amino acids via high-performance liquid chromatography.
Cohen SA, Michaud DP. Analytical biochemistry. 1993.
- DOI：[ 10.1006/abio.1993.1270 ](https://doi.org/10.1006/abio.1993.1270)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/8317704/)；核查层级：公开摘要与书目。
- 证据位置：公开摘要：stable unsymmetric urea、pH range 8.2–10.0、direct injection。
- 支持内容：AQC在快速一步反应中形成稳定非对称脲；摘要明确可直接进样，pH和试剂过量影响反应收率。
- 样品边界：氨基酸及蛋白水解物；荧光检测证据，不是在线CD证据。

### [31] Analysis of amino acid composition in proteins of animal tissues and foods as pre-column o-phthaldialdehyde derivatives by HPLC with fluorescence detection.
Dai Z, Wu Z, Jia S, Wu G. Journal of chromatography. B, Analytical technologies in the biomedical and life sciences. 2014.
- DOI：[ 10.1016/j.jchromb.2014.03.025 ](https://doi.org/10.1016/j.jchromb.2014.03.025)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/24731621/)；核查层级：公开摘要与书目。
- 证据位置：公开摘要：primary AA、2-mercaptoethanol/3-mercaptopropionic acid、rapid formation、easy automation。
- 支持内容：OPA与伯胺/非手性硫醇生成荧光衍生物；文献总结快速柱前反应、自动化和动物组织/食品蛋白水解组成分析。
- 样品边界：蛋白水解物及食品/动物组织组成分析；非D/L-CD方法。

### [32] The stability of the o-phthalaldehyde/2-mercaptoethanol derivatives of amino acids: an investigation using high-pressure liquid chromatography with a precolumn derivatization technique.
Cooper JD, Ogden G, McIntosh J, Turnell DC. Analytical biochemistry. 1984.
- DOI：[ 10.1016/0003-2697(84)90522-0 ](https://doi.org/10.1016/0003-2697(84)90522-0)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/6517322/)；核查层级：公开摘要与书目。
- 证据位置：公开摘要：stable on the HPLC column、optimal conditions。
- 支持内容：研究OPA/2-巯基乙醇氨基酸衍生物稳定性，指出在所述HPLC柱上稳定并给出适宜条件；不能把OPA所有体系一概认定不稳定。
- 样品边界：OPA/2-巯基乙醇衍生物与柱前HPLC方法研究。

### [33] Comparison of different derivatisation for amino acids determination of foie gras by high performance liquid chromatography (HPLC).
Wei R, Teng Y, Ning R, Luo Z, Bai L, Han C. British poultry science. 2024.
- DOI：[ 10.1080/00071668.2024.2375723 ](https://doi.org/10.1080/00071668.2024.2375723)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/39076129/)；核查层级：公开摘要与书目。
- 证据位置：公开摘要：三种衍生化组、17种氨基酸、运行时间及与自动氨基酸分析仪比较。
- 支持内容：比较OPA–FMOC、PITC、AQC对鹅肥肝氨基酸组成分析的表现；结果依方案和基质，不是OPA单独体系或在线CD性能的普遍排名。
- 样品边界：鹅肥肝组成分析；OPA–FMOC为组合路线，不等同本课题OPA＋硫醇。

### [34] Enantioselective separation of amino acids as biomarkers indicating life in extraterrestrial environments.
Pietrogrande MC. Analytical and bioanalytical chemistry. 2013.
- DOI：[ 10.1007/s00216-013-6915-0 ](https://doi.org/10.1007/s00216-013-6915-0)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/23539098/)；核查层级：公开摘要与书目。
- 证据位置：摘要中silylation reagent…unsuitable for detection of homochirality段
- 支持内容：GC删除项审查：综述区分普通GC挥发化和对映体测定；常用MTBSTFA硅烷化被明确指出不适于其讨论的homochirality检测。不能把所有硅烷化剂概括为成熟手性氨基酸方案。
- 样品边界：方法学综述；不据此断言所有硅烷化体系都绝不可能手性分离。

### [35] Comparison of derivatization and chromatographic methods for GC-MS analysis of amino acid enantiomers in physiological samples.
Waldhier MC, Dettmer K, Gruber MA, Oefner PJ. Journal of chromatography. B, Analytical technologies in the biomedical and life sciences. 2010.
- DOI：[ 10.1016/j.jchromb.2010.03.021 ](https://doi.org/10.1016/j.jchromb.2010.03.021)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/20371216/)；核查层级：公开摘要与书目。
- 证据位置：摘要：racemization during derivatization precluded accurate quantification及MCF段
- 支持内容：GC限制性证据：比较氟化/非氟化酸酐及氯甲酸酯；PFPA/七氟丁醇虽灵敏，但衍生化消旋妨碍准确对映体定量，MCF路线可避免其问题。
- 样品边界：真实样品：血清、尿液；为删除/后置酯化酰化组合提供具体理由，不表示这类反应不存在。


# 本次全稿复核与修正记录
依据此前保留的文献全文、公开摘要和书目记录复核；未将仅摘要可读的文献描述为已读全文。

## Trp/Phe错位
移出试剂容器，在图下单列“未衍生化实例（非试剂）”；第2页缩略图同步更新。

证据与边界：[27]手性柱＋在线CD分析Trp；[28]非手性HSS T3＋在线CD分析Phe。两者是分析物，不是试剂。

## 试剂与产物混写
PITC–PTH改为PITC → PTH，备注注明试剂→产物。

证据与边界：[25]为PTH路线，不能据此认定常规PTC有相同性能。

## OPA适用范围
第4页新增“不覆盖Pro等仲胺”；需固定硫醇、计时和稳定性条件。

证据与边界：[31]常规OPA/硫醇针对伯胺；不代表所有改进OPA反应都不可能处理仲胺。

## 机制与试剂并非逐一全兼容
第1页备注明确：同一平台列出的路线、试剂、检测器是代表实例，不能任意组合。

证据与边界：HPLC/GC的两种策略有不同文献；CE使用溶液手性选择剂，不能称手性固定相。

## HPLC-CD分类层级
备注明确HPLC-CD是HPLC的检测联用形式，单列是为展示研究重点。

证据与边界：不是与HPLC互斥的新分离原理；非手性柱一般不拆分同一氨基酸D/L。

## 原生氨基酸的适用性
保留限定：Trp为标准品/酶反应液实例，Phe为胰岛素水解液实例。

证据与边界：不可外推未衍生化Leu、Lys均能获得足够CD；[28]手性柱检查与在线CD定量是两套操作。

## AQC分类
保留上位功能分类“氨基酰化类”，注明不等同氯甲酸酯。

证据与边界：AQC产物为非对称脲[30]，FMOC产物为氨基甲酸酯；不得把AQC写成氯甲酸酯。

## 文献筛选与ee校准
保留修正后的消旋风险、单独CD验证、带符号经验响应比、独立QC等。

证据与边界：[25–26]支持总体思路，9水平/重复数/QC是拟议实验，不是文献原样SOP或已验证结果。

## 检测器来源完整性
补齐原备注D1、D2的完整书目；不改动[01–35]编号。

证据与边界：HPLC荧光与CE-MS各有具体氨基酸手性分析文献，不把理论兼容性当应用证据。

## 方法覆盖范围
明确本图为已核查的代表性方法，不声称所有GC/CE试剂均已穷尽。

证据与边界：NDA等名称不构成完整反应配方；具体共试剂、条件以原文为准。

# 第1页逐项文献映射

- HPLC：FITC/GITC/FDAA/FDLA/NBD-F：[01]／[02]／[02–03]／[04]／[05]
- HPLC：OPA+NAC或IBLC、OPA+DiCys：[02,06]；[07]
- HPLC：Dansyl-Cl/Dabsyl-Cl/FMOC-Cl/AQC：[08]／[09]／[10]／[11]
- GC：甲酯/五氟丙基/七氟丁基氯甲酸酯：[12]／[13]／[14]
- GC：氯甲酸乙酯＋手性醇：[15]
- CE：FITC/(R)-NCS/NBD-F/DTAF：[16]／[17]／[18]／[19]
- CE：OPA+ME/OPA+手性硫醇/NDA：[20]／[21]／[22]
- CE：Dansyl-Cl/FMOC-Cl/FLEC：[16]／[23]／[24]
- HPLC-CD：PITC→PTH/NBD-F：[25]／[26]
- 图下未衍生化分析物实例：Trp/Phe：[27]／[28]
- 检测器：HPLC UV/荧光/MS-MS：[02]／D1／[11]
- 检测器：GC FID/MS；CE UV/荧光/MS：[13]/[12]；[16]/[16–17,23]/D2
- 检测器：HPLC-CD CD/UV/MS：[25–28]，MS见[25]

# 检测方式补充文献


[D1] Determination of d-serine and related neuroactive amino acids in human plasma by high-performance liquid chromatography with fluorimetric detection.
Grant SL, Shulman Y, Tibbo P, Hampson DR, Baker GB.
Journal of chromatography. B, Analytical technologies in the biomedical and life sciences. 2006; 844: 278-282.
DOI: 10.1016/j.jchromb.2006.07.022
https://doi.org/10.1016/j.jchromb.2006.07.022
核查层级：公开摘要与书目。支持：HPLC：OPA/IBLC衍生化，人血浆D-Ser及相关氨基酸荧光检测。

[D2] Enantioselective analysis of proteinogenic amino acids in cerebrospinal fluid by capillary electrophoresis-mass spectrometry.
Prior A, Sánchez-Hernández L, Sastre-Toraño J, Marina ML, de Jong GJ, Somsen GW.
Electrophoresis. 2016; 37: 2410-2419.
DOI: 10.1002/elps.201600015
https://doi.org/10.1002/elps.201600015
核查层级：公开摘要与书目。支持：CE：FMOC衍生化、β-CD选择剂、CE-MS，脑脊液加标应用。

# 单纯CD氨基酸衍生化方法（新增36–41）
建议单独增加CD行：这里指衍生化后直接测定比色皿CD/UV光谱，不含色谱分离，不是另一种手性拆分。新增36–41编号在原01–35后续接，原编号和D1/D2不变。主图只列已核对的共价标记，不把金属配位/主客体非共价传感器当作衍生化试剂。

## 必须更正的缩写
DiCys在[7]中为N,N-二甲基-L-半胱氨酸（N,N-dimethyl-L-cysteine），有游离巯基。上一条回复将其解释为N,N′-二乙酰胱氨酸并称需要还原，是错误的；请以本次更正为准。

## [36] OPA＋对甲苯硫酚（p-TT）
反应类别：芳香二醛三组分缩合
完整文献：A rapid and sensitive method for chiroptical sensing of α-amino acids <i>via</i> click-like labeling with <i>o</i>-phthalaldehyde and <i>p</i>-toluenethiol.
作者：Li B, Zhang J, Li L, Chen G.
Chemical science. 2020.
DOI：10.1039/d0sc05749e
https://doi.org/10.1039/d0sc05749e
证据位置与层级：全文；Fig.1–3、Table1与脚注14；1分钟/12小时稳定性为文中具体条件，不泛化到全部OPA体系。
适用对象与限制：伯胺α氨基酸，Pro不反应，Cys有特殊产物，Lys存在多位点产物。Leu/Lys等有ee相关数据。单一AA标准体系，不是完整蛋白水解液逐组分分析。

## [37] FDNB（Sanger试剂，1-氟-2,4-二硝基苯）
反应类别：芳香亲核取代（SNAr）
完整文献：Repurposing the Sanger Reagent for Optical Sensing of the Concentration and Enantiomeric Ratio of Chiral Amines, Amino Alcohols, and Amino Acids.
作者：Kariapper FS, Wolf AU, Wolf C.
Chirality. 2025.
DOI：10.1002/chir.70062
https://doi.org/10.1002/chir.70062
证据位置与层级：全文；Fig.3氨基酸范围；Fig.4–5反应跟踪和定量示例，定量主例为1-苯乙胺，不能把其精度当成每种AA结果。
适用对象与限制：氨基酸及谷胱甘肽有CD响应实例；本文混合测量并非HPLC-CD。

## [38] 文献中的芳基氟探针
反应类别：芳香亲核取代（SNAr）
完整文献：Quantitative Chiroptical Sensing of Free Amino Acids, Biothiols, Amines, and Amino Alcohols with an Aryl Fluoride Probe.
作者：Thanzeel FY, Sripada A, Wolf C.
Journal of the American Chemical Society. 2019.
DOI：10.1021/jacs.9b07588
https://doi.org/10.1021/jacs.9b07588
证据位置与层级：公开摘要与书目；未读取原文结构/完整条件，不凭摘要猜测系统名称。
适用对象与限制：19种标准氨基酸及Asp、Pro、Met、Cys、Ala等定量示例；混合物验证不等于任意蛋白水解液均适用。

## [39] 4-氯-3-硝基香豆素
反应类别：共轭加成–消除
完整文献：Click chemistry enables quantitative chiroptical sensing of chiral compounds in protic media and complex mixtures.
作者：Thanzeel FY, Balaraman K, Wolf C.
Nature communications. 2018.
DOI：10.1038/s41467-018-07695-9
https://doi.org/10.1038/s41467-018-07695-9
证据位置与层级：全文；Results/Chiroptical click chemistry sensing；Fig.1与Supplementary Figures29–69。
适用对象与限制：包含Asp、Thr、Cys等氨基酸及其他胺/醇；复杂混合物主验证为不对称反应液，不是多种AA水解液。

## [40] 萘基–香豆素醛探针3
反应类别：醛胺缩合（动态共价）
完整文献：A Racemic Naphthyl-Coumarin-Based Probe for Quantitative Enantiomeric Excess Analysis of Amino Acids and Enantioselective Sensing of Amines and Amino Alcohols.
作者：Li JY, Wang L, Yin LP, Jiang XM, Guo K, Zhang C, Yu SS, Yu XQ, Wang Q.
ChemistryOpen. 2022.
DOI：10.1002/open.202200088
https://doi.org/10.1002/open.202200088
证据位置与层级：全文；Fig.2–4、Scheme2、Quantitative Enantiomeric Excess Analysis。
适用对象与限制：Val/Phe等标准品构型与ee；甲醇/KOH体系，约5–6小时；外消旋动态轴手性探针，不能称为严格非手性试剂。

## [41] Br-Coumarin探针
反应类别：摘要不足以确定完整反应分类
完整文献：A bifunctional coumarin-based CD probe for chiral analysis of amino acids in aqueous solution.
作者：Han M, Duan W, Huo Y, Huang X, Yu W, Li Y, Pu L.
Spectrochimica acta. Part A, Molecular and biomolecular spectroscopy. 2025.
DOI：10.1016/j.saa.2024.125654
https://doi.org/10.1016/j.saa.2024.125654
证据位置与层级：公开摘要与书目；尚未核实结构和完整配方，仅列入补充检索表，不进入主图反应类别。
适用对象与限制：摘要称THF/水1:4中16种AA，Cys/Pro/Phe的浓度与ee示例。

## PPT新增一行对应
芳香二醛→[36]；SNAr→[37–38]；共轭加成–消除→[39]；醛胺缩合→[40]。[41]只列文献表，不推断完整反应类别。

## OPA候选的证据升级
[36]直接证明OPA＋对甲苯硫酚的CD/UV读出和ee关系；故不再笼统说OPA没有CD文献。该硫醇无固定手性中心，不等于NAC/IBLC/DiCys手性硫醇路线。反应时间/稳定性/检出水平需限于文中条件。

## 与课题直接相关
[36]对Leu等作g–ee校准，对Lys报告多位点衍生物造成的浓度线性偏离，同时g–ee关系可用；Phe在底物范围。需单独确认Lys定量峰、衍生度与响应。

## ee方案如何利用新文献
可按[36]先复现直接CD/UV随ee变化，再验证LC流动相和在线检测。文中物理g与本PPT经验峰面积比R仍须区分；9点设计依旧为拟议。

## 为什么不能直接用于完整水解液
没有色谱时，多种衍生氨基酸的CD/UV信号叠加。单一AA的校准不能识别混合物中每种AA的ee；应先分离、纯化、建立验证过的选择性体系，或采用HPLC-CD。

## 配位/非共价探针如何处理
有相关CD识别研究，但不属于共价衍生化，未混入本行。完整水解液适用性同样需要另证。

## 检索与阅读边界
通过Europe PMC按circular dichroism、amino acids、derivatization、sensing、coumarin等检索并追溯参考文献。[36–37,39–40]阅读全文，[38,41]仅公开摘要与书目。不声称穷尽所有历史体系。