$$H(D_2) = -\left(\frac{2}{4}\log_2 \frac{2}{4} + \frac{2}{4}\log_2 \frac{2}{4}\right) = 1$$
$$ S=\sum_{i=0}^n A_i  ,  P=\prod_{i=0}^n B_i $$


`矩阵-向量`乘法是指$y=A \times x$， 其中$A$是一个$d \times d$维的矩阵， $x$ 是一个$d$ 维向量，列向量 $y$ 可以按如下方式计算:
$$ y_i = \sum_{k=1}^d a_{i,j} x_k $$




## 行内与独行

行内公式	$xyz$

块公式

$$H(D_2) = -\left(\frac{2}{4}\log_2 \frac{2}{4} + \frac{2}{4}\log_2 \frac{2}{4}\right) = 1$$

## 上标、下标与组合

上标符号	$x^4$  
下标符号	$x_1$
组合符号	$ a^2_{xyz}$

## 汉字、字体与格式

汉字形式	$V_{\mbox{初始}}$

字体控制	$\displaystyle \frac{x+y}{y+z}$	

下划线符号	$\underline{x+y}$

标签	$\tag{11}$

上大括号	$\overbrace{a+b+c+d}^{2.0}$

下大括号	$a+\underbrace{b+c}_{1.0}+d$	

上位符号	\stacrel{上位符号}{基位符号}	

$\vec{x}\stackrel{\mathrm{def}}{=}{x_1,\dots,x_n}$	

## 占位符

空格		$x \quad y$	

两个空格		$x \qquad y$	

小空格		$x \, y$	

中空格		$x \; y$	

紧贴		$x \! y$

## 定界符与组合

括号	$()\big(\big) \Big(\Big) \bigg(\bigg) \Bigg(\Bigg)$

中括号	[]	$[x+y]$

大括号	{ }	${x+y}$

自适应括号	\left \right	$\left(x\right), \left(x{yz}\right)$	

组合公式	{上位公式 \choose 下位公式}	${n+1 \choose k}={n \choose k}+{n \choose k-1}$

组合公式	{上位公式 \atop 下位公式}	$\sum_{k_0,k_1,\ldots>0 \atop k_0+k_1+\cdots=n}A_{k_0}A_{k_1}\cdots$

## 四则运算

加法运算	+	$x+y=z$	

减法运算	-	$x-y=z$	

加减运算	\pm	$x \pm y=z$	

减加运算	\mp	$x \mp y=z$	

乘法运算	\times	$x \times y=z$	

点乘运算	\cdot	$x \cdot y=z$	

星乘运算	\ast	$x \ast y=z$	

除法运算	\div	$x \div y=z$	

斜法运算	/	$x/y=z$	

分式表示	\frac{分子}{分母}	$\frac{x+y}{y+z}$	

分式表示	{分子} \voer {分母}	${x+y} \over {y+z}$	

绝对值表示	||	$|x+y|$	

## 高级运算

名称	符号	示例语法	示例
平均数运算	\overline{算式}	$\overline{xyz}$	

开二次方运算	\sqrt	$\sqrt x$	

开方运算	\sqrt[开方数]{被开方数}	$\sqrt[3]{x+y}$	

对数运算	\log	$\log(x)$	

极限运算	\lim	$\lim^{x \to \infty}_{y \to 0} {\frac{x}{y}}$	

极限运算	\displaystyle \lim	$\displaystyle \lim^{x \to \infty}_{y \to 0}{\frac{x}{y}}$

求和运算	\sum	$\sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$	

求和运算	\displaystyle \sum	$\displaystyle \sum^{x \to \infty}_{y \to 0}{\frac{x}{y}}$	

积分运算	\int	$\int^{\infty}_{0}{xdx}$	

积分运算	\displaystyle \int	$\displaystyle \int^{\infty}_{0}{xdx}$	

微分运算	\partial	$\frac{\partial x}{\partial y}$	

## 逻辑运算
名称	符号	示例语法	示例
等于运算	=	$x+y=z$	

大于运算	>	$x+y>z$	

小于运算	<	$x+y<z$	

大于等于运算	\geq	$x+y \geq z$	

小于等于运算	\leq	$x+y \leq z$	

不等于运算	\neq	$x+y \neq z$	

不大于等于运算	\ngeq	$x+y \ngeq z$	

不大于等于运算	\not\geq	$x+y \not\geq z$	

不小于等于运算	\nleq	$x+y \nleq z$	

不小于等于运算	\not\leq	$x+y \not\leq z$	

约等于运算	\approx	$x+y \approx z$	

