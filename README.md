# 实现一个简单版的日志库
### 参考
- https://blog.csdn.net/u013255127 的博客
### 功能
- 支持日志写入文件、打印到控制台
- 可根据日志文件大小、日志时间进行分割
### 实现逻辑
- 定义接口，包含Debug()/Warn()等方法
- 分别定义文件日志、控制台日志结构体
- 日志结构体分别实现自己的Debug()/Warn()方法
- var一个全局接口，根据config创建对象，然后接口调用方法