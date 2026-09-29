<!-- ============================== HEADER ============================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=300&color=0:0D0221,40:3B0764,75:9333EA,100:E879F9&text=BAHTIAR%20RIFAI&fontSize=72&fontColor=FFFFFF&fontAlignY=36&desc=Fullstack%20Developer%20%E2%80%A2%20Laravel%20Backend%20%E2%80%A2%20Vue.js&descAlignY=56&descSize=18&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/Bahtiarrifaistudent">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2400&pause=800&color=E879F9&center=true&vCenter=true&width=900&lines=%3E+php+artisan+serve+--profile=bahtiar;%3E+Crafting+clean+%26+scalable+Laravel+backends;%3E+Building+reactive+UIs+with+Vue.js;%3E+From+database+schema+to+deployment;%3E+Server+running+on+http://github.com/Bahtiarrifaistudent" alt="Typing SVG"/>
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Bahtiarrifaistudent&style=for-the-badge&color=9333EA&label=PROFILE+VIEWS&abbreviated=true"/>
  <img src="https://img.shields.io/github/followers/Bahtiarrifaistudent?style=for-the-badge&logo=github&logoColor=white&label=Followers&color=E879F9"/>
  <img src="https://img.shields.io/badge/Focus-Laravel%20Backend-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
</p>

<p align="center">
  <a href="https://github.com/Bahtiarrifaistudent"><img src="https://img.shields.io/badge/GitHub-3B0764?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="https://linkedin.com/in/bahtiarrifai3"><img src="https://img.shields.io/badge/LinkedIn-3B0764?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:bachtiarrifai55@gmail.com"><img src="https://img.shields.io/badge/Email-3B0764?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&height=3&color=0:0D0221,50:E879F9,100:0D0221" width="100%"/>

## `$ php artisan about`

```yaml
name      : Bahtiar Rifai
campus    : Politeknik Negeri Indramayu
role      : Fullstack Developer (Backend-oriented)
main      : Laravel + Vue.js
mission   : "Membangun aplikasi web yang rapi di belakang layar, nyaman di depan layar."
focus     :
  - REST API & arsitektur backend Laravel yang bersih dan scalable
  - Frontend reaktif dengan Vue.js + Inertia.js
  - Desain database relasional & optimasi query Eloquent
  - Deployment dan workflow DevOps yang sederhana tapi andal
contact   : bachtiarrifai55@gmail.com
motto     : "Code it clean. Ship it right."
```

## How I Build a Web App

```mermaid
flowchart LR
    subgraph FE["FRONTEND"]
        direction TB
        VUE["Vue.js"] --> INERTIA["Inertia.js"]
        BLADE["Blade + Livewire"]
        TW["Tailwind CSS"]
    end

    subgraph BE["BACKEND - LARAVEL"]
        direction TB
        ROUTE["Routing & Middleware"] --> CTRL["Controller & Service Layer"]
        CTRL --> ORM["Eloquent ORM"]
        AUTH["Sanctum / Breeze Auth"]
        QUEUE["Queue, Jobs & Events"]
    end

    subgraph DATA["DATA"]
        direction TB
        MYSQL[("MySQL")]
        REDIS[("Redis Cache")]
    end

    subgraph OPS["DEVOPS"]
        direction TB
        GIT["Git & GitHub"] --> CI["GitHub Actions"]
        CI --> DOCKER["Docker / Laravel Sail"]
        DOCKER --> DEPLOY["Nginx + VPS"]
    end

    FE -- "HTTP / API" --> BE
    BE --> DATA
    OPS -. "build & deploy" .-> BE

    classDef fe fill:#3B0764,stroke:#E879F9,color:#FFFFFF
    classDef be fill:#4C0519,stroke:#FF2D20,color:#FFFFFF
    classDef data fill:#0C4A6E,stroke:#22D3EE,color:#FFFFFF
    classDef ops fill:#1E1B4B,stroke:#A78BFA,color:#FFFFFF
    class VUE,INERTIA,BLADE,TW fe
    class ROUTE,CTRL,ORM,AUTH,QUEUE be
    class MYSQL,REDIS data
    class GIT,CI,DOCKER,DEPLOY ops
```

## Tech Stack

