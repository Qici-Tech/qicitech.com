# qicitech.com

GitHub Pages 静态站点仓库。

## 部署步骤

1. 把代码推到 `main` 分支。
2. 在 GitHub 仓库里打开 `Settings -> Pages`。
3. `Build and deployment` 里选择 `Deploy from a branch`。
4. 分支选 `main`，目录选 `/ (root)`。
5. 在阿里云 DNS 里添加：
   - `@` A -> `185.199.108.153`
   - `@` A -> `185.199.109.153`
   - `@` A -> `185.199.110.153`
   - `@` A -> `185.199.111.153`
   - `www` CNAME -> `Qici-Tech.github.io`

## 备注

- `CNAME` 文件里只放裸域名。
- 现有的邮件 `MX` / `TXT` 记录不要删。
