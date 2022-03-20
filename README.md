# sync-demo-21
POST /api/v1/files

跟POST /api/v1/texts类似
区别在于保存文件而不是保存文本

思路：
1. 获取go执行文件所在目录
2. 在该目录创建uploads目录
3. 将文件保存为另一个文件
4. 返回后者的下载路径