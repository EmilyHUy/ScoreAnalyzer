# 简易excel分析器

------

主要实现的功能是读入一个csv文件，比如某个班的学习成绩，软件进行分析后输出分析的结果到预设的word模版（dot文件）对应标签处，进而另存为一个新的word，即为输出的成绩分析表。使用了微软word自带的MWORD库进行了对word文档的读写。输入输出都可以自己选文件的位置，默认的学生属性有五列，默认的模版为上传的dot文件
