# 适用于温州大学的Latex模板

## 简介

本Latex模板为温州大学的同学们提供一份Latex编纂的报告模板，分为**Easy_version**（简易版）和**Professional_version**（详细版）。本模板仅适配至`texlive 2023`环境

**环境：texlive 2023**

## 常用语法示例

制表
``` Latex
\begin{table}[H]
    \centering
    \caption{表名}
    \begin{tabularx}{0.8\textwidth}{|X|X|X|X|}
    \hline
    A & B & C & D\\
    \hline
    1 & 2 & 3 & 4 \\
    \hline
    \end{tabularx}
\end{table}
```

插入图片
``` Latex
\begin{figure}[H]
    \centering
    \includegraphics[scale=0.8]{}
    \caption{图名}
\end{figure}
```

加粗
``` Latex
\textbf{加粗字体}
```

列项
``` Latex
\begin{itemize}
    \item[·] a
    \item[·] b
\end{itemize}
```

两端对齐
``` Latex
\begin{sloppypar}
针对特定区域设置自动换行，两端对齐
\end{sloppypar}
```

引用文献项，索引为`\bibitem{}`括号内的文字
``` Latex
\cite{索引}
```

行内数学公式 {𝐸1, 𝐸2, 𝐸3, ⋯ , 𝐸𝑛}
``` Latex
$\{ E_1, E_2, E_3, \dots , E_n , E_{n+1}\}$
```

居中数学公式 {𝐸1, 𝐸2, 𝐸3, ⋯ , 𝐸𝑛}
``` Latex
$$ \{ E_1, E_2, E_3, \dots , E_n , E_{n+1}\} $$
```