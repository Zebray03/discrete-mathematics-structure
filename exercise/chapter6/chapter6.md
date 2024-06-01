6.1 Exercises

10.

![](.\media\chapter6-1-10.drawio.svg)



13.

![](.\media\chapter6-1-13.drawio.svg)



14.

![](.\media\chapter6-1-14.drawio.svg)



16.

![](.\media\chapter6-1-16.drawio.svg)



18.

$\begin{bmatrix}
	1 & 1 & 1 & 1 & 1 \\
	0 & 1 & 0 & 1 & 0 \\
	0 & 0 & 1 & 0 & 1 \\
	0 & 0 & 0 & 1 & 0 \\
	0 & 0 & 0 & 0 & 1 \\
\end{bmatrix}$



26.

(a) $\{\{1,2,4,12\},\{3\}\}$

(b) $\{\{a,d,f\},\{b,e\},\{c\}\}$

(c) $\{\{1,2,3,4\}\}$

(d) $\{\{1,2,4,6,7,8\},\{3,5\}\}$

(e) $\{\{1,2\},\{3\},\{4,5,6,7,9\},\{8\}\}$



27.

(a) $2,3$

(b) $a,b,c$

(c) $1$

(d) $2,3$

(e) $2,3,7,8$



28.二者相等。

设偏序集$A$中不可比较元素全体为$U$，其最小划分线性顺序集为$\mathcal{L}=\{L_\alpha\}$，定义映射$f:U \rightarrow \mathcal{L},u \mapsto L_\alpha$，其中$u \in L_\alpha$，因$\{L_\alpha\}$两两无交，$f$良定义，进而为满射。因每个$L_\alpha$中不存在不可比较的元素，$f$为单射，从而$f$为双射，故$U$和$\mathcal{L}$具有相同的基数。$\textbf{Q.E.D.}$



29.

![](.\media\chapter6-1-29.drawio.svg)



30.

![](.\media\chapter6-1-30.drawio.svg)



34.

因$A \sube \mathbb{R}$，而<在$\mathbb{R}$上具有有传递性和反自反性，故<在$A$上是一个拟序。$\textbf{Q.E.D.}$



35.

传递性：对于$a,b,c \in A$满足$b\ R^{-1}\ a$且$c\ R^{-1}\ b$，那么有$a\ R\ b$且$b\ R\ c$。据$R$之传递性，$a\ R\ c$，那么$c\ R^{-1}\ a$。

反自反性：据$R$的反自反性，不存在$a \in A$有$a\ R\ a$，所以不存在$a \in A$有$a\ R^{-1}\ a$。

$\textbf{Q.E.D.}$



36.

对于$a,b\in\mathbb{Z}^+$，$a\ R\ b \iff a\ |\ b$且$a \neq b$



38.

验证$R$满足偏序的三条性质。

自反性：$m_{ij} \le m_{ij}, \forall i,j$，故$\textbf{M}\ R\ \textbf{M},\forall \textbf{M} \in A$。

反对称性：对于$\textbf{M},\textbf{N} \in A$满足$\textbf{M}\ R\ \textbf{N}$且$\textbf{N}\ R\ \textbf{M}$，$m_{ij} \le n_{ij}$且$n_{ij} \le m_{ij}, \forall i,j$，故$m_{ij} = n_{ij}, 1 \le i \le 2,\forall i,j$，即$\textbf{M} = \textbf{N}$。

传递性：对于$\textbf{M}_1,\textbf{M}_2,\textbf{M}_3 \in A$满足$\textbf{M}_1\ R\ \textbf{M}_2$且$\textbf{M}_2\ R\ \textbf{M}_3$，$m_{1ij} \le m_{2ij}$且$m_{2ij} \le m_{3ij},\forall i,j$，故$m_{1ij} \le m_{3ij},\forall i,j$，从而$\textbf{M}_1\ R\ \textbf{M}_3$。

$\textbf{Q.E.D.}$



40.

