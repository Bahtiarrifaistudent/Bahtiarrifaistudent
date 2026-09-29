<!-- ============================== HEADER ============================== -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=300&color=0:0D0221,40:3B0764,75:9333EA,100:E879F9&text=BAHTIAR%20RIFAI&fontSize=72&fontColor=FFFFFF&fontAlignY=36&desc=Fullstack%20Developer%20%E2%80%A2%20Laravel%20Backend%20%E2%80%A2%20Vue.js&descAlignY=56&descSize=18&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/Bahtiarrifaistudent">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=22&duration=2400&pause=800&color=E879F9&center=true&vCenter=true&width=900&lines=%3E+php+artisan+serve+--profile=bahtiar;%3E+Laravel+12+%2B+Inertia+%2B+Vue+3;%3E+Realtime+apps+with+Laravel+Reverb;%3E+Clean+APIs%2C+documented+automatically;%3E+Server+running+on+github.com/Bahtiarrifaistudent" alt="Typing SVG"/>
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
main      : Laravel 12 + Inertia.js + Vue 3
mission   : "Membangun aplikasi web yang rapi di belakang layar, nyaman di depan layar."
focus     :
  - Arsitektur backend Laravel: API, autentikasi, realtime broadcasting
  - SPA modern dengan Inertia.js + Vue 3 Composition API
  - Desain database relasional & Eloquent ORM
  - Dokumentasi API otomatis (OpenAPI)
contact   : bachtiarrifai55@gmail.com
motto     : "Code it clean. Ship it right."
```

## How I Build a Web App

<sub>Gambaran arsitektur dari project terbesar saya: <b>Monitoring App</b>, sistem monitoring perangkat realtime berbasis Laravel + Vue.</sub>

```mermaid
flowchart LR
    subgraph FE["FRONTEND"]
        direction TB
        VUE["Vue 3 - Composition API"] --> INERTIA["Inertia.js"]
        TW["Tailwind CSS v4"]
        VITE["Vite"]
    end

    subgraph BE["BACKEND - LARAVEL 12 / PHP 8.4"]
        direction TB
        ROUTE["Routing, Middleware, FormRequest"] --> ORM["Eloquent ORM + Migrations"]
        AUTH["Sanctum + Token Guard + Roles"]
        REVERB["Reverb WebSocket + Broadcasting"]
        DOCS["Scramble + Scalar API Docs"]
    end

    subgraph DATA["DATA & STORAGE"]
        direction TB
        MYSQL[("MySQL")]
        STORE[("Laravel Storage")]
    end

    subgraph AGENT["DESKTOP AGENT"]
        direction TB
        PY["Python Agent"] --> RTC["WebRTC Remote Desktop"]
    end

    subgraph OPS["DEV ENV & TOOLING"]
        direction TB
        LARAGON["Laragon"] --> PKG["Composer + npm"]
        PKG --> GIT["Git & GitHub"]
    end

    FE -- "Inertia request" --> BE
    BE -- "private channel" --> FE
    AGENT -- "REST API + Sanctum" --> BE
    BE --> DATA
    OPS -. "build & version" .-> BE

    classDef fe fill:#3B0764,stroke:#E879F9,color:#FFFFFF
    classDef be fill:#4C0519,stroke:#FF2D20,color:#FFFFFF
    classDef data fill:#0C4A6E,stroke:#22D3EE,color:#FFFFFF
    classDef agent fill:#14532D,stroke:#4ADE80,color:#FFFFFF
    classDef ops fill:#1E1B4B,stroke:#A78BFA,color:#FFFFFF
    class VUE,INERTIA,TW,VITE fe
    class ROUTE,ORM,AUTH,REVERB,DOCS be
    class MYSQL,STORE data
    class PY,RTC agent
    class LARAGON,PKG,GIT ops
