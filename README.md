# ML-DecisionTrees

### 1 Measure of Impurity

#### 1.1 Classification

#### Entropy

$$ Entropy(S) =  \sum_{i=1}^{c} -p_i * \log(p_i) $$

$$c: the num of class$$

$$ Entropy(S_2) =  \sum_{i=1}^{n} w_i * Entropy(P_i) $$

$$w_i: percentage of the ith partition $$

##### Info Gain

$$ InfoGain(F) = Entropy(S_1) - Entropy(S_2) $$

#### Gini

$$ Gini(S) = 1 - \sum_{i=1}^{c} p_i^2 $$

#### 1.2 Regression

#### SSR

$$ SSR = \sum_{i=1}^{n} (y_i - \hat{y})  $$

#### Tree Score

$$  TreeScore(T)=SSR + \alpha|\tilde{T}| $$