定义映射$f:A \rightarrow A',a \mapsto \log_2a$。直接验证，因为$A'$的选取，$a\ |\ b \iff f(a) \le f(b) \iff f(a) \le' f(b)$，故$a \le b \iff f(a) \le' f(b), \forall a,b\in A$，从而$f$是同构，进而$(A,\le)$与$(A',\le’)$同构。$\textbf{Q.E.D.}$



6.2 Exercises

6.

无极大元，有极小元0。



8.

有极大元48，有极小元2和3。



12.

有最大元5，无最小元。



14.

有最大元1，有最小元0。



17.

不等价，$A$中可能存在与$a$不可比较的元素，其仍满足(a)，但不满足(b)。



18.

不等价，$A$中可能存在与$a$​不可比较的元素，其仍满足(a)，但不满足(b)。



19.

(a)真，因$A$有限，上升链$a_1<a_2<\cdots$必有限长。

(b)假，练习6给出反例。

(c)真，因$A$有限，下降链$a_1>a_2>\cdots$必有限长。

(d)假，练习7给出反例。



20.

据定理2立刻得证。$\textbf{Q.E.D.}$



22.

设$a,b\in A$皆为$B$的最小上界，据定义，$a \le b$且$b \le a$，据反对称性得$a=b$。最大下界唯一性同理可证。$\textbf{Q.E.D.}$



23.

(a) $f,g,h$

(b) $a,b,c$

(c) $f$

(d) $c$



26.

(a) 5,8

(b) 1,2,3

(c) 不存在

(d) 3



32.

(a) $\begin{bmatrix}
	1 & 1 \\
	0 & 1 \\
\end{bmatrix},
\begin{bmatrix}
	1 & 1 \\
	1 & 1 \\
\end{bmatrix}$

(b) $\begin{bmatrix}
	0 & 0 \\
	0 & 1 \\
\end{bmatrix},
\begin{bmatrix}
	0 & 0 \\
	0 & 0 \\
\end{bmatrix}$

(c) $\begin{bmatrix}
	1 & 1 \\
	0 & 1 \\
\end{bmatrix}$

(d) $\begin{bmatrix}
	0 & 0 \\
	0 & 1 \\
\end{bmatrix}$



33.

![](.\media\chapter6-2-33.drawio.svg)



35.

最小元对应行全为1，最大元对应列全为1。



36.

![](C:\Users\20926\Desktop\discrete mathematics structure\exercise\chapter6\media\chapter6-2-36.drawio.svg)



37.

(a) $\{100,99,\cdots,51\}$，共50个。

(b) $\{2,4,8,16,32,64\}$



38.

即小于100的所有素数：$\{2,3,5,7,11,13,17,19,23,29,31,37,41,43,47,57,59,61,67,71,73,79,83,87,89,91,97\}$，共27个。



6.3 Exercises

1.是



2.否，$a \wedge b$不存在



3.否，$a \wedge b$不存在



4.是



5.是



6.是



13.

$\forall T_1,T_2 \sube T,T_1 \cap T_2,T_1 \cup T_2 \sube T$，故$P(T)$是$P(S)$的一个子格。$\textbf{Q.E.D.}$



14.

$\forall x,y \in [a,b]$，因$L$是格，$x \wedge y,x \vee y$良定义，从而$a \le x \wedge y \le x \le x \vee y \le b$，故$[a,b]$是一个子格。$\textbf{Q.E.D.}$​



15.

对于任意的线性偏序集$A$，$\forall x,y \in A$，不妨设$x \le y$，那么$x \wedge y = x,x \vee y = y$，故线性偏序集的任意子集均为子格。$\textbf{Q.E.D.}$



18.

对于有至少两个元素的有界格$L$，若不然，$\forall a,b\in L$，有$0 \le a \le I,0 \le b \le I$，$0=I$表明$a=b$，矛盾。$\textbf{Q.E.D.}$



19.

必要性：$a=a \wedge b \le b$。

充分性：据$a \le b$，$a$是$\{a,b\}$的一个下界，从而$a \le a\wedge b$，而又$a \wedge b\le a$，这表明$a \wedge b = a$。$\textbf{Q.E.D.}$



20.

$\forall a,b,c \in D_n,$$a \wedge (b \vee c) = a \wedge \mathrm{LCM}(b,c) = \mathrm{GCD}(a,\mathrm{LCM}(b,c))=\mathrm{LCM}(\mathrm{GCD}(a,b),\mathrm{GCD}(a,c))=(a \vee b) \wedge (a \vee c)$

$a \wedge (b \vee c) = a \wedge \mathrm{LCM}(b,c) = \mathrm{GCD}(a,\mathrm{LCM}(b,c))=\mathrm{LCM}(\mathrm{GCD}(a,b),\mathrm{GCD}(a,c))=(a \wedge b) \vee (a \wedge c)$

$a \vee (b \wedge c) = a \vee \mathrm{GCD}(b,c) = \mathrm{LCM}(a,\mathrm{GCD}(b,c))=\mathrm{GCD}(\mathrm{LCM}(a,b),\mathrm{LCM}(a,c))=(a \vee b) \wedge (a \vee c)$

故$D_n$是分配格。$\textbf{Q.E.D.}$



22.

对于分配格$L$及其子格$L_1$，$\forall a,b,c \in L,a \wedge (b \vee c) = (a \wedge b) \vee (a \wedge c),a \vee (b \wedge c) = (a \vee b) \wedge (a \vee c)$，故$\forall a,b,c \in L_1,a \wedge (b \vee c) = (a \wedge b) \vee (a \wedge c),a \vee (b \wedge c) = (a \vee b) \wedge (a \vee c)$，从而$L_1$也是分配格。$\textbf{Q.E.D.}$



24.

$a \vee (a' \wedge b) = (a \vee a') \wedge (a \vee b) = 0 \wedge (a \vee b) = a \vee b$

$a \wedge (a' \vee b) = (a \wedge a') \vee (a \wedge b) = I \vee (a \wedge b) = a \wedge b$​

$\textbf{Q.E.D.}$​



26.

(a) 对于分配格$L$，$a,b,c\in L,a \le c,a \vee (b \wedge c) = (a \vee b) \wedge (a \vee c) = (a \vee b) \wedge c$。$\textbf{Q.E.D.}$

(b) $a \wedge (b \vee c)=a \wedge I=a$但$(a \wedge b) \vee (a \wedge c) = 0 \vee 0 = 0$，从而不是分配格。

$a \vee (b \wedge I)=a \vee b = (a \vee b) \wedge I,0 \vee (b \wedge c)=b \wedge c = (0 \vee b) \wedge c$，从而是模格。$\textbf{Q.E.D.}$



27.

$D_{42}=\{1,2,3,6,7,14,21,42\}$

$1'=42,2'=21,3'=14,6'=7,7'=6,14'=3,21'=2,42'=1$



29.

不是分配格，不是有补格



34.

$a'=e,b'=c,c'=d,d'=c,e'=a$



37.

图6.57中子格$\{a,b,d\}$不是有补格。$\textbf{Q.E.D.}$



38.

对于有界格$(L,\vee,\wedge,0,I)$及其子格$(L_1,\vee,\wedge)$，据Zorn引理，取$L_1$的一个极大元$a^*$，任取$L_1$的极大元$a$，因$L_1$是格，$a \vee a^* \in L_1$，而$a^* \le a \vee a^*$且$a^*$极大，这表明$a^* = a \vee a^*$，从而$a=a^*$，故$a^*$是$L_1$的最大元。同理可证$L_1$中存在最小元，故$L_1$为有界格。$\textbf{Q.E.D.}$



39.

对于模格$L$及其子格$L_1$，$\forall a,b,c \in L_1,a \le c$，因$a,b,c \in L$，$a \vee (b \wedge c) = (a \vee b) \wedge c$，故$L_1$也是模格。$\textbf{Q.E.D.}$



40.

对于线性有序集$L$，$\forall a,b,c \in L$，不妨设$a \le b \le c$，那么

$a \wedge (b \vee c) = a\wedge c = a = a \vee a = (a \wedge b) \vee (a \wedge c)$

$a \vee (b \wedge c) = a \vee b = b = b\wedge c = (a \vee b) \wedge (a \vee c)$​

故$L$是分配格。$\textbf{Q.E.D.}$
