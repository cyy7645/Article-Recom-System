# Article-Recom-System

### recommendation.ipynb：  
定义了所有的函数和最后的两个接口函数 func1 和 func2

### func1：
为每隔一段时间运行一次，用于更新数据集的TD-IDF表，数据集预处理的字典等中间变量  

### func2：  
实时调用，每进入一篇新文章，调用一次此函数，把最相似的N篇文章id写入 write_keys.txt中

### chinese_stop_words.txt： 
存放中文停用词文件

### new_doc.txt： 
待找相似文章的文件

### news： 
原始数据集

### tmp： 
存放中间值的文件 （func1的返回值） 

### write_keys.txt：
找到的相似文章id 存放在该文件下
