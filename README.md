<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/hero-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
    <img src="assets/hero-light.svg" alt="Muhammad Saleh Janjua — full-stack software engineer" width="100%">
  </picture>
</p>

<p align="center">
  I build full-stack applications and the delivery systems that ship them.<br>
  <sub>Computer Software Engineering · PAF-IAST · 2026</sub>
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
      IT service management platform with ticket lifecycles, SLA automation, role-based access, asset management, incident workflows, and audit trails.<br><br>
      <code>Next.js</code> <code>NestJS</code> <code>PostgreSQL</code> <code>Prisma</code> <code>Redis</code>
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/MimaarAssociates">Mimaar Associates</a></strong><br>
      Company website and admin content platform delivered through a Jenkins pipeline to an Ubuntu VM.<br><br>
      <code>Next.js</code> <code>TypeScript</code> <code>Prisma</code> <code>PostgreSQL</code> <code>Jenkins</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/Cryptojacking_Detection_Tool">CryptoDetect</a></strong><br>
      Cryptojacking detection with a Python monitoring agent, FastAPI backend, React dashboard, and Random Forest/XGBoost models.<br><br>
      <code>Python</code> <code>FastAPI</code> <code>React</code> <code>scikit-learn</code> <code>XGBoost</code>
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/LinkPulse">LinkPulse</a></strong><br>
      Self-hostable URL shortener with click analytics, link expiration, and per-user ownership controls. In development.<br><br>
      <code>.NET</code> <code>ASP.NET Core</code> <code>Blazor</code> <code>Clerk</code> <code>SQL Server</code>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/AgileCapacityTracker">Agile Capacity Tracker</a></strong><br>
      Sprint and team-capacity dashboard with workload charts and GitHub issue synchronization.<br><br>
      <code>Java</code> <code>Spring Boot</code> <code>Next.js</code> <code>PostgreSQL</code>
    </td>
    <td width="50%" valign="top">
      <strong><a href="https://github.com/salesmayn-code/portfolio">Portfolio</a></strong><br>
      The engineering portfolio behind this profile, presenting selected systems and the delivery work around them.<br><br>
      <code>Next.js</code> <code>TypeScript</code> <code>Tailwind CSS</code> <code>Vercel</code>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/salesmayn-code?tab=repositories">All repositories</a>
</p>

## Stack

<table width="100%">
  <tr>
    <th align="left" width="22%">Layer</th>
    <th align="left">Tools</th>
  </tr>
  <tr>
    <td><strong>Application</strong></td>
    <td>TypeScript · JavaScript · React · Next.js</td>
  </tr>
  <tr>
    <td><strong>Backend</strong></td>
    <td>Node.js · Express · NestJS · Python · FastAPI · .NET</td>
  </tr>
  <tr>
    <td><strong>Data</strong></td>
    <td>PostgreSQL · SQL Server · SQLite · Prisma</td>
  </tr>
  <tr>
    <td><strong>Delivery</strong></td>
    <td>Jenkins · GitHub Actions · Docker · PM2 · Nginx</td>
  </tr>
  <tr>
    <td><strong>Quality</strong></td>
    <td>Jest · pytest · Playwright · API testing</td>
  </tr>
</table>

## Delivery

I care about the path from commit to production, not just the application code.

<p align="center">
  <code>checkout</code> → <code>install</code> → <code>lint</code> → <code>test</code><br>
  <code>prisma migrate</code> → <code>build</code> → <code>rsync</code> → <code>pm2 restart</code>
</p>

The Mimaar Associates pipeline runs these stages in Jenkins, injects credentials from the Jenkins credential store, and deploys to an Ubuntu VM behind Nginx with PM2 supervising the process.

## Currently

Building **OpsDesk** — an IT service management platform with SLA automation, incident and change workflows, and a transactional outbox.
