$$
\begin{align}  		
    \min  \quad  
    &\sum \limits _{t=1} ^{T} \sum \limits _{i=1}^{N} (E^{blnc}_{it} )^ 2      \\
    \text{s. t. }   \quad   
    & 	    	E^{blnc} _{it}=
    \sum \limits_{j=1,  j \ne i}^{N} x _{ij}^{t} \cdot P_0 \cdot \frac{d_{jt}}{W\log (1 + \text{SNR})}  
    +\sum_{j=1 ,j \ne i }^{N} x _{ji}^{t} \cdot P_0 \cdot \frac{d_{it}}{W\log (1 + \text{SNR})}  \\
    &\quad  \quad + \lambda_{i} \cdot f_{it}^{3} \cdot \Delta T
    ,\quad i = 1, \dots ,N      \\
    & \sum    _{ j= 1} ^{N}
    { x_{ij}^{t} \cdot  r'_{jt}} \le C_{it}       \label{cons1}   \\
    & \sum  _{ i= 1} ^N x_{ij}^{t} 	\ge 1  \label{cons2} \\
    &     	f_{it} \ge 0         \label{cons3}\\
    &      x_{it}^{t} \in \{0,1\}	  \label{cons4}
\end{align} 
$$

