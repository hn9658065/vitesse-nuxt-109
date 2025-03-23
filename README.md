<h2 align="center">
<a href="https://github.com/antfu/vitesse">Vitesse</a> for Nuxt 3 with Chrome 109
</h2>

<p align="center">
<br>
基于<a href="https://stackblitz.com/github/antfu/vitesse-nuxt">Vitesse  for Nuxt 3</a>修改，为适应低版本浏览器（Chrome 109）做了兼容。
</p>

## 特性

### ✨ Unocss 配置

- 基于 `presetWind3` 的原子CSS引擎
- 集成以下预设：
  - 🌪️ Tailwind 语义预设（presetWind3）
  - 🎨 属性模式（presetAttributify）
  - 🖼️ 图标系统（presetIcons）
  - 📝 排版预设（presetTypography）
  - 🌐 Web字体预设（presetWebFonts）
- 使用 Fontshare 作为字体服务提供商
- 包含以下字体家族：
  - `sans`: DM Sans
  - `serif`: DM Serif Display
  - `mono`: DM Mono

## 使用准备

### 本地克隆

如果希望手动克隆并保持更干净的 Git 历史记录

```bash
npx degit hn9658065/vitesse-nuxt my-nuxt-app
cd my-nuxt-app
pnpm i # 如果尚未安装 pnpm，请先运行：npm install -g pnpm
```
