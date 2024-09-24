# HGDM
>Heterogeneous Diffusion Graph Learning
![model](./HDL.jpg)
## Abstract
Recent advances in Graph Neural Networks (GNNs) have significantly improved modeling of graph-structured data. However, traditional GNNs face challenges in dealing with complex heterogeneous structures commonly found in real-world applications. While recent studies have addressed dependencies among heterogeneous interactions, two major challenges persist: 1) Noisy data within heterogeneous structures can impair the learning of embeddings and negatively affect graph learning tasks; 2) Existing methods fail to capture complex semantic transitions among heterogeneous relations, impacting downstream predictions. To address these issues, we introduce a novel framework, Heterogeneous Graph Diffusion Model (HGDM), which incorporates a cross-view denoising strategy. This strategy effectively transforms auxiliary heterogeneous data into the target semantic space to distill task-relevant information. Our approach features a latent heterogeneous graph diffusion mechanism, which manages noise through an innovative forward and backward diffusion process. This method simultaneously achieves heterogeneous graph denoising and cross-type transition, and also eases the challenges of graph generation by leveraging its latent-space diffusion process. We validated our proposed framework through comprehensive experiments on both public and industrial datasets. The evaluation results demonstrate that \model\ outperforms existing methods in both link prediction and node classification tasks, showcasing its robustness and efficiency in processing heterogeneous graphs.
## Environment
- python=3.8
- torch=1.12.1
- numpy=1.23.1
- scipy=1.9.1
- dgl=1.0.2+cu113
