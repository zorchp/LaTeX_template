$$
  R_i(t)= \begin{cases}\dfrac{N_i(t-1)}{k_i(t-1)} & \text { if } s_i(t-1)=1, \\ 1-\dfrac{N_i(t-1)}{k_i(t-1)} & \text { if } s_i(t-1)=0.\end{cases}
$$


$$
I_{i \rightarrow j}(t)=c \cdot \frac{e^{\alpha \cdot R_j(t-1)}}{\sum_{k \in \Omega_i} e^{\alpha \cdot R_k(t-1)}}
$$

$$
\sigma_{I_{i \rightarrow j}}=\frac{1}{G} \sum_{k \in \Omega_i}\left(I_{i \rightarrow k}-\frac{c}{G}\right)^2,
$$

$$
\bar{\sigma}_{I_{i \rightarrow j}}=\frac{1}{N} \sum_{i=1}^N \sigma_{I_{i \rightarrow j}},
$$

$$
U_i(t)=\frac{r}{G} \sum_{j \in \Omega_i} \sum_{k \in \Omega_j} I_{k \rightarrow j}(t)-s_i(t) \cdot c.
$$

$$
P\left(s_j \rightarrow s_i\right)(t)=\frac{1}{1+\exp \left[\left(U_i(t)-U_j(t)\right) / \kappa\right]},
$$
