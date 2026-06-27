# 时间去哪了 · 部署说明

## 文件清单
```
index.html    ← 主页面
manifest.json ← PWA 配置
sw.js         ← 离线缓存（Service Worker）
```

## 部署到 GitHub Pages（5分钟）

1. 在 GitHub 新建仓库，例如 `time-tracker`
2. 把三个文件上传进去（Upload files）
3. 进入仓库 Settings → Pages → Source 选 `main` 分支 → Save
4. 等约1分钟，访问 `https://你的用户名.github.io/time-tracker/`

## 手机添加到主屏幕（变成 App）

### iPhone（Safari）
1. 用 Safari 打开网址
2. 点底部分享按钮 □↑
3. 选"添加到主屏幕"
4. 点"添加"

### Android（Chrome）
1. 用 Chrome 打开网址
2. 弹出"添加到主屏幕"提示，点击即可
3. 或点右上角菜单 → "添加到主屏幕"

## 数据说明
- 数据保存在**本地浏览器**（localStorage）
- 换设备 / 清除浏览器数据前，请在设置页「导出 JSON」备份
- 导入备份：设置页 → 「导入备份」，选择之前导出的 JSON 文件

## 注意
- 需要一个图标文件（icon-192.png、icon-512.png）才能完美显示
  PWA 图标，可以先用任意图片代替，不影响主要功能
