1. 行和为0
2. 矩阵中无相反向量
3. 无零向量
4. 无相同列
5. 元素仅为 0, 1, -1

step1 80 组非零向量 上下对应的向量和为0
\[\begin{bmatrix}  0 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\ -1 \\ -1 \end{bmatrix} \; \]
\[\begin{bmatrix}  0 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  1 \\  1 \end{bmatrix} \; \]

需要39个向量，多了一组，删去最后一组即可















上下交换第27-39列 第一行的和为0

\[\begin{bmatrix}  0 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  1 \\ -1 \end{bmatrix} \;\]
\[\begin{bmatrix}  0 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\ -1 \\  1 \end{bmatrix} \; \]

这样第14-39列已经完全确定了，再交换上下列会导致第一行的和不为0

将目光放在前13列上

后26列第二行和为 1*4+(-1)*5+1*8 = 7

选择第7-13列上下交换
发现第5,6 列第二个元素均为1
因此选择第6-13列上下交换






\[\begin{bmatrix}  0 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  1 \\ -1 \end{bmatrix} \;\]
\[\begin{bmatrix}  0 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\ -1 \\  1 \end{bmatrix} \; \]

从第5列之后的元素也固定了

第三行行和为4 需要移动两列 选择3-4列


















\[\begin{bmatrix}  0 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  1 \\  1 \\ -1 \end{bmatrix} \;\]
\[\begin{bmatrix}  0 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  0 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\  0 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix} -1 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\  1 \\ -1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  0 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\  1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\  1 \\ -1 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\ -1 \\  0 \end{bmatrix} \;
\begin{bmatrix}  1 \\ -1 \\ -1 \\  1 \end{bmatrix} \; \]


由于前面矩阵排列是按照最后一项 -1 0 1的顺序排列的，因此最后一列和为0

上下两个矩阵均为所求，二者对应的轻重情况反号。