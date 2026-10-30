# 蒙洋 · Yang Meng

个人学术主页 / Personal academic homepage.

直接用浏览器打开 `index.html` 即可访问，无需安装依赖或构建。部署到 GitHub Pages 时，将 `index.html` 与 `avatar-cartoon.png` 放在同一目录。

Open `index.html` in a browser. No dependencies or build step are required. Keep `index.html` and `avatar-cartoon.png` together when deploying to GitHub Pages.

## 功能 / Features

- 中文、English、双语三种显示模式，默认双语，自动记住选择。
- Chinese, English, and bilingual views, with the selected language saved locally.
- 邮箱链接与一键复制；复制不可用时显示手动复制提示。
- Clickable email and copy button, with a manual-copy message if clipboard access is unavailable.
- 支持手机、平板与桌面布局，支持键盘操作及减少动态效果偏好。
- Responsive layout, keyboard access, and reduced-motion support.

## 内容维护 / Editing

所有文字与样式位于 `index.html`。中英文内容分别用 `data-lang="zh"` 和 `data-lang="en"` 标记。修改邮箱时，同时更新页面中的 `mailto:` 链接、可见地址和脚本里的 `email` 常量。

All text and styles live in `index.html`. Chinese and English content use `data-lang="zh"` and `data-lang="en"`. To update the email, change the `mailto:` link, visible address, and JavaScript `email` constant.

教育经历中的院校和时间沿用原主页内容。卡通头像是原创插画，不是根据本人照片绘制的肖像。原来的 `avatar.png` 可保留，不影响页面。

Institutions and dates are retained from the original homepage. The cartoon avatar is an original illustration, not a likeness based on a personal photograph. The original `avatar.png` may be retained without affecting the page.
