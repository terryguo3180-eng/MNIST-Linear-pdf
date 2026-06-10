# MNIST-Linear
A giant formula that implements a simple forward pass with only one linear layer and integer arithmetic. Its accuracy on MNIST test set is around 92%, which is basically the limit for tiny linear networks like this. The computation is simple enough that you can even work out by hand, if you have enough patience :D

I doubt if anyone's gonna do this but $a_{i,j}$ stands for the brightness of the pixel at column $i$ and row $j$ (indices starts from 0), which is an integer between 0 to 255. As an example, 6 can be expressed as something like this:
<img width="1926" height="933" alt="image" src="https://github.com/user-attachments/assets/cdec7627-7ac3-4b0b-847b-fba52b3c6f6b" />
You can plug in these values into the formula inside `p6.md`, most of the terms are just zero so they cancel out, and the rest of them is really not much. If you get all the calculations right, you might end up with a pretty high value on $p_{6}$. Even better, you can do this on all the other formulas in this repo, and you'll find that their values are all below $p_{6}$. Pretty fun math excercise.
