# IFT6756_H2021_Project
Analyze the use of intermediate layer representations of the Neural Network in identifying adversarial attacks using [Deep kNN](https://arxiv.org/abs/1803.04765) method when applied to poisoned models and whether we can detect adversarial examples that are engineered using [ILA](https://openaccess.thecvf.com/content_ICCV_2019/papers/Huang_Enhancing_Adversarial_Example_Transferability_With_an_Intermediate_Level_Attack_ICCV_2019_paper.pdf)_
Code adapated from [DeepKNN](https://github.com/bam098/deep_knn ) and [PoisonedData](https://colab.research.google.com/github/pralab/secml/blob/HEAD/tutorials/06-MNIST_dataset.ipynb). Dataset is MNIST. \ 

This is experiment is carried out in collaboration with [Nehal](https://github.com/nehal1995).

There are 3 notebooks for analyzing the poisoned data using DeepkNN, 
1. poisoned_data_DkNN_10_labels.ipynb
2. poisoned_data_DkNN_2_labels.ipynb
3. PoisonDkNN_FinalNotebook.ipynb

Apart from the standard MNIST dataset, poisoned data is available in files with '.npy' extension.
First two notebooks use poisoned dataset during training of CNN. Third notebook deals with poisoned dataset separately as a test set.
Experiments for DeepkNN_ILA  with code adapated from [ILA](https://github.com/CUAI/Intermediate-Level-Attack) is work in progress.

Project report sans ILA experiment is at [Report](https://github.com/Bharys/IFT6756_H2021_Project/blob/main/IFT_6756_Project_Report.pdf)
