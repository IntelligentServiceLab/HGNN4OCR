# HGNN4OCR
说明：由于数据集太大，MOOCCubeX的数据自行下载：https://github.com/THU-KEG/MOOCCubeX
为了融合用户以及课程的文本信息，用户-课程-课程视频资源结构信息并且融合用户和课程的学习风格信息，从而面向用户推荐个性化的课程资源，提出了一种基于超图神经网络（Hypergraph Neural Network，HGNN）的课程推荐方法，命名为HGNN-OCRec。该方法沿用了第三章提出的方法LS-OCRec的优势，融合了用户-课程学习风格信息作为辅助信息。HGNN-OCRec中有四个组件：一个是文本信息表示组件，使用BERT对用户-课程文本信息进行表征。第二个是结构信息表示组件，使用HGNN用于表征用户，课程以及课程视频资源的结构信息。第三个是用户-课程学习风格信息，在本章中，使用了新的更庞大的数据集MOOCCubeX 来获取更多的学习风格信息。最后一个是课程推荐组件。将文本信息向量，结构信息向量以及学习风格向量拼接后，输入到自注意力神经因子分解机（Self-Attention Neural Factorization Machine，SANFM）中。
