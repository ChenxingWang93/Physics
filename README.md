# Physics

#### Some convention: 一些约定俗称

|Symbol 符号|Description 描述|
|----------|---------------|
|𝑎|unbolded, lowercase letter is a ***scalar*** 标量|
|𝐴|unbolded, uppercase letter is (still) a ***scalar*** 仍然是标量|
|𝐚|bolded, lowercase letter is a ***vector*** 向量|
|𝐀|bolded, uppercase letter is a ***matrix*** 矩阵|
|𝐚 ∊ ℛ^n|is an ***n***-dimensional vector n维向量|
|𝐀 ∊ ℛ^{m×n}|𝐀 is an ***m*** by ***n*** vector {m×n}矩阵|
|𝔸 ∊ ℛ^{m×n×o×...}|𝔸 is a higher-order(3rd and above)tensor 高维张量|

#### following operators and special matrices: 运算符和特殊矩阵

|Symbol 符号|Description 描述|
|----------|----------------|
|![图片](https://github.com/ChenxingWang93/Math/assets/31954987/240d2b17-9406-4509-980a-5f42b85b5be9)|2-norm (§C.1.1)|
|![图片](https://github.com/ChenxingWang93/Math/assets/31954987/ac29109d-1d31-40cb-bfc1-ec40e12d3ab3)|Frobenius norm 弗罗贝尼乌斯范数(§C.3)|
|𝐀∶𝐁|Double-contraction of matrices 矩阵双收缩 **𝐀** and **𝐁**|
|𝔸∶𝐁|Double-contraction of higher-order tensor 𝔸 and matrix 𝐁 双收缩高阶张量 𝔸 与双收缩矩阵 𝐁 §3.2,§.3)|
|𝐀⊗𝐁|A ***Kronecker product*** between two matrices 两矩阵的克罗内克积 (§C.5)|
|𝑡𝑟 𝐀|***trace*** of matrix ***𝐀***, i.e. the sum of its diagonal entries, 对角线条目的总和 (§C.2)|
|𝚍𝚎𝚝 𝐀|***determinant*** of matrix ***𝐀*** 矩阵行列式|
|𝚟𝚎𝚌 (⋅)|***flattening*** or ***vectorization*** of a matrix or tensor 矩阵和张量的扁平化和向量化(§3)|
|𝟶|The zero matrix, a.k.a. the null matrix. Nothing but zeros 零矩阵又称零矩阵，除了零什么都没有|
|𝚰|The identity matrix. A diagonal matrix of all ones 特征矩阵。全为对角矩阵|

These symbols are reserved for the following deformation-specific phenomena: 符号保留用于以下 特定-变形🫠 现象：
|Symbol|Description|
|------|-----------|
||rest vertex, before deformation 变形前的静止顶点|
||deformed vertex 变形定点|
|𝐅 = <img width="150" alt="image" src="https://github.com/ChenxingWang93/Math/assets/31954987/7797087e-c628-4dae-992b-7131f0f436fa">|deformation gradient, in 3D 3维变形梯度|
|𝐅 = <img width="85" alt="image" src="https://github.com/ChenxingWang93/Math/assets/31954987/5251ea3b-3aef-4589-8cb8-54b6a33dc626">|deformation gradient, in 2D 2维变形梯度|
|𝑪|right Cauchy-Green tensor, 右柯西格林张量 𝐂 = |
|𝑬|Green's strain, 格林应变|
|𝒕|translation 移动|
|𝒂|anisotropic fiber direction from 各向异性纤维方向|
|𝚥|𝚥 = 𝑑𝑒𝑡 𝐅, the current relative volume of 𝐅 𝐅当前的相对体积|
|𝑔_{1}|flattened gradient of 𝐼_{1} invariant from(§5.5) 𝐼_{1}的拍平梯度 不变 形式|
|𝑔_{2}|flattened gradient of 𝐼_{2} invariant from(§5.5) 𝐼_{2}的拍平梯度 不变 形式|
|𝑔_{𝚥} ≡ g_{3}|flattened gradient of 𝚥 ≡ 𝐼_{3} invariant from(§4.2.2.1)|
