# 🧠 NN_Inference_Practice 神经网络推理实践 🤖 
深度学习推理框架用于对已训练完成的神经网络进行预测，也就是说，能够将深度训练框架例如`Pytorch`中定义的算法移植到中心侧和端侧，并高效执行  
与训练框架不同的是，深度学习推理框架没有梯度反向传播功能，因为算法模型文件中的权重系数已经被固化，推理框架只需要读取、加载并完成对新数据的预测即可

## 组织结构
✨- [01-环境配置](https://github.com/m0dulo/NN_Inference_Practice/tree/main/warmup_armadillo)  
✨- [02-张量 Tensor 类和输入数据的内存排布](https://github.com/m0dulo/NN_Inference_Practice/tree/main/tensor_impl_armadillo)  

## 致谢  
感谢深度学习推理框架 [KuiperInfer](https://github.com/zjhellofss/KuiperInfer) 作者 [傅莘莘](https://github.com/zjhellofss) 大佬的无私奉献和帮助