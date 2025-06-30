# Tesla API Public Key Server

这个仓库托管Tesla API集成所需的公钥文件。

## 文件说明

- `/.well-known/appspecific/com.tesla.3p.public-key.pem` - Tesla API公钥
- `/callback/` - OAuth回调页面

## 访问地址

- 公钥: `https://YOUR_USERNAME.github.io/tesla-api-keys/.well-known/appspecific/com.tesla.3p.public-key.pem`
- 回调: `https://YOUR_USERNAME.github.io/tesla-api-keys/callback/`

## 使用说明

1. 将公钥文件放置在正确的路径
2. 在Tesla开发者配置中使用上述URL
3. 确保文件可以通过HTTPS访问

## 安全说明

- 这个仓库包含公钥（非私钥），可以安全地公开
- 私钥应该始终保密，不要提交到任何仓库