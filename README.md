# ECE 285 Style Transfer
Description
===========

This is Project B: Style Transfer developed by Team Deep Learning Hackers with members Sanjeev Sinha, Yue Yang, Jeffrey Alido, and James Salem. We implemented two methods of style transfer, one from Leon Gatys and the other from Justin Johnson. In this repository, we have working demos of both style transfer methods, as well as all the trained models we used for the image transformation network used in the real-time (Johnson) method. When we had both methods behaving as expected, we experimented with different parameters (optimizers, style weights, networks for image transformations). We worked with different types of CNNs and observed whether the style transfer was better or worse than using Johnson's original network. When experimenting with Gaty's style transfer, we looked at using a different optimizer as well. We also experimented with the style weights along with these different variables. 

Requirements
============

Our implementation and experiments use the following packages:
os   
numpy  
torch, nn (from torch), functional (from torch.nn), torch.utils.data   
torchvision  
pandas Image (from PIL)  
pyplot (from matplotlib)  
nntools (given from ECE 285 @ UCSD)  

Code
====

official_gatys.ipynb - runs the Gatys implementation (explained in Section 3.1) as well as the experiments (shown in Figure 3)  
Johnson_Implementation.ipynb - runs the Johnson implementation (explained in Section 3.2, shown in Figure 5)   
Johnson Demo.ipynb - runs experiments of Johnson implementation with different architectures (explained in Section 3.2, shown in Figure 6)  

