# USB-VIRUS
最近出现在公司的病毒，请大家帮忙分析

杀毒软件查杀后
用这个命令就能去除隐藏：attrib -s -h H:\* /s /d

参数：

/S 处理当前文件夹及其子文件夹中的匹配文件

/D 也处理文件夹

这样就能将 H 盘所有的文件和文件夹的系统属性（System）和隐藏属性（Hidden）属性去除

是不是新变种？ 之前设置查看隐藏文件就能看见U盘文件
