# Pass It On · 她圈

这是由原型收敛而成的第一版完整静态网站。

## 运行

在项目目录执行：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000/`。

## 当前页面

| 文件 | 说明 |
|------|------|
| index.html | 品牌首页、注册流程和社区入口 |
| login.html | 测试账号登录页 |
| dashboard.html | 登录后的发愿板、帮助她、Pass It On、燃料库和个人中心 |

首页注册完成后可进入 Dashboard；Dashboard 支持桌面侧栏和移动端底部导航。

测试账号：`demo@passiton.cn`，密码：`PassItOn2026`。该账号仅用于本地静态演示。

## 历史来源

## 文件说明

| 文件 | 说明 |
|------|------|
| 01_landing_page.html | Landing Page 最终版（品牌名 Pass It On） |
| 02_dashboard_main.html | 登录后主界面 · 最新版（四大版块 + 社区圈子） |
| 03_dashboard_v2.html | Dashboard v2（含燃料库完整版） |
| 04_dashboard_v1.html | Dashboard v1 |
| 05_landing_page_v2.html | 她圈 Landing Page v2（功能完善版） |
| 06_landing_page_v1.html | 她圈 Landing Page v1（初始版） |

## 功能模块

### Landing Page
- 品牌介绍 + 价值主张
- 用户注册流程（手机/邮箱验证码）
- 身份证上传 + 面部识别 + 声纹验证
- 婉拒非女性用户机制
- 燃料库预览版块

### Dashboard（登录后主界面）
1. **发愿板** — 四步发愿指引 + 成功故事展示 + 进行中的愿望卡片
2. **帮助她** — 筹集资金/库存销货/就业机会/创业资源愿望清单
3. **Pass It On** — 每日2次/每周3次帮助限额，实时配额显示
4. **燃料库** — 考研考公/留学/语言/移民政策资料库
5. **社区圈子** — 雅思/澳洲WHV/考研/大厂求职等分类聊天室

## 品牌信息
- 品牌名：Pass It On（中文：传下去）
- 简称：PIO
- 主色：玫瑰红 #D4537E
- 理念：一个帮助下一个，涟漪不会停止
