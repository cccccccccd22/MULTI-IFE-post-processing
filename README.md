# MULTI-IFE-post-processing

data for computing turning point
***
we use $nr=p$ to compute turning point, in data.h5 we have:

dene1，electron number density($cm^{-3}$), $n^e$, $120 \times 130$ matrix

x1，interface position(cm), r, $120 \times 130$ matrix

time1, simulation time(s), $1 \times 130$ matrix

timeMatrix1 =  repmat(time1, size(x1, 1), 1), $120 \times 130$ matrix

Additionally, $N_c = \frac{\pi m_e c^2}{e^2 \lambda _L^2}$, $\lambda _L = 0.25 \mu m$, $1 - n^2 = s = \frac{n^e}{N_c}$


