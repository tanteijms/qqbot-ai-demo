# 部署指南

## 🚀 快速部署到 GitHub Pages

### 第1步：提交代码

```bash
# 在仓库目录下执行
git add .
git commit -m "Add QQ AI atmosphere demo with docs"
git push origin main
```

### 第2步：开启 GitHub Pages

1. 访问你的 GitHub 仓库页面
2. 点击 **Settings**（设置）
3. 在左侧菜单找到 **Pages**
4. 在 **Source** 下拉菜单中选择 **main** 分支
5. 点击 **Save**（保存）

### 第3步：等待部署

- 等待 2-3 分钟
- GitHub 会自动构建和部署
- 部署完成后，页面会显示访问链接

### 第4步：访问 Demo

你的 Demo 地址将是：
```
https://你的用户名.github.io/qqbot-ai-demo/
```

例如，如果你的 GitHub 用户名是 `zhangsan`，那么地址就是：
```
https://zhangsan.github.io/qqbot-ai-demo/
```

## ✅ 验证部署

访问上述链接，确保：
- ✅ 页面正常加载
- ✅ 6个场景都能演示
- ✅ 动画流畅
- ✅ 无报错

## 📝 提交比赛

将这个链接填写到比赛提交表单的 **产品 Demo 链接** 栏位。

## 🔧 本地测试

如果想在本地测试：

```bash
# 方法1：直接打开
open index.html

# 方法2：启动本地服务器
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## 🆘 常见问题

### Q: GitHub Pages 没有生效？
A: 等待 5-10 分钟，GitHub 需要时间构建。刷新 Settings → Pages 页面查看状态。

### Q: 页面显示 404？
A: 检查仓库是否设置为 Public，以及 Pages 是否正确配置。

### Q: 修改后没有更新？
A: 
```bash
git add .
git commit -m "Update demo"
git push origin main
# 等待几分钟后刷新页面（Ctrl+Shift+R 强制刷新）
```

## 📦 仓库结构

```
qqbot-ai-demo/
├── index.html          # 主页面（Demo）
├── README.md           # 项目说明
├── LICENSE             # 开源协议
├── .gitignore          # Git 忽略文件
├── docs/               # 文档目录
│   ├── 产品方案.md      # 完整产品方案
│   └── 录屏脚本.md      # 录屏演示脚本
└── assets/             # 资源目录
    └── images/         # 图片资源
```

## 🎯 下一步

1. ✅ 部署 Demo 到 GitHub Pages
2. ⏭️ 录制产品演示视频（参考 docs/录屏脚本.md）
3. ⏭️ 生成 PDF 说明文档（从 docs/产品方案.md 转换）
4. ⏭️ 提交比赛

**加油！🚀**