```

## Tech Stack

<table>
  <tr>
    <th align="center" width="33%">FRONTEND</th>
    <th align="center" width="34%">BACKEND</th>
    <th align="center" width="33%">DEVOPS & TOOLING</th>
  </tr>
  <tr>
    <td align="center" valign="top">
      <img src="https://skillicons.dev/icons?i=vue,js,tailwind,vite,html,css&perline=3&theme=dark"/>
      <br/><br/>
      <sub>Vue 3 dengan <code>&lt;script setup&gt;</code>, <code>useForm</code> & <code>usePage</code>, terhubung ke Laravel lewat Inertia.js.</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://skillicons.dev/icons?i=laravel,php,mysql&perline=3&theme=dark"/>
      <br/><br/>
      <sub>Laravel 12 di atas PHP 8.4: Eloquent, Blade, validasi, autentikasi API, hingga WebSocket.</sub>
    </td>
    <td align="center" valign="top">
      <img src="https://skillicons.dev/icons?i=git,github,vscode&perline=3&theme=dark"/>
      <br/>
      <img src="https://img.shields.io/badge/Laragon-0D0221?style=flat-square&logo=laravel&logoColor=0E83CD"/>
      <img src="https://img.shields.io/badge/Composer-0D0221?style=flat-square&logo=composer&logoColor=C4B5FD"/>
      <img src="https://img.shields.io/badge/npm-0D0221?style=flat-square&logo=npm&logoColor=CB3837"/>
      <br/><br/>
      <sub>Lingkungan lokal Laragon, dependency lewat Composer & npm, versioning dengan Git branch.</sub>
    </td>
  </tr>
</table>

## Laravel Ecosystem I've Used

<p align="center"><b>Full-stack Glue</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Inertia.js-0D0221?style=flat-square&logo=inertia&logoColor=9553E9"/>
  <img src="https://img.shields.io/badge/Blade-0D0221?style=flat-square&logo=laravel&logoColor=FF2D20"/>
  <img src="https://img.shields.io/badge/Vite-0D0221?style=flat-square&logo=vite&logoColor=646CFF"/>
</p>

<p align="center"><b>Auth & Access Control</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Laravel_Sanctum-0D0221?style=flat-square&logo=laravel&logoColor=FF2D20"/>
  <img src="https://img.shields.io/badge/Token_Guard-0D0221?style=flat-square&logo=laravel&logoColor=E879F9"/>
  <img src="https://img.shields.io/badge/Role_Management-0D0221?style=flat-square&logo=laravel&logoColor=22D3EE"/>
</p>

<p align="center"><b>Realtime & Communication</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Laravel_Reverb-0D0221?style=flat-square&logo=laravel&logoColor=FF2D20"/>
  <img src="https://img.shields.io/badge/Broadcasting_%26_Events-0D0221?style=flat-square&logo=laravel&logoColor=E879F9"/>
  <img src="https://img.shields.io/badge/WebRTC-0D0221?style=flat-square&logo=webrtc&logoColor=white"/>
</p>

<p align="center"><b>API Documentation</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Scramble-0D0221?style=flat-square&logo=laravel&logoColor=A78BFA"/>
  <img src="https://img.shields.io/badge/OpenAPI-0D0221?style=flat-square&logo=openapiinitiative&logoColor=6BA539"/>
  <img src="https://img.shields.io/badge/Scalar-0D0221?style=flat-square&logo=swagger&logoColor=22D3EE"/>
</p>

<p align="center"><b>Media & File</b></p>
<p align="center">
  <img src="https://img.shields.io/badge/Laravel_Storage-0D0221?style=flat-square&logo=laravel&logoColor=FF2D20"/>
  <img src="https://img.shields.io/badge/GD_Library_(WebP)-0D0221?style=flat-square&logo=php&logoColor=777BB4"/>
  <img src="https://img.shields.io/badge/CSV_%26_Excel_Export-0D0221?style=flat-square&logo=microsoftexcel&logoColor=217346"/>
</p>

## Project Highlight: Monitoring App

<table>
  <tr>
    <td>
      <b>Sistem monitoring perangkat realtime</b> berbasis Laravel 12 + Inertia + Vue 3, dengan desktop agent Python yang berkomunikasi lewat REST API.
      <br/><br/>
      <b>Yang saya bangun di dalamnya:</b>
      <ul>
        <li>REST API untuk agent dengan autentikasi <b>Laravel Sanctum</b>, plus token guard terpisah untuk API admin</li>
        <li>Update status realtime lewat <b>Laravel Reverb</b> (private channel per device) dengan fallback HTTP polling</li>
        <li><b>Remote desktop</b> melalui WebRTC signaling (offer / answer / ICE)</li>
        <li><b>Geofencing</b> dengan algoritma ray-casting buatan sendiri untuk deteksi masuk/keluar zona</li>
        <li><b>Policy engine</b> per device/group: screenshot, URL/USB/download filter, kontrol WiFi, hotspot & Bluetooth</li>
        <li>Konversi screenshot ke <b>WebP</b> dengan GD Library, report CSV & Excel per tab</li>
        <li>Dokumentasi API otomatis dengan <b>Scramble + Scalar</b></li>
      </ul>
      <sub><b>Agent:</b> Python, Tkinter, pywin32, psutil, mss, Pillow, requests</sub>
    </td>
  </tr>
</table>

## Roadmap 2026

```diff
+ [x] Membangun aplikasi Laravel 12 + Inertia.js + Vue 3
+ [x] REST API dengan Sanctum & dokumentasi OpenAPI otomatis
+ [x] Fitur realtime dengan Laravel Reverb & Broadcasting
+ [x] Integrasi WebRTC untuk remote desktop
! [ ] Automated testing untuk API (Pest / PHPUnit)
! [ ] Containerization dengan Docker
! [ ] CI/CD & deployment otomatis ke server
```

## Other Experience

<sub>Di luar web development, saya juga pernah mengerjakan project di bidang keamanan siber, AI, dan smart city.</sub>

<table>
  <tr>
    <th align="center" width="33%">CYBER SECURITY</th>
    <th align="center" width="34%">AI & DATA</th>
    <th align="center" width="33%">WEB PROJECTS</th>
  </tr>
  <tr>
    <td valign="top">
      <sub>
        <b><a href="https://github.com/Bahtiarrifaistudent/Simulasi-Brute-Force-attack">Simulasi Brute Force Attack</a></b><br/>
        Simulasi serangan brute force dengan Python.<br/><br/>
        <b><a href="https://github.com/Bahtiarrifaistudent/Penanganan-Brute-Force-Attack">Penanganan Brute Force Attack</a></b><br/>
        Implementasi teknik mitigasinya.
      </sub>
    </td>
    <td valign="top">
      <sub>
        <b><a href="https://github.com/Bahtiarrifaistudent/Asisten-20berbasis-20NLP-20Polindra">Asisten berbasis NLP Polindra</a></b><br/>
        Asisten virtual kampus berbasis Natural Language Processing (Jupyter Notebook).<br/><br/>
        <b><a href="https://github.com/Bahtiarrifaistudent/ricescanai">RiceScanAI</a></b><br/>
        Eksplorasi AI untuk tanaman padi.
      </sub>
    </td>
    <td valign="top">
      <sub>
        <b><a href="https://github.com/Bahtiarrifaistudent/smartcity-indramayu">Smart City Indramayu</a></b><br/>
        Prototype platform smart governance, waste management & layanan publik.<br/><br/>
        <b><a href="https://github.com/Bahtiarrifaistudent/Floral-Innovators">Floral Innovators</a></b><br/>
        Aplikasi web berbasis Laravel Blade.
      </sub>
    </td>
  </tr>
  <tr>
    <td align="center"><img src="https://skillicons.dev/icons?i=py,linux&theme=dark"/></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=py&theme=dark"/> <img src="https://img.shields.io/badge/Jupyter-0D0221?style=flat-square&logo=jupyter&logoColor=F37626"/></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=laravel,html,css&theme=dark"/></td>
  </tr>
</table>

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
