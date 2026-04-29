# Streamlit 傻瓜部署教程

## 📱 前置要求
- ✅ 代码已上传到 GitHub（你已完成）
- ✅ Streamlit 应用文件（`streamlit_app.py` 或 `app.py`）
- ✅ `requirements.txt` 文件包含所有依赖

---

## 🚀 部署步骤（5分钟完成）

### 第一步：访问 Streamlit Cloud
打开浏览器，访问：[streamlit.io](https://streamlit.io)

### 第二步：登录或注册
- 点击 **Sign up** 或 **Sign in**
- 推荐用 **GitHub 账号直接登录**（最简单）

### 第三步：创建应用
1. 点击左上角 **Create app**
2. 或点击 **New app** 按钮

### 第四步：配置应用信息
会出现一个表单，填写以下内容：

| 项目 | 填写内容 | 例子 |
|------|---------|------|
| **Repository** | 你的 GitHub 仓库 | `DJY527717/CareerPilotDJY` |
| **Branch** | 分支名称 | `main` |
| **Main file path** | 应用主文件 | `streamlit_app.py` 或 `app.py` |

### 第五步：点击 Deploy
- 点击 **Deploy** 按钮
- 等待 1-5 分钟自动部署

### 第六步：完成！🎉
- 部署成功后会显示一个 URL
- 访问这个 URL 就能看到你的应用
- URL 类似：`https://careerpilot-yourusername.streamlit.app`

---

## ✅ 验证部署成功
- 能打开 URL
- 页面加载出内容
- 和本地运行的效果一样

---

## 🔄 后续更新流程

每次本地修改代码后，只需：

```bash
git add .
git commit -m "描述你的改动"
git push origin main
```

**Streamlit Cloud 会自动检测到更新，自动重新部署！** ✨

不需要手动再操作，几分钟内就会自动更新。

---

## ❌ 常见问题

### Q: 部署失败了怎么办？
A: 检查：
- ✅ `requirements.txt` 中是否有所有必需的包
- ✅ 仓库是否公开
- ✅ 主文件路径是否正确

### Q: 怎么查看部署日志？
A: 在 Streamlit Cloud 的应用页面，左侧有 **Manage app** → **Rerun** 或查看日志

### Q: 应用加载很慢？
A: 第一次加载可能慢，因为在初始化环境。刷新试试。

### Q: 怎么删除应用？
A: Streamlit Cloud 应用列表 → 选择应用 → **Settings** → **Delete app**

---

## 🎯 总结
1. 打开 streamlit.io
2. 用 GitHub 账号登录
3. 点 Create app
4. 选仓库、分支、主文件
5. 点 Deploy
6. 等待完成
7. Done! 🚀

