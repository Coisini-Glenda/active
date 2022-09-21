# 草稿
为什么这个就可以!

$$
\hat{\bf t}^i={\mathrm{ChannelAttn}}({\bf t}^i)\\
\hat{\bf g}^i={\mathrm{SpatialAttn}}({\bf g}^i)\\
\hat{\bf b}^i={\mathrm{Conv}}({\bf t}^i{\bf W}^i_1\odot {\bf g}^i{\bf W}^i_2)\\
{\bf f}^i={\mathrm{Residual}}([\hat{\bf b}^i,\hat{\bf t}^i,\hat{\bf g}^i])
$$
