## 24.2-1

> Run $\text{DAG-SHORTEST-PATHS}$ on the directed graph of Figure 24.5, using vertex $r$ as the source.

- $d$ values:

    $$
    \begin{array}{cccccc}
    r & s & t & x & y & z \\\\
    \hline
    0 & \infty & \infty & \infty & \infty & \infty \\\\
    0 & 5 & 3 & \infty & \infty & \infty \\\\
    0 & 5 & 3 & 11 & \infty & \infty \\\\
    0 & 5 & 3 & 10 & 7 & 5 \\\\
    0 & 5 & 3 & 10 & 7 & 5 \\\\
    0 & 5 & 3 & 10 & 7 & 5
    \end{array}
    $$

- $\pi$ values:

    $$
    \begin{array}{cccccc}
    r & s & t & x & y & z \\\\
    \hline
    \text{NIL} & \text{NIL} & \text{NIL} & \text{NIL} & \text{NIL} & \text{NIL} \\\\
    \text{NIL} & r & r & \text{NIL} & \text{NIL} & \text{NIL} \\\\
    \text{NIL} & r & r & s & \text{NIL} & \text{NIL} \\\\
    \text{NIL} & r & r & t & t & t \\\\
    \text{NIL} & r & r & t & t & t \\\\
    \text{NIL} & r & r & t & t & t
    \end{array}
    $$
