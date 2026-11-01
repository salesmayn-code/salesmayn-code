<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
    <img src="assets/hero-light.svg" alt="Muhammad Saleh Janjua — full-stack software engineer" width="100%">
  </picture>
</p>

<p align="center">
  I build full-stack applications and the delivery systems that ship them.<br>
  Computer Software Engineering · PAF-IAST · 2026
</p>

<p align="center">
  <a href="https://portfolio-salesmayn.vercel.app/"><strong>Portfolio</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/muhammadsalehjanjua"><strong>LinkedIn</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="mailto:MuhammadSalehJanjua@gmail.com"><strong>Email</strong></a>
</p>

## Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/OpsDesk">OpsDesk</a></strong><br>
      <code>Next.js</code> <code>NestJS</code> <code>PostgreSQL</code> <code>Redis</code><br><br>
      IT service management platform with ticket lifecycles, SLA automation, role-based access, asset management, incident workflows, and audit trails.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/MimaarAssociates">Mimaar Associates</a></strong><br>
      <code>Next.js</code> <code>TypeScript</code> <code>Prisma</code> <code>Jenkins</code><br><br>
      Company website and admin content platform delivered through a Jenkins pipeline to an Ubuntu VM.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/Cryptojacking_Detection_Tool">CryptoDetect</a></strong><br>
      <code>Python</code> <code>FastAPI</code> <code>React</code> <code>XGBoost</code><br><br>
      Cryptojacking detection with a Python monitoring agent, FastAPI backend, React dashboard, and Random Forest/XGBoost models.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/LinkPulse">LinkPulse</a></strong><br>
      <code>.NET</code> <code>ASP.NET Core</code> <code>Blazor</code> <code>SQL Server</code><br><br>
      Self-hostable URL shortener with click analytics, link expiration, and per-user ownership controls. In development.
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/AgileCapacityTracker">Agile Capacity Tracker</a></strong><br>
      <code>Java</code> <code>Spring Boot</code> <code>Next.js</code> <code>PostgreSQL</code><br><br>
      Sprint and team-capacity dashboard with workload charts and GitHub issue synchronization.
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/portfolio">Portfolio</a></strong><br>
      <code>Next.js</code> <code>TypeScript</code> <code>Tailwind CSS</code> <code>Vercel</code><br><br>
      The engineering portfolio behind this profile, presenting selected systems and the delivery work around them.
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/salesmayn-code?tab=repositories">All repositories</a>
</p>

## Stack

<table>
  <tr>
    <td width="50%" valign="top">
      <strong>Application</strong><br>
      TypeScript · JavaScript · React · Next.js<br>
      Interfaces, state, and client data
    </td>
    <td width="50%" valign="top">
      <strong>Backend</strong><br>
      Node.js · Express · NestJS · Python · FastAPI · .NET<br>
      APIs, background jobs, and domain workflows
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Data</strong><br>
      PostgreSQL · SQL Server · SQLite · Prisma · Redis<br>
      Schemas, migrations, queries, and caching
    </td>
    <td width="50%" valign="top">
      <strong>Delivery</strong><br>
      Jenkins · GitHub Actions · Docker · PM2 · Nginx<br>
      Pipelines, containers, and production deployments
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong>Quality</strong><br>
      Jest · pytest · Playwright · API testing<br>
      Unit, integration, and end-to-end tests
    </td>
    <td width="50%" valign="top">
      <strong>Security</strong><br>
      Authentication · RBAC · secrets management<br>
      Access control and audit trails
    </td>
  </tr>
</table>
## Delivery

I care about the path from commit to production, not just the application code.

<p>
  <code>checkout</code> → <code>install</code> → <code>lint</code> → <code>test</code><br>
  <code>prisma migrate</code> → <code>build</code> → <code>rsync</code> → <code>pm2 restart</code>
</p>

The Mimaar Associates pipeline runs these stages in Jenkins, injects credentials from the Jenkins credential store, and deploys to an Ubuntu VM behind Nginx with PM2 supervising the process.

## Currently

Building **OpsDesk** — an IT service management platform with SLA automation, incident and change workflows, and a transactional outbox.
