# blade-log

这是一个简单的日志实现，可能是一个简易版的 `logback`。

## 特性

- 格式化日志输出
- 彩色日志打印
- 输出日志到文件
- 多种日志级别
- 不依赖第三方库
- 双缓冲队列保证高性能
- 按文件大小切割
- 百万吞吐量

## 使用

加入依赖


```xml
<dependency>
    <groupId>com.bladejava</groupId>
    <artifactId>blade-log</artifactId>
    <version>0.0.7</version>
</dependency>
```

## 配置

```bash
com.blade.logger.rootLevel=INFO
com.blade.logger.path=./logs
com.blade.logger.name=app
```

