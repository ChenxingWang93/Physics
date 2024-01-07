### TOC
#### **2**.Deformation Fundamentals ***变形🫠的基础***
  - Do I Need to Read This Chapter? 
  - What Kind of Squashing Are We Talking About? ***我们在谈论什么样的 挤压***
  - How Squashed Am I? 
    - Measuring The Wrong Way ***以错误的方式 来衡量***
    - Removing the Translation(Easy) ***移除 移动Translation(Easy)***
    - Deformation Gradient: Really Important ***变形梯度：很重要***
    - Removing the Rotation(Not So Easy) ***移除 旋转Rotation(Not So Easy)***
  - Force Computation: How Much Should I Push Back? ***力的计算 要用多大的力才能推回***
    - Computing ***计算***
    - Don't Do It This Way ***不要这样做***
    - What Now? 
#### **3**.Computing Forces the Tensor Way ***以 张量形式 计算 力***
  - Thinking About 3rd-Order Tensors ***3阶 张量***
  - Multiplication With 3rd-Order Tensors ***3阶 张量***
  - Multiplication With Flattened Tensors ***展平 张量***
  - Computing Forces(Finally) ***计算 力***
    - Computing the Tensor ***计算 张量***
  - Dirichlet Forces: So Easy ***狄利克雷 力***
  - Other Forces: Still Pretty Easy ***其他力 Still Pretty Easy⭐⭐***
    - St. Venant Kirchhoff, Stretching Only ***圣 维南 基尔霍夫，仅拉伸***
    - The Complete St.Venan Kirchhoff ***完备的 圣 维南 基尔霍夫***
    - As-Rigid-As-Possible ***尽可能 严格的***
    - The Many Forms of Neo-Hookean ***新虎克 的多种形式***
#### **4**.Computing Forces Gradients the Tensor Way ***以 张量形式 计算 力梯度***
  - 4th-order Tensors ***4阶 张量***
  - Computing Force Gradients ***计算 力的 梯度***
    - Dirichlet Hessian: So Easy ***狄利克雷 黑森 So easy⭐***
    - Neo-Hookean: Not So Easy ***新虎克：Not So Easy⭐⭐⭐***
    - St. Venant-Kirchhoff: Things Get Worse ***圣 维南 基尔霍夫***
    - As-Rigid-As-Possible: Things Go Terribly Wrong ***尽可能 严格的***
#### **5**.A Better Way For Isotropic Solids ***各向同性 固体 的更优形式***
  - The Situation So Far
  - The Cauchy- Green Invariants(a.k.a The Wrong Way) ***柯西 - 格林不变量***
    - The Gradients & Hessians of the Invariants ***梯度 &不变量的 黑森***
    - Getting Any Hessian, the Cauchy-Green Way ***黑森，柯西格林 方法***
    - St.Venant Kirchhoff Stretching, the Cauchy-Green Way ***圣 维南 基尔霍夫拉伸，柯西-格林 方法***
    - Neo-Hookean, the Cauchy-Green Way ***新虎克，柯西-格林 方法***
    - As-Rigid-As-Possible: Things Go Terribly Wrong(Again) ***尽可能严格：事情变得很糟糕***
  - A Better Set of Invariants? ***不变量 集***
    - Invariants as Rotation Removers ***不变量作为 旋转移除***
    - Invariants as Geometric Measurements ***不变量作为 几何度量***
    - A New Set of Invariants ***不变量 集***
    - Does ARAP Work Now? ***尽可能 严格***
  - The Eigenmatrices of the Rotation Gradient ***旋转梯度 的特征矩阵***
    - What's an Eigenmatrix? ***什么是 特征矩阵***
    - Structures Lurk in the Decomposition of an Eigenmatrix ***潜伏结构 特征矩阵 的 分解***
    - What About the Eigenvalue? ***特征值***
    - Building the Rotation Gradient(Finally) ***建立旋转 梯度***
  - Building a Generic Hessian (Finally) ***建立 通用黑森***
      - Neo-Hookean, the Smith et al. (2019) Way ***新虎克 史密斯 et al***
      - ARAP, the Smith et al. (2019) Way ***尽可能 严格，史密斯 et al***
      - Symmetric Dirichlet, the Smith et al.(2019) Way ***对称 狄利克雷***

  
#### **6**.A Friendlier Neo-Hookean Energy ***一种更友好的 新虎克 能量***
  - Cauchy-Green vs. Smith et al.(2019) ***柯西-格林 vs 史密斯 et al***
    - Maybe Mooney Didn't Know About the Polar Decomposition ***穆尼 并不了解极坐标 分解***
    - Maybe Mooney Didn't Care About Inversion ***穆尼 并不在意 逆转***
  - ARAP (And Others) Don't Do Great ***不要完美***
    - A Brief Aside: The Lame Parameters ***旁白：蹩脚的参数***
    - St.Venant Kirchhoff Doesn't Do Better ***圣 维南 基尔霍夫***
    - Co- Rotational Doesn't Do Better ***同-旋转 没有更好***
    - Neo-Hookean Is Okey Unless It Burns The House Down ***新虎克 是ok的***
  - A Better Neo-Hookean Energy? ***一种 更好的 新 虎克 能量？***
    - So Many Neo-Hookeans ***太多的 新虎克定律***
    - Let's Mix-And-Match Our Own *** ***
    - A Stable Neo-Hookean Energy ***一种稳定的 新胡克定律***
  - A Bunch of Other Stable Energies ***一堆其他 稳定的能量***
    - Stable Mooney-Rivlin ***稳定的 Mooney-Rivlin***
    - Stable Arruda-Boyce ***稳定的 Arruda-Boyce***
    - Stable Fung Hardening ***稳定的 Fung Hardening***
   

