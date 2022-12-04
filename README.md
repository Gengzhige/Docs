# 梗直哥内容精选

![title](./assets/title.png)

## AI+生物学论文合集

过去几十年，生物数据集的规模与复杂性大幅增长，这使得机器学习越来越多地用于为潜在生物过程构建信息与预测模型。所有机器学习技术都在让模型与数据相匹配；然而，具体的方法多种多样，乍一看似乎令人眼花缭乱。对于不同类型的生物数据，该如何选择特定的机器学习技术？

  <p><strong>机器学习算法</strong></p>
  <table>
    <tr>
      <td>
        <p><strong>方法</strong></p>
      </td>
      <td>
        <p><strong>数据类型与优缺点</strong></p>
      </td>
      <td>
        <p><strong>示例应用</strong></p>
      </td>
      <td>
        <p><strong>相关论文</strong></p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>岭回归</p>
      </td>
      <td rowspan="2">
        <p><strong>数据类型</strong></p>
        <p>标签固定数量的特征</p>
        <p><strong>优势</strong></p>
        <p>容易解释；容易训练；良好的基准</p>
        <p><strong>缺点</strong></p>
        <p>无法学习复杂的特征关系；</p>
        <p>与大量功能过度匹配</p>
      </td>
      <td>
        <p>蛋白质变体效果预测</p>
      </td>
      <td>
        <p>Munro, D. & Singh, M. DeMaSk: a deep mutational scanning substitution matrix and its use for variant impact prediction. Bioinformatics 36, 5322–5329(2020).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>生物化学反应动力学</p>
      </td>
      <td>
        <p>Haario, H. & Taavitsainen, V.-M. Combining soft and hard modelling in chemical kinetic models. Chemom.Intell. Lab. Syst. 44, 77–98 (1998).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>支持向量机SVM</p>
      </td>
      <td rowspan="2">
        <p><strong>数据类型</strong></p>
        <p>标签固定数量的特征</p>
        <p><strong>优势</strong></p>
        <p>能同时进行线性和非线性分类和回归</p>
        <p><strong>缺点</strong></p>
        <p>扩展大型数据级困难</p>
      </td>
      <td>
        <p>蛋白质功能预测</p>
      </td>
      <td>
        <p>Cozzetto, D., Minneci, F., Currant, H. & Jones, D. T.FFPred 3: feature- based function prediction for all gene ontology domains. Sci. Rep. 6, 31865 (2016).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>跨膜蛋白拓扑预测</p>
      </td>
      <td>
        <p>Nugent, T. & Jones, D. T. Transmembrane protein topology prediction using support vector machines.BMC Bioinformatics 10, 159 (2009).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>多层感知机</p>
      </td>
      <td rowspan="2">
        <p><strong>数据类型</strong></p>
        <p>贴上标签</p>
        <p>固定数量的功能</p>
        <p><strong>优势</strong></p>
        <p>可以使用比诸如此类架构更少的层来适应数据集</p>
        <p>卷积神经网络的应用使它更容易和更快训练</p>
        <p><strong>缺点</strong></p>
        <p>容易过拟合；海量参数；可解释性低</p>
      </td>
      <td>
        <p>蛋白质二级结构预测</p>
      </td>
      <td>
        <p>Buchan, D. W. A. & Jones, D. T. The PSIPRED Protein Analysis Workbench: 20 years on. Nucleic Acids Res.47, W402–W407 (2019).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>药物毒性预测</p>
      </td>
      <td>
        <p>Mayr, A., Klambauer, G., Unterthiner, T. & Hochreiter, S.DeepTox: toxicity prediction using deep learning.Front. Environ. Sci. 3, 80 (2016).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>随机森林</p>
      </td>
      <td rowspan="2">
        <p><strong>数据类型</strong></p>
        <p>标签固定数量的特征</p>
        <p><strong>优势</strong></p>
        <p>每个决策树是人类可读的，允许解释决策是如何做出的；</p>
        <p>对特征缩放和标准化不太敏感，因此更容易训练和调整</p>
        <p><strong>缺点</strong></p>
        <p>不太适合回归；</p>
        <p>许多决策树很难解释</p>
      </td>
      <td>
        <p>疾病相关基因组突变预测</p>
      </td>
      <td>
        <p>Bao, L., Zhou, M. & Cui, Y. nsSNPAnalyzer: identifying disease- associated nonsynonymous single nucleotide polymorphisms. Nucleic Acids Res. 33, W480–W482(2005).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>蛋白质-配体相互作用评分</p>
      </td>
      <td>
        <p>Wang, C. & Zhang, Y. Improving scoring- docking-screening powers of protein- ligand scoring functions using random forest. J. Comput. Chem. 38, 169–177(2017).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>聚类</p>
      </td>
      <td rowspan="2">
        <p><strong>数据类型</strong></p>
        <p>未标记的固定数量的特征</p>
        <p><strong>优势</strong></p>
        <p>对于低维数据，好的聚类易于识别；</p>
        <p>集群验证指标可用来评估性能</p>
        <p><strong>缺点</strong></p>
        <p>对于某些方法，扩展到大型数据集很困难；</p>
        <p>嘈杂的数据集有时会产生矛盾的结果</p>
      </td>
      <td>
        <p>基因表达分析</p>
      </td>
      <td>
        <p>Altman, N. & Krzywinski, M. Clustering. Nat. Methods 14, 545–546 (2017).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>蛋白质结构预测中的模型选择</p>
      </td>
      <td>
        <p>Zhang, Y. & Skolnick, J. SPICKER: a clustering approach to identify near- native protein folds. J. Comput. Chem.30, 865–871 (2004).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>降维</p>
      </td>
      <td rowspan="2">
        <p><strong>数据类型</strong></p>
        <p>未标记的</p>
        <p>大量且固定数量的功能</p>
        <p><strong>优势</strong></p>
        <p>提供数据的可视化表示；</p>
        <p>拟合优度评估通常用于评估工作表现</p>
        <p><strong>缺点</strong></p>
        <p>很难同时保留全局和本地数据差异；</p>
        <p>对于某些方法，缩放到大量样本很困难</p>
      </td>
      <td>
        <p>单细胞转录组</p>
      </td>
      <td>
        <p>Kobak, D. & Berens, P. The art of using t- SNE for single- cell transcriptomics. Nat. Commun. 10, 5416&nbsp;(2019).This article provides a discussion and tips for using t- SNE as a dimensionality reduction technique on single- cell transcriptomics data.</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>分子动力学轨迹分析</p>
      </td>
      <td>
        <p>Teodoro, M. L., Phillips, G. N. Jr & Kavraki, L. E.Understanding protein flexibility through dimensionality reduction. J. Comput. Biol. 10,617–634 (2003).</p>
      </td>
    </tr>
  </table>
  <p><strong>深度学习算法</strong></p>
  <table>
    <tr>
      <td>
        <p>方法</p>
      </td>
      <td>
        <p><strong>数据类型与优缺点</strong></p>
      </td>
      <td>
        <p><strong>示例应用</strong></p>
      </td>
      <td>
        <p><strong>相关论文</strong></p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>CNN</p>
      </td>
      <td rowspan="2">
        <p><strong>数据类型</strong></p>
        <p>按网格排列的空间数据</p>
        <p><strong>优势</strong></p>
        <p>变量输入的大小</p>
        <p>学习模式与输入位置无关</p>
        <p><strong>缺点</strong></p>
        <p>接收字段，被考虑的输入量；</p>
        <p>当预测每个像素的输出时，可能会受到限制；很难训练更深层的架构，使用许多层来增加接受域，并做出更复杂的预测</p>
      </td>
      <td>
        <p>蛋白质残基-残基基础及距离预测</p>
      </td>
      <td>
        <p>Senior, A. W. et al. Improved protein structure prediction using potentials from deep learning.Nature 577, 706–710 (2020).Technology company DeepMind entered the CASP13 assessment in protein structure prediction and its method using deep learning was the most accurate of the methods entered.</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>医学图像识别</p>
      </td>
      <td>
        <p>Esteva, A. et al. Dermatologist- level classification of skin cancer with deep neural networks. Nature 542,115–118 (2017).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>RNN</p>
      </td>
      <td rowspan="2">
        <p><strong>数据类型</strong></p>
        <p>顺序数据（例如生物序列或时间序列数据）</p>
        <p>允许可变输入大小</p>
        <p><strong>优势</strong></p>
        <p>变量输入的大小</p>
        <p>序列存在于生物学的许多领域</p>
        <p><strong>缺点</strong></p>
        <p>长时间训练</p>
        <p>高计算内存需求</p>
      </td>
      <td>
        <p>蛋白质工程</p>
      </td>
      <td>
        <p>Alley, E. C., Khimulya, G., Biswas, S., AlQuraishi, M.& Church, G. M. Unified rational protein engineering with sequence- based deep representation learning.Nat. Methods 16, 1315–1322 (2019).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>预测临床事件</p>
      </td>
      <td>
        <p>Choi, E., Bahadori, M. T., Schuetz, A., Stewart, W. F.& Sun, J. Doctor AI: predicting clinical events via recurrent neural networks. JMLR Workshop Conf.Proc. 56, 301–318 (2016).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="3">
        <p>自编码器</p>
      </td>
      <td rowspan="3">
        <p><strong>数据类型</strong></p>
        <p>标记或未标记的数据</p>
        <p>固定或可变的输入大小取决于架构</p>
        <p><strong>优势</strong></p>
        <p>潜空间提供来低维表示，可用于可视化输入数据；</p>
        <p>能否生成新的样品，这在蛋白质设计等领域是有用的</p>
        <p><strong>缺点</strong></p>
        <p>潜在空间特定于训练集中的数据，可能不适用于其他数据集；</p>
        <p>测试新生成的样品通常需要湿实验</p>
      </td>
      <td>
        <p>蛋白质与基因工程</p>
      </td>
      <td>
        <p>Linder, J., Bogard, N., Rosenberg, A. B. & Seelig, G.A generative neural network for maximizing fitness and diversity of synthetic DNA and protein sequences.Cell Syst. 11, 49–62.e16 (2020).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>DNA甲基化的预测</p>
      </td>
      <td>
        <p>Wang, Y. et al. Predicting DNA methylation state of CpG dinucleotide using genome topological features and deep networks. Sci. Rep. 6, 19598(2016).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>神经种群动态</p>
      </td>
      <td>
        <p>Pandarinath, C. et al. Inferring single- trial neural population dynamics using sequential auto- encoders.Nat. Methods 15, 805–815 (2018).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="3">
        <p>图卷积网络</p>
        <p>GCN</p>
      </td>
      <td rowspan="3">
        <p><strong>数据类型</strong></p>
        <p>以实体之间的连接（空间、交互或关联）为特征的数据</p>
        <p>允许可变输入大小</p>
        <p><strong>优势</strong></p>
        <p>支持可变的图大小，这很重要，因为生物学中的大多数图都有可变的大小；</p>
        <p>通过跟踪图的连通性来学习模式，因此预测器使用了大多数相关的关联</p>
        <p><strong>缺点</strong></p>
        <p>对大型、密集连接图的高计算内存要求；</p>
        <p>很难培养更深层的架构</p>
      </td>
      <td>
        <p>预测药物的属性</p>
      </td>
      <td>
        <p>Zitnik, M., Agrawal, M. & Leskovec, J. Modeling polypharmacy side effects with graph convolutional networks. Bioinformatics 34, i457–i466 (2018).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>解释分子结构</p>
      </td>
      <td>
        <p>Stokes, J. M. et al. A deep learning approach to antibiotic discovery. Cell 181, 475–483 (2020).&nbsp;In this work, a deep learning model predicts antibiotic activity, with one candidate showing broad- spectrum antibiotic activities in mice.</p>
        <p>Gainza, P. et al. Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning. Nat. Methods 17, 184–192 (2020).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>知识提取</p>
      </td>
      <td>
        <p>Schlichtkrull, M. et al. Modeling relational data with graph convolutional networks. arXiv&nbsp;https://arxiv.org/abs/1703.06103&nbsp;(2019).</p>
      </td>
    </tr>
  </table>
  <p><strong>生物大数据</strong></p>
  <table>
    <tr>
      <td>
        <p>输入数据</p>
      </td>
      <td>
        <p><strong>推荐模型与挑战</strong></p>
      </td>
      <td>
        <p><strong>预测任务示例</strong></p>
      </td>
      <td>
        <p><strong>相关论文</strong></p>
      </td>
    </tr>
    <tr>
      <td rowspan="3">
        <p>基因序列</p>
      </td>
      <td rowspan="3">
        <p><strong>推荐模型</strong></p>
        <p>1D CNNs</p>
        <p>RNNs</p>
        <p>Transformers</p>
        <p><strong>挑战</strong></p>
        <p>基因组中重复区域感兴趣的稀疏区域长序列</p>
      </td>
      <td>
        <p>DNA可访问性</p>
      </td>
      <td>
        <p>Kelley, D. R., Snoek, J. & Rinn, J. L. Basset: learning the regulatory code of the accessible genome with deep convolutional neural networks. Genome Res. 26,990–999 (2016).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>3D基因组组织</p>
      </td>
      <td>
        <p>Fudenberg, G., Kelley, D. R. & Pollard, K. S. Predicting 3D genome folding from DNA sequence with Akita.Nat. Methods 17, 1111–1117 (2020)</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>增强子-启动子交互</p>
      </td>
      <td>
        <p>Zeng, W., Wu, M. & Jiang, R. Prediction of enhancer- promoter interactions via natural language processing. BMC Genomics 19, 84 (2018).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="3">
        <p>蛋白质序列</p>
      </td>
      <td rowspan="3">
        <p><strong>推荐模型</strong></p>
        <p>使用共变数据的二维CNN和残差网络；</p>
        <p>带窗口的多层感知机</p>
        <p>Transformers</p>
        <p><strong>挑战</strong></p>
        <p>宏基因组数据存储存在许多地方，因此很难访问；</p>
        <p>数据泄漏（来自同源基因）会使验证变得困难</p>
      </td>
      <td>
        <p>蛋白质结构</p>
      </td>
      <td>
        <p>Senior, A. W. et al. Improved protein structure prediction using potentials from deep learning.Nature 577, 706–710 (2020).Technology company DeepMind entered the CASP13 assessment in protein structure prediction and its method using deep learning was the most accurate of the methods entered.</p>
        <p>Tegunov, D. & Cramer, P. Real- time cryo- electron microscopy data preprocessing with Warp.Nat. Methods 16, 1146–1152 (2019).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>蛋白质功能</p>
      </td>
      <td>
        <p>Antczak, M., Michaelis, M. & Wass, M. N.Environmental conditions shape the nature of a minimal bacterial genome. Nat. Commun. 10, 3100 (2019).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>蛋白质相互作用</p>
      </td>
      <td>
        <p>Sun, T., Zhou, B., Lai, L. & Pei, J. Sequence- based prediction of protein protein interaction using a deep- learning algorithm. BMC Bioinformatics 18,277 (2017).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="3">
        <p>蛋白质三维结构</p>
      </td>
      <td rowspan="3">
        <p><strong>推荐模型</strong></p>
        <p>GCNs分子图</p>
        <p>使用坐标的3D CNN</p>
        <p>利用结构特征的传统方法聚类</p>
        <p><strong>挑战</strong></p>
        <p>缺乏数据，尤其是蛋白质复合物；</p>
        <p>缺乏关于无需蛋白质的数据</p>
      </td>
      <td>
        <p>蛋白质模型细化</p>
      </td>
      <td>
        <p>Hiranuma, N. et al. Improved protein structure refinement guided by deep learning based accuracy estimation. Nat. Commun. 12, 1340 (2021).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>蛋白质模型质量评估</p>
      </td>
      <td>
        <p>Pagès, G., Charmettant, B. & Grudinin, S. Protein model quality assessment using 3D oriented convolutional neural networks. Bioinformatics 35,3313–3319 (2019).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>突变后稳定性的变化</p>
      </td>
      <td>
        <p>Pires, D. E. V., Ascher, D. B. & Blundell, T. L. DUET: a server for predicting effects of mutations on protein stability using an integrated computational approach.Nucleic Acids Res. 42, W314–W319 (2014).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>基因表达</p>
      </td>
      <td rowspan="2">
        <p><strong>推荐模型</strong></p>
        <p>集群</p>
        <p>CNNs</p>
        <p>自编码器</p>
        <p><strong>挑战</strong></p>
        <p>共表达与功能之间的联系尚不清楚</p>
        <p>高维度</p>
        <p>高噪音</p>
      </td>
      <td>
        <p>基因间相互作用或共表达</p>
      </td>
      <td>
        <p>Yuan, Y. & Bar- Joseph, Z. Deep learning for inferring gene relationships from single- cell expression data.Proc. Natl Acad. Sci. USA 116, 27151–27158 (2019).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>转录机制的组织</p>
      </td>
      <td>
        <p>Chen, L., Cai, C., Chen, V. & Lu, X. Learning a hierarchical representation of the yeast transcriptomic machinery using an autoencoder model. BMC Bioinformatics 17, S9 (2016).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>质谱分析</p>
      </td>
      <td rowspan="2">
        <p><strong>推荐模型</strong></p>
        <p>使用光谱数据的CNN</p>
        <p>使用派生特征的传统方法</p>
        <p><strong>挑战</strong></p>
        <p>缺乏标准基准</p>
        <p>不同数据集之间需要进行标准化</p>
      </td>
      <td>
        <p>检测光谱中的峰图</p>
      </td>
      <td>
        <p>Kantz, E. D., Tiwari, S., Watrous, J. D., Cheng, S.& Jain, M. Deep neural networks for classification of LC- MS spectral peaks. Anal. Chem. 91, 12407–12413(2019).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>代谢物注释</p>
      </td>
      <td>
        <p>Dührkop, K. et al. SIRIUS 4: a rapid tool for turning tandem mass spectra into metabolite structure information. Nat. Methods 16, 299–302 (2019).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="3">
        <p>图像</p>
      </td>
      <td rowspan="3">
        <p><strong>推荐模型</strong></p>
        <p>2D CNN和残差网络</p>
        <p>自编码器</p>
        <p>利用图像特征的传统方法</p>
        <p><strong>挑战</strong></p>
        <p>数据收集的系统差异会影响预测；</p>
        <p>难以获得大数据集的一致性数据</p>
      </td>
      <td>
        <p>医学图像识别</p>
      </td>
      <td>
        <p>Poplin, R. et al. Prediction of cardiovascular risk factors from retinal fundus photographs via deep learning. Nat. Biomed. Eng. 2, 158–164 (2018).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>冷冻电子显微镜图像重建</p>
      </td>
      <td>
        <p>Yao, R., Qian, J. & Huang, Q. Deep- learning with synthetic data enables automated picking of cryo- EM particle images of biological macromolecules.Bioinformatics 36, 1252–1259 (2020).</p>
        <p>Zhong, E. D., Bepler, T., Berger, B. & Davis, J. H. CryoDRGN: reconstruction of heterogeneous cryo- EM structures using neural networks. Nat. Methods 18,176–185 (2021).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>RNA测序概要</p>
      </td>
      <td>
        <p>Schmauch, B. et al. A deep learning model to predict RNA- Seq expression of tumours from whole slide images. Nat. Commun. 11, 3877 (2020).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="4">
        <p>分子结构</p>
      </td>
      <td rowspan="4">
        <p><strong>推荐模型</strong></p>
        <p>GCNs分子图</p>
        <p>传统方法或利用分子特征的多层感知机</p>
        <p>使用基于文本的分子结构表示（如smile）的RNN自编码器</p>
        <p><strong>挑战</strong></p>
        <p>只有很小一部分可能的小分子的实验数据可用</p>
      </td>
      <td>
        <p>抗生素活性</p>
      </td>
      <td>
        <p>Stokes, J. M. et al. A deep learning approach to antibiotic discovery. Cell 181, 475–483 (2020).&nbsp;In this work, a deep learning model predicts antibiotic activity, with one candidate showing broad- spectrum antibiotic activities in mice.</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>药物毒性</p>
      </td>
      <td>
        <p>Mayr, A., Klambauer, G., Unterthiner, T. & Hochreiter, S.DeepTox: toxicity prediction using deep learning.Front. Environ. Sci. 3, 80 (2016).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>蛋白配体结合</p>
      </td>
      <td>
        <p>Wang, C. & Zhang, Y. Improving scoring- docking-screening powers of protein- ligand scoring functions using random forest. J. Comput. Chem. 38, 169–177(2017).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>新型药物代</p>
      </td>
      <td>
        <p>Das, P. et al. Accelerated antimicrobial discovery via deep generative models and molecular dynamics simulations. Nat. Biomed. Eng. 5, 613–623 (2021).</p>
      </td>
    </tr>
    <tr>
      <td rowspan="2">
        <p>蛋白质相互作用网络</p>
      </td>
      <td rowspan="2">
        <p><strong>推荐模型</strong></p>
        <p>GCNs</p>
        <p>图嵌入</p>
        <p><strong>挑战</strong></p>
        <p>互动网络可能是不完整的细胞位置影响蛋白质是否相互作用</p>
        <p>可能的组合数量大</p>
      </td>
      <td>
        <p>多重药理副作用</p>
      </td>
      <td>
        <p>Zitnik, M., Agrawal, M. & Leskovec, J. Modeling polypharmacy side effects with graph convolutional networks. Bioinformatics 34, i457–i466 (2018).</p>
      </td>
    </tr>
    <tr>
      <td>
        <p>蛋白质功能</p>
      </td>
      <td>
        <p>Gligorijevic,&nbsp;V., Barot, M. & Bonneau, R. deepNF:deep network fusion for protein function prediction.Bioinformatics 34, 3873–3881 (2018).</p>
      </td>
    </tr>
  </table>