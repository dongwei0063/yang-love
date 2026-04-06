# 🌿 杨 - 恋爱小程序

两个人的私密日记，一棵共同浇灌的情感之树。

## 功能

- 🏠 **首页** - 在一起天数统计，快捷入口
- 📝 **恋爱日记** - 日历视图写日记，手写字体
- 🎯 **纪念日倒数** - 添加重要日期，快到时提醒
- 💌 **甜蜜瞬间** - 照片记录美好一刻
- ⭐ **小愿望** - 愿望清单，达成时撒花庆祝
- 💬 **悄悄话** - 情侣专属双向消息
- 📖 **回忆墙** - 时间线回顾所有甜蜜时刻
- 🎨 **三套主题** - 樱花季 / 星空夜 / 奶油风

## 快速开始（本地预览）

```bash
# 方式一：直接在浏览器打开
open index.html

# 方式二：用本地服务器（避免跨域问题）
cd yang-love
python3 -m http.server 8080
# 访问 http://localhost:8080
```

## 部署到 Vercel（免费）

### 方式一：拖拽上传（最简单）

1. 访问 https://vercel.com/new
2. 直接把 `yang-love` 文件夹拖入页面
3. 等待部署完成，获得网址

### 方式二：GitHub（推荐，持续更新）

```bash
cd yang-love
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/YOUR_USERNAME/yang-love.git
git push -u origin main
# 然后在 vercel.com Import 你的仓库
```

## 云同步（可选）

免费注册 [Supabase](https://supabase.com)，在设置页面填入 Project URL 和 anon key，即可开启云端数据同步。

## 截图

[待添加]

## License

MIT
