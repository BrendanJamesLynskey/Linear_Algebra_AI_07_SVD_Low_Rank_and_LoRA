# SVD, Low-Rank &amp; LoRA

Deck 07 of the [Linear Algebra for AI / ML](https://github.com/BrendanJamesLynskey/LLM_Hub_Linear_Algebra) series.

**Live presentation:** https://brendanjameslynskey.github.io/Linear_Algebra_AI_07_SVD_Low_Rank_and_LoRA/

The Singular Value Decomposition is the most useful theorem in applied linear algebra. It gives the best low-rank approximation of any matrix &mdash; the foundation of LoRA, MLA, low-rank KV-cache compression, and almost every "just project to a smaller space" trick in modern ML. Includes an interactive image-rank slider that visualises Eckart-Young directly.

## What's inside

- The SVD theorem and the three matrices $U, \Sigma, V$
- Geometric reading: rotate / scale / rotate
- Relation to eigendecomposition: right singular vectors = eigenvectors of $A^\top A$
- Truncated SVD and the Eckart-Young-Mirsky theorem (best rank-$k$ approximation)
- Effective rank, stable rank, $\varepsilon$-rank; what real ML weight matrices look like
- LoRA &mdash; fine-tuning as a rank constraint; param count, scaling, the $\alpha/r$ factor
- The LoRA family: QLoRA, DoRA, VeRA, PiSSA, LoRA+
- DeepSeek MLA &mdash; low-rank latent KV cache, ~20&times; reduction
- Interactive image-rank slider with singular-value bar chart and Frobenius error
- The pseudoinverse via SVD and ridge regression as small-singular-value smoothing

Single-page HTML, KaTeX-rendered maths, no build step. Open `index.html` directly.
