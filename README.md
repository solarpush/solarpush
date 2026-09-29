# Pierre Nicolas

> **Software Engineer & Systems Builder**  
> *Crafting low-overhead desktop utilities, document pipelines & type-safe data layers.*

[![GitHub](https://img.shields.io/badge/GitHub-solarpush-181717?style=flat-square&logo=github)](https://github.com/solarpush)
[![Snapcraft](https://img.shields.io/badge/Snapcraft-region--to--share-E95420?style=flat-square&logo=snapcraft&logoColor=white)](https://snapcraft.io/region-to-share)
[![npm](https://img.shields.io/badge/npm-@lpdjs/firestore--repo--service-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/@lpdjs/firestore-repo-service)

---

### 📦 Products & Open Source

<table>
  <tr>
    <td width="66%">
      <h4><a href="https://github.com/solarpush/region-to-share">region-to-share</a></h4>
      <p>Native screen region sharing utility for Linux video calls (<code>Meet</code>, <code>Teams</code>, <code>Discord</code>).</p>
      <ul>
        <li><b>Wayland & X11</b> native capture via <code>XDG Desktop Portal</code>.</li>
        <li>Ultra-low latency overlay with negligible CPU impact.</li>
      </ul>
      <code>snap install region-to-share</code>
    </td>
    <td width="33%" align="center" valign="middle">
      <code>Rust</code><br><code>egui</code><br><code>Linux Desktop</code>
    </td>
  </tr>
  <tr>
    <td width="66%">
      <h4><a href="https://github.com/solarpush/fX">fX</a></h4>
      <p>High-throughput Factur-X / ZUGFeRD / EN16931 PDF/A-3 generator.</p>
      <ul>
        <li>Benchmarked at <b>~165 PDF/s</b> for high-volume B2B e-invoicing.</li>
        <li>Standalone microservice ready for ERPs (<code>Dolibarr</code>, <code>Invoice Ninja</code>).</li>
      </ul>
    </td>
    <td width="33%" align="center" valign="middle">
      <code>Go</code><br><code>Typst</code><br><code>Microservice</code>
    </td>
  </tr>
  <tr>
    <td width="66%">
      <h4><a href="https://www.npmjs.com/package/@lpdjs/firestore-repo-service">firestore-repo-service (FRS)</a></h4>
      <p>Type-safe Firestore ORM & repository layer for TypeScript and Node.js.</p>
      <ul>
        <li>Auto-generated typed repositories with compile-time query safety.</li>
        <li>Supports batch operations, transactions, pagination, and aggregations.</li>
      </ul>
      <code>npm i @lpdjs/firestore-repo-service</code>
    </td>
    <td width="33%" align="center" valign="middle">
      <code>TypeScript</code><br><code>Node.js</code><br><code>Firebase</code>
    </td>
  </tr>
</table>

---

### 🛠️ Core Focus & Systems

| Domain | Focus & Tooling |
| :--- | :--- |
| **Desktop & Systems** | Wayland protocols, X11, Snap packaging, native UI (`Rust`, `egui`) |
| **Document Compliance** | Electronic invoicing (Factur-X, EN16931), PDF/A-3 rendering (`Go`, `Typst`) |
| **Cloud & Backend** | Type-safe data layers, VoIP integration (`Asterisk` / `MikoPBX`), containerized microservices |
