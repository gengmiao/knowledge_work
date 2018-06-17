# 功能描述

**Function:根据用户输入的内容进行展示结果/根据用户的输入进行推荐**</br>

**之前的测试功能函数**</br>
   *通过get_data_spider.py 和get_data_sparql.py获取数据，（如果没有该数据，我们通过spider从百度文库上获取数据）经过测试之后，我们将Sparql语句集成到.net框架之中*</br>
**Main.cs**</br>
   *根据用户输入的电影名称进行模糊查询，点击按钮进行搜索，并将搜索的结果以表格的形式进行呈现，其中包含电影的一些基本属性（such as ：地址、名字、作者、摘要等基本信息）*</br>
**Recommond.cs**</br>
   *用户通过输入电影的基本类别，点击按钮之后进行搜索，搜索结果为推荐给用户的电影*