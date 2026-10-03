<div align="center">

# Indranil Maiti

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=400&size=20&duration=3200&pause=900&color=2563EB&center=true&vCenter=true&width=520&lines=Design+Engineer;I+live+between+Figma+and+code;Snell's+law%2C+wired+to+a+design+token" alt="Design Engineer" />

<br/>

**I design and build interfaces where the behaviour is computed, not approximated.**

<br/>

<img src="https://img.shields.io/badge/-%20-8300B5?style=flat-square" height="6" />
<img src="https://img.shields.io/badge/-%20-3B2BFF?style=flat-square" height="6" />
<img src="https://img.shields.io/badge/-%20-00A3FF?style=flat-square" height="6" />
<img src="https://img.shields.io/badge/-%20-00D97E?style=flat-square" height="6" />
<img src="https://img.shields.io/badge/-%20-C8E600?style=flat-square" height="6" />
<img src="https://img.shields.io/badge/-%20-FFD400?style=flat-square" height="6" />
<img src="https://img.shields.io/badge/-%20-FF8A00?style=flat-square" height="6" />
<img src="https://img.shields.io/badge/-%20-FF2D2D?style=flat-square" height="6" />

<br/><br/>

<a href="https://www.indrabuildswebsites.com/">
  <img src="https://img.shields.io/badge/Portfolio-indrabuildswebsites.com-2563EB?style=flat-square&labelColor=0D1117" alt="Portfolio" />
</a>
<a href="https://www.linkedin.com/in/indranil-maiti-b56967228/">
  <img src="https://img.shields.io/badge/LinkedIn-Indranil%20Maiti-2563EB?style=flat-square&labelColor=0D1117&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://x.com/Nil_phy_dreamer">
  <img src="https://img.shields.io/badge/X-@Nil__phy__dreamer-2563EB?style=flat-square&labelColor=0D1117&logo=x&logoColor=white" alt="X" />
</a>
<a href="mailto:indranilmaiti16@gmail.com">
  <img src="https://img.shields.io/badge/Email-indranilmaiti16@gmail.com-2563EB?style=flat-square&labelColor=0D1117&logo=gmail&logoColor=white" alt="Email" />
</a>

<sub>Toruń, Poland · GMT+2 · he/him</sub>

</div>

---

## `[ 01 ]` &nbsp; The optics lab

I studied light before I built interfaces, so my portfolio has an optical bench on it.

A point source, a lens, a prism and a screen. Every ray is refracted on its own by the paraxial thin-lens law — nothing tells the fan where to meet. **That they meet at all is the thin-lens equation, emerging rather than being applied.** Put the prism in and the source turns white; fifteen wavelengths are then refracted at both glass faces with a refractive index of their own, from the published Sellmeier coefficients for real Schott glass.

Slide the sampler along the spectrum, press *use this colour*, and **that wavelength becomes the site's accent** — live in every section, and persisted.

Eight interface components came out of it. Each one is something interfaces already do, done from the equation instead of from an impression of it:

| | Replaces | Physics |
|---|---|---|
| **Fresnel edge** | the uniform 1px glass border | `R = R₀ + (1 − R₀)(1 − cos θ)⁵` |
| **Refraction, not blur** | `backdrop-filter: blur()` | `d = t·sin(θ₁ − θ₂)/cos(θ₂)` |
| **Caustic shadow** | `box-shadow` under glass | ray density after refraction |
| **Total internal reflection** | a shake animation | `θc = arcsin(n₂/n₁)` |
| **Depth of field** | a hand-picked blur ramp | circle of confusion |
| **Chromatic aberration** | a fixed 2px RGB offset | `f(λ) → m(λ)`, offset ∝ radius |
| **Thin-film interference** | an iridescent gradient | `R(λ) ∝ sin²(π·Δ/λ)` |
| **Diffraction grating** | a holographic gradient | `d · sin θ = m λ` |

The maths lives in pure modules with no React in them, and **`npm run optics:check` holds all of it against closed forms, published constants and conservation laws** — 105 assertions. The marcher's smallest achievable deviation matches `δ_min = 2·arcsin(n·sin(A/2)) − A` to three decimals. The caustic conserves light to one part in a hundred thousand. A film of zero thickness comes out dark, which is why a soap bubble goes black just before it bursts.

