# Active Data Collection and Management for Real-World Continual Learning via Pretrained Oracle

[[`Paper`](https://openaccess.thecvf.com/content/CVPR2024W/CLVISION/html/Chavan_Active_Data_Collection_and_Management_for_Real-World_Continual_Learning_via_CVPRW_2024_paper.html)] [[`Poster`](https://drive.google.com/file/d/1_8FC60_aXVbQHE0Ygls-7R0rwjBmtdyx/view?usp=sharing)] [[`Summary Video`](https://youtu.be/HwEzN7DfJw0?si=yCd5bYWm204ICdOb)]

**Abstract:** Incremental Learning (IL) deals with learning from continuous streams of data while minimising catastrophic forgetting. This field of Machine Learning (ML) research has introduced several novel approaches and methodologies for varying configurations. However academic Continual Learning setups generally work with well-curated datasets under predefined conditions which do not hold for practical applications. In real-world scenarios the problem of ML starts with data collection and curation. Depending on the application different challenges are posed w.r.t. data management such as similar objects unbalanced data containing sparse samples visual artefacts digitisation and camera setup. This becomes an incrementally compounding issue in Continual Learning projects with data drift and varying conditions. We propose Active Data Collection and Management (ADCM) a straightforward and effective general framework for data collection coreset/exemplar selection and analysis. A pretrained Oracle model provides ground truth distribution for the other model that learns incrementally. We couple ADCM with traditional ML/IL setups and demonstrate its suitability for real-world tasks such as fine-grained classification and anomaly detection. A baseline implementation of ADCM for Class-IL matches state-of-the-art exemplar selection strategies providing an improvement in average incremental accuracy of 1.5% with Dynamically Expandable Representation (DER) and 4.1% with PODNet against Herding and 0.8% on old class data against Reinforced Memory Management (RMM); and shows improved performance for general coreset selection. Our code will be available on this repository.


![Poster_img](https://github.com/Vivek9Chavan/ADCM/blob/main/ADCM_CVPRW_Poster.png)

