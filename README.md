# MNIST-Linear
A giant formula that implements a simple forward pass with only one linear layer and integer arithmetic. The accuracy on MNIST test set is around 92%, which is basically the limit for networks of this scale. The computation is simple enough that you can even work out by hand, if you have enough patience :D

$$
p_0 = 20a_{0,0}-3a_{0,1}-7a_{0,2}-2a_{0,3}-15a_{0,4}+a_{0,5}-10a_{0,7}+a_{0,8}-10a_{0,9}+7a_{0,10}+a_{0,11}+a_{0,12}-14a_{0,13}-3a_{0,14}
$$
$$
-7a_{0,15}-18a_{0,16}+14a_{0,17}-9a_{0,18}+8a_{0,19}+6a_{0,20}-4a_{0,21}+4a_{0,22}+5a_{0,23}-9a_{0,24}+9a_{0,25}-14a_{0,26}\\
$$
