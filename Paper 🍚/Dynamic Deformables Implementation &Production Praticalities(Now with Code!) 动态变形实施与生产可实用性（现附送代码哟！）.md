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
      - Symmetric Dirichlet, the Smith et al.(2019) Way

  
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
    - A Stable Neo-Hookean Energy 
  - A Bunch of Other Stable Energies
    - Stable Mooney-Rivlin
    - Stable Arruda-Boyce
    - Stable Fung Hardening
#### **7**.The Analytic Eigensystems of Isotropic Energies ***各向同性 分析特征系统***
  - Keeping Everything Semi- Positive Definite
  - Can ARAP Go Indefinite
  - The Eigendecompositions of Arbitrary Energies
    - The General Eigensystem of
    - All Isotropic Energies Have the Exact Same Eigenvectors
    - Cranking Out Analytic Eigenvalues
    - If You‘re Lucky, Things Get Simpler 
  - The Stable Neo-Hookean Eigensystem
    - When Does It Go Indefinite?

#### **8**.A Better Way for Anisotropic Solids ***各向异性 固体 的更优形式***
  - what‘s anisotropy？
  - the (wrong) Cauchy-green invariants, again
    - the  and  invariants
    - gradients and hessians, again
    - the eigensystem of
    - the eigensystem of
    - the eigensystems of arbitrary energies
    - matlab/octave implementation
  - better invariants, again
    - an inversion-aware invariant
    - the gradient of
    - the sign of
  - an inversion-aware anisotropic energy
    - previous models, and their issues
    - an anisotropic arap model
    - what other models are out there?

#### **9**.Tips for Computing &Debugging Force Derivatives ***计算 &调试 力的导数***
  - a warning to non-cabal members


#### **10**.Thin Shell Forces ***薄壳力***
  - handy derivatives of a few vector operators
    - jacobian of a unit vector
    - the derivative of the dot product of two vectors
    - jacobian of the cross product of two vectors
    - energy functions, forces and their jacobians  
  - stretch 拉
    - stretch damping
  - shear 剪
    - shear damping
  - dihedral bend 弯
    - derivatives of  and
    - approximating the force jacobian
    - bend damping
    - implementation details 


#### **11**.Implicit Integrati Methods ***隐式 积分 方法***
  - 


#### **12**.Constrained Backward- Euler ***带约束的 向后 🔄欧拉***
  -


#### **13**.Collision Processing ***碰撞💥处理***
  -


#### **14**.Collision energies ***碰撞💥能量***
  -


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
