# 对SEE软件的简要介绍
详情参考SEE的文章 https://www.tandfonline.com/doi/full/10.1080/13102818.2019.1593052 ，SEE软件是一个用于在GWAS数据上搜索上位性SNP组合的软件，它针对上位性搜索这个课题，设计并使用了一种原创的进化算法，类似于和声算法，在进化算法中，同时使用8个用于评价一个SNP组合是否为上位性的函数，整合这8个函数作为进化算法的适应度函数。SEE是Sort Exploitation Exploration的缩写，该软件的算法主要由这三部分组成，其中Sort用于整合8个评价函数作为进化算法的适应度函数，而Exploitation和Exploration用于探索新的SNP组合。
本网页的制作旨在让阅读本文的研究者们，可以复现本文的实验，为您在该领域的学习和研究带来一定的便利。
# 运行方法
在文章中SEE和BEAM, DECMDR, MACOED, SNPHarvester, SNPRuler, AntEpiSeeker进行了对比，以下为这些软件的原论文和软件的链接：
BEAM
https://www.researchgate.net/publication/6117902_Bayesian_inference_of_epistatic_interactions_in_case-control_studies?enrichId=rgreq-1d428109abb62fe1140ca9fff7f8d2fa-XXX&enrichSource=Y292ZXJQYWdlOzYxMTc5MDI7QVM6MTA0Njk1Njc4ODk4MTg1QDE0MDE5NzI4MDQ3MDI%3D&el=1_x_3&_esc=publicationCoverPdf
https://sites.fas.harvard.edu/~junliu/BEAM/
DECMDR
https://academic.oup.com/bioinformatics/article/33/15/2354/3100457
https://goo.gl/p9sLuJ
MACOED
https://academic.oup.com/bioinformatics/article/31/5/634/2748185
http://www.csbio.sjtu.edu.cn/bioinf/MACOED/
SNPHarvester
https://academic.oup.com/bioinformatics/article/25/4/504/249552
http://bioinformatics.ust.hk/SNPHarvester.html
SNPRuler
https://academic.oup.com/bioinformatics/article/26/1/30/182742
http://bioinformatics.ust.hk/SNPRuler.zip
为防止这些链接挂掉，本网页也上传了这些软件。
SEE的可执行文件和运行方法稍后更新
# 源码
稍后更新
# 数据
SEE的文章中，真实数据为非公开数据集，您可以自行去WTCCC的网站申请使用，我没有权利发布给您。
因此，本文只提供模拟数据。
模拟数据一共有72个，其中，12DME模型的数据是从MACOED的网站上下载的，一共1200个数据文件，每个上位性模型对应100个数据文件，60个DNME模型是由GAMETES_2.1这个软件根据DECMDR提供的penetrance tables生成的，DECMDR提供的penetrance tables在它文章的supplementary文件中，我根据它提供的word文件，整理成了GAMETES_2.1识别的模型文件，将在本网页中上传，您可以根据这些penetrance tables文件，使用GAMETES_2.1来生成DNME模拟数据集。
GAMETES_2.1文章链接：https://biodatamining.biomedcentral.com/articles/10.1186/1756-0381-5-16
GAMETES_2.1软件链接：http://sourceforge.net/projects/gametes/files/
DME数据链接：http://www.csbio.sjtu.edu.cn/bioinf/MACOED/
