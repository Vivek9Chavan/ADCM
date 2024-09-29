# Active Data Collection and Management for Real-World Continual Learning via Pretrained Oracle

[[`Paper`](https://openaccess.thecvf.com/content/CVPR2024W/CLVISION/html/Chavan_Active_Data_Collection_and_Management_for_Real-World_Continual_Learning_via_CVPRW_2024_paper.html)] [[`Poster`](https://drive.google.com/file/d/1_8FC60_aXVbQHE0Ygls-7R0rwjBmtdyx/view?usp=sharing)] [[`Summary Video`](https://youtu.be/HwEzN7DfJw0?si=yCd5bYWm204ICdOb)]

**Abstract:** Incremental Learning (IL) deals with learning from continuous streams of data while minimising catastrophic forgetting. This field of Machine Learning (ML) research has introduced several novel approaches and methodologies for varying configurations. However academic Continual Learning setups generally work with well-curated datasets under predefined conditions which do not hold for practical applications. In real-world scenarios the problem of ML starts with data collection and curation. Depending on the application different challenges are posed w.r.t. data management such as similar objects unbalanced data containing sparse samples visual artefacts digitisation and camera setup. This becomes an incrementally compounding issue in Continual Learning projects with data drift and varying conditions. We propose Active Data Collection and Management (ADCM) a straightforward and effective general framework for data collection coreset/exemplar selection and analysis. A pretrained Oracle model provides ground truth distribution for the other model that learns incrementally. We couple ADCM with traditional ML/IL setups and demonstrate its suitability for real-world tasks such as fine-grained classification and anomaly detection. A baseline implementation of ADCM for Class-IL matches state-of-the-art exemplar selection strategies providing an improvement in average incremental accuracy of 1.5% with Dynamically Expandable Representation (DER) and 4.1% with PODNet against Herding and 0.8% on old class data against Reinforced Memory Management (RMM); and shows improved performance for general coreset selection. Our code will be available on this repository.


![Poster_img](https://github.com/Vivek9Chavan/ADCM/blob/main/ADCM_Poster_CVPRW.png)

# A System 1 and System 2 Perspective on Continual Learning for Practical Implementation

[[`Paper`](https://drive.google.com/file/d/1R2IpWB1dlymLCUB0kvpJnu49acIMJkta/view?usp=drive_link)] [[`Poster`](https://drive.google.com/file/d/1vbhL9r-hSThIvE5iK7VjEa8NEd1er-yN/view?usp=sharing)]

**Abstract:** Deep Learning based approaches have led to several breakthroughs in Computer Vision (CV) research. However, catastrophic forgetting and the plasticity-rigidity dilemma remain a fundamental obstacle in our path to machine intelligence. Continual Learning (CL) research aims to address this issue through replay, model augmentation, regularisation and other techniques. In this paper, we analyse CL using the Dual Process theory and related frameworks. We extend concepts and theories from studies on human reasoning and learning to ongoing CL developments. We argue that Continual Learning is a System 2 problem, and derive insights about the practical application of existing approaches. We develop our hypotheses and verify their validity on publicly available and varied datasets. Our approach involves encoding contextual semantic information and robust pretraining. Experiments show that these techniques can improve model performance under diverse scenarios.


![Poster_img](![HCV](https://github.com/user-attachments/assets/44878e34-da5d-424f-862f-95082a90450c))

## Code and resources will be available here soon.

## Acknowledgements

Our code borrows heavily form the following repositories:

https://github.com/G-U-N/PyCIL

https://github.com/facebookresearch/dino

https://github.com/facebookresearch/VICRegL

<a name="bibtex"></a>
## Citation

If you find our work or any of our materials useful, please cite our paper:
```
@InProceedings{Chavan_2024_CVPR,
    author    = {Chavan, Vivek and Koch, Paul and Schl\"uter, Marian and Briese, Clemens and Kr\"uger, J\"org},
    title     = {Active Data Collection and Management for Real-World Continual Learning via Pretrained Oracle},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
    month     = {June},
    year      = {2024},
    pages     = {4085-4096}
}

@InProceedings{Chavan_2024_ECCV,
    author    = {Chavan, Vivek and Heimann, Oliver and Kr\"uger, J\"org},
    title     = {A System 1 and System 2 Perspective on Continual Learning for Practical Implementation},
    booktitle = {European Conference on Computer Vision (ECCV) Workshops},
    month     = {October},
    year      = {2024}
}
