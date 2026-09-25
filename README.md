<!-- ═══════════════ 🌊 HEADER (امواج) + 🌧️ MATRIX BACKGROUND ═══════════════ -->
<div align="center" style="position: relative;">
  <!-- لایه بک‌گراند باران ماتریکس -->
  <img src="matrix-rain.svg" width="100%" style="position: absolute; top: 0; left: 0; z-index: 0;" />
  
  <!-- لایه هدر موج‌دار (روی باران قرار می‌گیرد) -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=I%27m%20Hiva&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Developer%20%7C%20Builder%20%7C%20Dreamer&descAlignY=58&descSize=18" width="100%" style="position: relative; z-index: 1;" />
</div>
<!-- ═══════════════ ⌨️ نام متحرک ═══════════════ -->
<div align="center">
  <a href="https://github.com/HivaFourotan">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=30&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=Hi+%F0%9F%91%8B+I'm+Hiva;Full-Stack+Developer+%F0%9F%92%BB;Open+Source+Enthusiast+%E2%9C%A8;Building+cool+stuff+with+friends+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</div>

<!-- ═══════════════ 🎨 SVG اختصاصی Hiva-OS ═══════════════ -->
<div align="center">
  <img src="hiva-os.svg" width="100%" />
</div>

<!-- ═══════════════ 🐍 اسنیک (دمو — بدون ورک‌فلو) ═══════════════ -->
<div align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%" />
</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117,00FF41,00F7FF&height=220&section=header&text=Hi,%20I'm%20Hiva&fontSize=62&fontColor=ffffff&fontAlignY=36&desc=Developer%20%C2%B7%20Builder%20%C2%B7%20Curious%20about%20physics&descAlignY=58&descAlign=62" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=00F7FF&center=true&vCenter=true&width=640&lines=JavaScript%2C+TypeScript+and+Python;I+like+taking+ideas+apart+and+rebuilding+them)](https://github.com/HivaFourotan)

</div>

### About
```ts
const hiva = {
  basedIn: "Tehran, Iran",
  learning: ["TypeScript", "JavaScript", "Python", "HTML"],
  interestedIn: ["interfaces", "open source", "physics"],
  currently: "finishing small OS-style UI experiments",
};

### Now

- Building [Mac-Os-26-](https://github.com/HivaFourotan/Mac-Os-26-) — a from-scratch desktop-style interface
- Building [Linux-Ubuntu-26.04](https://github.com/HivaFourotan/Linux-Ubuntu-26.04)
- Learning TypeScript and shipping smaller experiments in public

### Stack

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=HivaFourotan&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=HivaFourotan&layout=compact&theme=tokyonight&hide_border=true"/>

</div>


مارِ خودت فقط با یک Action در مخزن پروفایل (`HivaFourotan/HivaFourotan`) ساخته می‌شود. فایل `.github/workflows/snake.yml` را با این محتوا بساز:

```yaml
name: contribution snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: HivaFourotan
          outputs: dist/snake.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
