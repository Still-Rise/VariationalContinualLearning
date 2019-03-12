# Variational Continual Learning (VCL)
An implementation of the Variational Continual Learning (VCL) algorithms proposed by Nguyen, Li, Bui, and Turner (ICLR 2018).

```
@inproceedings{nguyen2018variational,
  title = {Variational Continual Learning},
  author = {Nguyen, Cuong V. and Li, Yingzhen and Bui, Thang D. and Turner, Richard E.},
  booktitle = {International Conference on Learning Representations},
  year = {2018}
}
```
**To run the Permuted MNIST experiment:**

	python run_permuted.py

**To run the Split MNIST experiment:**

	python run_split.py
	
**Requirements:**
<ul> 
	<li> Torch 1.0 </li>
	<li> Python 3.6 </li>
</ul>

## Results
### VCL in Deep discriminative models


Permuted MNIST
![](/misc/permuted_mnist_main.png)
![](/misc/permuted_mnist_coreset_sizes.png)


Split MNIST
![](/misc/split_mnist_main_part1.png)
![](/misc/split_mnist_main_part2.png)
... with Variational Generative Replay (VGR):<br/>
![](/misc/VGR.png)
