# Home

Welcome to CS 189/289A! This class covers theoretical foundations, algorithms, methodologies, and applications for machine learning. Topics may include supervised methods for regression and classication (linear models, trees, neural networks, ensemble methods, instance-based methods); generative and discriminative probabilistic models; deep learning models including CNNs, transformers, graph neural networks for vision and language tasks; and Markovian models for reinforcement learning and robotics.

**Textbook:** [_Deep Learning_](https://www.bishopbook.com/) by Bishop and Bishop.

Professors will post slides prior to lecture at this Google Drive [folder](https://drive.google.com/drive/folders/1hM6_gb8-cel4-hQ9_sMcm9krwfzmppkU?usp=drive_link) (for faster access). The material here is redundant with the website, but it may take up to a day or two for the website to get updated with the slides after lecture. The “Post-Lecture” subfolder contains updates to slides that the professors may make right after lecture. In addition, lecture recordings will be uploaded automatically to this Haas Panopto [folder](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx#folderID=%22380bd203-98f7-4a83-946e-b1d401302c37%22).

If you have not been added to **EdStem**, you may join through this [link](https://edstem.org/us/join/RUHntB). The **Gradescope** code is **DKPWZW**.

**Note:** The topics for future lectures, discussions, and HWs are **tentative** and may be moved around, changed, or removed.

## Overview <a href="#overview" id="overview"></a>

### Week 1 <a href="#week-1" id="week-1"></a>

| 8/29 | LECTURE 1 [Introduction and Logistics](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=2a2b47b1-dc5f-41e4-8258-b1d4013efe89) ([Slides](https://drive.google.com/file/d/1B-ikDeLJy045W0cw4qpP616MQXSRpqQh/view?usp=drive_link)) | READING 1.1-1.2.4                                                                                                                                                         |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|      | HOMEWORK 1 Math Review (**Due** ~~9/11~~ **9/12 11:59pm**)                                                                                                                                                                                           | [PDF](https://eecs189.org/docs/hw_fa24/hw1.pdf) / [Files](https://eecs189.org/docs/hw_fa24/hw1.zip) / [LaTeX Template](https://eecs189.org/docs/hw_fa24/hw1_template.tex) |

### Week 2 <a href="#week-2" id="week-2"></a>

| 9/3 | LECTURE 2 [Maximum Likelihood Estimation](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=78393f71-f7d8-4877-8ae4-b1d4013efedc) ([Slides](https://drive.google.com/file/d/1BsohO4nidHSdP3eZtWmcAN9mAMvID4B2/view?usp=sharing)) | <p>READING<br>2-2.1.2 (rules of probability: sum, product)<br>2.1.6 (independent RVs)<br>2.2-2.2.1 (probability densities in continuous spaces)<br>2.3-2.3.2 (univariate Gaussian, likelihood)<br>3-3.1.3 (Bernoulli, binomial, multinomial, MLE)</p> |
| --- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|     | DISCUSSION 0 Math Pre-Requisites Review                                                                                                                                                                                                              | [Worksheet](https://eecs189.org/docs/dis_fa24/dis0.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis0sol.pdf)                                                                                                                                  |
| 9/5 | LECTURE 3 [Multivariate Gaussians](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=eeb87936-eb47-436b-b6e5-b1d4013efefb) ([Slides](https://drive.google.com/file/d/11ozzwYUqyJnHeCxbKE9TL-kgZAyrykN5/view?usp=drive_link))     | READING 3-3.2.3 (multivariate Gaussians: geometry, moments, covariance forms)                                                                                                                                                                         |

### Week 3 <a href="#week-3" id="week-3"></a>

| 9/10 | LECTURE 4 [Linear Regression 1](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=0b684900-3ef3-411e-bb68-b1d4013eff13) ([Slides](https://drive.google.com/file/d/14vblwqegBN7BC8-l1sAsRmiEVIu0TFmR/view?usp=drive_link)) | READING 4-4.1.4                                                                                                                                                                                   |
| ---- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|      | DISCUSSION 1 MLE & Gaussians                                                                                                                                                                                                                  | [Worksheet](https://eecs189.org/docs/dis_fa24/dis1.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis1sol.pdf)                                                                              |
| 9/12 | LECTURE 5 [Linear Regression 2](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=56e9bd90-5e0c-4333-bbac-b1d4013eff2e) ([Slides](https://drive.google.com/file/d/1S8WxurxGYTv6BZs3LGCHSR-tYkEvV8bC/view?usp=drive_link)) | <p>READING<br>1.25-1.26 (regularization, model selection)<br>2.1.3 (Bayes theorem)<br>2.6 (Bayesian modeling)<br>4.1.6 (regularization for linear regression)<br>9.2.2 (Lasso regularization)</p> |
|      | HOMEWORK 2 Linear/Logistic Regression & Classification (**Due 9/25 11:59pm**)                                                                                                                                                                 | [PDF](https://eecs189.org/docs/hw_fa24/hw2.pdf) / [Files](https://eecs189.org/docs/hw_fa24/hw2.zip) / [LaTeX Template](https://eecs189.org/docs/hw_fa24/hw2template.tex)                          |

### Week 4 <a href="#week-4" id="week-4"></a>

| 9/17 | LECTURE 6 [Classification - Generative & Discriminative](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=e0e7d595-678f-4064-a105-b1d4013eff4f) ([Slides](https://drive.google.com/file/d/1-g3MKFW9lDqYA9nRz9RbpPaztAFvVszq/view?usp=drive_link)) | READING 5.1, 5.2.1, 5.2.2, 5.2.4, 5.3                                                                                |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
|      | DISCUSSION 2 Regularization & MAP                                                                                                                                                                                                                                      | [Worksheet](https://eecs189.org/docs/dis_fa24/dis2.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis2sol.pdf) |
| 9/19 | LECTURE 7 [Logistic Regression & Neural Networks](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=a245360c-f0f3-4b7d-bd8d-b1d4013eff6c) ([Slides](https://drive.google.com/file/d/1MSqZtGFwyzRe6RD-MNKDIrfYvORK1TvO/view?usp=drive_link))        | READING 5.3.1, 5.4.1-5.4.4, 6.1-6.2                                                                                  |

### Week 5 <a href="#week-5" id="week-5"></a>

| 9/24 | LECTURE 8 [Backpropagation and Gradient Descent 1](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=27000014-6252-4b89-a499-b1d4013eff92) ([Slides](https://drive.google.com/file/d/1vfk8jqrsUay0J9IB-IPMnHwOp3IOZSnd/view?usp=drive_link)) | READING 6.2, 6.4, 7.1, 7.2, 5.4.4                                                                                                                                        |
| ---- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|      | DISCUSSION 3 Classification & Logistic Regression                                                                                                                                                                                                                | [Worksheet](https://eecs189.org/docs/dis_fa24/dis3.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis3sol.pdf)                                                     |
| 9/26 | LECTURE 9 [Backpropagation and Gradient Descent 2](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=9ac17588-cef2-45f7-acd5-b1d4013effaf) ([Slides](https://drive.google.com/file/d/17tf2EgsyLHTAus6azWdTRSZH4cNkd2-4/view?usp=sharing))    | READING 5.4.4, 8                                                                                                                                                         |
|      | HOMEWORK 3 Neural Networks (**Due 10/9 11:59pm**)                                                                                                                                                                                                                | [PDF](https://eecs189.org/docs/hw_fa24/hw3.pdf) / [Files](https://eecs189.org/docs/hw_fa24/hw3.zip) / [LaTeX Template](https://eecs189.org/docs/hw_fa24/hw3template.tex) |

### Week 6 <a href="#week-6" id="week-6"></a>

| 10/1 | LECTURE 10 [Neural Networks - CNNs, Batch Norm, & ResNets](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=90e02259-b095-494f-a363-b1d4013effc7) ([Slides](https://drive.google.com/file/d/1KVk_pfkzSkofNzwDo3kTLQosWOD9Y1gg/view?usp=drive_link)) | READING 7.4, 9.5, 10                                                                                                 |
| ---- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------- |
|      | DISCUSSION 4 Neural Networks and Backpropagation                                                                                                                                                                                                                         | [Worksheet](https://eecs189.org/docs/dis_fa24/dis4.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis4sol.pdf) |
| 10/3 | LECTURE 11 [Neural Networks - Attention & Transformers](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=42f09b54-f2f8-48ea-9e10-b1d4013effe9) ([Slides](https://drive.google.com/file/d/1IFyzNFeuLwuqOyC4ro90PMTuppCAGnND/view?usp=sharing))       | READING 5.3, 12.1                                                                                                    |

### Week 7 <a href="#week-7" id="week-7"></a>

| 10/8  | LECTURE 12 [Dimensionality Reduction & PCA](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5af23bc9-902e-4a00-8fda-b1d4013f0009) ([Slides](https://drive.google.com/file/d/1LJUJsVbpbwUWS9veFofSuzkOkIYjhNIw/view?usp=drive_link)) | READING 16.1                                                                                                                                                             |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|       | DISCUSSION 5 Convolution and Attention                                                                                                                                                                                                                    | [Worksheet](https://eecs189.org/docs/dis_fa24/dis5.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis5sol.pdf)                                                     |
| 10/10 | LECTURE 13 [t-SNE](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=e60ff9dc-7403-4a84-b53d-b1d4013f0028) ([Slides](https://drive.google.com/file/d/1nWYPS98wNO2jVLvBMB32szsDOXu7edbQ/view?usp=drive_link))                          |                                                                                                                                                                          |
|       | HOMEWORK 4 Dimensionality Reduction & Decision Theory (**Due 10/25 11:59pm**)                                                                                                                                                                             | [PDF](https://eecs189.org/docs/hw_fa24/hw4.pdf) / [Files](https://eecs189.org/docs/hw_fa24/hw4.zip) / [LaTeX Template](https://eecs189.org/docs/hw_fa24/hw4template.tex) |

### Week 8 <a href="#week-8" id="week-8"></a>

| 10/15 | LECTURE 14 [Clustering](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=6b06ad21-49af-4254-9500-b1d4013f004c) ([Slides](https://drive.google.com/file/d/1I4sni1y5iXR7LjdBQ1TMn5ZtDl7Umrp3/view?usp=drive_link))                          | READING 15.1 (not including 15.1.1), 15.2                                                                            |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
|       | DISCUSSION 6 Dimensionality Reduction Techniques                                                                                                                                                                                                               | [Worksheet](https://eecs189.org/docs/dis_fa24/dis6.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis6sol.pdf) |
| 10/16 | MIDTERM (7-9pm, Dwinelle 155)                                                                                                                                                                                                                                  |                                                                                                                      |
| 10/17 | LECTURE 15 [Nearest Neighbors & Metric Learning](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=e28b1ff9-717c-4217-b592-b1d4013f0085) ([Slides](https://drive.google.com/file/d/1p6uiI2y1ZCKCouFpxoJ72yC1JmPS2Df1/view?usp=drive_link)) | READING 3.5, 6.3.5                                                                                                   |

### Week 9 <a href="#week-9" id="week-9"></a>

| 10/22 | LECTURE 16 [Model Evaluation](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=194fc155-3acd-4009-a3c3-b1d4013f00a7) ([Slides](https://drive.google.com/file/d/16xXuolUV9K14jYSI4_xggsLgt6xPn9CY/view?usp=sharing))               | READING 5.25, 5.26                                                                                                                                                       |
| ----- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|       | DISCUSSION 7 Gaussian Mixture Models                                                                                                                                                                                                                   | [Worksheet](https://eecs189.org/docs/dis_fa24/dis7.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis7sol.pdf)                                                     |
| 10/24 | LECTURE 17 [Decision Trees & Ensembling](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5a92474e-2705-41f1-bfe7-b1d4013f00ce) ([Slides](https://drive.google.com/file/d/1U5EFGq1NkYKdy4xSMB-CI7FP-2_4pgxM/view?usp=drive_link)) | READING 9.6 not including 9.6.1 (model averaging)                                                                                                                        |
|       | HOMEWORK 5 Bias/Variance, Nearest Neighbors, Decision Trees (**Due 11/8 11:59pm**)                                                                                                                                                                     | [PDF](https://eecs189.org/docs/hw_fa24/hw5.pdf) / [Files](https://eecs189.org/docs/hw_fa24/hw5.zip) / [LaTeX Template](https://eecs189.org/docs/hw_fa24/hw5template.tex) |

### Week 10 <a href="#week-10" id="week-10"></a>

| 10/29 | LECTURE 18 [Bias-Variance Tradeoff & Over/Under-Fitting](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=a00177aa-d77e-4098-b867-b1d4013f00f1) ([Slides](https://drive.google.com/file/d/1bWeLeK3xaIQrUr-oUQVjOVGOnxQhg3Vo/view?usp=drive_link)) | READING 4.2, 4.3, 9.3.2                                                                                              |
| ----- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
|       | DISCUSSION 8 Bias/Variance, Decision Trees, & Nearest Neighbors                                                                                                                                                                                                        | [Worksheet](https://eecs189.org/docs/dis_fa24/dis8.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis8sol.pdf) |
| 10/31 | LECTURE 19 [Hidden Markov Models & Graphical Models 1](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=1cb78411-61e2-43d7-9c93-b1d4013f0112) ([Slides](https://drive.google.com/file/d/1lpj2Ax6fU1ei--5GJqw35YT-5gg45zjD/view?usp=drive_link))   | READING 11                                                                                                           |

### Week 11 <a href="#week-11" id="week-11"></a>

| 11/5 | LECTURE 20 [Hidden Markov Models & Graphical Models 2](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=9ecbbdee-d01b-4f10-810c-b1d4013f0132) ([Slides](https://drive.google.com/file/d/1i9UX9FwgKjfpYgKlnFIJuPXjmj9gwxXw/view?usp=sharing)) | READING Bishop 11; [Barber](http://web4.cs.ucl.ac.uk/staff/D.Barber/textbook/090310.pdf) 23.2.2, 23.2.5                                                                  |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|      | DISCUSSION 9 Random Forests and HMMs Intro                                                                                                                                                                                                                        | [Worksheet](https://eecs189.org/docs/dis_fa24/dis9.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis9sol.pdf)                                                     |
| 11/7 | LECTURE 21 [Generative Models 1](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=01b09f69-c06d-4faf-9dc7-b1d4013f0152) ([Slides](https://drive.google.com/file/d/1NL-JzwKWoF8OfODRVzt2mmFhcsaCKzIp/view?usp=sharing))                       | READING 14.3                                                                                                                                                             |
|      | HOMEWORK 6 Graphical Models & Langevin MCMC (**Due 11/20 11:59pm**)                                                                                                                                                                                               | [PDF](https://eecs189.org/docs/hw_fa24/hw6.pdf) / [Files](https://eecs189.org/docs/hw_fa24/hw6.zip) / [LaTeX Template](https://eecs189.org/docs/hw_fa24/hw6template.tex) |

### Week 12 <a href="#week-12" id="week-12"></a>

| 11/12 | LECTURE 22 [Generative Models 2](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=6b1316da-dbfa-41ba-b546-b1d4013f0178) ([Slides](https://drive.google.com/file/d/1LY_43MV4uLmWF9IYHDt818k44mTkTWcU/view?usp=drive_link))                                | READING 20.3                                                                                                           |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
|       | DISCUSSION 10 Langevin Sampling                                                                                                                                                                                                                                               | [Worksheet](https://eecs189.org/docs/dis_fa24/dis10.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis10sol.pdf) |
| 11/14 | LECTURE 23 [Markov Decision Processes & Reinforcement Learning](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=f35157a8-cfa3-468e-8076-b1d4013f019c) ([Slides](https://drive.google.com/file/d/1yzpf9CAw2TiJ8angMWYM0khRxselfhYV/view?usp=drive_link)) |                                                                                                                        |

### Week 13 <a href="#week-13" id="week-13"></a>

| 11/19 | LECTURE 24 [Graph Neural Networks 1](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=7a341980-ce54-4ae4-aba6-b1d4013f01d7) ([Slides](https://drive.google.com/file/d/1F9DGGR5OS06ZcScBT6stm1zrRDOJKIo0/view?usp=sharing))                       | READING 13                                                                                                                                                                   |
| ----- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|       | DISCUSSION 11 Score Matching; MDPs & Reinforcement Learning                                                                                                                                                                                                           | [Worksheet](https://eecs189.org/docs/dis_fa24/dis11.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis11sol.pdf)                                                       |
| 11/21 | LECTURE 25 [Graph Neural Networks 2](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Sessions/List.aspx#folderID=%22380bd203-98f7-4a83-946e-b1d401302c37%22) ([Slides](https://drive.google.com/file/d/1W4Tckoy7lSL8ryG3DVFK4btAcjl5WweG/view?usp=drive_link)) | READING 13                                                                                                                                                                   |
|       | HOMEWORK 7 Score Matching, MDPs, Graph Neural Networks & Kernels (**Due 12/7 11:59pm**)                                                                                                                                                                               | [PDF](https://eecs189.org/docs/hw_fa24/hw7.pdf) / [Files](https://eecs189.org/docs/hw_fa24/hw7code.zip) / [LaTeX Template](https://eecs189.org/docs/hw_fa24/hw7template.tex) |

### Week 14 <a href="#week-14" id="week-14"></a>

| 11/26 | LECTURE 26 [Kernel Methods](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=0193d400-0332-4b45-a3cc-b1d4013f0217) ([Slides](https://drive.google.com/file/d/14cDmyVgTB5H3o_sknJaMdlsb0qmBb79H/view?usp=sharing)) |   |
| ----- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | - |
| 11/28 | No Lecture (Thanksgiving)                                                                                                                                                                                                              |   |

### Week 15 <a href="#week-15" id="week-15"></a>

| 12/3 | LECTURE 27 [Causality](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=3582f4e3-35fa-4798-83cb-b1d4013f025d) ([Slides](https://drive.google.com/file/d/1Uu_zILze3vKJxsX-iKqT0IWRu29tfzkq/view?usp=sharing))                              | OPTIONAL READING [Hardt](https://mlstory.org/) Chapters 9 & 10                                                         |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
|      | DISCUSSION 12 Graph Neural Networks, Kernel Methods & Causality                                                                                                                                                                                                | [Worksheet](https://eecs189.org/docs/dis_fa24/dis12.pdf) / [Solutions](https://eecs189.org/docs/dis_fa24/dis12sol.pdf) |
| 12/5 | LECTURE 28 [Special Topics - Computational Biology](https://berkeley-haas.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=5e7552d6-0398-4597-b57f-b1d4013f027e) ([Slides](https://drive.google.com/file/d/1B0gILCXnSYSu8Uipc-PiBzMC7mzu5Z1y/view?usp=sharing)) |                                                                                                                        |

### Week 16 (RRR Week) <a href="#week-16-rrr-week" id="week-16-rrr-week"></a>

| 12/10 | TA REVIEW SESSION Pre-Midterm Material (1-3 PM, Soda 306)              | [Slides](https://eecs189.org/docs/pre-midterm-review.pdf)  |
| ----- | ---------------------------------------------------------------------- | ---------------------------------------------------------- |
| 12/11 | TA REVIEW SESSION Post-Midterm Material (9-11 AM, Soda Wozniak Lounge) | [Slides](https://eecs189.org/docs/post-midterm-review.pdf) |

### Week 17 (Finals Week) <a href="#week-17-finals-week" id="week-17-finals-week"></a>

| 12/17 | FINAL EXAM (8-11am) | [Blank](https://eecs189.org/docs/exams/finalf24blank.pdf) / [Solutions](https://eecs189.org/docs/exams/finalf24.pdf) |
| ----- | ------------------- | -------------------------------------------------------------------------------------------------------------------- |