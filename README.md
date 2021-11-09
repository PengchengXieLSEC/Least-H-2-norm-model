# Least-H-2-norm-model

1.	主函数
主函数为dataProcess.py。
2.	每个文件夹作用
1)	文件夹alg1、alg2、alg3、alg4、alg5分别是关于算法DFO1、DFO2、Powell、Nelder-Mead、BFGS的文件，各个子文件的run_test_fun1、run_test_fun2、run_test_fun3、run_test_fun4、run_test_fun5分别为算法DFO1、DFO2、Powell、Nelder-Mead、BFGS的主训练函数；
2)	文件夹results保存重要参数的计算结果；
3)	文件夹resultspic保存实验结果图。
3.	主要文件作用
1)	文件dataProcess.py为主函数，包含各个算法的主要参数设置、分析训练结果、保存训练结果；
2)	文件fujian.py包含了各个算法训练数据的预处理函数，以及计算中间参数的函数；
3)	文件myPic.m展示Performance Profile，Accuracy Profile，Data Profile实验结果；
4)	文件func_acc_itr.m展示各个算法训练函数’eg3’ 的收敛曲线图。

