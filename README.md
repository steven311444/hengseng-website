# Heng Seng - China Supply Partner 网站

英文单页企业站（2026-08-12 改版）：
Apple 极简黑白风 + 品牌绿 `#0F5C3D`，英雄区预留上海天际线头图，四条产品线（第四条为仿真花），含数字带、Why Us、5 步流程、行业图标墙、真实评价占位、FAQ、询盘表单。

## 本地预览

用浏览器直接打开 `index.html` 即可（无需服务器）。

## 目录结构

- `index.html` + `style.css` — 新版（Apple 黑白绿风格），即当前部署/预览版本
- `v1-classic/` — 老服务器版本风格（深绿 + 橙色按钮）套用新内容的版本，本地预览
- `v2-apple/` — 新版独立副本，本地预览
- `preview.pdf` — 新版导出的 PDF 预览

两个版本均为本地可直接打开预览的静态页面，双击 `index.html` 即可。

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

## 待补图片清单（页面中已用虚线占位标明）

## 图片现状

| 位置 | 使用图片 | 状态 |
|---|---|---|
| 英雄区背景 | `images/shanghai.jpg`（备选 `shanghai-night.jpg`） | ✅ 已放，可替换自己的上海照片 |
| 产品卡 1 工程防护 | `construction-protection.jpg` | ✅ 已放（免费图，建议后续换产品实拍） |
| 产品卡 2 遮阳网/篷布 | `pvc-fabric.jpg` | ✅ 已放（自有 PVC 篷房图） |
| 产品卡 3 捆绑带 | `binding-strap.jpg` | ✅ 已放（自有捆绑带图） |
| 产品卡 4 仿真花 | `artificial-flowers.jpg` | ✅ 已放（Pexels 免费图） |
| 信任区（验货流程） | 视频 `videos/pvc-strength-test.mp4`（待放入）+ 封面 `qc-inspection.jpg` | ⏳ 视频文件待用户提供 |

> 免费图许可：Pexels License（免署名）+ Flickr CC BY 2.0（页脚已署名 Jnzl's Photos、ubrayj02）。
> `tarpaulin.jpg` 为备用篷布图，暂未使用。

## 视频

- 验货区视频：把实验室 PVC 强度测试视频放到 `videos/pvc-strength-test.mp4`（v2-apple 同步放一份），页面自动生效。

## 待补内容

- 客户评价区：从 WhatsApp 真实回复中整理（不编造）
- 数字统计带：按实际数据校准（当前为示例值）
- 询盘表单：提交后自动打开 WhatsApp（+86 159 0183 8520）并填入表单内容；如需邮件后端可换 Formspree/Web3Forms
- 每类产品详情页或 PDF 目录下载
