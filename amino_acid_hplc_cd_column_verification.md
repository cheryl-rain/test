# HPLC–CD：手性柱与未衍生化路线核查

独立检索与相关全文核查：2026-10-28。检索Europe PMC/PubMed及Crossref；重点查方法、流路、检测器和色谱图，排除同一论文分别进行手性HPLC与离线CD造成的误判。

## 结论与PPT修改

- HPLC–CD氨基酸分析并非仅有“非手性衍生化”一种路线。已找到未衍生化氨基酸直接分析，以及手性固定相分离后在线CD检测的明确原始文献。
- 最直接的手性柱证据是[27]：CROWNPAK CR(+)分离D/L-Trp，在线CD-1595在233 nm测椭圆度；正文Figure 4展示D/L峰，不只是仪器清单或离线CD光谱。
- [28]提供未衍生化Phe与猪胰岛素水解液的在线HPLC–CD案例，但其在线定量用的是非手性HSS T3；同文CROWNPAK只是另外的D-Phe光学纯度检查，不能混写为手性柱在线CD定量。
- 新版PPT的HPLC–CD行改为“①手性固定相；②非手性分离”，右侧增加“无需衍生化：Trp[27]、Phe[28]”。衍生化与否是样品处理维度，固定相是否手性是分离维度，两者不等同。
- 选择原则页仍保留本课题的PITC/AQC/OPA候选，但注明衍生化并非HPLC–CD普遍必要条件；Phe/Leu/Lys能否直接检测或经衍生化达到要求，须按目标氨基酸验证。
- 编号1–26保持不变；新增直接路线文献为27、28；原末尾两篇删除项/限制性讨论来源移至29、30。

## 已有直接证据的路线

| 路线 | 代表体系 | 应用边界 |
|---|---|---|
| 非手性衍生化＋非手性色谱＋CD | [25] PITC–PTH；[26] NBD-F | 分别为PTH/肽及肽水解液，以及NBD/食品样品。 |
| 未衍生化＋手性柱＋在线CD | [27] Trp，CROWNPAK CR(+) | D/L标准及酶反应液；不能泛称蛋白水解液验证。 |
| 未衍生化＋非手性柱＋在线CD | [28] Phe，HSS T3 | 氨基酸混合物及猪胰岛素水解液。 |

## 新增原始文献及具体位置

