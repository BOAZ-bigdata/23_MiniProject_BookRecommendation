# 23_Mini_Project : ✧ Book-Recommendation ✧

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
- Taking into account that the actual rating matrix is sparse and side information is limited, we aimed to implement an accurate recommendation model tailored to each user’s preferences.
- To achieve this, we formed teams of two, studied the relevant research papers, and implemented the two models described below.

### 1) GLocal-K
![image](https://github.com/user-attachments/assets/b4b51347-aba7-4617-8746-f57123b84c6c)
- Paper : https://arxiv.org/abs/2108.12184
- Reference : https://paperswithcode.com/paper/glocal-k-global-and-local-kernels-for

### 2) LightGCN
![image](https://github.com/user-attachments/assets/177a2622-dc22-409d-bfd5-1dedd3f7b731)
- Paper : https://arxiv.org/abs/2002.02126
- Reference : https://paperswithcode.com/method/lightgcn

# Metrics
- NDCG
- Recall
- Precision
- Map

# Conclusion
- After performing EDA on the Amazon book dataset, we found that there were relatively few user reviews per individual item, despite the dataset containing a wide variety of different items.
- Since this was our first experience implementing a research paper, we encountered many difficulties, and it’s regrettable that we weren’t able to modify the model itself to better suit our dataset.
- We also regret not being able to implement an app or web interface to showcase the recommended results, which highlights a technical shortcoming in our approach.
