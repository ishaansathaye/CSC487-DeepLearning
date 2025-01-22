# Gradient Descent

Loss function:
$l = -(z^{(i)}y^{(i)})$
Compute the gradient of the loss function with respect to the weights:
$\frac{\partial l}{\partial w_j} = -y^{(i)}x_j^{(i)}$
- Steps:
    - $z^{(i)} = w^Tx^{(i)}$
    - $w_j = w_j - \alpha \frac{\partial l}{\partial w_j}$
    - $w_j = w_j + \alpha y^{(i)}x_j^{(i)}$