### [27] Tryptophanase-catalyzed L-tryptophan synthesis from D-serine in the presence of diammonium hydrogen phosphate.
Shimada A, Ozaki H, Saito T, Noriko F. International journal of molecular sciences. 2009.
- DOI：[ 10.3390/ijms10062578 ](https://doi.org/10.3390/ijms10062578)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/19582219/)；[开放全文](https://pmc.ncbi.nlm.nih.gov/articles/PMC2705506/)。
- 核查层级：全文＋摘要。
- 直接证据：CROWNPAK CR(+)先分离D/L-Trp，在线CD-1595于233 nm检测相反椭圆度峰；UV于280 nm检测；无需衍生化。
- 原文位置：全文：Results/Determination of optical isomeric form by circular dichroism；Figure 4；Experimental/Tryptophan analyses by use of HPLC。
- 样品边界：标准D/L-Trp及色氨酸酶合成反应液；不是蛋白质水解液。

### [28] A novel potential primary method for quantification of enantiomers by high performance liquid chromatography-circular dichroism.
Luo Y, Wu L, Yang B, Jin Y, Zheng K, He Z. Scientific reports. 2018.
- DOI：[ 10.1038/s41598-018-25682-4 ](https://doi.org/10.1038/s41598-018-25682-4)
- [PubMed](https://pubmed.ncbi.nlm.nih.gov/29743524/)；[开放全文](https://pmc.ncbi.nlm.nih.gov/articles/PMC5943587/)。
- 核查层级：全文＋摘要。
- 直接证据：未衍生化Phe经非手性HSS T3分离后在线CD检测，定量猪胰岛素水解液Phe。CROWNPAK柱是另一独立的D-Phe光学纯度检查，并不是该在线CD定量路线。
- 原文位置：全文：Instruments and reagents；Optimization of the HPLC separation conditions；Figure 3（独立手性纯度检查）；Figures 4F、5D（实际在线CD）；pINS应用。
- 样品边界：纯Phe、氨基酸混合物及猪胰岛素水解液。

### [27] 为什么可以认定为在线手性柱–CD？

正文说明样品先在Crownpack CR(+)柱分离，随后用CD-1595检测；CD波长233 nm。Figure 4a为D/L-Trp标准品，4b为酶合成产物。D-Trp约11.4 min负峰、L-Trp约14.6 min正峰；这是该波长及条件下的结果，不是D/L与CD正负号的通用规则。UV另在280 nm监测。

### [28] 为什么不能误判为手性柱–CD？

Methods的CROWNPAK CR+用于估计D-Phe内标的对映体纯度，检测波长200 nm，结果为Figure 3；实际在线CD定量的HPLC分离使用Waters HSS T3。Figure 4F和Figure 5D展示在线CD结果，CD定量波长216.5 nm。

## 每个PPT位置对应的文献

| 方法／位置 | 试剂或直接分析体系 | 来源 |
|---|---|---|
| HPLC/UHPLC／异硫氰酸酯类 | FITC | [01] |
| HPLC/UHPLC／异硫氰酸酯类 | GITC | [02] |
| HPLC/UHPLC／芳香亲核取代类 | FDAA | [02], [03] |
| HPLC/UHPLC／芳香亲核取代类 | FDLA | [04] |
| HPLC/UHPLC／芳香亲核取代类 | NBD-F | [05] |
| HPLC/UHPLC／OPA类 | OPA＋NAC | [06] |
| HPLC/UHPLC／OPA类 | OPA＋IBLC | [02], [06] |
| HPLC/UHPLC／OPA类 | OPA＋DiCys | [07] |
| HPLC/UHPLC／磺酰氯类 | Dansyl-Cl | [08] |
| HPLC/UHPLC／磺酰氯类 | Dabsyl-Cl | [09] |
| HPLC/UHPLC／氨基酰化类 | FMOC-Cl | [10] |
| HPLC/UHPLC／氨基酰化类 | AQC | [11] |
| GC／氯甲酸酯类 | 氯甲酸甲酯（MCF） | [12] |
| GC／氯甲酸酯类 | 五氟丙基氯甲酸酯（PFPCF） | [13] |
| GC／氯甲酸酯类 | 七氟丁基氯甲酸酯（HFBCF） | [14] |
| GC／氯甲酸酯＋手性醇组合 | 氯甲酸乙酯＋(S)-(+)-3-甲基-2-丁醇 | [15] |
| CE／异硫氰酸酯类 | FITC | [16] |
| CE／异硫氰酸酯类 | (R)-NCS | [17] |
| CE／芳香亲核取代类 | NBD-F | [18] |
| CE／芳香亲核取代类 | DTAF | [19] |
| CE／芳香二醛类 | OPA＋2-巯基乙醇（ME） | [20] |
| CE／芳香二醛类 | OPA＋手性硫醇 | [21] |
| CE／芳香二醛类 | NDA | [22] |
| CE／磺酰氯类 | Dansyl-Cl | [16] |
| CE／氨基酰化类 | FMOC-Cl | [23] |
| CE／氨基酰化类 | FLEC | [24] |
| HPLC–CD／异硫氰酸酯/后续转化路线 | PITC–PTH | [25] |
| HPLC–CD／芳香亲核取代类 | NBD-F | [26] |
| HPLC–CD／无需衍生化/手性固定相 | 未衍生化Trp＋CROWNPAK CR(+)＋在线CD | [27] |
| HPLC–CD／无需衍生化/非手性分离 | 未衍生化Phe＋HSS T3＋在线CD | [28] |

## 完整参考文献（更新为30篇）

### [01] Chiral nano-liquid chromatography-mass spectrometry applied to amino acids analysis for orange juice profiling.
D'Orazio G, Cifuentes A, Fanali S. Food chemistry. 2008.
- DOI：[ 10.1016/j.foodchem.2007.11.062 ](https://doi.org/10.1016/j.foodchem.2007.11.062)
- 核查层级：公开摘要与书目；证据位置：摘要：FITC、vancomycin-modified silica-diol、orange juice段。
- 支持内容：HPLC：FITC标记后在万古霉素手性固定相上进行nano-LC–MS分析。
- 适用范围：真实样品：橙汁；非水解液。

### [02] Chirality determination of unusual amino acids using precolumn derivatization and liquid chromatography-electrospray ionization mass spectrometry.
Hess S, Gustafson KR, Milanowski DJ, Alvira E, Lipton MA, Pannell LK. Journal of chromatography. A. 2004.
- DOI：[ 10.1016/j.chroma.2004.02.068 ](https://doi.org/10.1016/j.chroma.2004.02.068)
- 核查层级：公开摘要与书目；证据位置：摘要首句四种试剂及RP-HPLC/UV/MS段。
- 支持内容：HPLC：直接比较FDAA、GITC、S-NIFE及OPA–IBLC；经反相HPLC–UV/ESI-MS分析非常见氨基酸立体异构体。
- 适用范围：非常见氨基酸及海洋肽应用方向；摘要不足以核实全部具体水解步骤。

### [03] LC-MS/MS-Based Separation and Quantification of Marfey's Reagent Derivatized Proteinogenic Amino Acid DL-Stereoisomers.
Ayon NJ, Sharma AD, Gutheil WG. Journal of the American Society for Mass Spectrometry. 2019.
- DOI：[ 10.1007/s13361-018-2093-9 ](https://doi.org/10.1007/s13361-018-2093-9)
- 核查层级：公开摘要与书目；证据位置：摘要：Marfey derivatization、19 pairs、MRSA extracts段。
- 支持内容：HPLC：FDAA/Marfey衍生化结合反相LC–MS/MS，实现19对常见手性氨基酸的分离定量。
- 适用范围：标准品与MRSA提取物；非蛋白水解液验证。

### [04] Reliable and sensitive analysis of amino acids in the peptidoglycan of actinomycetes using the advanced Marfey's method.
Nozawa Y, Sakai N, Arai K, Kawasaki Y, Harada K. Journal of microbiological methods. 2007.
- DOI：[ 10.1016/j.mimet.2007.05.003 ](https://doi.org/10.1016/j.mimet.2007.05.003)
- 核查层级：公开摘要与书目；证据位置：摘要：L-FDLA/D-FDLA、acid hydrolysis、cell wall段。
- 支持内容：HPLC：L-/D-FDLA advanced Marfey法，结合LC/MS确定细胞壁氨基酸构型。
- 适用范围：真实酸水解样品：放线菌细胞壁肽聚糖；肽聚糖不等同于普通蛋白质。

### [05] Simultaneous determination of hydrophilic amino acid enantiomers in mammalian tissues and physiological fluids applying a fully automated micro-two-dimensional high-performance liquid chromatographic concept.
Hamase K, Miyoshi Y, Ueno K, Han H, Hirano J, Morikawa A, Mita M, Kaneko T, Lindner W, Zaitsu K. Journal of chromatography. A. 2010.
- DOI：[ 10.1016/j.chroma.2009.09.002 ](https://doi.org/10.1016/j.chroma.2009.09.002)
- 核查层级：公开摘要与书目；证据位置：摘要：NBD-F、Pirkle type enantioselective column、rat plasma/urine段。
- 支持内容：HPLC：NBD-F标记后，反相一维分离组分，Pirkle型手性二维拆分对映体。
- 适用范围：真实样品：大鼠血浆、尿液等；非水解液。

### [06] High-performance liquid chromatography evaluation of the enantiomeric purity of amino acids by means of automated precolumn derivatization with ortho-phthalaldehyde and chiral thiols.
Kühnreich R, Holzgrabe U. Chirality. 2016.
- DOI：[ 10.1002/chir.22660 ](https://doi.org/10.1002/chir.22660)
- 核查层级：公开摘要与书目；证据位置：摘要：N-acetyl-L-cysteine、N-isobutyryl-L-cysteine、PFP column段。
- 支持内容：HPLC：OPA＋NAC或IBLC自动柱前衍生化，普通PFP柱分离非对映衍生物并评价对映体杂质。
- 适用范围：氨基酸原料/标准品对映体纯度；非水解液。

### [07] Dimethylcysteine (DiCys)/o-Phthalaldehyde Derivatization for Chiral Metabolite Analyses: Cross-Comparison of Six Chiral Thiols.
Lkhagva A, Tai HC. Molecules (Basel, Switzerland). 2021.
- DOI：[ 10.3390/molecules26247416 ](https://doi.org/10.3390/molecules26247416)
- 核查层级：公开摘要与书目；证据位置：摘要：DiCys/OPA、six chiral thiols、rice extracts段。
- 支持内容：HPLC：OPA＋DiCys与其他五种手性硫醇比较；LC-MS分析氨基酸对映体。
- 适用范围：真实样品：大米水提取物；非蛋白水解液。

### [08] Enantioseparation of dansyl amino acids by HPLC on a monolithic column dynamically coated with a vancomycin derivative.
Pittler E, Schmid MG. Biomedical chromatography : BMC. 2010.
- DOI：[ 10.1002/bmc.1430 ](https://doi.org/10.1002/bmc.1430)
- 核查层级：公开摘要与书目；证据位置：摘要：Dansyl amino acids、All investigated compounds were separated段。
- 支持内容：HPLC：Dansyl氨基酸在万古霉素衍生物动态涂覆的整体柱上实现对映体分离。
- 适用范围：模型氨基酸衍生物；不声称水解液验证。

### [09] Simultaneous analysis of D- and L-serine in cerebrospinal fluid by use of HPLC.
Sethuraman R, Krishnamoorthy MG, Lee TL, Liu EH, Chiang S, Nishimura W, Sakai M, Minami T, Tachibana S. Clinical chemistry. 2007.
- DOI：[ 10.1373/clinchem.2007.086702 ](https://doi.org/10.1373/clinchem.2007.086702)
- 核查层级：公开摘要与书目；证据位置：摘要Methods、Results及Conclusion。
- 支持内容：HPLC：Dabsyl-serine经预分离、脱盐，再在Sumichiral柱上拆分D/L并以UV–Vis检测。
- 适用范围：真实样品：脑脊液；非水解液。

### [10] Imaging Peptide and Protein Chirality via Amino Acid Analysis by Chiral × Chiral Two-Dimensional Correlation Liquid Chromatography.
Woiwode U, Reischl RJ, Buckenmaier S, Lindner W, Lämmerhofer M. Analytical chemistry. 2018.
- DOI：[ 10.1021/acs.analchem.8b00676 ](https://doi.org/10.1021/acs.analchem.8b00676)
- 核查层级：公开摘要与书目；证据位置：摘要：FMOC-derivatized…peptide hydrolysates；gramicidin and bacitracin段。
- 支持内容：HPLC：FMOC氨基酸经奎宁/奎尼丁两维手性色谱分析，给出肽水解物组成与构型图。
- 适用范围：真实肽水解物：gramicidin、bacitracin。

### [11] Comprehensive Online Reversed-Phase × Chiral Two-Dimensional Liquid Chromatography-Mass Spectrometry with Data-Independent Sequential Window Acquisition of All Theoretical Fragment-Ion Spectra-Acquisition for Untargeted Enantioselective Amino Acid Analysis.
Karongo R, Horak J, Lämmerhofer M. Analytical chemistry. 2022.
- DOI：[ 10.1021/acs.analchem.2c03042 ](https://doi.org/10.1021/acs.analchem.2c03042)
- 核查层级：公开摘要与书目；证据位置：摘要：AQC、chiral tandem column、two peptide hydrolysate samples及oxytocin段。
- 支持内容：HPLC：AQC标记结合反相×手性二维LC–MS/MS，用于治疗肽水解液的组成和构型指认。
- 适用范围：真实肽水解液：包括oxytocin等治疗肽；这是手性LC证据，不是CD证据。

### [12] Gas chromatography-mass spectrometry analysis of amino acid enantiomers as methyl chloroformate derivatives: application to space analysis.
Zampolli MG, Basaglia G, Dondi F, Sternberg R, Szopa C, Pietrogrande MC. Journal of chromatography. A. 2007.
- DOI：[ 10.1016/j.chroma.2006.12.033 ](https://doi.org/10.1016/j.chroma.2006.12.033)
- 核查层级：公开摘要与书目；证据位置：摘要：methyl/alkyl chloroformate、Chirasil-L-Val、16 pairs段。
- 支持内容：GC：氯甲酸甲酯/醇/吡啶衍生化，结合Chirasil-L-Val及SIM-MS，实现多对氨基酸对映体分析。
- 适用范围：标准品与空间分析方法开发；非蛋白水解液应用。

### [13] Gas chromatographic analysis of amino acid enantiomers in Carbetocin peptide hydrolysates after fast derivatization with pentafluoropropyl chloroformate.
Zahradnícková H, Hartvich P, Simek P, Husek P. Amino acids. 2008.
- DOI：[ 10.1007/s00726-007-0577-1 ](https://doi.org/10.1007/s00726-007-0577-1)
- 核查层级：公开摘要与书目；证据位置：题名；摘要：traditional acid hydrolysis、GC/FID、Carbetocin段。
- 支持内容：GC：五氟丙基氯甲酸酯快速衍生化，结合手性柱GC/FID分析肽水解液。
- 适用范围：真实肽酸水解液：Carbetocin（卡贝缩宫素）。

### [14] GC separation of amino acid enantiomers via derivatization with heptafluorobutyl chloroformate and Chirasil-L-Val column.
Zahradnícková H, Husek P, Simek P. Journal of separation science. 2009.
- DOI：[ 10.1002/jssc.200900400 ](https://doi.org/10.1002/jssc.200900400)
- 核查层级：公开摘要与书目；证据位置：摘要：HFBCF、19 AA enantiomers、except proline/arginine/cystine段。
- 支持内容：GC：七氟丁基氯甲酸酯（HFBCF）衍生化后，在Chirasil-Val柱评价氨基酸对映体分离。
- 适用范围：标准品；非全部氨基酸都达到有效分离。

### [15] Enantioseparation of chiral amino acids as the N(O,S)-ethoxycarbonylated diastereomeric esters by achiral dual-capillary column gas chromatography.
Lee J, Kim KR, Won S, Kim JH, Goto J. The Analyst. 2001.
- DOI：[ 10.1039/b106610m ](https://doi.org/10.1039/b106610m)
- 核查层级：公开摘要与书目；证据位置：摘要：ethyl chloroformate、chiral alcohol、achiral columns及Yakult段。
- 支持内容：GC：氯甲酸乙酯引入EOC保护，再用(S)-(+)-3-甲基-2-丁醇等手性醇酯化；在非手性DB-5/DB-17柱拆分非对映异构体。
- 适用范围：真实样品：发酵乳Yakult；非水解液。

### [16] Analysis of amino acid enantiomers derived from antitumor antibiotics using chiral capillary electrophoresis.
Liu J, Dabrah TT, Matson JA, Klohr SE, Volk KJ, Kerns EH, Lee MS. Journal of pharmaceutical and biomedical analysis. 1997.
- DOI：[ 10.1016/s0731-7085(97)00020-4 ](https://doi.org/10.1016/s0731-7085(97)00020-4)
- 核查层级：公开摘要与书目；证据位置：摘要中hydrolysate、dansyl chloride、fluorescein isothiocyanate及应用段。
- 支持内容：CE：FITC和Dansyl-Cl。文中分别用于LIF及UV检测，结合金属螯合CE和环糊精MEKC分析抗肿瘤缩肽完全水解液。
- 适用范围：肽完全水解液：BMY-45012及类似物；不是普通游离氨基酸标记的推测。

### [17] Cyclodextrin-Modified Capillary Zone Electrophoresis for the Chiral Analysis of Proline and Hydroxyproline Stereoisomers in Chicken Collagen Hydrolysates.
Vodova M, Babini E, Soglia F, Bordini M, Lioi M, Tengattini S, Temporini C, Gotti R. International journal of molecular sciences. 2025.
- DOI：[ 10.3390/ijms26125832 ](https://doi.org/10.3390/ijms26125832)
- 核查层级：全文＋摘要；证据位置：已读全文：2.1、2.2、2.3；3.1、3.3、3.4；Figures 2、5、6。
- 支持内容：CZE：(R)-NCS为手性异硫氰酸酯；结合β-CD/DM-β-CD分离Pro及羟脯氨酸异构体。OPA/ME在本法中是预封闭伯胺步骤，不是目标仲胺的主标记试剂。
- 适用范围：真实蛋白水解液：鸡III型胶原；全文明确酸水解和实样应用。

### [18] Chiral separation and determination of excitatory amino acids in brain samples by CE-LIF using dual cyclodextrin system.
Wagner Z, Tábi T, Jakó T, Zachar G, Csillag A, Szökő E. Analytical and bioanalytical chemistry. 2012.
- DOI：[ 10.1007/s00216-012-6384-x ](https://doi.org/10.1007/s00216-012-6384-x)
- 核查层级：公开摘要与书目；证据位置：摘要：fluorescent derivatization with 4-fluoro-7-nitro…及brain samples段。
- 支持内容：CE：NBD-F标记Asp/Glu；双环糊精CE-LIF分离并测定脑样品中的对映体。
- 适用范围：真实样品：雏鸡脑内游离氨基酸；未声称蛋白质水解液验证。

### [19] CE-LIF chiral separation of aspartic acid and glutamic acid enantiomers using human serum albumin and sodium cholate as dual selectors.
Wang S, Fan L, Cui S. Journal of separation science. 2009.
- DOI：[ 10.1002/jssc.200900341 ](https://doi.org/10.1002/jssc.200900341)
- 核查层级：公开摘要与书目；证据位置：摘要：DTAF全名、HSA and SC、compound amino acids injection段。
- 支持内容：CE：DTAF标记Asp/Glu，HSA/胆酸钠双选择剂辅助对映体分离。DTAF属于芳香亲核取代标记，不是异硫氰酸酯。
- 适用范围：真实样品：复方氨基酸注射液；非水解液。

### [20] Method for on-line derivatization and separation of aspartic acid enantiomer in pharmaceuticals application by the coupling of flow injection with micellar electrokinetic chromatography.
Cheng Y, Fan L, Chen H, Chen X, Hu Z. Journal of chromatography. A. 2005.
- DOI：[ 10.1016/j.chroma.2005.03.019 ](https://doi.org/10.1016/j.chroma.2005.03.019)
- 核查层级：公开摘要与书目；证据位置：摘要：derivatization reagents、chiral selector、micellar chemical及real sample段。
- 支持内容：MEKC：OPA＋2-巯基乙醇（ME）标记，β-CD提供手性识别，SDS提供胶束体系。
- 适用范围：真实样品：复方氨基酸注射液；非水解液。

### [21] Separation and enantiomer determination ofOPA-derivatised amino acids by using capillary zone electrophoresis.
Kang L, Buck RH. Amino acids. 1992.
- DOI：[ 10.1007/bf00806080 ](https://doi.org/10.1007/bf00806080)
- 核查层级：公开摘要与书目；证据位置：摘要首句及MECC/free solution段。
- 支持内容：CE：OPA＋手性硫醇生成非对映异构体；文中研究自由溶液CE和SDS-MECC。
- 适用范围：氨基酸衍生物分离研究；摘要未给真实水解液应用。

### [22] 3-[(3-Dehydroabietamidopropyl)dimethylammonio]-1-propane-sulfonate as a new type of chiral surfactant for enantiomer separation in micellar electrokinetic chromatography.
Zhao S, Wang H, Pan Y, He M, Zhao Z. Journal of chromatography. A. 2007.
- DOI：[ 10.1016/j.chroma.2007.01.139 ](https://doi.org/10.1016/j.chroma.2007.01.139)
- 核查层级：公开摘要与书目；证据位置：摘要：NDA-D/L-amino acids、chiral surfactant及6 pairs段。
- 支持内容：MEKC：NDA标记氨基酸，DHAMAP手性表面活性剂提供手性分离。
- 适用范围：六对所测衍生物的分离研究；不外推至所有氨基酸或水解液。

### [23] Chiral capillary electrophoresis with UV-excited fluorescence detection for the enantioselective analysis of 9-fluorenylmethoxycarbonyl-derivatized amino acids.
Prior A, Coliva G, de Jong GJ, Somsen GW. Analytical and bioanalytical chemistry. 2018.
- DOI：[ 10.1007/s00216-018-1148-x ](https://doi.org/10.1007/s00216-018-1148-x)
- 核查层级：全文＋摘要；证据位置：已读全文：Introduction、Chemicals、AA derivatization、Results and discussion/CSF application。
- 支持内容：CE：FMOC-Cl；β-CD辅助手性分离，并用UV激发荧光检测，应用于脑脊液。
- 适用范围：真实样品：脑脊液游离氨基酸；非水解液。

### [24] Enantiomeric separation of amino acids using micellar electrokinetic chromatography after pre-column derivatization with the chiral reagent 1-(9-fluorenyl)-ethyl chloroformate.
Chan KC, Muschik GM, Issaq HJ. Electrophoresis. 1995.
- DOI：[ 10.1002/elps.1150160183 ](https://doi.org/10.1002/elps.1150160183)
- 核查层级：公开摘要与书目；证据位置：摘要：(+)-/(-)-FLEC、SDS、diastereomers及FMOC比较段。
- 支持内容：MEKC：手性FLEC衍生化后用SDS体系分离非对映异构体；同时比较FMOC＋环糊精的直接分离路线。
- 适用范围：标准品/方法研究；非水解液验证。

### [25] Determination of sequence and absolute configuration of peptide amino acids by HPLC-MS/CD-based detection of liberated N-terminus phenylthiohydantoin amino acids.
Hahn D, Wang W, Choi H, Kang H. Scientific reports. 2022.
- DOI：[ 10.1038/s41598-022-14205-x ](https://doi.org/10.1038/s41598-022-14205-x)
- 核查层级：全文＋摘要；证据位置：已读全文：Introduction、Results and discussion、Methods；摘要末句acid hydrolysates。
- 支持内容：HPLC–MS/CD：PITC经Edman路线生成PTH-AA，建立对照并用于合成肽和天然缩肽；另分析合成肽酸水解液。
- 适用范围：真实肽及肽酸水解液；不可把PTH证据移植到常规PTC衍生物。

### [26] High-throughput comprehensive analysis of D- and L-amino acids using ultra-high performance liquid chromatography with a circular dichroism (CD) detector and its application to food samples.
Eto S, Yamaguchi M, Bounoshita M, Mizukoshi T, Miyano H. Journal of chromatography. B, Analytical technologies in the biomedical and life sciences. 2011.
- DOI：[ 10.1016/j.jchromb.2011.07.025 ](https://doi.org/10.1016/j.jchromb.2011.07.025)
- 核查层级：公开摘要与书目；证据位置：摘要：NBD-F was selected；does not require separation；food samples段。
- 支持内容：UHPLC–CD：筛选后选择NBD-F，利用g-factor计算%D，无需在柱上拆分同种氨基酸D/L。
- 适用范围：真实食品样品：黑醋、发酵乳、酸奶；摘要未证明完整蛋白水解流程。

### [27] Tryptophanase-catalyzed L-tryptophan synthesis from D-serine in the presence of diammonium hydrogen phosphate.
Shimada A, Ozaki H, Saito T, Noriko F. International journal of molecular sciences. 2009.
- DOI：[ 10.3390/ijms10062578 ](https://doi.org/10.3390/ijms10062578)
- 核查层级：全文＋摘要；证据位置：全文：Results/Determination of optical isomeric form by circular dichroism；Figure 4；Experimental/Tryptophan analyses by use of HPLC。。
- 支持内容：CROWNPAK CR(+)先分离D/L-Trp，在线CD-1595于233 nm检测相反椭圆度峰；UV于280 nm检测；无需衍生化。
- 适用范围：标准D/L-Trp及色氨酸酶合成反应液；不是蛋白质水解液。

### [28] A novel potential primary method for quantification of enantiomers by high performance liquid chromatography-circular dichroism.
Luo Y, Wu L, Yang B, Jin Y, Zheng K, He Z. Scientific reports. 2018.
- DOI：[ 10.1038/s41598-018-25682-4 ](https://doi.org/10.1038/s41598-018-25682-4)
- 核查层级：全文＋摘要；证据位置：全文：Instruments and reagents；Optimization of the HPLC separation conditions；Figure 3（独立手性纯度检查）；Figures 4F、5D（实际在线CD）；pINS应用。。
- 支持内容：未衍生化Phe经非手性HSS T3分离后在线CD检测，定量猪胰岛素水解液Phe。CROWNPAK柱是另一独立的D-Phe光学纯度检查，并不是该在线CD定量路线。
- 适用范围：纯Phe、氨基酸混合物及猪胰岛素水解液。

### [29] Enantioselective separation of amino acids as biomarkers indicating life in extraterrestrial environments.
Pietrogrande MC. Analytical and bioanalytical chemistry. 2013.
- DOI：[ 10.1007/s00216-013-6915-0 ](https://doi.org/10.1007/s00216-013-6915-0)
- 核查层级：公开摘要与书目；证据位置：摘要中silylation reagent…unsuitable for detection of homochirality段。
- 支持内容：GC删除项审查：综述区分普通GC挥发化和对映体测定；常用MTBSTFA硅烷化被明确指出不适于其讨论的homochirality检测。不能把所有硅烷化剂概括为成熟手性氨基酸方案。
- 适用范围：方法学综述；不据此断言所有硅烷化体系都绝不可能手性分离。

### [30] Comparison of derivatization and chromatographic methods for GC-MS analysis of amino acid enantiomers in physiological samples.
Waldhier MC, Dettmer K, Gruber MA, Oefner PJ. Journal of chromatography. B, Analytical technologies in the biomedical and life sciences. 2010.
- DOI：[ 10.1016/j.jchromb.2010.03.021 ](https://doi.org/10.1016/j.jchromb.2010.03.021)
- 核查层级：公开摘要与书目；证据位置：摘要：racemization during derivatization precluded accurate quantification及MCF段。
- 支持内容：GC限制性证据：比较氟化/非氟化酸酐及氯甲酸酯；PFPA/七氟丁醇虽灵敏，但衍生化消旋妨碍准确对映体定量，MCF路线可避免其问题。
- 适用范围：真实样品：血清、尿液；为删除/后置酯化酰化组合提供具体理由，不表示这类反应不存在。
