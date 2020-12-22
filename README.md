# PointerNetwork

**Tested with Python 3.8 and Pytorch 1.7.0**  

Implementation of the paper [_Pointer Networks_](https://arxiv.org/abs/1506.03134) to solve TSP problem.  

Trained with 100000 cities with 5 to 10 cities, and tested with 10000 cities with 5 to 10 cities and 1000 cities with 10 to 15 cities.   
With 10,000 data of 5-10 cities, the accurate solution is about 40%, and the other solutions are all within 1.1 times of the length of best path.  
With 1000 data of 10-15 cities, basically will not get an accurate solution, but the solution is also controlled within 1.2 times of the best path.  



实现论文《Pointer Networks》，解决TSP问题  

训练数据集为100000个城市数为5-10的数据  
用10000个5-10城市数的数据测试，得到准确解的有40%左右，其余解长度都在最佳路径的1.1倍以内  
用1000个10-15城市数的数据测试，基本不会得到准确解，但是解也控制在最佳路径的1.2倍以内  


The network model refers to https://github.com/ast0414/pointer-networks-pytorch/blob/master/model.py  

The dataset generation refers to https://github.com/shirgur/PointerNet/blob/master/Data_Generator.py  
