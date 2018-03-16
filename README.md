# CNNs-visualization
利用MATLAB里的反卷积和反池化实现
***
[Visualizing and Understanding Convolutional Networks中文讲解](http://blog.csdn.net/tina_ttl/article/details/52048765)
***
[video](http://videolectures.net/eccv2014_zeiler_convolutional_networks/)
***
[中文翻译](http://blog.csdn.net/kklots/article/details/17136059)

##
王同学，想请你帮我思考一下做个东西：不知道你看过那个visualizing and understanding cnn那篇文章没有。你可以看到，他的可视化是通过上采样以及反卷积把某层的冲激响应映射会原始的RGBk空间中显示出来，这个比较合理。跟我提供的代码不太一样，我是直接将某层的冲激响应转成灰度图或者热图显示出来。你是否可以考虑参照那篇文章，用matlab把这个实现，因为我觉得这样更合理。给你提供函数表https://cn.mathworks.com/help/nnet/functionlist.html
##
可以用里头的transposedConv2dLayer和maxUnpooling2dLayer实现
##
建议使用vgg16网络，不用alexnet网络
