## 瑕疵数据集

### 1. Vision-based SIS for steel

[Vision-based SIS for steel](http://faculty.neu.edu.cn/me/songkc/Vision-based_SIS_Steel.html)（东北大学热轧带钢表面缺陷数据集）是东北大学的宋克臣等几位老师收集的，一共包含了三类数据。该网站主要用于介绍基于视觉的钢表面缺陷检测系统的研究进展。

该数据集包含：[NEU surface defect database](http://faculty.neu.edu.cn/yunhyan/NEU_surface_defect_database.html)（收集了夹杂、划痕、压入氧化皮、裂纹、麻点和斑块6种缺陷，每种缺陷300张，图像尺寸为 200×200。数据集包括分类和目标检测两部分，不过目标检测的标注中有少量错误，需要注意。），[Micro surface defect database](http://faculty.neu.edu.cn/yunhyan/SCACM.html)（微小型的带钢缺陷数据，缺陷只有约 6×6 个像素大小），[Oil pollution defect database](http://faculty.neu.edu.cn/yunhyan/SLSM.html)（油污干扰的硅钢表面缺陷数据集）。

### 2. Kaggle 中谢韦尔钢铁公司提供的带钢缺陷数据集

[Severstal: Steel Defect Detection](https://www.kaggle.com/c/severstal-steel-defect-detection/data) 数据集中提供了四种类型的带钢表面缺陷。训练集共有 12568 张，测试集 5506 张。图像尺寸为 1600×256。

有如果有学术研究的需要，可以无限制使用，请将 [PAO Severstal](https://www.severstal.com/) 指定为数据集所有者。

### 3. UCI Steel Plates Faults Data Set

[Steel Plates Faults Data Set](https://archive.ics.uci.edu/ml/datasets/Steel+Plates+Faults) 包含了7种带钢缺陷类型。这个数据集不是图像数据，而是带钢缺陷的 28 种特征数据，可用于机器学习项目。

### 4. DAGM 2007 数据集

该数据集是人为生成的，一共包含了 10 个class，图像大小为 512×512。见 [Weakly Supervised Learning for Industrial Optical Inspection](https://hci.iwr.uni-heidelberg.de/content/weakly-supervised-learning-industrial-optical-inspection)

弱监督学习下的工业光学检测。

数据集介绍：

- 主要针对纹理背景上的杂项缺陷。
- 较弱监督的训练数据。
- 包含是个数据集，前六个为训练数据集，后四个为测试数据集。
- 每个数据集均包含以灰度8位PNG格式保存的1000个“无缺陷”图像和150个“有缺陷”图像。每个数据集由不同的纹理模型和缺陷模型生成。
- “无缺陷”图像显示的背景纹理没有缺陷，“无缺陷”图像的背景纹理上恰好有一个标记的缺陷。
- 所有数据集已随机分为大小相等的训练和测试子数据集。
- 弱标签以椭圆形表示，大致表示缺陷区域。 

### 5. 磁瓦缺陷数据集

中国科学院自动所一个课题组收集的数据集，是“Saliency of magnetic tile surface defects”这篇论文的数据集。收集了6种常见磁瓦缺陷的图像，并做了语义分割的标注。见 [Magnetic-tile-defect-datasets](https://github.com/abin24/Magnetic-tile-defect-datasets.)。

### 6. Kolektor 表面缺陷数据集

[Kolektor Surface-Defect Dataset](https://www.vicos.si/Downloads/KolektorSDD) 数据集是 Kolektor Group 收集并标注的电子换向器缺陷数据集。数据集中包含了50种编写的电子换向器，每种有8张图片以及其语义分割的label。图像的大小为500×1240像素。为了更方便的训练，需提前将图像调整为512×1408。

### 7. 铁轨表面缺陷数据集

[RSDDs](http://icn.bjtu.edu.cn/Visint/resources/RSDDs.aspx) 数据集包含两种类型的数据集：第一种是从快车道捕获的I型RSDDs数据集，其中包含67个具有挑战性的图像。第二个是从普通/重型运输轨道捕获的II型RSDDs数据集，其中包含128个具有挑战性的图像。

两个数据集的每幅图像至少包含一个缺陷，并且背景复杂且噪声很大。

RSDDs 数据集中的这些缺陷已由一些专业的人类观察员在轨道表面检查领域进行了标记。

数据集介绍：

- RSDDs数据集包含两种类型的数据集：第一种是从快车道捕获的I型RSDDs数据集，其中包含67个具有挑战性的图像。第二个是从普通/重型运输轨道捕获的II型RSDDs数据集，其中包含128个具有挑战性的图像。
- 两个数据集的每幅图像至少包含一个缺陷，并且背景复杂且噪声很大。
- RSDDs数据集中的这些缺陷已由一些专业的人类观察员在轨道表面检查领域进行了标记。

### 8. 水泥道路裂缝数据集

[CrackForest](https://github.com/cuilimeng/CrackForest) 相关 Matlab 源码：https://github.com/pdollar/edges

主要针对水泥路面的裂缝检测，可用于分类、分割和 Detection。

### 9. 印刷电路板（PCB）瑕疵数据集

数据下载链接：[印刷电路板（PCB）瑕疵数据集](http://robotics.pkusz.edu.cn/resources/dataset/)

数据介绍：这是一个公共的合成PCB数据集，由北京大学发布，其中包含1386张图像以及6种缺陷（缺失孔，鼠标咬伤，开路，短路，杂散，伪铜），用于检测，分类和配准任务。

### 10. AITEX数据集（面料缺陷）

- 数据集下载链接：https://pan.baidu.com/s/1cfC4Ll5QlnwN5RTuSZ6b7w
- 提取码：b9uy

数据介绍：该数据库由七个不同织物结构的245张4096 x 256像素图像组成。数据库中有140个无缺陷图像，每种类型的织物20个，除此之外，有105幅纺织行业中常见的不同类型的织物缺陷（12种缺陷）图像。图像的大尺寸允许用户使用不同的窗口尺寸，从而增加了样本数量。Internet上的数据库还包含所有具有缺陷的图像的分割mask，使得白色像素表示缺陷区域，其余像素为黑色。

### 11. 天池布匹缺陷数据（竞赛）

- 数据下载链接：https://pan.baidu.com/s/1LMbujxvr5iB3SwjFGYHspA
- 提取码：gat2

数据介绍：在布匹的实际生产过程中，由于各方面因素的影响，会产生污渍、破洞、毛粒等瑕疵，为保证产品质量，需要对布匹进行瑕疵检测。布匹疵点检验是纺织行业生产和质量管理的重要环节，目前人工检测易受主观因素影响，缺乏一致性；并且检测人员在强光下长时间工作对视力影响极大。由于布匹疵点种类繁多、形态变化多样、观察识别难道大，导致布匹疵点智能检测是困扰行业多年的技术瓶颈。本数据涵盖了纺织业中布匹的各类重要瑕疵，每张图片含一个或多种瑕疵。数据包括包括素色布和花色布两类，其中，素色布数据约8000张，用于初赛；花色布数据约12000张，用于复赛。

### 12. 天池铝型材表面瑕疵数据集（竞赛）

数据集下载链接：[广东工业智造大数据创新大赛-智能算法赛赛题与数据-天池大赛-阿里云天池](https://tianchi.aliyun.com/competition/entrance/231682/information)

数据介绍：在铝型材的实际生产过程中，由于各方面因素的影响，铝型材表面会产生裂纹、起皮、划伤等瑕疵，这些瑕疵会严重影响铝型材的质量。为保证产品质量，需要人工进行肉眼目测。然而，铝型材的表面自身会含有纹路，与瑕疵的区分度不高。传统人工肉眼检查十分费力，不能及时准确的判断出表面瑕疵，质检的效率难以把控。近年来，深度学习在图像识别等领域取得了突飞猛进的成果。铝型材制造商迫切希望采用最新的AI技术来革新现有质检流程，自动完成质检任务，减少漏检发生率，提高产品的质量，使铝型材产品的生产管理者彻底摆脱了无法全面掌握产品表面质量的状态。

大赛数据集里有1万份来自实际生产中有瑕疵的铝型材监测影像数据，每个影像包含一个或多种瑕疵。供机器学习的样图会明确标识影像中所包含的瑕疵类型。

### 13. KTH-TIPS database

数据集下载链接：http://www.nada.kth.se/cvap/databases/kth-tips/download.html

数据集介绍：一共11类真实世界物体表面纹理和材质的图像数据集，在不同姿态和光照下获取，可用来对物体表面材质进行检测和识别。

### 14. 桥梁裂缝图像数据

数据集下载链接：https://pan.baidu.com/s/1bplPrPl

数据介绍：主要针对桥梁裂缝的检测数据。

### 15. 混凝土表面裂纹缺陷数据集

数据集包含带有和不带有裂纹的各种混凝土表面的图像。 图像数据在单独的文件夹中分为负片（无裂纹）和正片（无裂纹）两部分，用于图像分类。 每个类别有20000张图像，总共40000张图像，带227 x 227像素的RGB通道。

官方链接：https://www.kaggle.com/arunrk7/surface-crack-detection