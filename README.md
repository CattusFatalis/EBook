# EBook
Minecraft成书内容外置插件
服务端：spigot-1.21.8

使用方法：
1. 将插件放入服务端的plugins
2. 启动服务器
3. 将合适大小的txt格式的文件放入plugins\EBook\books里
4. 进入服务器后使用书与笔输入[B]文件名
5. 文件名不用带后缀，例如红楼梦.txt只需要输入[B]红楼梦
6. 给书与笔签名成成书后打开成书既可以显示txt内容
7. java版成书上限只有100页，所以显示数量有限，所以大的txt文件请提前分割成若干个符合要求的小txt，成书的字符限制规则请查询Minecraft Wiki

指令列表：
1. /setauthor 设置玩家手中书的作者
2. /bookreload clear 清空书籍缓存
3. /bookreload stats 显示缓存统计信息

版本（请自行测试）
1. 可以兼容spigot的插件的服务端理论都可以使用
2. 理论上可以向下兼容部分游戏版本

没有使用混淆加密
