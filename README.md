```python
def sin(x)
return sin

gnuplot(sin())
```
```
   1 ++----------------**---------------+----**-----------+--------**-----++
     +                *+ *              +   *  *          +  sin(x) ****** +
 0.8 ++              *    *                *    *                *    *   ++
     |               *    *                *    *                *    *    |
 0.6 ++              *     *              *      *              *      *  ++
     *              *       *             *       *             *      *   |
 0.4 +*             *       *             *       *             *      *  ++
     |*            *        *            *        *            *        *  |
 0.2 +*            *        *            *        *            *        * ++
     | *          *          *          *          *          *          * |
   0 ++*          *          *          *          *          *          *++
     |  *         *           *         *           *         *           *|
-0.2 ++ *         *           *         *           *         *           *+
     |   *       *            *        *            *        *            *|
-0.4 ++  *       *            *        *            *        *            *+
     |   *      *              *      *              *      *              *
-0.6 ++  *      *              *      *              *      *             ++
     |    *     *               *     *               *    *               |
-0.8 ++    *   *                 *   *                *    *              ++
     +     *  *        +         *  *   +              *  *                +
  -1 ++-----**---------+----------**----+---------------**+---------------++
    -10               -5                0                 5                10
```


<div align="center">

$$
\displaystyle\Huge \begin{array}{c}
\displaystyle\Huge \mathbf{z}_i = \begin{bmatrix} p_{i,1} \\ p_{i,2} \\ \vdots \\ p_{i,m} \end{bmatrix} \in \mathbb{R}^m
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\displaystyle\Huge \mathbf{S} = \left[ \begin{array}{c} \mathbf{z}_1 \\\\ \mathbf{z}_2 \\\\ \vdots \\\\ \mathbf{z}_n \end{array} \right] = \left[ \begin{array}{c} \begin{bmatrix} p_{1,1} \\ p_{1,2} \\ \vdots \\ p_{1,m} \end{bmatrix} \\\\ \begin{bmatrix} p_{2,1} \\ p_{2,2} \\ \vdots \\ p_{2,m} \end{bmatrix} \\\\ \vdots \\\\ \begin{bmatrix} p_{n,1} \\ p_{n,2} \\ \vdots \\ p_{n,m} \end{bmatrix} \end{array} \right] \in \mathbb{R}^{n \times m}
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\mathcal{T} = \left[ \begin{array}{c} \mathbf{S}_1 \\\\ \mathbf{S}_2 \\\\ \vdots \\\\ \mathbf{S}_\tau \end{array} \right] = \left[ \begin{array}{c} \left[ \begin{array}{c} \mathbf{z}_{1,1} \\ \vdots \\ \mathbf{z}_{1,n} \end{array} \right] \\\\ \left[ \begin{array}{c} \mathbf{z}_{2,1} \\ \vdots \\ \mathbf{z}_{2,n} \end{array} \right] \\\\ \vdots \\\\ \left[ \begin{array}{c} \mathbf{z}_{\tau,1} \\ \vdots \\ \mathbf{z}_{\tau,n} \end{array} \right] \end{array} \right] \in \mathbb{R}^{\tau \times n \times m}
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\Phi: \mathcal{T} \to \mathcal{H} \quad \text{wobei} \quad \dim(\mathcal{H}) = \infty
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\\\\
\displaystyle\Huge \Delta \mathcal{E} = \frac{\Phi(\mathcal{T}_{\text{soll}}) - \Phi(\mathcal{T}_{\text{ist}})}{\Delta t + 1}
\end{array}
$$

</div>
