# Federated clustering

Federated clustering (FC) plays a crucial role in resolving the challenge of clustering non-IID data across devices and organizations (i.e. clients) by leveraging distributed data processing and privacy-preserving techniques, enhancing both efficiency and security.

Although the field holds considerable importance, it has not yet garnered widespread attention. To draw the community's attention to this research field and make it more accessible to newcomers, we created this repository, summarizing relevant papers and corresponding code sources. 

This repository will be regularly maintained with updates. We are looking forward to any comments or discussions on this topic!

# FC Zoo
FC, as an extension of centralized clustering, naturally suggests an algorithm design approach that extends the methodologies of centralized clustering. The summarized extensions are outlined below.

### Shallow FC
  
<details>
<summary> k-means extensions  </summary>

|    Title    |  Publication  | Year     | Code |
|  :---------  | :------      | :------  | :------ | 
| :triangular_flag_on_post: SDA-FC: Bridging Federated Clustering and Deep Generative Model| Information Sciences | 2024 | https://github.com/Jarvisyan/SDA-FC|
|Asynchronous Federated Clustering with Unknown Number of Clusters | AAAI | 2025 | https://github.com/Yunfan-Zhang/AFCL |
|Federated Multi-View K-Means Clustering | IEEE Transactions on Pattern Analysis and Machine Intelligence | 2024 | - |
|One-Shot Federated Clustering Based on Stable Distance Relationships | IEEE Transactions on Industrial Informatics | 2024 | https://github.com/mlyizhang/nnfc |
|Jigsaw Game: Federated Clustering | Transactions on Machine Learning Research | 2024 | - |
|Greedy centroid initialization for federated K-means | Knowledge and Information Systems | 2024 | - |
|Machine Unlearning of Federated Clusters | ICLR | 2023 | https://github.com/thupchnsky/mufc |
|Secure Federated Clustering | arxiv | 2022 | - |
|Heterogeneity for the Win: One-Shot Federated Clustering | ICML | 2021 | https://github.com/metastableB/kfed |
</details>


<details>
<summary> fuzzy c-means extensions </summary>
  
|    Title    |  Publication  | Year     | Code |
|  :---------  | :------      | :------  | :------ | 
|Federated c-means and Fuzzy c-means Clustering Algorithms for Horizontally and Vertically Partitioned Data | IEEE Transactions on Artificial Intelligence | 2024 | https://github.com/Unipisa/FederatedClustering |
|An Efficient Federated Multi-view Fuzzy C-Means Clustering Method | IEEE Transactions on Fuzzy Systems | 2023 | https://github.com/XingchenHu2017/FedMVFPC |
| Towards Federated Clustering: A Federated Fuzzy c-Means Algorithm (FFCM) | AAAI-workshop | 2022 | https://github.com/stallmo/federated_clustering |
|Federated FCM: Clustering under privacy requirements | IEEE Transactions on Fuzzy Systems | 2021 | - |
</details>


<details>
<summary> spectral clustering extensions </summary>

|    Title    |  Publication  | Year     | Code |
|  :---------  | :------      | :------  | :------ | 
|Federated spectral clustering via secure similarity reconstruction | NIPS | 2023 | https://github.com/jicongfan/Federated-Spectral-Clustering |
|FedSpectral+: Spectral Clustering using Federated Learning | AAAI-workshop | 2023 | - |
|Federated Multi-View Spectral Clustering | IEEE Access | 2023 | - |
</details>


<details>
<summary> NMF extensions </summary>

|    Title    |  Publication  | Year     | Code |
|  :---------  | :------      | :------  | :------ | 
|Federated Matrix Factorization: Algorithm Design and Application to Data Clustering | IEEE Transactions on Signal Processing | 2022 | https://github.com/wshuai317/FedMF |

|Secure Federated Clustering | arxiv | 2022 | - |
|Secure Federated Clustering | arxiv | 2022 | - |
</details>


<details>
<summary> density clustering extensions </summary>

|    Title    |  Publication  | Year     | Code |
|  :---------  | :------      | :------  | :------ | 
|Horizontal Federated Density Peaks Clustering | IEEE Transactions on Neural Networks and Learning Systems | 2023 | - |
</details>


### Deep FC
<details>
<summary> k-means extensions  </summary>

|    Title    |  Publication  | Year     | Code |
|  :---------  | :------      | :------  | :------ | 
| :triangular_flag_on_post: CCFC++: Enhancing Federated Clustering through Feature Decorrelation | arXiv | 2024 | - |
| :triangular_flag_on_post: CCFC: Bridging Federated Clustering and Contrastive Learning | arXiv | 2024 | https://github.com/Jarvisyan/CCFC-pytorch |
| :triangular_flag_on_post: Privacy-preserving federated deep clustering based on gan | arXiv | 2022 | -|
|An autoencoder-based confederated clustering leveraging a robust model fusion strategy for federated unsupervised learning | Information Fusion | 2025 | - |
|Federated Deep Multi-View Clustering with Global Self-Supervision | ACM-MM | 2023 | - |
</details>


<details>
<summary> others </summary>
  
|    Title    |  Publication  | Year     | Code |
|  :---------  | :------      | :------  | :------ | 
|Federated Momentum Contrastive Clustering | ACM Transactions on Intelligent Systems and Technology | 2024 | - |
</details>
