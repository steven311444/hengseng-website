# Heng Seng - China Supply Partner 网站

英文单页企业站（首页 / 产品 4 条线 / 为什么选我们 / 合作流程 / 联系）。

## 本地预览

用浏览器直接打开 `index.html` 即可（无需服务器）。

## 部署（免费托管，绑定 hengsengcn.com）

### 方案 A：GitHub Pages（推荐）

1. 新建 GitHub 仓库，把 `index.html` 和 `style.css` 推上去。
2. 仓库 Settings → Pages → Source 选 main 分支根目录，保存。
3. 在域名服务商（DNS）添加记录：
   - A 记录指向 `185.199.108.153`、`185.199.109.153`、`185.199.110.153`、`185.199.111.153`
   - 或 CNAME `hengsengcn.com` → `<用户名>.github.io`
4. Pages 设置里填自定义域名 `hengsengcn.com`，开启 HTTPS。

### 方案 B：Vercel / Netlify

1. 登录 vercel.com 或 netlify.com，Import 该目录/仓库。
2. 部署后 Domain 设置里添加 `hengsengcn.com`，按提示在 DNS 加 CNAME 记录。

## 待补充内容

- WhatsApp 号码（联系区占位符）
- 产品图册 / 真实产品照片
- 公司资质（如有）
- 每类产品详情页或 PDF 目录下载
