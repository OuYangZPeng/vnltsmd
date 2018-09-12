# vnltsmd
How to Use boost export c++ for python

打开vnltsmd工程，并且把ltsapi中的库文件和dll文件都包含进去，点击项目-> 属性 -> vc++目录 中配置好Anaconda的include目录， boost的根目录和Python目录。

在连接器中的附加库目录中添加boost_1_67_0\stage\lib目录、Anaconda的Anaconda\libs目录以及Python\libs目录就ok了。