<sub>Three of those were caught by the assertions. Two only by screenshotting.</sub>

---

## `[ 02 ]` &nbsp; Selected work

<table>
<tr>
<td width="50%" valign="top">

### CraftUI
**Building** · [craftui.space](https://www.craftui.space/)

A growing library of blocks, sections and interactive components built on Motion — micro-interactions and animation, with the fundamentals done properly.

`Next.js` `Tailwind` `Motion`

</td>
<td width="50%" valign="top">

### Quest
**Freelance** · [fraterny.com/quest](https://www.fraterny.com/quest)

An AI-powered platform for psychological assessment. Design and build, front to back.

`React` `Tailwind` `Node.js` `MongoDB`

</td>
</tr>
</table>

---

## `[ 03 ]` &nbsp; Writing

I write about the small things that make interfaces feel right.

- **[Fixing invisible space with two lines of CSS](https://www.indrabuildswebsites.com/blog)** — `text-box-trim`, `text-box-edge`, and why your buttons have never been vertically centred
- **[State management with Zustand](https://www.indrabuildswebsites.com/blog)** — setting it up without the ceremony

---

## `[ 04 ]` &nbsp; What I build with

<div align="center">

<img src="https://img.shields.io/badge/TypeScript-2563EB?style=flat-square&labelColor=0D1117&logo=typescript&logoColor=2563EB" />
<img src="https://img.shields.io/badge/React-2563EB?style=flat-square&labelColor=0D1117&logo=react&logoColor=2563EB" />
<img src="https://img.shields.io/badge/Next.js-2563EB?style=flat-square&labelColor=0D1117&logo=nextdotjs&logoColor=2563EB" />
<img src="https://img.shields.io/badge/Tailwind-2563EB?style=flat-square&labelColor=0D1117&logo=tailwindcss&logoColor=2563EB" />
<img src="https://img.shields.io/badge/Motion-2563EB?style=flat-square&labelColor=0D1117&logo=framer&logoColor=2563EB" />
<img src="https://img.shields.io/badge/GSAP-2563EB?style=flat-square&labelColor=0D1117&logo=greensock&logoColor=2563EB" />
<br/>
<img src="https://img.shields.io/badge/Node.js-8B8B93?style=flat-square&labelColor=0D1117&logo=nodedotjs&logoColor=8B8B93" />
<img src="https://img.shields.io/badge/MongoDB-8B8B93?style=flat-square&labelColor=0D1117&logo=mongodb&logoColor=8B8B93" />
<img src="https://img.shields.io/badge/MDX-8B8B93?style=flat-square&labelColor=0D1117&logo=mdx&logoColor=8B8B93" />
<img src="https://img.shields.io/badge/Figma-8B8B93?style=flat-square&labelColor=0D1117&logo=figma&logoColor=8B8B93" />
<img src="https://img.shields.io/badge/SVG%20%2F%20Canvas-8B8B93?style=flat-square&labelColor=0D1117" />
<img src="https://img.shields.io/badge/Git-8B8B93?style=flat-square&labelColor=0D1117&logo=git&logoColor=8B8B93" />

</div>

<div align="center"><sub>Blue is what I reach for first. Grey is what I reach for when the job needs it.</sub></div>

---

## `[ 05 ]` &nbsp; Stats

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=Indra-photon&show_icons=true&hide_border=true&count_private=true&bg_color=0D1117&title_color=2563EB&icon_color=2563EB&text_color=8B8B93&hide=issues" alt="GitHub Stats" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Indra-photon&layout=compact&hide_border=true&bg_color=0D1117&title_color=2563EB&text_color=8B8B93&langs_count=6" alt="Top Languages" />

<br/>

<img height="150" src="https://github-readme-streak-stats.herokuapp.com/?user=Indra-photon&hide_border=true&background=0D1117&ring=2563EB&fire=2563EB&currStreakLabel=2563EB&sideLabels=8B8B93&dates=8B8B93&sideNums=8B8B93&currStreakNum=FFFFFF" alt="Streak" />

</div>

---

## `[ 06 ]` &nbsp; Open to work

I'm looking for **design engineer** and **product-minded frontend** roles — teams where the interface is the product and someone is expected to care about why the easing curve is that one.
