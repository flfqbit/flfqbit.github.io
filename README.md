# flfqbit.github.io
A blog for notes of blockchain

#错误处理日志
## 20200515  
- Gridea在同步时报错，无法正常同步。采用了更换token等方法依然无法解决。  
- 退而求其次，采用github desktop的方式，手动更新Gridea生成的输出文件“E:\blog\Gridea\output”。然而，github desktop也显示push 错误，错误信息是
time pout。猜测是使用VPN的原因。  
-- 通常查询网络，可以通过修改git代理端口的方式解决问题  
--- 链接：https://www.jianshu.com/p/2a4b1c6f9819  
--- 指令：
---- git config --global http.proxy "127.0.0.1:1080"  
---- git config --global https.proxy "127.0.0.1:1080"  
-- 解决了github desktop同步的问题，博客https://flfqbit.github.io/能够正常显示最新的文档。  
- Gridea同步仍然报错，猜测Gridea内置的git模块，还没有修改端口。  
- 此问题暂时没解决，估计要找到Gridea的git代理修改方法才能够解决此问题。  
