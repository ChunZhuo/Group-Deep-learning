# Group-Deep-learning
Equivariance, group theory for deep learning

**Group theory**

**Affine groups**
![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/0d462d47-0f3a-4f7b-968a-c6509c4673e3)


**A representation**
$\mathrm{\rho}: G \to GL(V) $ 

A representation GL(V) general linear group

$\mathrm{\rho}$ is a group homomorphism 

$\mathrm{\rho}(g)$ is a linear transformation that is parameterized by group elements $g\in G$

$$\mathrm{\rho}(g')\mathrm{\rho}(g)[v]= \mathrm{\rho}(g' \dot  g)[v]$$

**Left-regular representation**
$$\mathscr{L_{g}} [f] (x) = f(g^{-1}\dot x)$$
$$\lambda : h \to gh$$

for all $$h \in G$$
**Right-regular representation**
$$\rho : h \to hg^{-1}$$

**Group action**
$$\forall_{g,g' \in G, x \in X}: g \odot (g' \odot x) = (gg') \odot x$$
**Transitive action**
An action 
$\odot : G \times X \to X$
that $$\forall x_{0},x \in X, \exists {g} \in {G} : x = g \odot x_{0}$$

Homogeneous space: A space X on which G acts transitively

![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/836a6873-21c9-4d41-bf36-5fa9f2d60930)
![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/8d38feb2-d620-4930-a710-aeb69b32138e)
https://proceedings.neurips.cc/paper_files/paper/2019/file/45d6637b718d0f24a237069fe41b0db4-Paper.pdf
https://gabri95.github.io/Thesis/thesis.pdf


**Equivalence of group representations**
$\rho^{A}(g)$ and $\rho^{B}(g)$ are equivalent
if:
$\rho^{B}(g) = Q^{-1}\rho^{A}(g)Q$
**representation is called reducible if **

![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/fa7264c5-17ea-49cd-a856-2e836adc248b)


![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/ca463a45-d71c-44c4-b96e-1a6a87ba86a4)

____________________
Steerable basis (circular harmonics)

![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/69eabf1f-5850-489d-9e61-a764b890e687)

![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/3225454a-ec65-4d9d-a667-6b6b9788dbda)

![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/31e311f2-7004-4740-867d-28b308c743af)

![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/429727fd-b31c-4a15-907a-4b897bd1d66a)

![image](https://github.com/ChunZhuo/Group-Deep-learning/assets/118121876/94118139-2a91-4656-8860-26d921770d90)