恒定等于运算	\equiv	$x+y \equiv z$	

## 集合运算
名称	符号	示例语法	示例
属于运算	\in	$x \in y$	
不属于运算	\notin	$x \notin y$	
不属于运算	\not\in	$x \not\in y$	
子集运算	\subset	$x \subset y$	
子集运算	\supset	$x \supset y$	
真子集运算	\subseteq	$x \subseteq y$	
非真子集运算	\subsetneq	$x \subsetneq y$	
真子集运算	\supseteq	$x \supseteq y$	
非真子集运算	\supsetneq	$x \supsetneq y$	
非子集运算	\not\subset	$x \not\subset y$	
非子集运算	\not\supset	$x \not\supset y$	
并集运算	\cup		$x \cup y$
交集运算	\cap		$x \cap y$
差集运算	\setminus	$x \setminus y$	
同或运算	\bigodot	$x \bigodot y$	
同与运算	\bigotimes	$x \bigotimes y$	
实数集合	\mathbb{R}	$\mathbb{R}$	
自然数集合	\mathbb{Z}	$\mathbb{Z}$	
空集	\emptyset	$\emptyset$	

## 数学符号

无穷	\infty	$\infty$	

虚数	\imath	$\imath$	

虚数	\jmath	$\jmath$	

数学符号	\hat{a}	$\hat{a}$	

数学符号	\check{a}	$\check{a}$	

数学符号	\breve{a}	$\breve{a}$	

数学符号	\tilde{a}	$\tilde{a}$	


数学符号	\bar{a}	$\bar{a}$	

矢量符号	\vec{a}	$\vec{a}$	

数学符号	\acute{a}	$\acute{a}$	

数学符号	\grave{a}	$\grave{a}$	

数学符号	\mathring{a}	$\mathring{a}$	

一阶导数符号	\dot{a}	$\dot{a}$	

二阶导数符号	\ddot{a}	$\ddot{a}$	

上箭头	\uparrow	$\uparrow$	

上箭头	\Uparrow	$\Uparrow$	

下箭头	\downarrow	$\downarrow$	

下箭头	\Downarrow	$\Downarrow$	

左箭头	\leftarrow	$\leftarrow$	

左箭头	\Leftarrow	$\Leftarrow$	

右箭头	\rightarrow	$\rightarrow$	

右箭头	\Rightarrow	$\Rightarrow$	

底端对齐的省略号	\ldots	$1,2,\ldots,n$	

中线对齐的省略号	\cdots	$x_1^2 + x_2^2 + \cdots + x_n^2$	

竖直对齐的省略号	\vdots	$\vdots$	

斜对齐的省略号	\ddots	$\ddots$


## 矩阵


$$ \begin{matrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{matrix}$$	

$$\left [ \begin{matrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{matrix} \right] $$

$$ \begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{bmatrix} 
$$	

$$ \begin{Bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{Bmatrix} $$

## 希腊字母 
$$
  A	\alpha   
  B		 \beta
  
	\Gamma		\gamma
	\Delta		\delta
	E		\epsilon
	Z		\zeta
	H		\eta
	\Theta		\theta
	I		\iota
	K		\kappa
	\Lambda		\lambda
	M		\mu
	N		\nu
	\Xi		\xi
	O		\omicron
	\Pi		\pi
	P		\rho
	\Sigma		\sigma
	T		\tau
	\Upsilon		\upsilon
	\Phi		\phi
	X		\chi
	\Psi		\psi
	v		\omega
  $$
  
## 特殊符号
$$
	\times		
  \pm
	\pm		
  \div
	\mid
$$			
 
$$
  \circ
	\ast		\bigotimes
	\bigoplus		\prod
	\coprod		\iint
	\int		\nabla
	\oint		\because
	\infty		\therefore
	\forall		\not\subset
	\exists		\emptyset
	\bigcup		\bigcap
	\bigvee		\bigwedge
	\check{y}		\breve{y}
	\uparrow		\downarrow
	\Uparrow		\downarrow
	\rightarrow		\varepsilon
	\leftarrow		\Rightarrow
	\eta		\Leftarrow
	\Longleftarrow		\longleftarrow
	\vartheta		\longrightarrow
	\pi		\tau
	\chi		\partial
  
  
	\lbrace \rbrace		\omicronο
	\overline{a}		\Leftrightarrow
	\angle		\rightleftharpoons
	\triangle		\nearrow
	\nwarrow		\searrow
	\swarrow		\diamondsuit
	\diamond		\heartsuit
	\parallel

