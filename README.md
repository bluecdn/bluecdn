<div align="center">
  <a href="https://bluecdn.com">
    <img src="./assets/bluecdn-avatar.png" width="120" height="120" alt="BlueCDN" />
  </a>

  <h1>BlueCDN</h1>

  <p>
    Front-end CDN mirrors, static assets, web fonts, and avatar acceleration for developers.
  </p>

  <p>
    <a href="https://static.bluecdn.com">Static CDN</a>
    ·
    <a href="https://gravatar.bluecdn.com">Avatar Proxy</a>
    ·
    <a href="https://www.bluecdn.com">Website</a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/CDN-0052D9?style=for-the-badge" alt="CDN" />
    <img src="https://img.shields.io/badge/Static%20Assets-111827?style=for-the-badge" alt="Static Assets" />
    <img src="https://img.shields.io/badge/Web%20Fonts-0052D9?style=for-the-badge" alt="Web Fonts" />
    <img src="https://img.shields.io/badge/Avatar%20API-111827?style=for-the-badge" alt="Avatar API" />
  </p>
</div>

---

## BlueCDN Ecosystem

BlueCDN is organized as a set of small, focused services. Each subdomain has one clear job.

| Service | Domain | What it provides |
|---|---|---|
| Main CDN | [bluecdn.com](https://bluecdn.com) | JavaScript and CSS package search, mirror links, quick copy snippets, and front-end resource discovery. |
| Static CDN | [static.bluecdn.com](https://static.bluecdn.com) | Web fonts, FontAwesome, public static assets, jsDelivr-style paths, and cdnjs-style proxy paths. |
| Avatar API | [gravatar.bluecdn.com](https://gravatar.bluecdn.com) | Gravatar-compatible avatar acceleration with Cravatar, Gravatar, WeAvatar, QQ avatar, and default fallback. |
| Status | status.bluecdn.com | Operational status and visibility for BlueCDN services. |

## What We Optimize For

- Stable front-end resource URLs that are easy to paste into real projects.
- Cache-friendly paths for static assets, fonts, icons, and package files.
- Better access across domestic and overseas network routes.
- Small services with clear boundaries instead of one large platform.
- Practical documentation that explains how each service is deployed and used.

## Quick Usage

```html
<!-- JS package mirror -->
<script src="https://static.bluecdn.com/npm/vue@3/dist/vue.global.prod.js"></script>

<!-- cdnjs-style asset path -->
<script src="https://static.bluecdn.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>

<!-- FontAwesome -->
<link rel="stylesheet" href="https://static.bluecdn.com/libs/fontawesome/7.3.0/css/all.min.css">

<!-- Web font -->
<link rel="stylesheet" href="https://static.bluecdn.com/fonts/noto-sans-sc.css">

<!-- Gravatar-compatible avatar -->
<img src="https://gravatar.bluecdn.com/avatar/{hash}?s=160" alt="avatar">
```

## Project Layout

BlueCDN is being consolidated by subdomain:

| Area | Responsibility |
|---|---|
| `bluecdn.com` | Main site, search experience, package metadata, and public landing pages. |
| `static.bluecdn.com` | Static resource deployment, fonts, FontAwesome, and CDN reverse proxy routes. |
| `gravatar.bluecdn.com` | LiteAvatar service and avatar proxy runtime. |
| `status.bluecdn.com` | Health checks, service status, and operational visibility. |

## Stack

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white" alt="Caddy" />
  <img src="https://img.shields.io/badge/Git%20LFS-F64935?style=flat-square&logo=gitlfs&logoColor=white" alt="Git LFS" />
  <img src="https://img.shields.io/badge/Bunny%20CDN-F97316?style=flat-square" alt="Bunny CDN" />
  <img src="https://img.shields.io/badge/Baidu%20CDN-2563EB?style=flat-square" alt="Baidu CDN" />
</p>

## Repository Map

Public repositories are being reorganized under the BlueCDN account.

| Repository | Purpose |
|---|---|
| `bluecdn` | GitHub profile README for the BlueCDN account. |
| `bluecdn.com` | Main BlueCDN service. |
| `bluecdn.static` | Static CDN deployment source. |
| `LiteAvatar` | Avatar proxy service for `gravatar.bluecdn.com`. |

---

<div align="center">
  <p>
    Fast, simple, and practical front-end resources.
  </p>
</div>
