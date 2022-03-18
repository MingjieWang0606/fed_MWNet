# fed_MWNet

### 3.16  
在moon代码上，已经添加meta部分。正在运行测试中  
使用默认参数  

fed_avg :0.6592  
moon:0.66  
ourmodel:0.681400  


### 3.18   

| model      | dataset  | alg    | test acc |
|------------|----------|--------|----------|
| simple-cnn | cifar10  | fedavg | 66.32    |
| simple-cnn | cifar10  | fedavg | 65.92    |
| simple-cnn | cifar10  | moon   | 67.24    |
| simple-cnn | cifar10  | moon   | 68.03    |
| simple-cnn | cifar10  | meta   | 68.14    |
|     \      |     \    |   \    |     \    |
| simple-cnn | cifar100 | moon   | 31.18    |
| simple-cnn | cifar100 | moon   | 31.25    |
| simple-cnn | cifar100 | fedavg | 31.19    |
|     \      |     \    |   \    |     \    |
| resnet50   | cifar100 | moon   | 69.65    |
| resnet50   | cifar100 | fedavg | 68.86    |
| resnet50   | cifar100 | meta   | 68.86    |
|     \      |     \    |   \    |     \    |
| resnet50   | tinyimagenet | meta   | 22.00    |
| resnet50   | tinyimagenet | fedavg   | 21.56    |
| resnet50   | tinyimagenet | moon   | running    |