#### **7**.The Analytic Eigensystems of Isotropic Energies ***各向同性 分析特征系统***
  - Keeping Everything Semi- Positive Definite ***半正定***
  - Can ARAP Go Indefinite ***ARAP能否 不定***
  - The Eigendecompositions of Arbitrary Energies ***任意能量的 特征值分解***
    - The General Eigensystem of ***通用 本征系统***
    - All Isotropic Energies Have the Exact Same Eigenvectors ***各向同性能量 的完全相同特征向量***
    - Cranking Out Analytic Eigenvalues ***发动 分析特征值***
    - If You‘re Lucky, Things Get Simpler ***如果你幸运，事情就会变得简单***
  - The Stable Neo-Hookean Eigensystem ***稳定的 新虎克特征系统***
    - When Does It Go Indefinite? ***什么时候是 不定的？***

#### **8**.A Better Way for Anisotropic Solids ***各向异性 固体 的更优形式***
  - What‘s Anisotropy？***什么是 各向异性***
  - The(Wrong) Cauchy-Green Invariants, Again ***（错误❌）柯西-格林 不变量***
    - The  and  Invariants ***不变量***
    - Gradients and Hessians, Again ***梯度 &hessians***
    - The Eigensystem of ***特征系统***
    - The Eigensystem of ***特征系统***
    - The Eigensystems of Arbitrary Energies ***随机能量的 特征系统***
    - Matlab/Octave Implementation ***matlab/octave 实施***
  - Better Invariants, Again 
    - An Inversion-Aware Invariant
    - The Gradient of
    - The Sign of
  - An Inversion-Aware Anisotropic Energy
    - Previous Models, and Their Issues
    - An Anisotropic ARAP Model
    - What Other Models Are Out There?

#### **9**.Tips for Computing &Debugging Force Derivatives ***计算 &调试 力的导数***
  - A Warning To Non-Cabal Members


#### **10**.Thin Shell Forces ***薄壳力***
  - Handy derivatives of a few vector operators ***一些 向量 操作符的 手动导数***
    - Jacobian of a unit vector ***单位向量 雅各比***
    - The derivative of the dot product of two vectors ***两向量 点积 导数***
    - Jacobian of the cross product of two vectors ***两向量 叉积 雅各比***
    - Energy Functions, Forces, and their Jacobians ***能量函数，力，&其雅各比***
  - Stretch ***拉***
    - Stretch Damping ***拉伸阻尼***
  - Shear ***剪***
    - Shear Damping ***剪切阻尼***
  - Dihedral Bend ***弯***
    - Derivatives of  and
    - Approximating the force Jacobian ***力 雅各比***
    - Bend Damping ***弯阻尼***
    - Implementation Details ***实施细节***


#### **11**.Implicit Integrati Methods ***隐式 积分 方法***
  - Backward Differentiation Methods in
  - Time Integration in HOBAK
    - Velocity- Based BDF-1 
    - Position- Based BDF-1
    - Newmark and Newton-Raphson 


#### **12**.Constrained Backward- Euler ***带约束的 向后 🔄欧拉***
  - Constraint- Filtering in Baraff-Witkin Cloth
    - Pre-Filtered Preconditioned Conjugate Gradient (PPCG)
  - Performance Improvement Techniques
  - Reverse Cuthill-Mckee
  - System Assembly
  - System Reduction and Boundary Conditions
  - PPCG Solver Details
  - Preconditioning
  - A World on Determinism
  - Writing Efficient OpenMP Code


#### **13**.Collision Processing ***碰撞💥处理***
  - Proximity Queries
  - Filtered Constraints for One-Way Response
  - Proximity Between Dynamic Meshes
  - Penalty Forces for Two-Way Response
  - Faux Friction Effects 
  - Debugging Proximity Contact Detection
  - Continuous Collision Detection
  - CCD Response of a Single Collision
  - Resolving CCD Collisions in Chronological Order
  - Global Intersection Analysis
  - Using GIA with Proximity and CCD
  - Things Not Covered


#### **14**.Collision energies ***碰撞💥能量***
  - What Energies? ***什么能量？***
  - A Vertex-Face Energy ***一个 顶点面 能量***
    - A Position-Based Energy ***一个位置为基础 能量***
    - What's Position-Based Energy ***什么是位置为基础 能量***
    - What's the Energy Doing? ***能量都在做什么呢？***
    - The Collision Force ***碰撞💥 力***
    - The Collision Hessian ***碰撞💥 hessian***
  - Another(Better?Identical?)Vertex-Face Energy ***（更优？）顶点-面 能量***
    - Another Position-Based Energy ***位置为基础的能量***
    - The Collision Force ***碰撞💥力***
    - The Collision Hessian ***碰撞💥 hessian***
  - Non-Zero Rest-Length Vertex Energies ***非0⃣️静止长度 顶点能量***
  - The Actual Vertex-Face Energy Used ***实际 顶点-面 能量***
    - Just to Drive You Crazy
    - There's A Reversal Problem ***逆向🔄 问题***
  - An Edge- Edge Energy ***边-边 能量***
   - The Collision Energy ***碰撞💥 能量***
   - The Collision Gradient ***碰撞💥 梯度***
   - The Collision Hessian ***碰撞💥 黑森***
   - You Have to Reverse It Sometimes ***撤销↩️***
  - The Actual Edge- Edge Energy Used in Fizt ***实际 边-边能量***
    - A Fly in the Ointment ***软膏上的一只苍蝇🪰***
    - The Fizt Energy ******
    - The Negated Version ***否定版本***
    - This Part Isn't in Fizt ******
  - What About Eigenvalue Clamping? ***特征值 阻尼***


#### A
#### B
#### C
#### D
#### E
#### F
#### G
#### H 
#### I
#### J
