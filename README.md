# 23 Mini Project: ✧BookRecommendation
도서 데이터 기반 추천시스템 (LightGCN, GLocal-K) 구현

- **Usage:**
  - [ ] Session
  - [ ] Conference
  - [x] Mini projects
  - [ ] Study

- **Period:**
  - 2024.10 ~ 2024.12

- **Team:**
  - **Team Manager:** [윤왕규](https://github.com/yoonwanggyu)
  - **Team Members:** [김경민](https://github.com/rudals6151), [백다운](https://github.com/nuebaek), [오영민](https://github.com/oymin2001)

---

# Backgrounds
- We initiated this project to deepen our understanding of the ongoing advancements and emerging trends in the field of recommendation systems.  
- We chose **LightGCN** and **GLocal-K** to develop models that precisely capture users’ inherent preferences while ensuring scalability and efficiency.  
- As research increasingly explores integrating recommendation systems with large language models (LLMs), we plan to maintain an active interest and continue our exploration in this direction.

# Data
- This is a large-scale Amazon Reviews dataset, collected in 2023 by McAuley Lab, and it includes rich features such as:  
  - User Reviews (ratings, text, helpfulness votes, etc.)  
  - Item Metadata (descriptions, price, raw image, etc.)  
  - Links (user-item / bought together graphs)
- Link : https://amazon-reviews-2023.github.io
  
# Models
- 
## 1) GLocal-K
- Paper : https://arxiv.org/abs/2108.12184
- Reference : https://paperswithcode.com/paper/glocal-k-global-and-local-kernels-for

## 2) LightGCN
- Paper : https://arxiv.org/abs/2002.02126
- Reference : https://paperswithcode.com/method/lightgcn

# Metrics
- NDCG, Recall, Precision, Map
  
