代码已开源，仅供交流学习使用，请勿商用。不适合上主链操作。
上主链使用后如产生安全问题概不负责。
思路交流请联系：https://s.denglianqiu.cn/smartContractComunication

使用方式，配制好基础的pycharm环境，安装对应的moldue，直接运行即可。
代码思路很简单，使用web3.py模块与链上的dogeswapRouter合约进行简单买入卖出交互
调用的合约方法是swapExactTokensForWDOGE，swapExactWDOGEForTokens，这两个方法
具体参见uni的交互说明，作用是最大程度的获取交换数量。由于本人学艺不精，没找到怎么获得流动池的方法，
所以手动设置，至少获得数量，设置为0，即默认以方法获得的数量为基础。相比较在dogeswap.org的交互来讲，或许操作稍微复杂点。
但是胜在可以很方便的对不同的币进行买卖。并且由于相对于网站少了滑点检测数据通信这一项，速度要快上不少，很少会出现卡链的情况。
dogeSwap压缩包为生成的可执行文件，使用方式：将dogeswap.zip解压缩，运行dist目录下的exe可执行文件。
