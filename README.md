<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:667eea,100:764ba2&height=200&section=header&text=Hi%20There!%20I'm%20Rendrastya&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Fullstack%20Developer%20%40%20Guestlist.id&descAlignY=55&descSize=18" width="100%"/>

<a href="https://github.com/DenverCoder1/readme-typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=7C3AED&center=true&vCenter=true&width=600&lines=Building+things+for+Guestlist.id+%F0%9F%8C%B4;React+%2B+Next.js+%2B+Go+%2B+PostgreSQL;Turning+coffee+into+code+in+Bali;Always+learning%2C+occasionally+debugging+at+2am" alt="Typing SVG" />
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=Rastyaa&label=Profile%20Views&color=7c3aed&style=flat" alt="profile views"/>
<img src="https://img.shields.io/badge/dynamic/json?color=7c3aed&label=followers&query=%24.followers&url=https%3A%2F%2Fapi.github.com%2Fusers%2FRastyaa&style=flat" alt="followers"/>

</div>

<br/>

## 👋 About Me

- 🔭 Currently building **[Guestlist.id](https://guestlist.id)** — a Bali-based activity & experience booking platform
- 💻 Fullstack: **React, Next.js, TypeScript, Go, PostgreSQL, Docker, Firebase, Cloudflare, React Native**
- 📫 Reach me at **reenkdk2314@gmail.com**
- ⚡ Fun fact: I ship features by day, and my brain keeps compiling them by night

<div align="center">
<a href="mailto:reenkdk2314@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
</div>

<br/>

## 🛠️ Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,go,postgres,docker,firebase,cloudflare,reactnative,nodejs,git,figma,linux&perline=7"/>
</div>

<br/>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Rastyaa&show_icons=true&theme=tokyonight&hide_border=true&count_private=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rastyaa&layout=compact&theme=tokyonight&hide_border=true"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Rastyaa&theme=tokyonight&hide_border=true"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=Rastyaa&theme=tokyonight&no-frame=true&row=1&column=7"/>

</div>

<br/>

## 🐍 Contribution Snake

<div align="center">
<img src="https://raw.githubusercontent.com/Rastyaa/Rastyaa/output/github-contribution-grid-snake.svg"/>
</div>

<p align="center"><i>⚠️ This one won't render until you set up the GitHub Action below — see setup notes.</i></p>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:764ba2,100:667eea&height=100&section=footer"/>
</div>

---

## ⚙️ Setup Notes (baca dulu sebelum panik kalau ada yang gak muncul)

1. **File ini harus jadi README di repo khusus profil.** Kalau belum ada, buat repo baru bernama persis `Rastyaa` (sama seperti username GitHub-mu), lalu paste isi file ini sebagai `README.md`. GitHub otomatis menampilkannya di halaman profil.

2. **Stats card / streak card kadang lambat atau kena rate limit** — ini instance publik gratis yang dipakai banyak orang, jadi kadang muncul "Error" sementara. Biasanya pulih sendiri dalam beberapa menit; kalau sering terjadi, kamu bisa self-host di Vercel-mu sendiri (linknya ada di masing-masing repo project).

3. **Animasi ular (snake) butuh GitHub Action** supaya bisa jalan. Buat file `.github/workflows/snake.yml` di repo `Rastyaa/Rastyaa` isinya:

```yaml
name: generate animation
on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches: [ main ]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Rastyaa
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

   Push filenya, lalu jalankan manual sekali lewat tab **Actions → Run workflow**. Setelah itu ularnya akan otomatis "memakan" grafik kontribusimu tiap 6 jam.

4. **Ganti tema:** semua card di atas pakai tema `tokyonight`. Tinggal ganti jadi `dark`, `radical`, `merko`, `dracula`, `synthwave`, dll — daftar lengkap ada di masing-masing repo project (github-readme-stats, github-profile-trophy, dst).
