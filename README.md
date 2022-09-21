# 草稿
为什么这个就可以!

$$
\hat{\bf t}^i={\mathrm{ChannelAttn}}({\bf t}^i)\\
\hat{\bf g}^i={\mathrm{SpatialAttn}}({\bf g}^i)\\
\hat{\bf b}^i={\mathrm{Conv}}({\bf t}^i{\bf W}^i_1\odot {\bf g}^i{\bf W}^i_2)\\
{\bf f}^i={\mathrm{Residual}}([\hat{\bf b}^i,\hat{\bf t}^i,\hat{\bf g}^i])
$$
+ 白醋暗示v
  + 哦护士背诵
    + bcibvb 胡高回报闺女aryaegr
    $$
    \hat{\bf v}^l={\rm SA}({\bf v})\\
     \hat{\bf q}^l={\rm SA}({\bf q})\\
      \hat{\bf b}^l={\rm FC}({\bf v}^l{\bf W}_1\odot {\bf q}^l{\bf W}_2)\\
      {\bf f}^l={\rm Residual}([\hat{\bf b}^l,\hat{\bf q}^l,\hat{\bf v}^l])\\
      {\bf f}={\rm Fusion}({\bf f}^1,{\bf f}^2,\cdots,{\bf f}^L)
      $$