<table>
  <tr>
    <th align="center" width="33%">FRONTEND</th>
    <th align="center" width="34%">BACKEND</th>
    <th align="center" width="33%">DEVOPS</th>
  </tr>
  <tr>
    <td align="center" valign="top">
      <img src="https://skillicons.dev/icons?i=vue,js,html,css,tailwind,vite&perline=3&theme=dark"/>
      <br/><br/>
      <sub>Vue.js sebagai minat utama di sisi frontend, dipadukan dengan Inertia.js agar terhubung mulus ke Laravel.</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://skillicons.dev/icons?i=laravel,php,mysql,redis,postman&perline=3&theme=dark"/>
      <br/><br/>
      <sub>Laravel adalah rumah saya: API, autentikasi, queue, hingga struktur kode yang maintainable.</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://skillicons.dev/icons?i=git,github,githubactions,docker,nginx,linux&perline=3&theme=dark"/>
      <br/><br/>
      <sub>Versioning, CI/CD sederhana, containerization, sampai aplikasi online di server.</sub>
    </td>
  </tr>
</table>

## Laravel Ecosystem I've Explored

<p align="center"><b>Starter Kit & Full-stack Glue</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Inertia.js-0D0221?style=flat-square&logo=inertia&logoColor=9553E9"/>
  <img src="https://img.shields.io/badge/Livewire-0D0221?style=flat-square&logo=livewire&logoColor=FB70A9"/>
  <img src="https://img.shields.io/badge/Laravel_Breeze-0D0221?style=flat-square&logo=laravel&logoColor=FF2D20"/>
  <img src="https://img.shields.io/badge/Laravel_Jetstream-0D0221?style=flat-square&logo=laravel&logoColor=FF2D20"/>
  <img src="https://img.shields.io/badge/Filament-0D0221?style=flat-square&logo=laravel&logoColor=FDAE4B"/>
</p>

<p align="center"><b>Auth & Security</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Laravel_Sanctum-0D0221?style=flat-square&logo=laravel&logoColor=FF2D20"/>
  <img src="https://img.shields.io/badge/Laravel_Socialite-0D0221?style=flat-square&logo=laravel&logoColor=FF2D20"/>
  <img src="https://img.shields.io/badge/Spatie_Permission-0D0221?style=flat-square&logo=laravel&logoColor=E879F9"/>
</p>

<p align="center"><b>Data, Report & Utility</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Laravel_Excel-0D0221?style=flat-square&logo=microsoftexcel&logoColor=217346"/>
  <img src="https://img.shields.io/badge/DomPDF-0D0221?style=flat-square&logo=adobeacrobatreader&logoColor=EC1C24"/>
  <img src="https://img.shields.io/badge/Spatie_Media_Library-0D0221?style=flat-square&logo=laravel&logoColor=E879F9"/>
  <img src="https://img.shields.io/badge/Yajra_DataTables-0D0221?style=flat-square&logo=laravel&logoColor=22D3EE"/>
</p>

<p align="center"><b>Dev Tools & Testing</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Laravel_Sail-0D0221?style=flat-square&logo=docker&logoColor=2496ED"/>
  <img src="https://img.shields.io/badge/Laravel_Telescope-0D0221?style=flat-square&logo=laravel&logoColor=A78BFA"/>
  <img src="https://img.shields.io/badge/Debugbar-0D0221?style=flat-square&logo=laravel&logoColor=F4645F"/>
  <img src="https://img.shields.io/badge/Pest_PHP-0D0221?style=flat-square&logo=php&logoColor=F472B6"/>
  <img src="https://img.shields.io/badge/PHPUnit-0D0221?style=flat-square&logo=php&logoColor=777BB4"/>
</p>

## Featured Projects

<p align="center">
  <a href="https://github.com/Bahtiarrifaistudent/Floral-Innovators">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bahtiarrifaistudent&repo=Floral-Innovators&hide_border=true&bg_color=0D0221&title_color=E879F9&icon_color=22D3EE&text_color=C4B5FD" width="49%"/>
  </a>
  <a href="https://github.com/Bahtiarrifaistudent/smartcity-indramayu">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bahtiarrifaistudent&repo=smartcity-indramayu&hide_border=true&bg_color=0D0221&title_color=E879F9&icon_color=22D3EE&text_color=C4B5FD" width="49%"/>
  </a>
</p>

## Roadmap 2026

```diff
+ [x] Menguasai dasar Laravel: routing, Eloquent, Blade, migration
+ [x] Membangun aplikasi CRUD dengan autentikasi & role permission
+ [x] Mencoba berbagai library ekosistem Laravel
! [ ] Membangun SPA dengan Laravel + Inertia.js + Vue.js
! [ ] REST API yang terdokumentasi dan teruji (Pest)
! [ ] Deployment otomatis dengan Docker & GitHub Actions
- [ ] Laravel Certified Developer ... coming soon
```

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Bahtiarrifaistudent&show_icons=true&hide_border=true&bg_color=0D0221&title_color=E879F9&icon_color=22D3EE&text_color=C4B5FD&rank_icon=github&count_private=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bahtiarrifaistudent&layout=compact&hide_border=true&bg_color=0D0221&title_color=E879F9&text_color=C4B5FD&langs_count=6" height="170"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Bahtiarrifaistudent&hide_border=true&background=0D0221&ring=E879F9&fire=22D3EE&currStreakNum=FFFFFF&currStreakLabel=E879F9&sideNums=FFFFFF&sideLabels=C4B5FD&dates=A78BFA&stroke=3B0764" width="70%"/>
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Bahtiarrifaistudent&bg_color=0D0221&color=C4B5FD&line=E879F9&point=22D3EE&area=true&area_color=9333EA&hide_border=true" width="100%"/>
</p>

