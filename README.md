# hao123 智能导航系统

hao123 风格导航页 + 在线工具集合，可直接部署为浏览器主页。

## 文件结构

```
hao123/
├── index.html          # 主页 - 奇易智能导航系统
├── 1.html              # 定制导航系统
├── 2.html              # 奇艺科技导航网站
├── 123.html            # 多功能科学计算器
├── 131.html            # 齿轮参数计算器
├── 2013002.html        # 搜索引擎登录入口大全
├── 2025.html           # 汉字启蒙 · 一年级识字
├── 2026.html           # 口算小达人
├── TEST.html           # 网络速度测试
├── Unlock.html         # 解锁码生成器
├── customs.html        # 智能税务计算器
├── zlcalculator.html   # 智能理财计算器
├── css/style.css
└── js/{list.js, script.js}
```

## 已包含工具

| 页面 | 功能 |
|------|------|
| 智能理财计算器 | 汇率、贷款、存款、个人所得税 |
| 智能税务计算器 | 一般纳税人专用 |
| 网络速度测试 | 下载/上传速度测试 |
| 解锁码生成器 | 金米自动化设备 |
| 多功能科学计算器 | 科学计算 |
| 齿轮参数计算器 | 齿轮参数计算 |
| 搜索引擎入口 | 开放平台/sitemap/导航站入口 |
| 汉字启蒙 | 一年级识字 |
| 口算小达人 | 口算练习 |

## 部署

### GitHub Pages
仓库 Settings → Pages → 选择 main 分支 → Save

### Nginx / Docker
```bash
git clone https://github.com/martinfengdz/hao123-navigation.git
cd hao123-navigation
python3 -m http.server 8080
```

## 技术栈
- 原生 HTML5 + CSS3 + JavaScript
- 无第三方依赖
- 响应式设计
