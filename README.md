- 👋 Hi, I’m @NakeAskarov
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
NakeAskarov/NakeAskarov is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
:root {
  --text: #2B3044;
  --line: #BBC1E1;
  --line-active: #275EFE;
}

p {
  font-size: 18px;
  margin: 0;
  color: var(--text);
}
p a {
  display: inline-block;
  position: relative;
  text-decoration: none;
  color: inherit;
  margin: 0 var(--spacing, 0px);
  transition: margin 0.25s;
}
p a svg {
  width: 76px;
  height: 40px;
  position: absolute;
  left: 50%;
  bottom: 0;
  transform: translate(-50%, 7px) translateZ(0);
  fill: none;
  stroke: var(--stroke, var(--line));
  stroke-linecap: round;
  stroke-width: 2px;
  stroke-dasharray: var(--offset, 69px) 278px;
  stroke-dashoffset: 361px;
  transition: stroke 0.25s ease var(--stroke-delay, 0s), stroke-dasharray 0.35s;
}
p a:hover {
  --spacing: 4px;
  --stroke: var(--line-active);
  --stroke-delay: .1s;
  --offset: 180px;
}

html {
  box-sizing: border-box;
  -webkit-font-smoothing: antialiased;
}

* {
  box-sizing: inherit;
}
*:before, *:after {
  box-sizing: inherit;
}

body {
  min-height: 100vh;
  display: flex;
  font-family: "Inter", Arial;
  justify-content: center;
  align-items: center;
  background: #F6F8FF;
}
body .dribbble {
  position: fixed;
  display: block;
  right: 20px;
  bottom: 20px;
}
body .dribbble img {
  display: block;
  height: 28px;
}
body .twitter {
  position: fixed;
  display: block;
  right: 64px;
  bottom: 14px;
}
body .twitter svg {
  width: 32px;
  height: 32px;
  fill: #1da1f2;
}
# Link hover animation

A Pen created on CodePen.io. Original URL: [https://codepen.io/aaroniker/pen/VwjexVy](https://codepen.io/aaroniker/pen/VwjexVy).