<details>
<summary><b>Tips jaga streak: WIB vs UTC (klik untuk buka)</b></summary>
<br/>

GitHub mencatat kontribusi dalam **UTC**, sedangkan kita hidup di **WIB (UTC+7)**.

| Commit di WIB | Tercatat GitHub (UTC) |
| --- | --- |
| 10 Mei, 00:00 - 06:59 | 9 Mei (masih hari kemarin) |
| 10 Mei, 07:00 - 23:59 | 10 Mei |

> Mau streak aman? Commit setelah **jam 07.00 WIB**.
</details>

<!-- ======================= OPSIONAL: hapus blok <details> ini jika tidak diperlukan ======================= -->
<details>
<summary><b>Eksplorasi Lain (opsional): Cyber Security & AI</b></summary>
<br/>

Di luar web development, saya juga pernah bereksperimen di bidang keamanan siber dan kecerdasan buatan.

<p align="center">
  <a href="https://github.com/Bahtiarrifaistudent/Simulasi-Brute-Force-attack">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bahtiarrifaistudent&repo=Simulasi-Brute-Force-attack&hide_border=true&bg_color=0D0221&title_color=E879F9&icon_color=22D3EE&text_color=C4B5FD" width="49%"/>
  </a>
  <a href="https://github.com/Bahtiarrifaistudent/Penanganan-Brute-Force-Attack">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bahtiarrifaistudent&repo=Penanganan-Brute-Force-Attack&hide_border=true&bg_color=0D0221&title_color=E879F9&icon_color=22D3EE&text_color=C4B5FD" width="49%"/>
  </a>
  <a href="https://github.com/Bahtiarrifaistudent/Asisten-20berbasis-20NLP-20Polindra">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bahtiarrifaistudent&repo=Asisten-20berbasis-20NLP-20Polindra&hide_border=true&bg_color=0D0221&title_color=E879F9&icon_color=22D3EE&text_color=C4B5FD" width="49%"/>
  </a>
  <a href="https://github.com/Bahtiarrifaistudent/ricescanai">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Bahtiarrifaistudent&repo=ricescanai&hide_border=true&bg_color=0D0221&title_color=E879F9&icon_color=22D3EE&text_color=C4B5FD" width="49%"/>
  </a>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,sklearn,tensorflow&theme=dark"/>
  <br/>
  <img src="https://img.shields.io/badge/Jupyter-0D0221?style=flat-square&logo=jupyter&logoColor=F37626"/>
  <img src="https://img.shields.io/badge/Kali_Linux-0D0221?style=flat-square&logo=kalilinux&logoColor=557C94"/>
  <img src="https://img.shields.io/badge/Wireshark-0D0221?style=flat-square&logo=wireshark&logoColor=1679A7"/>
  <img src="https://img.shields.io/badge/OWASP-0D0221?style=flat-square&logo=owasp&logoColor=white"/>
</p>
</details>
<!-- ======================= akhir blok opsional ======================= -->

## Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Bahtiarrifaistudent/Bahtiarrifaistudent/output/github-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Bahtiarrifaistudent/Bahtiarrifaistudent/output/github-snake.svg"/>
    <img alt="snake animation" src="https://raw.githubusercontent.com/Bahtiarrifaistudent/Bahtiarrifaistudent/output/github-snake-dark.svg"/>
  </picture>
</p>

---

<table align="center">
  <tr>
    <td align="center">
      <i>"Frontend yang indah membuat orang datang,<br/>backend yang kokoh membuat mereka bertahan."</i>
      <br/><br/>
      <b>- Bahtiar Rifai</b>
    </td>
  </tr>
</table>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=3000&pause=1000&color=22D3EE&center=true&vCenter=true&width=600&lines=Process+finished+with+exit+code+0;Terima+kasih+sudah+mampir!;Jangan+lupa+follow+ya!" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&height=130&section=footer&color=0:E879F9,50:9333EA,100:0D0221" width="100%"/>
