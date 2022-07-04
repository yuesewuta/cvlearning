## 贝叶斯估计
为了解决
P_\lambda (X ^ j =a_{jl}| Y =c_k)=\frac{\sum_{i=1}^{N}{I(x_i ^{(j)}=a_{jl},y_i=c_k )+\lambda } }{\sum_{i=1}^{N}{I()y_i=c_k} +S_j \lambda } 


其中\lambda ≥ 0 ,那么显然当\ lambda ＞0 时候,P不为零,一般去 \ lambda  =1 此时称为拉普拉斯平滑，如果取0  那么就是极大似然估计.

并且
