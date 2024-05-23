# MULTI-IFE-post-processing
data for computing turning point
转折点定义为$nr=p$
数据集中包含
dene1，electron number density(cm^-3), 即$n^e$，120*130矩阵
x1，interface position(cm)；120*130矩阵
time1, simulation time(s)；1*130矩阵
timeMatrix1 =  repmat(time1, size(x1, 1), 1)；120*130矩阵

$N_c = \frac{\pi m_e c^2}{e^2 \lambda _L^2}$
其中$\lambda _L^2$为0.25微米
已知$1 - n^2 = s = \frac{n^e}{N_c}$
由dene1先推出折射率n的分布n(r)，接着通过求解n(r) r = p解出$r_t$
