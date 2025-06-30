# Tesla Public Key Directory

将生成的 `com.tesla.3p.public-key.pem` 文件放置在此目录中。

## 文件要求

- 文件名必须是：`com.tesla.3p.public-key.pem`
- 必须是有效的PEM格式公钥
- 必须可以通过HTTPS访问

## 生成公钥

公钥将在运行 `python main.py` 时自动生成在：
```
lib/tesla_api/TeslaKeys/com.tesla.3p.public-key.pem
```

将该文件复制到这个目录即可。